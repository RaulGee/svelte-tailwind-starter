<script>
	// router
	import { Router, Link, Route } from "svelte-routing";
	// Components
	import Nav from './Components/Nav.svelte';
	import MobileNav from './Components/MobileNav.svelte';
	import ContactSection from './Components/ContactSection.svelte';
	import TopBtn from './Components/TopBtn.svelte';
	import Modal from './Components/Modal.svelte';
	// Variables
	let topBtn;

	let isMenuOpen = false;
	let isTopShowing = false;
	let isFormOpen = false;
	// functions
	function showMenu() {
		isMenuOpen = true;
	}

	function hideMenu() {
		isMenuOpen = false;
	}

	function showForm() {
		isFormOpen = true;
	}

	function hideForm() {
		isFormOpen = false;
	}

	function showTop() {
		isTopShowing = true;
	}

	function hideTop() {
		isTopShowing = false;
	}

	function scrollBottom() {
		document.body.scrollTo(0, document.body.scrollHeight);
	}

	function scrollTop() {
		document.body.scrollTo(0, 0);
	}

	window.onscroll = function() {
		scrollFunction()
	};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    showTop();
  } else {
    isTopShowing = false;
  }
}
	
</script>

<style>
</style>

<Nav {showMenu} {scrollBottom} {showForm}/>
{#if isMenuOpen}
	<MobileNav {hideMenu} {scrollBottom} {showForm} />
{/if}

{#if isFormOpen}
	<Modal {hideForm}>
		<ContactSection 
			{hideForm}
		/>
	</Modal>
{/if}

