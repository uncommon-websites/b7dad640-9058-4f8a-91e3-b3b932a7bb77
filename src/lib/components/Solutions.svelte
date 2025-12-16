<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-serif text-4xl text-gray-900">Nossas soluções</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="Identificar & Proteger"
      title="Gestão de riscos e proteção"
      description="Identifique vulnerabilidades em sistemas, ativos e dados. Implemente soluções de proteção para garantir a entrega de serviços críticos e proteger sua infraestrutura contra ameaças cibernéticas."
    >
      <!-- Visual for Block 1: Shield Protection -->
      <div class="relative w-full h-full flex items-center justify-center">
        <!-- Central Shield -->
        <div class="w-20 h-20 bg-gray-900 shadow-lg rounded-lg flex items-center justify-center z-10 border-2 border-gray-700">
           <svg class="w-10 h-10 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
             <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
           </svg>
        </div>
        
        <!-- Security Elements -->
        <div class="absolute top-1/4 left-1/4 bg-white p-3 shadow rounded border border-gray-100 animate-pulse">
            <div class="text-[10px] font-bold text-gray-700">Firewall</div>
        </div>
        <div class="absolute top-1/4 right-1/4 bg-white p-3 shadow rounded border border-gray-100">
            <div class="text-[10px] font-bold text-gray-700">IDS/IPS</div>
        </div>
        <div class="absolute bottom-1/4 left-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="text-[10px] font-bold text-gray-700">SIEM</div>
        </div>
         <div class="absolute bottom-1/4 right-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="text-[10px] font-bold text-gray-700">EDR</div>
        </div>
        
        <!-- Connecting Lines -->
        <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-20" viewBox="0 0 400 300">
            <path d="M100 100 L200 150 M300 100 L200 150 M150 220 L200 150 M250 220 L200 150" stroke="currentColor" stroke-width="1" stroke-dasharray="4 4" />
        </svg>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="Detectar & Responder"
      title="Monitoramento e resposta 24/7"
      description="SOC com inteligência artificial para detecção contínua de eventos de segurança. Resposta automatizada a incidentes com análise em tempo real e ações imediatas para neutralizar ameaças."
      reversed={true}
    >
      <!-- Visual for Block 2: Threat Alert -->
      <div class="bg-white rounded-lg shadow-xl p-6 w-3/4 max-w-sm border border-red-200">
        <div class="flex items-center space-x-3 mb-4">
            <div class="w-8 h-8 rounded-full bg-red-100 flex items-center justify-center">
                <svg class="w-4 h-4 text-red-600" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M8.257 3.099c.765-1.36 2.722-1.36 3.486 0l5.58 9.92c.75 1.334-.213 2.98-1.742 2.98H4.42c-1.53 0-2.493-1.646-1.743-2.98l5.58-9.92zM11 13a1 1 0 11-2 0 1 1 0 012 0zm-1-8a1 1 0 00-1 1v3a1 1 0 002 0V6a1 1 0 00-1-1z" clip-rule="evenodd"></path>
                </svg>
            </div>
            <div class="text-xs text-gray-500">Alerta de Ameaça • Crítico</div>
        </div>
        <h4 class="font-serif text-xl mb-4 text-red-600">Tentativa de Intrusão</h4>
        <div class="space-y-2 mb-6 text-xs text-gray-600">
            <div class="flex justify-between"><span>Origem:</span><span class="font-mono">185.220.101.45</span></div>
            <div class="flex justify-between"><span>Tipo:</span><span>Brute Force SSH</span></div>
            <div class="flex justify-between"><span>Status:</span><span class="text-green-600 font-bold">Bloqueado</span></div>
        </div>
        <button class="w-full bg-gray-900 text-white py-2 rounded text-sm font-medium flex items-center justify-center space-x-2">
            <span>Analisar Incidente</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </button>
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Recuperar & Governar"
      title="Continuidade e conformidade"
      description="Garanta disponibilidade e recuperação rápida de sistemas afetados. Políticas, procedimentos e processos para monitorar requisitos regulatórios, legais e de gestão de riscos alinhados ao NIST."
    >
       <!-- Visual for Block 3: Compliance Report -->
       <div class="bg-white rounded shadow-lg p-8 w-2/3 max-w-xs border border-gray-100 relative">
          <div class="flex justify-between items-center mb-6 border-b pb-2">
              <div class="font-bold text-xs">CG One</div>
              <div class="w-4 h-4 bg-gray-900 rounded-full"></div>
          </div>
          <div class="mb-4">
              <h5 class="font-bold text-sm">Relatório de Conformidade</h5>
              <div class="text-[10px] text-gray-400">NIST Cybersecurity Framework 2.0</div>
          </div>
          <div class="space-y-3 text-[9px] text-gray-600">
              <div class="flex justify-between items-center">
                <span>Identificar</span>
                <span class="text-green-600 font-bold">✓ 98%</span>
              </div>
              <div class="flex justify-between items-center">
                <span>Proteger</span>
                <span class="text-green-600 font-bold">✓ 95%</span>
              </div>
              <div class="flex justify-between items-center">
                <span>Detectar</span>
                <span class="text-green-600 font-bold">✓ 100%</span>
              </div>
              <div class="flex justify-between items-center">
                <span>Responder</span>
                <span class="text-green-600 font-bold">✓ 97%</span>
              </div>
          </div>
       </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
