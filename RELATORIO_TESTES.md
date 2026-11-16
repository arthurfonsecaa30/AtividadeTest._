1. Métricas de Desempenho (Performance) <br>
  First Contentful Paint (FCP) (Primeira Pintura com Conteúdo),"0,4 s"<br>
  Largest Contentful Paint (LCP) (Maior Pintura com Conteúdo),"2,2 s"<br>
  Total Blocking Time (TBT) (Tempo Total de Bloqueio),0 ms<br>
  Cumulative Layout Shift (CLS) (Mudança Cumulativa de Layout),0<br>
  Speed Index (Índice de Velocidade),"0,6 s"<br>

2. Diagnósticos e Oportunidades de Melhoria<br>
  Otimizar a entrega de imagens (Economia estimada de 1.811 KiB): Reduzir o tamanho e o tempo de download das imagens melhorará<br>
 o tempo de carregamento percebido e o resultado de LCP.<br>
  Descoberta da requisição LCP: Para otimizar o LCP, a imagem principal deve ser detectável imediatamente no HTML, evitando o<br>
uso de carregamento tardio (lazy-loading) nela e aplicando o atributo fetchpriority="high".<br>
  Árvore de dependências de rede (Latência máxima do caminho crítico: 421 ms): Recomenda-se evitar o encadeamento de requisições<br>
críticas, reduzindo o tamanho dos arquivos ou adiando o carregamento de recursos desnecessários:<br>
    /AtividadeTest._/ (arthurfonsecaa30.github.io) — 238 ms | 1,78 KiB<br>
    /AtividadeTest._/style.css (arthurfonsecaa30.github.io) — 421 ms | 1,16 KiB<br>
    /AtividadeTest._/script.js (arthurfonsecaa30.github.io) — 337 ms | 0,00 KiB<br>
  Requisições que bloqueiam a renderização: Arquivos externos (como CSS e JS) estão atrasando a renderização inicial da página.<br>
  Políticas de cache eficientes (Economia estimada de 1 KiB): Configurar tempos de cache adequados para o armazenamento local dos<br>
arquivos estáticos.<br>

4. Acessibilidade e Usabilidade<br>
  Contraste de cores: Apenas o botão "CLIQUE AQUI" apresenta falha de contraste entre a cor do texto e a cor de fundo; os demais<br>
  elementos da página estão adequados.<br>
  Responsividade: A página não apresenta redimensionamento nem adaptação adequada para dispositivos móveis (mobile).<br>
