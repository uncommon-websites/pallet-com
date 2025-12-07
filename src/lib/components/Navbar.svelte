<script lang="ts">
  // Navbar component
</script>

<nav class="fixed top-0 left-0 right-0 z-50 border-b border-white/10 bg-[#050505]/80 backdrop-blur-md transition-all duration-300">
  <div class="mx-auto max-w-[1400px] px-6 h-16 flex items-center justify-between">
    <!-- Left: Logo & Links -->
    <div class="flex items-center gap-12">
      <a href="/" class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
        <svg viewBox="0 0 24 24" fill="none" class="w-6 h-6 text-white" xmlns="http://www.w3.org/2000/svg">
          <path d="M12 2L2 7L12 12L22 7L12 2Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M2 17L12 22L22 17" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M2 12L12 17L22 12" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        Pallet
      </a>

      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-400">
        <a href="#" class="hover:text-white transition-colors">Product</a>
        <a href="#" class="hover:text-white transition-colors">Operation Types</a>
        <a href="#" class="hover:text-white transition-colors">Articles</a>
        <a href="#" class="hover:text-white transition-colors">Company</a>
      </div>
    </div>

    <!-- Right: Actions -->
    <div class="flex items-center gap-4">
      <a href="#" class="hidden lg:flex items-center gap-2 text-sm text-gray-300 hover:text-white transition-colors group">
        <span class="bg-white/10 px-1.5 py-0.5 rounded text-xs text-white font-medium">News</span>
        <span>Our $27M Series B</span>
        <svg class="w-4 h-4 group-hover:translate-x-0.5 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
      </a>
      
      <a href="#" class="bg-white/10 hover:bg-white/20 text-white text-sm font-medium px-4 py-2 rounded-md transition-colors border border-white/10">
        Book a demo
      </a>
    </div>
  </div>
</nav>
