<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from '../pages/Home.svelte';
  import Work from '../pages/Work.svelte';
  import Resume from '../pages/Resume.svelte';

  export let showMenu;
  export let showForm;
</script>

<Router>
  <div class="bg-transparent">
    <header>
      <div class="relative bg-transparent">
        <div class="flex justify-end items-center max-w-7xl mx-auto px-4 py-6 sm:px-6 flex-end md:space-x-10 lg:px-8">
          <div class="-mr-2 -my-2 md:hidden">
            <button on:click={showMenu} type="button" class="bg-white rounded-md p-2 inline-flex items-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-blue-700" on:click={showMenu}>
              <span class="sr-only">Open menu</span>
              <!-- Heroicon name: outline/menu -->
              <svg on:click={showMenu} class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
              </svg>
            </button>
          </div>
          <nav class="hidden md:flex space-x-10">
            <Link  to="/" class="text-lg font-medium text-gray-500 hover:text-gray-900 hover:no-underline">
              Home
            </Link>
            <Link to="/mywork" class="text-lg font-medium text-gray-500 hover:text-gray-900 hover:no-underline">
              My Work
            </Link>
            <Link to="/aboutme" class="text-lg font-medium text-gray-500 hover:text-gray-900 hover:no-underline">
              About Me
            </Link>
          </nav>
          <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0">
            <Link on:click={showForm} href="#" class="ml-8 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-md text-lg font-medium text-blue-700 bg-white hover:bg-blue-700 hover:text-blue-100 hover:no-underline">
              Contact Me
            </Link>
          </div>
        </div>
      </div>
    </header>
  </div>
  <Route path="/" component={Home} />
  <Route path="/mywork" component={Work} />
  <Route path="/aboutme" component={Resume} />
</Router>