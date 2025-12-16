<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 mb-16 text-center">
    <h2 class="font-serif text-4xl text-gray-900">Confiança de líderes do mercado</h2>
  </div>

  <div class="px-4 md:px-12 max-w-5xl mx-auto">
    <div class="flex flex-col md:flex-row gap-12 items-center">
      <!-- Image -->
      <div class="w-full md:w-1/3">
        <div class="aspect-[3/4] bg-gray-200 rounded-lg overflow-hidden relative">
          <img 
            src="/generated/image-professional-brazilian-it-manager-in-bus-1765925643775-1.webp" 
            alt="Fernando Bruno dos Santos" 
            class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500"
          />
          <div class="absolute bottom-4 left-4 text-white text-xs font-bold uppercase tracking-widest opacity-80">
            B3
          </div>
        </div>
      </div>

      <!-- Quote -->
      <div class="w-full md:w-2/3">
        <blockquote class="font-light text-xl md:text-2xl text-gray-500 leading-relaxed mb-8">
          "Há várias empresas pelas quais passei, e a Compugraf sempre esteve ao meu lado, trabalhando tanto na proteção de dados quanto em Cyber Security, <span class="text-gray-900">fazendo a diferença em nossa jornada de segurança.</span>"
        </blockquote>
        
        <div class="border-t border-gray-200 border-dashed pt-6">
          <div class="font-serif text-lg font-bold text-gray-900">Fernando Bruno dos Santos</div>
          <div class="text-sm text-gray-500">Gerente de TI</div>
          <div class="text-sm text-gray-500">B3 - Brasil, Bolsa, Balcão</div>
        </div>
      </div>
    </div>
  </div>
</SectionWrapper>
