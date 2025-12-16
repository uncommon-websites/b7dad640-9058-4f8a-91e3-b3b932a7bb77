<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-12">
    <!-- Text -->
    <div class="w-full md:w-1/2">
      <h2 class="font-serif text-3xl md:text-4xl text-gray-900 mb-6">
        Excelência e certificações
      </h2>
      <p class="text-gray-500 mb-2">Qualidade certificada ISO 9001.</p>
      <p class="text-gray-500 mb-2">Alinhamento com NIST Framework 2.0.</p>
      <p class="text-gray-500 mb-8">Reconhecida como Great Place to Work.</p>
      
      <a href="#" class="text-gray-900 font-medium hover:underline text-sm">
        Saiba mais
      </a>
    </div>

    <!-- Badges -->
    <div class="w-full md:w-1/2 flex justify-center md:justify-end gap-6">
      <!-- Badge 1 - ISO 9001 -->
      <div class="w-24 h-24 rounded-full bg-gray-100 flex flex-col items-center justify-center text-center p-2">
        <div class="text-[10px] font-bold text-gray-900 mb-1">ISO</div>
        <div class="text-[10px] text-gray-500">9001</div>
      </div>

      <!-- Badge 2 - NIST -->
      <div class="w-24 h-24 rounded-full bg-gray-100 flex flex-col items-center justify-center text-center p-2 relative border border-dashed border-gray-300">
        <div class="absolute inset-0 rounded-full border border-dashed border-gray-400 animate-spin-slow"></div>
        <div class="text-[10px] font-bold text-gray-900">NIST</div>
        <div class="text-[10px] text-gray-500">CSF 2.0</div>
        <!-- Stars visual approximation -->
        <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
             <div class="w-16 h-16 border border-dotted border-gray-400 rounded-full"></div>
        </div>
      </div>

      <!-- Badge 3 - GPTW -->
      <div class="w-24 h-24 rounded-full bg-gray-100 flex flex-col items-center justify-center text-center p-2">
        <div class="mb-1">
             <svg class="w-4 h-4 text-gray-900 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
        </div>
        <div class="text-[10px] font-bold text-gray-900">Great</div>
        <div class="text-[10px] text-gray-500">Place to Work</div>
      </div>
    </div>
  </div>
</SectionWrapper>
