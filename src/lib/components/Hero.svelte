<script lang="ts">
  // Hero section with dashboard mockups
</script>

<section class="relative pt-32 pb-20 overflow-hidden border-b border-white/10">
  <!-- Grid Background -->
  <div class="absolute inset-0 pointer-events-none">
    <div class="absolute inset-0 bg-[linear-gradient(to_right,#27272a_1px,transparent_1px),linear-gradient(to_bottom,#27272a_1px,transparent_1px)] bg-[size:4rem_4rem] [mask-image:radial-gradient(ellipse_60%_50%_at_50%_0%,#000_70%,transparent_100%)] opacity-20"></div>
  </div>

  <div class="relative z-10 mx-auto max-w-[1400px] px-6">
    <div class="max-w-3xl">
      <h1 class="text-5xl md:text-7xl font-medium tracking-tight text-white mb-6 text-balance leading-[1.1]">
        Your smartest AI logistics worker
      </h1>
      <p class="text-xl text-gray-400 mb-10 max-w-2xl text-balance leading-relaxed">
        Process paperwork and automate clickwork with the AI worker that remembers every detail of your workflow.
      </p>
      
      <div class="flex flex-wrap gap-4 mb-20">
        <button class="bg-white text-black px-6 py-3 rounded-md font-medium hover:bg-gray-200 transition-colors">
          Try risk-free for 60 days
        </button>
        <button class="bg-[#111] text-white border border-white/20 px-6 py-3 rounded-md font-medium hover:bg-[#222] transition-colors">
          Explore CoPallet
        </button>
      </div>
    </div>

    <!-- Dashboard Mockup -->
    <div class="relative w-full rounded-tl-xl rounded-tr-xl border border-white/10 bg-[#0a0a0a] shadow-2xl overflow-hidden">
      <!-- Browser Chrome -->
      <div class="h-10 bg-[#111] border-b border-white/10 flex items-center px-4 gap-2">
        <div class="flex gap-1.5">
          <div class="w-3 h-3 rounded-full bg-red-500/20"></div>
          <div class="w-3 h-3 rounded-full bg-yellow-500/20"></div>
          <div class="w-3 h-3 rounded-full bg-green-500/20"></div>
        </div>
      </div>

      <!-- App Content -->
      <div class="flex h-[600px]">
        <!-- Sidebar -->
        <div class="w-64 border-r border-white/10 bg-[#0a0a0a] p-4 hidden md:block">
          <div class="flex items-center gap-2 mb-6 text-white font-medium">
            <div class="w-5 h-5 bg-white rounded-sm"></div>
            Pallet
          </div>
          
          <div class="space-y-1">
            <div class="flex items-center justify-between text-xs text-gray-500 px-2 py-1">
              <span>Agents</span>
              <span class="bg-white/10 text-white px-1.5 rounded">7</span>
            </div>
            <div class="bg-white/5 text-white px-2 py-1.5 rounded text-sm flex items-center gap-2">
              <span class="w-4 h-4 border border-white/40 rounded-sm"></span>
              Order Entry
            </div>
            <div class="text-gray-400 px-2 py-1.5 rounded text-sm flex items-center gap-2 hover:bg-white/5">
              <span class="w-4 h-4 border border-white/20 rounded-sm"></span>
              Track & Trace
            </div>
            <div class="text-gray-400 px-2 py-1.5 rounded text-sm flex items-center gap-2 hover:bg-white/5">
              <span class="w-4 h-4 border border-white/20 rounded-sm"></span>
              Quoting
            </div>
             <div class="text-gray-400 px-2 py-1.5 rounded text-sm flex items-center gap-2 hover:bg-white/5">
              <span class="w-4 h-4 border border-white/20 rounded-sm"></span>
              POD Entry
            </div>
          </div>
        </div>

        <!-- Main Area -->
        <div class="flex-1 bg-[#050505] flex flex-col">
          <!-- Header -->
          <div class="h-14 border-b border-white/10 flex items-center px-6 justify-between bg-[#050505]">
            <div class="flex items-center gap-6">
                <div class="flex items-center gap-3 text-white font-medium">
                     <div class="w-6 h-6 rounded bg-orange-500/20 flex items-center justify-center text-orange-500">
                        <svg class="w-3.5 h-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10" />
                        </svg>
                     </div>
                     Order Entry Agent
                </div>
                <div class="h-4 w-px bg-white/10"></div>
                <div class="flex items-center gap-2 text-xs text-gray-400">
                    <span>Status</span>
                    <span class="flex items-center gap-1.5 text-green-400 bg-green-500/10 px-2.5 py-1 rounded-full border border-green-500/20">
                        <div class="w-1.5 h-1.5 rounded-full bg-green-400 animate-pulse"></div>
                        Running
                    </span>
                </div>
            </div>
          </div>

          <!-- Content Split -->
          <div class="flex-1 flex overflow-hidden">
            <!-- Steps -->
            <div class="w-64 border-r border-white/10 p-4 hidden lg:block">
               <div class="space-y-4">
                 <div class="flex items-center gap-3 text-sm text-green-500">
                   <div class="w-5 h-5 rounded-full bg-green-500/20 flex items-center justify-center text-[10px]">✓</div>
                   Read document
                   <span class="ml-auto text-xs text-gray-500">3s</span>
                 </div>
                 <div class="flex items-center gap-3 text-sm text-white">
                   <div class="w-5 h-5 rounded-full border border-white/40 flex items-center justify-center animate-pulse">
                     <div class="w-2 h-2 bg-white rounded-full"></div>
                   </div>
                   Extract information
                   <span class="ml-auto text-xs text-gray-500">2s</span>
                 </div>
                 <div class="flex items-center gap-3 text-sm text-gray-500">
                   <div class="w-5 h-5 rounded-full border border-white/10"></div>
                   Create order
                   <span class="ml-auto text-xs text-gray-500">2s</span>
                 </div>
                  <div class="flex items-center gap-3 text-sm text-gray-500">
                   <div class="w-5 h-5 rounded-full border border-white/10"></div>
                   Enter order details
                   <span class="ml-auto text-xs text-gray-500">6s</span>
                 </div>
               </div>
            </div>

            <!-- Document View -->
            <div class="flex-1 p-6 overflow-auto bg-[#0a0a0a]">
                <div class="bg-white rounded-lg shadow-sm p-8 max-w-2xl mx-auto min-h-[800px] text-black text-xs font-mono">
                    <!-- Fake Document Content -->
                    <div class="flex justify-between mb-8 border-b pb-4">
                        <div>
                            <h2 class="text-lg font-bold mb-2">Straight Bill of Lading</h2>
                            <div class="p-2 bg-blue-50 border border-blue-100 rounded mb-2">
                                <span class="text-blue-600 font-bold">BOL#: 1000000020880</span>
                            </div>
                        </div>
                        <div class="text-right">
                            <div class="p-1 bg-blue-50 border border-blue-100 rounded inline-block">
                                Date: 04/15/2024
                            </div>
                        </div>
                    </div>
                    
                    <div class="grid grid-cols-2 gap-8 mb-8">
                        <div class="p-3 bg-blue-50/50 border border-blue-100/50 rounded">
                            <div class="font-bold mb-1">SHIPPER</div>
                            <div>BIG BOB BURGERS</div>
                            <div>4937 Aaron Smith Drive</div>
                            <div>Harrisburg, PA 17102</div>
                        </div>
                        <div class="p-3 bg-blue-50/50 border border-blue-100/50 rounded">
                            <div class="font-bold mb-1">CONSIGNEE</div>
                            <div>Everline</div>
                            <div>4037 Steele Street</div>
                            <div>Wheaton, IL 60187</div>
                        </div>
                    </div>

                    <table class="w-full border-collapse border border-gray-300 mb-8">
                        <thead>
                            <tr class="bg-gray-100">
                                <th class="border border-gray-300 p-2 text-left">QTY</th>
                                <th class="border border-gray-300 p-2 text-left">TYPE</th>
                                <th class="border border-gray-300 p-2 text-left">DESCRIPTION</th>
                                <th class="border border-gray-300 p-2 text-right">WEIGHT</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="border border-gray-300 p-2 bg-blue-50/30">30</td>
                                <td class="border border-gray-300 p-2">PLTS</td>
                                <td class="border border-gray-300 p-2">BEEF BURGERS</td>
                                <td class="border border-gray-300 p-2 text-right">900.00</td>
                            </tr>
                            <tr>
                                <td class="border border-gray-300 p-2 bg-blue-50/30">60</td>
                                <td class="border border-gray-300 p-2">CS</td>
                                <td class="border border-gray-300 p-2">BEEF BURGERS</td>
                                <td class="border border-gray-300 p-2 text-right">1800.00</td>
                            </tr>
                        </tbody>
                    </table>
                    
                    <div class="border-t pt-4">
                        <div class="font-bold mb-2">SPECIAL INSTRUCTIONS</div>
                        <div class="p-2 bg-yellow-50 border border-yellow-100 rounded text-yellow-800">
                            Trailer must be maintained at -20°F during transit.
                        </div>
                    </div>
                </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
