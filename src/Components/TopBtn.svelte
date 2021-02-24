<script>
  export let scrollTop;
  export let scrollFunction;
</script>

<button on:click={scrollTop} class="fixed bottom-3 right-8 md:bottom-5 md:right-10 z-50 border-transparent hover:bg-blue-600 bg-blue-700 rounded-lg stroke-current text-white">
  <svg class="w-10 h-10 md:w-12 md:h-12 lg:w-14 lg:h-14" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24">
    <path d="M6 4h12v2H6zm.707 11.707L11 11.414V20h2v-8.586l4.293 4.293l1.414-1.414L12 7.586l-6.707 6.707z" fill="white"/></svg>
</button>

w-10 h-10 md:w-12 md:h-12 lg:w-14 lg:h-14