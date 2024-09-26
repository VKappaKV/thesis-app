<script>
	import '../app.css'
	let isMobileMenuOpen = false;
  
	function toggleMobileMenu() {
	  isMobileMenuOpen = !isMobileMenuOpen;
	}
  </script>
  
  <header class="bg-white shadow-md py-4 px-6 flex items-center justify-between">
	<h1 class="text-2xl md:text-3xl font-bold text-gray-900">
	  CODELAB Thesis Program
	</h1>
	<nav class="hidden md:flex space-x-6">
	  <a href="/" class="text-gray-600 hover:text-blue-600 transition duration-300">
		Home
	  </a>
	  <a href="/projects" class="text-gray-600 hover:text-blue-600 transition duration-300">
		Projects
	  </a>
	  <a href="/schedule" class="text-gray-600 hover:text-blue-600 transition duration-300">
		Schedule
	  </a>
	  <a href="/contact" class="text-gray-600 hover:text-blue-600 transition duration-300">
		Contact
	  </a>
	</nav>
  
	<!-- Hamburger icon for mobile -->
	<button class="md:hidden text-gray-900 focus:outline-none" on:click={toggleMobileMenu} aria-label="Toggle navigation">
	  <!-- SVG for Hamburger Icon -->
	  <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
		<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
	  </svg>
	</button>
  
	<!-- Mobile menu -->
	{#if isMobileMenuOpen}
	  <nav class="absolute top-16 left-0 w-full bg-white shadow-md md:hidden">
		<ul class="flex flex-col items-center space-y-4 py-4">
		  <li><a href="/" class="text-gray-600 hover:text-blue-600 transition duration-300">Home</a></li>
		  <li><a href="/projects" class="text-gray-600 hover:text-blue-600 transition duration-300">Projects</a></li>
		  <li><a href="/schedule" class="text-gray-600 hover:text-blue-600 transition duration-300">Schedule</a></li>
		  <li><a href="/contact" class="text-gray-600 hover:text-blue-600 transition duration-300">Contact</a></li>
		</ul>
	  </nav>
	{/if}
  </header>
  
  <slot></slot>

  <style>
	/* Additional custom styles, if necessary */
  </style>
  