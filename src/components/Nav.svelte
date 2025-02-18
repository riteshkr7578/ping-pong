<script>
  let isOpen = false; 
</script>

<nav class="bg-white fixed w-full top-0 z-50 ">
  <div class="container mx-auto px-4 lg:px-8 py-3 flex items-center justify-between">
    
    <!-- Logo -->
    <a href="/" class="flex items-center space-x-6">
      <img src="/logo.svg" alt="PingPong Logo" class="h-8 sm:h-10">
    </a>

    <!-- Mobile Menu Button -->
    <button 
      class="md:hidden text-black focus:outline-none"
      on:click={() => isOpen = !isOpen}
    >
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
      </svg>
    </button>

    <!-- Desktop Menu -->
    <div class="hidden md:flex space-x-6 items-center font-sans ml-6">
      <div class="relative group">
        <button class="text-black font-medium flex items-center">
          Features
          <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div class="absolute hidden group-hover:block bg-white shadow-lg rounded-md mt-2 w-40">
          <a href="#" class="block px-4 py-2 hover:bg-gray-100">Feature 1</a>
          <a href="#" class="block px-4 py-2 hover:bg-gray-100">Feature 2</a>
        </div>
      </div>
      <a href="#" class="text-black font-medium">Customers</a>
      <a href="#" class="text-black font-medium">Pricing</a>
      <a href="#" class="text-black font-medium">Blog</a>
    </div>

    <!-- Auth Buttons -->
    <div class="hidden md:flex items-center space-x-6 ml-auto">
      <a href="#" class="text-black font-medium">Login</a>
      <a href="#" class="bg-green-500 text-white px-5 py-2 font-medium text-lg rounded-lg">Get started</a>
    </div>
  </div>

  <!-- Mobile Menu -->
  {#if isOpen}
    <div class="md:hidden bg-white shadow-lg">
      <a href="#" class="block px-4 py-2 text-black font-medium">Features</a>
      <a href="#" class="block px-4 py-2 text-black font-medium">Customers</a>
      <a href="#" class="block px-4 py-2 text-black font-medium">Pricing</a>
      <a href="#" class="block px-4 py-2 text-black font-medium">Blog</a>
      <div class="border-t mt-2">
        <a href="#" class="block px-4 py-2 text-black font-medium">Login</a>
        <a href="#" class="block px-4 py-2 bg-green-500 text-white text-center rounded-lg">Get started</a>
      </div>
    </div>
  {/if}
</nav>
