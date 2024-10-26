# SEO (Search Engine Optimization)

  - É a otimização para motores de busca
  - Páginas HTML aparecendo nas pesquisas
  - SEO é um conjunto de técnicas e práticas que melhoram o posicionamento de um site ou conteúdo na internet. 
  - Isso é importante para aumentar o tráfego do seu site, garantindo que as pessoas encontrem as informações relacionadas ao seu negócio. 
  - Um site bem posicionado nos resultados de busca é mais visível para os clientes e pode aumentar as vendas. 
  - O SEO é essencial para os desenvolvedores, pois mesmo que o site esteja bem construído, se não for encontrado, não adianta.
  - SERP(Search Engine Result Page) - Página de resultados do motor de busca 

## Otimização
  - Fatores que definem uma boa otimização
    - `On-page` 
      É tudo que está dentro da página, que temos controle.
      - Técnico(Dev)
      - Conteúdo(Copywriter/Redator)
    - `Off-page`
      É tudo que está fora da nossa página, não temos controle.
      - Compartilhamento de links

  ![imageOnPage-OffPage](./assets/OnPage-OffPage.webp)

## Core Web Vitals (Principais Métricas da Web)
  [Introducing Web Vitals](https://blog.chromium.org/2020/05/introducing-web-vitals-essential-metrics.html)

  `3 Métricas que medem a experiência do usuário em sites.`

  ![imageCoreWebVitals](/assets/core-web-vitals.webp)
  
### `Largest Content Paint (LCP) — Tempo de Carregamento da Página`

  - A LCP, também conhecida como Maior Pintura de Conteúdo, verifica o tempo de renderização do conteúdo principal de uma página quando ela começa a carregar. 
  - O conteúdo principal geralmente é a maior imagem ou bloco de texto numa janela de visualização — uma área visível de um site no dispositivo de um usuário.

  Os dados LCP são compostos, principalmente, pelos seguintes elementos:

  - Elementos de imagens
  - Elementos de blocos de texto
  - Imagens de pôster de vídeo
  - Imagens de plano de fundo

  Os donos de sites precisam garantir que a pontuação das Core Web Vitals seja de 2,5 segundos ou menos para oferecer uma boa experiência de usuário e atingir a velocidade ideal do site.

---
### `Interaction to Next Paint (INP) — Interatividade da Página`

  - A INP mede o quão rápido sua página reage a uma interação do usuário, como clicar em um link ou em um botão de chamada.

  - Um tempo alto de INP indica que o visitante precisa esperar um tempo mais longo para a página atualizar após a interação. Isso pode prejudicar a experiência do usuário e aumentar sua taxa de rejeição.

  As pontuações INP são classificadas desta forma:

  - `Bom` – menos de 200 milissegundos
  - `Precisa melhorar` – entre 200 e 500 milissegundos
  - `Ruim` – mais de 500 milissegundos`

  Para melhorar sua classificação de INP, avalie o tamanho e a complexidade do seu site. Certifique-se de minificar arquivos JavaScript, ativar a compressão Gzip e usar uma rede de distribuição de conteúdo (CDN).

---
### `Cumulative Layout Shift — Experiência Visual do Site`

  - A CLS, ou Mudança Cumulativa de Layout, mede a estabilidade visual e verifica se há alguma mudança inesperada no layout da página do site.

  - O movimento inesperado ocorre quando elementos da página, como texto, botões e imagens são carregados de forma assíncrona e, com isso, empurrados para baixo enquanto a página ainda carrega.

  - Geralmente, esse tipo de mudança inesperada causa frustração no usuário porque ele pode clicar em outra coisa diferente da que realmente queria quando os elementos visuais mudam de lugar.

  A pontuação ideal de CLS é de 0,1 ou menos.

---
### `Ferramentas para Medir as Core Web Vitals`

  - Como as Core Web Vitals se tornaram um indicador de ranqueamento, os especialistas em SEO precisam monitorar suas pontuações e garantir que essas métricas performem bem para aparecerem no topo dos resultados de pesquisa do Google.

  As três ferramentas do Google que medem a Core Web Vitals são:

  - `PageSpeed Insights` — essa ferramenta apresenta os dados da Core Web Vitals em dispositivos móveis e em computadores durante os últimos 28 dias. Ela também exibe uma análise de teste de velocidade para verificar o tempo de carregamento do seu site. Para usar essa ferramenta, vá até o site do PageSpeed Insights, insira uma URL e clique no botão Analisar.

  - `Lighthouse` — é uma ferramenta de código aberto e automatizada que monitora o desempenho do site. O Lighthouse tem diversas métricas que o PageSpeed Insights não tem, como acessibilidade e SEO. Há dois métodos de usar essa ferramenta: a primeira é instalar a extensão; a segunda é clicar com o botão direito na página que deseja analisar e selecionar Inspecionar e depois clicar em Lighthouse.

  - `Search Console` — para visualizar o relatório de Core Web Vitals nessa ferramenta, basta ir até a seção Melhorias. Diferente do Lighthouse e do PageSpeed Insights, o Search Console permite verificar todas as páginas do seu site juntas.