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

### `3 Estágios do Google`
  Como trabalham os robôs e algoritmos do Google:

  - CRAWLING
    - É quando o robô do Google procura na internet por textos, imagens e vídeos
    
  - INDEXING
    - É quando o algoritmo do Google observa o conteúdo das páginas, como título, 
      imagens e vídeos, e decide se a página será indexada
    
  - SERVING
    - É quando o Google entrega os resultados da pesquisa para o usuário, levando 
      em consideração fatores como localização e tipo de dispositivo

### `Rendering`

  - É o processo de transformar o JavaScript em HTML. 
  - O robô precisa interpretar o JavaScript como se fosse HTML para entender o conteúdo da página.
  - O Crawler pode encontrar páginas que não estão completamente renderizadas, ou seja, construídas principalmente com JavaScript. 
    - Isso requer uma fila de renderização antes que o conteúdo possa ser indexado. 

### `URL(Uniform Resource Locator)`
  
  `Uma URL é um localizador de recursos único, como:`
  - Uma página HTML, 
  - Um arquivo JavaScript, 
  - Uma imagem ou um vídeo. 

  `Melhores práticas de URLs:`
    
  - É importante entender que as URLs não devem conter caracteres especiais ou espaços, 
  sendo convertidas para o formato ASCII válido. 
    
    `Ao criar uma URL, é recomendado que ela seja:`
      - Simples, 
      - Descritiva,
      - Contenha palavras relevantes. 

      ```
      https://blog.exemplo.com.br/aprendendo-sobre-url
      ```
      
      `Além disso, é importante considerar a transformação para UTF-8 e evitar práticas ruins, como:`
      
      - O uso de caracteres especiais, 
      - Underscores e espaços,
      - Palavras juntas
      
        Ruim para a leitura de um ser humano.

      `Problemas comuns podem surgir quando não há um padrão na estrutura da URL, como:`
      - A presença de muitos parâmetros de pesquisa. 
      
      `Para resolver esses problemas`, é necessário criar uma estrutura de URL organizada e inteligível, 
      bloquear o acesso a URLs problemáticas no arquivo robots.txt 
       
      `Evitar o uso de IDs de sessão nas URLs.` 
      Considere usar cookies em vez disso
      
      `Também é importante considerar:`
      - Uso de `certificados SSL` para encriptar os dados e transformar o HTTP em `HTTPS`. 
      - O Google considera URLs com e sem www como diferentes. 
        - É recomendado adicionar todas as versões no Search Console.
        ```
        http://exemplo.com.br
        https://exemplo.com.br
        http://www.exemplo.com.br
        https://www.exemplo.com.br
        ```
      - Trabalhar com redirecionamentos canônicos para evitar conteúdo duplicado.

### `Links`

  Os links são utilizados para encontrar uma nova página, devem ser claros e explicativos.
  `Exemplo links rastreáveis:`
  ```html
    <a href="https://exemplo.com">
    <a href="/products/category/shoes">
  ``` 
  - Utilizando o atributo "title" ou o texto alternativo da imagem "alt" para fornecer informações sobre a página de destino.
  É recomendado usar textos simples e concisos, evitando frases genéricas como "clique aqui". 
 
  `Exemplo:`
  ```html
    <a href="https://exemplo.com/products" title="Product list"></a>

    <a href="https://exemplo.com/products">
      <img src="img-exemplo.jpg" alt="product image">
    </a>
  ``` 

  - `links internos:` Ajudam o Google a entender a estrutura do seu site.
    - Referencia ao próprio conteúdo,
    - Melhor entendimento so Google em relação ao site como um todo.
    - Ajuda a encontrar outras páginas dentro do seu próprio site.
      - É recomendado ter ao menos 1 link referenciando outra página pois ajuda na experiência do usuário.

  - `links externos:` Estabelecem confiança e relevância. 
    - Ajuda a estabelecer confiança pois geralmente as pessoas irão citar bons sites para seus leitores e o 
    robô do Google entende que o conteúdo é relevante, pois está citando a fonte.
    - É ótimo para o robô encontrar novos bons sites, aumentando a relevância perante o robô.
    - Se você não confiar na fonte use `no-follow`
      - `tag "nofollow":` Serve para qualificar links externos e evitar que sejam seguidos pelo robô do Google.
      ```html
        <a rel="nofollow" href="https://www.exemplo.com.br">App Example</a>
        <!-- 
          nofollow, ugc, sponsored:
          são valores para usar no atributo relationship e podem ser 
          utilizados múltiplos, apenas separando por vírgulas. 
        -->
      ```

