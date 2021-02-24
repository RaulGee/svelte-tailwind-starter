<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from '../pages/Home.svelte';
  import Work from '../pages/Work.svelte';
  import Resume from '../pages/Resume.svelte';
  export let hideMenu;
  export let showForm;

  function showHide() {
    showForm();
    hideMenu();
  }
</script>


<Router>
  <div class="absolute z-30 top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden">
    <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 bg-white divide-y-2 divide-gray-50">
    <div class="pt-5 pb-6 px-5">
      <div class="flex items-center justify-between">
        <div>
          <h2 class="text-bold text-blue-700 text-2xl">Raul Guirado</h2>
        </div>
        <div class="-mr-2">
          <button type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-blue-700" on:click={hideMenu}>
            <span class="sr-only">Close menu</span>
            <!-- Heroicon name: outline/x -->
            <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
          </button>
        </div>
      </div>
      <div class="mt-6">
        <nav class="grid grid-cols-1 gap-7">
          <Link on:click={hideMenu} to="/" class="-m-3 p-3 flex items-center rounded-lg hover:bg-gray-50">
            <!-- <div class="flex-shrink-0 flex items-center justify-center h-10 w-10 rounded-md bg-blue-700 text-white">
              <!-- Heroicon name: outline/inbox -->
              <!-- </div> -->
              <div on:click={hideMenu} class="ml-4 text-base font-medium text-gray-900 hover:no-underline">
                Home
              </div>
            </Link>
            
            <Link on:click={hideMenu} to="/mywork" class="-m-3 p-3 flex items-center rounded-lg hover:bg-gray-50">
              <!-- <div class="flex-shrink-0 flex items-center justify-center h-10 w-10 rounded-md bg-blue-700 text-white">
                <!-- Heroicon name: outline/annotation -->
                <!-- </div> --> 
                <div class="ml-4 text-base font-medium text-gray-900">
                  My Work
                </div>
              </Link>
              
              <Link on:click={hideMenu} to="/resume" class="-m-3 p-3 flex items-center rounded-lg hover:bg-gray-50">
                <!-- <div class="flex-shrink-0 flex items-center justify-center h-10 w-10 rounded-md bg-blue-700 text-white">
                  <!-- Heroicon name: outline/chat-alt-2 -->
                  <!-- </div> --> 
                  <div class="ml-4 text-base font-medium text-gray-900">
                    Resume
                  </div>
                </Link>
              </nav>
            </div>
          </div>
          <div class="py-6 px-5">
            <div class="grid grid-cols-2 gap-4">
            </div>
            <div class="">
              <Link on:click={showHide} to="#" class="w-full flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-blue-100 bg-blue-700 hover:bg-blue-600 hover:text-blue-100 hover:no-underline">
                Contact Me
              </Link>
            </div>
          </div>
        </div>
      </div>
      <Route path="/" component={Home} />
      <Route path="/mywork" component={Work} />
      <Route path="/resume" component={Resume} />
    </Router>
      
      <!--
        Mobile menu, show/hide based on mobile menu state.
        
        Entering: "duration-200 ease-out"
        From: "opacity-0 scale-95"
        To: "opacity-100 scale-100"
        Leaving: "duration-100 ease-in"
        From: "opacity-100 scale-100"
        To: "opacity-0 scale-95"
      -->