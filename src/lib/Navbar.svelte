<script lang="ts">
  import Button from './Button.svelte';
  
  let isMenuOpen = false;
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-sm border-b border-gray-200/50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-20">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center">
        <a href="/" class="flex items-center gap-2">
          <!-- Pet Anthemz Logo Icon -->
          <svg width="32" height="32" viewBox="0 0 96 95" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M65.5946 30.0964C73.7657 38.2675 79.5137 47.2795 82.2155 55.226C84.9288 63.2063 84.5245 69.9453 80.6881 73.7817C76.8516 77.6182 70.1126 78.0225 62.1323 75.3092C54.1858 72.6074 45.1738 66.8594 37.0027 58.6883C28.8317 50.5173 23.0837 41.5053 20.3819 33.5588C17.6686 25.5784 18.0728 18.8395 21.9093 15.003C25.7458 11.1665 32.4847 10.7623 40.4651 13.4756C48.4116 16.1774 57.4236 21.9254 65.5946 30.0964Z" stroke="black"/>
            <path d="M59.3798 36.3116C67.5508 44.4827 73.2988 53.4947 76.0006 61.4412C78.714 69.4216 78.3097 76.1605 74.4732 79.997C70.6367 83.8334 63.8978 84.2377 55.9174 81.5244C47.971 78.8226 38.9589 73.0746 30.7879 64.9035C22.6169 56.7325 16.8688 47.7205 14.167 39.774C11.4537 31.7936 11.858 25.0547 15.6945 21.2182C19.5309 17.3817 26.2699 16.9775 34.2502 19.6908C42.1967 22.3926 51.2088 28.1406 59.3798 36.3116Z" stroke="black"/>
          </svg>
          <span class="font-bold text-xl tracking-tight">Pet Anthemz</span>
        </a>
      </div>

      <!-- Desktop Navigation -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#how-it-works" class="text-sm font-medium hover:text-orange-brand transition-colors">How It Works</a>
        <a href="#genres" class="text-sm font-medium hover:text-orange-brand transition-colors">Genres</a>
        <a href="#testimonials" class="text-sm font-medium hover:text-orange-brand transition-colors">Testimonials</a>
        <a href="#charity" class="text-sm font-medium hover:text-orange-brand transition-colors">Our Mission</a>
      </div>

      <!-- Right Side -->
      <div class="hidden md:flex items-center space-x-6">
        <Button href="#" className="!py-2 !px-4 !text-sm">Create Your Song &rarr;</Button>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button on:click={() => isMenuOpen = !isMenuOpen} class="text-gray-600 hover:text-gray-900 focus:outline-none">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>
    </div>
  </div>
</nav>
