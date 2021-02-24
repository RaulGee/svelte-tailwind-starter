<script>
  export let name = '';
  export let email = '';
  export let message = '';
  export let hideForm;

</script>

<div class="bg-white py-16 px-4 overflow-hidden sm:px-6 lg:px-6 lg:py-10">
  <div class="relative max-w-xl mx-auto">
    <div class="text-center">
      <h2 class="text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
        Contact
      </h2>
      <p class="mt-4 text-lg leading-6 text-gray-500">
        Have a question or want to work together?
      </p>
    </div>
    <div class="mt-10">
      <form action="#" method="POST" data-netlify="true" class="grid grid-cols-1 gap-y-6 sm:grid-cols-2 sm:gap-x-8">
        <div class="sm:col-span-2">
          <label for="name" class="block text-sm font-medium text-gray-700">Name</label>
          <div class="mt-1">
            <input on:bind={name} type="text" name="name" id="name" autocomplete="organization" class="py-3 px-4 block w-full shadow-sm focus:ring-blue-700 focus:border-blue-700 border-gray-300 rounded-md">
          </div>
        </div>
        <div class="sm:col-span-2">
          <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
          <div class="mt-1">
            <input on:bind={email} id="email" name="email" type="email" autocomplete="email" class="py-3 px-4 block w-full shadow-sm focus:ring-blue-700 focus:border-blue-700 border-gray-300 rounded-md">
          </div>
        </div>
        <div class="sm:col-span-2">
          <label for="message" class="block text-sm font-medium text-gray-700">Message</label>
          <div class="mt-1">
            <textarea on:bind={message} id="message" name="message" rows="4" class="py-3 px-4 block w-full shadow-sm focus:ring-indigo-500 focus:border-blue-700 border-gray-300 rounded-md"></textarea>
          </div>
        </div>
        <div class="sm:col-span-2">
          <button type="submit" class="w-full inline-flex items-center justify-center px-6 py-3 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-blue-700 text-blue-100 hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
            Submit
          </button>
        </div>
      </form>
    </div>
  </div>
</div>

<!--
  This example requires Tailwind CSS v2.0+ 
  
  This example requires some changes to your config:
  
  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/forms'),
    ]
  }
  ```
-->