### `Sitemap`

  - É um arquivo que lista todas as páginas do seu site. 
  - Ele ajuda os mecanismos de busca a encontrar e indexar seu site de forma eficiente. 
  O Sitemap é útil para:
  - comunicar páginas novas, atualizadas e/ou relevantes 
  - fornecer informações detalhadas sobre o conteúdo do site.
    - Vídeos: duração, avaliação, restrição de idade.
    - Imagem: Localização da imagem.
    - Notícias: título e data de publicação.
  - É especialmente recomendado para sites grandes e complexos. 
  - Sites novos.
  
  Existem várias maneiras de criar um Sitemap, incluindo o uso de geradores online ou ferramentas como o Screaming Frog. 
  Recomendamos o uso do [xml-sitemaps.com](https://www.xml-sitemaps.com/) se você não tiver uma ferramenta que já crie o Sitemap para você.

  `Exemplo de xml:`
  ```xml
  <?xml version="1.0" encoding="UTF-8"?>
  <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
    <url>
      <loc>https://www.example.com/foo.html</loc>
      <lastmod>2022-06-04</lastmod>
      <changefreq>monthly</changefreq>
      <priority>0.8</priority>
    </url>
  </urlset>
  ```

### `Robots.txt`

  Gerenciamento de tráfego para o crawler

  - Cuidados com a sobrecarga de requisições
    - O robots.txt permite definir permissões e restrições para os bots de busca. 

  - Não é um mecanismo para manter páginas fora do Google
    - Para isso, podemos usar a estratégia de bloquear indexação com `noindex`

  - Pode manter arquivos fora do Google
    - É importante ressaltar que o robots.txt não impede que as páginas sejam indexadas pelo Google, mas pode ser usado para bloquear arquivos específicos, como áudio, imagem, vídeo, scripts ou CSS. 
    - No entanto, é preciso ter cuidado ao bloquear esses arquivos para não afetar a funcionalidade das páginas. 

    - O arquivo robots.txt deve ser criado na raiz do site, seguindo algumas regras simples. 
      ``` 
      Serviços de criação de sites como Wix ou Blogger, não precisa dessa etapa, pois o gerenciamento é feito conforme a plataforma 
      ```
      - Criar um arquivo de nome `robots.txt`.(Em formato UTF-8, max 500kib)
      - Criar regras desejadas.
      - Criar na raiz do código.

  É possível definir diretivas para diferentes user-agents, como o Googlebot, e especificar quais URLs são permitidas ou negadas. 

  `A regra fundamental é que toda url será aceita, a menos que seja negada`
  ```
  User-agent: Googlebot
  Disallow: /nogooglebot/

  User-agent: *
  Allow: /

  Sitemap: https://www.example.com/sitemap.xml
  ```

  `Exemplo 2:`

  ```
  # Examplo 1: block only Googlebot(Robô do Google)

  User-agent: Googlebot
  Disallow: /

  # Examplo 2: block Googlebot and Adsbot

  User-agent: Googlebot
  User-agent: AdsBot-Google
  Disallow: /

  # Examplo 3: block all crawlers except Adsbot (Adsbot crawlers must be named explicitly)

  User-agent: *
  Disallow: /
  Disallow: /*.xls$
  Allow: /public/

  ```
  É importante lembrar que o robots.txt funciona apenas no domínio principal e não nos subdomínios. 
  Além disso, pode haver uma demora de até 24 horas para que as alterações no arquivo sejam refletidas.

  Para mais informações acesse a [documentação](https://developers.google.com/search/docs/crawling-indexing/robots/intro?hl=pt-br)