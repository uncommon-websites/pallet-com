<script lang="ts">
    // Feature Grid Component
</script>

<section class="bg-[#050505] pb-32">
    <div class="mx-auto max-w-[1400px] px-6 space-y-32">
        
        <!-- Feature 1 -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            <div class="lg:col-span-3 space-y-6 hidden lg:block">
                 <div class="flex items-center gap-3 text-red-500 text-xs font-mono tracking-widest uppercase">
                    <span class="w-1.5 h-1.5 bg-red-500 rounded-full"></span>
                    Contextual Accuracy
                 </div>
                 <div class="text-gray-600 text-xs font-mono tracking-widest uppercase pl-4.5">AI Document Digitization</div>
                 <div class="text-gray-600 text-xs font-mono tracking-widest uppercase pl-4.5">Continuously Learning</div>
                 
                 <div class="pt-12">
                    <a href="#" class="flex items-center gap-2 text-sm text-white hover:text-gray-300 transition-colors">
                        Discover CoPallet
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                    </a>
                 </div>
            </div>
            
            <div class="lg:col-span-6">
                <div class="aspect-square bg-[#0a0a0a] border border-white/10 rounded-lg overflow-hidden relative group">
                    <!-- Placeholder for video/animation -->
                    <div class="absolute inset-0 flex items-center justify-center">
                        <div class="w-3/4 h-3/4 bg-[#111] rounded border border-white/5 p-4 relative">
                            <!-- Chat/Context UI Mockup -->
                            <div class="space-y-3">
                                <div class="flex gap-3">
                                    <div class="w-8 h-8 rounded-full bg-gray-800"></div>
                                    <div class="flex-1 bg-gray-800/50 rounded p-3 text-xs text-gray-400">
                                        Set Freight Class to 60 for Big Bob Burgers by default.
                                    </div>
                                </div>
                                <div class="flex gap-3 flex-row-reverse">
                                    <div class="w-8 h-8 rounded-full bg-red-600/20 flex items-center justify-center text-red-500 text-xs">AI</div>
                                    <div class="flex-1 bg-red-900/10 border border-red-500/20 rounded p-3 text-xs text-gray-300">
                                        Understood. I've updated the customer profile for Big Bob Burgers. Future orders will default to Freight Class 60.
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="lg:col-span-3">
                <h3 class="text-2xl font-medium text-white mb-4">Deep context about your operations</h3>
                <p class="text-gray-400 leading-relaxed">
                    CoPallet learns from your natural language instructions about your unique process and edge cases. E.g. set Freight Class to 60 for Big Bob Burgers by default.
                </p>
            </div>
        </div>

        <!-- Feature 2 -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            <div class="lg:col-span-3 hidden lg:block"></div> <!-- Spacer for alignment -->
            
            <div class="lg:col-span-6">
                <div class="aspect-video bg-[#0a0a0a] border border-white/10 rounded-lg overflow-hidden relative flex items-center justify-center p-8">
                     <!-- Form Extraction UI -->
                     <div class="w-full max-w-md bg-[#111] border border-white/10 rounded-lg p-4 shadow-2xl">
                        <div class="flex items-center gap-3 mb-4 border-b border-white/5 pb-3">
                            <div class="w-8 h-8 rounded bg-orange-500/10 flex items-center justify-center">
                                <div class="w-4 h-4 border-2 border-orange-500 rounded-full border-t-transparent animate-spin"></div>
                            </div>
                            <div>
                                <div class="text-xs text-white font-medium">Completing form</div>
                                <div class="text-[10px] text-gray-500">CoPallet</div>
                            </div>
                            <div class="ml-auto w-4 h-4 rounded-full border border-white/20"></div>
                        </div>
                        
                        <div class="space-y-3">
                            <div class="grid grid-cols-2 gap-3">
                                <div>
                                    <label class="text-[10px] text-gray-500 block mb-1">BOL Number*</label>
                                    <div class="bg-[#050505] border border-white/10 rounded px-2 py-1.5 text-xs text-white">4303746333</div>
                                </div>
                                <div>
                                    <label class="text-[10px] text-gray-500 block mb-1">Load Number*</label>
                                    <div class="bg-[#050505] border border-white/10 rounded px-2 py-1.5 text-xs text-white">0003582302</div>
                                </div>
                            </div>
                             <div class="grid grid-cols-2 gap-3">
                                <div>
                                    <label class="text-[10px] text-gray-500 block mb-1">Ship Date*</label>
                                    <div class="bg-[#050505] border border-white/10 rounded px-2 py-1.5 text-xs text-white flex justify-between items-center">
                                        April 18
                                        <svg class="w-3 h-3 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                                    </div>
                                </div>
                                <div>
                                    <label class="text-[10px] text-gray-500 block mb-1">Delivery Date*</label>
                                    <div class="bg-[#050505] border border-white/10 rounded px-2 py-1.5 text-xs text-white flex justify-between items-center">
                                        April 19
                                        <svg class="w-3 h-3 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                                    </div>
                                </div>
                            </div>
                             <div>
                                <label class="text-[10px] text-gray-500 block mb-1">Origin Address*</label>
                                <div class="bg-[#050505] border border-white/10 rounded px-2 py-1.5 text-xs text-white">205 Robert Thompson Rd</div>
                            </div>
                        </div>
                     </div>
                </div>
            </div>
            
            <div class="lg:col-span-3">
                <h3 class="text-2xl font-medium text-white mb-4">AI document digitization reads any format</h3>
                <p class="text-gray-400 leading-relaxed">
                    Extract data from any format of doc (BOL/POD/ASN/packing list). Reliably handle multi-leg shipments, multi-page tables, handwriting, and more.
                </p>
            </div>
        </div>

        <!-- Feature 3 -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            <div class="lg:col-span-3 hidden lg:block"></div> <!-- Spacer for alignment -->
            
            <div class="lg:col-span-6">
                <div class="aspect-video bg-[#0a0a0a] border border-white/10 rounded-lg overflow-hidden relative flex items-center justify-center p-8">
                    <!-- Feedback Loop UI -->
                    <div class="w-full max-w-sm bg-white rounded-lg p-6 text-black shadow-2xl relative">
                        <div class="absolute -top-12 left-0 right-0 flex justify-center">
                             <div class="bg-[#111] text-white text-[10px] px-3 py-1 rounded-full border border-white/20 flex items-center gap-2">
                                <span class="w-1.5 h-1.5 bg-red-500 rounded-full"></span>
                                Order parsing failed
                             </div>
                        </div>
                        
                        <h4 class="font-bold mb-1">How to proceed?</h4>
                        <p class="text-xs text-gray-600 mb-4">The pickup is in 4 days. Please enter the missing data or request a new BOL.</p>
                        
                        <div class="space-y-3">
                            <div>
                                <label class="text-[10px] font-bold text-gray-500 uppercase">Temperature specifications</label>
                                <input type="text" class="w-full border-b border-gray-200 py-1 text-sm focus:outline-none focus:border-black" />
                            </div>
                             <div>
                                <label class="text-[10px] font-bold text-gray-500 uppercase">Notes</label>
                                <input type="text" class="w-full border-b border-gray-200 py-1 text-sm focus:outline-none focus:border-black" />
                            </div>
                        </div>
                        
                        <div class="mt-6 flex gap-2">
                            <button class="bg-gray-100 px-3 py-1.5 rounded text-xs font-medium">Cancel</button>
                            <button class="bg-black text-white px-3 py-1.5 rounded text-xs font-medium">Request new BOL</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="lg:col-span-3">
                <h3 class="text-2xl font-medium text-white mb-4">Learns from human feedback</h3>
                <p class="text-gray-400 leading-relaxed">
                    CoPallet gets smarter over time by flagging uncertain decisions for review and learning from feedback to improve future performance.
                </p>
            </div>
        </div>

    </div>
</section>
