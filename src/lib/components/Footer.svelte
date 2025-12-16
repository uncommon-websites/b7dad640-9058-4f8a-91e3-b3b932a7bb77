<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<div class="bg-black text-white py-24 px-4 md:px-8 max-w-[1400px] mx-auto relative">
    <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-8">
        <h2 class="font-serif text-3xl md:text-4xl">
            Proteja seu negócio hoje
        </h2>
        
        <a href="#" class="inline-flex items-center px-6 py-3 bg-gray-800 border border-gray-700 text-white font-medium rounded hover:bg-gray-700 transition-colors">
            Fale com especialistas <span class="ml-2">→</span>
        </a>
    </div>
</div>

<SectionWrapper withBorderBottom={false} className="py-12">
    <div class="px-4 md:px-12">
        <!-- Top Row -->
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center border-b border-gray-200 border-dashed pb-12 mb-12">
            <div class="text-xs text-gray-500 mb-4 md:mb-0">
                +55 (11) 3323-3322 • ouvidoria@cg-one.com
            </div>
            
            <div class="flex space-x-6 text-xs text-gray-500 font-medium">
                <a href="#" class="hover:text-gray-900">Blog</a>
                <a href="#" class="hover:text-gray-900">Soluções</a>
                <a href="#" class="hover:text-gray-900">Clientes</a>
                <a href="#" class="hover:text-gray-900">Sobre Nós</a>
            </div>
        </div>

        <!-- Bottom Row -->
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center text-[10px] text-gray-400">
            <div class="mb-4 md:mb-0">
                ©2025 CG One. Todos os direitos reservados.
            </div>
            
            <div class="mb-4 md:mb-0">
                Av. Angélica, 2346, 13º andar, Consolação, São Paulo - SP, CEP 01228-200
            </div>
            
            <div class="flex space-x-4">
                <a href="#" class="hover:text-gray-600">Política de Privacidade</a>
                <span>•</span>
                <a href="#" class="hover:text-gray-600">Termos de Serviço</a>
            </div>
        </div>
    </div>
</SectionWrapper>

<!-- Cookie Banner -->
<div class="fixed bottom-4 right-4 bg-white border border-gray-200 shadow-lg p-4 rounded-lg max-w-sm z-50 flex items-center gap-4">
    <p class="text-xs text-gray-600">
        Usamos cookies para personalizar conteúdo e analisar tráfego, em conformidade com a LGPD.
    </p>
    <button class="text-xs font-medium bg-gray-100 hover:bg-gray-200 px-3 py-1 rounded transition-colors">
        Aceitar
    </button>
</div>
