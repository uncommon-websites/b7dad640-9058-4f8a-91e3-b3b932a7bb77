<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-12">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-8">
    <!-- Logos -->
    <div class="flex flex-wrap items-center gap-8 md:gap-12 grayscale opacity-70">
        <!-- B3 -->
        <div class="h-6 font-bold text-2xl tracking-tight">B3</div>
        <!-- FIS Global -->
        <div class="h-6 font-bold text-lg tracking-wide uppercase">FIS</div>
        <!-- Banco Alfa -->
        <div class="h-8 flex flex-col leading-none text-xs font-bold uppercase">
            <span>BANCO</span>
            <span>ALFA</span>
        </div>
        <!-- Serasa -->
        <div class="h-6 font-bold text-lg italic">Serasa</div>
    </div>

    <!-- Trust Text -->
    <div class="text-gray-400 text-sm font-light text-right md:text-left">
      Confiança de mais de 500 empresas brasileiras
    </div>
  </div>
</SectionWrapper>
