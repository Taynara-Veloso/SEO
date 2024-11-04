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

### `Block Indexing(Bloqueando a indexação)`

  `Como bloquear a indexação do Google usando a estratégia "noindex".` 
  
  Essa estratégia permite que solicitemos ao Google que remova uma página dos resultados de busca. No entanto, é importante lembrar que essa estratégia não funcionará se a página estiver bloqueada no arquivo "robots.txt". 
  
  - A implementação é simples, basta adicionar uma meta tag com o nome "robots" e o conteúdo "noindex". 
  - Isso funciona para todos os crawlers. 
  - Também é possível adicionar outras estratégias, como "nofollow", para evitar que os links dentro da página sejam seguidos.

  `Exemplo 1 - Usando CMS`
  ```html
    <meta name="robots" content="noindex"> <!-- todos os crawlers -->
    <meta name="googlebot" content="noindex"> <!-- apenas o googlebot -->
  ```
  `Exemplo 2 - Adicionando no Header da requisição`

  - Utilizado para arquivos no geral, como pdf, videos, imagens, etc...
  ```
    X-Robots-Tag: noindex
  ```
  #### `Problemas`

  - Dependendo da relevancia da página, o google pode demorar meses para remover ela das pesquisas
  - `robots.txt` pode causar conflito com essa estratégia
  
  Para entender melhor o processo acesse o [suporte do google](https://developers.google.com/search/docs/crawling-indexing/block-indexing?hl=pt-br&sjid=429931964660093021-SA)

### `Canonicalization`

  `canonicalização e URLs canônicas:` 

 - A canonicalização é o processo de determinar qual é a `URL verdadeira` para o Google, quando há páginas duplicadas ou conteúdo duplicado. 
 - Isso pode acontecer quando há páginas com argumentos de filtro de busca, páginas com HTTP e HTTPS, ou versões de teste que ficaram online. 
 - O Google determina a URL canônica, mas podemos ajudar indicando qual é a página verdadeira. 
 - Podemos fazer isso através de redirecionamentos e do uso do atributo "relation canonical" no HTML. 
 - É importante sempre referenciar a URL canônica ao compartilhar conteúdo e evitar informações divergentes. 
 - O Google dará preferência ao HTTPS e considerará as páginas sugeridas no sitemap como canônicas.

 ```html
  <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <link rel="canonical" href="https://example.com/products"/>
      <title>Document</title>
    </head>
    <body>
    </body>
  </html>
 ```
 `arquivos não HTML`
 ```
  Link: <https://example.com/downloads/products-img.pdf>; rel="canonical"
 ```

### `Redirects`

  `Redirecionamento e como configurá-lo corretamente:`

- O redirecionamento é uma forma de informar ao Google que uma determinada URL não está mais disponível e foi movida para outro local. 
- Existem três etapas para configurar o redirecionamento: 
  - via servidor, através de respostas HTTP; `recomentado`
  - através de meta tags no código HTML da página; 
  ```html
    <meta http-equiv="refresh" content="0; url=https://example.com/newLocation">
  ```
  - via JavaScript. 
  
- Recomenda-se utilizar o redirecionamento via servidor, pois é mais eficiente. 
- Dependendo da ferramenta que você está utilizando, existem outras opções disponíveis. 

Como programadores, é importante entendermos essas técnicas para implementar o redirecionamento corretamente.

Para entender melhor o redirecionamento acesse o [suporte do google](https://developers.google.com/search/docs/crawling-indexing/301-redirects?hl=pt-br)

### `Structured Data`

  Structured Data(dados estruturados do Google):
  
  - Essa é uma forma de ajudar o Google a entender o tipo de conteúdo do seu site e como ele deve ser apresentado nos resultados de pesquisa. 
  - Você pode criar dados estruturados usando ferramentas como:
    - [WebCode.tools](https://WebCode.tools)
    - [search.google](https://search.google.com/test/rich-results)
    - [schema.org](https://schema.org/)
  - O schema.org é uma comunidade aberta que fornece diretrizes e documentação para ajudar na criação desses dados. 
  - Você pode testar seus dados estruturados usando a URL ou o snippet de código no schema.org. 

Lembre-se de sempre atualizar-se sobre as melhores práticas e usar as ferramentas disponíveis para facilitar o processo.

### `Sitelinks`

  Os Sitelinks são links agrupados que aparecem nos resultados de busca do Google.

  - `Objetivo:` Ajudar os usuários a encontrar informações com mais eficiência.

  - `Como funciona:` O Google utiliza um algoritmo de agrupamento de links para exibir esses Sitelinks.

  - `Quando é indexado?:` Eles são indexados e aparecem quando são úteis para o usuário. 

  - `Algumas melhores práticas para ter Sitelinks:`
    Por ser um processo automático do Google, existem algumas melhores práticas para ajudar a aparição dessa seção.

    - ter títulos e cabeçalhos relevantes e compactos, 
    - Uma estrutura lógica de fácil navegação para os usuários, 
    - Links para páginas importantes,
    - Evitar conteúdo repetitivo. 

  - `E para remover:` O Google também dá a dica de que é possível remover um Sitelink removendo a página ou utilizando a estratégia de noindex.

### `Metatags`

 As metatags são tags que ficam dentro do elemento `<head>` do seu documento HTML e fornecem informações sobre o conteúdo da página. Algumas das metatags que o Google considera são: 
  - A definição do conjunto de caracteres utilizado, 
  - A indicação de que o site é responsivo para dispositivos móveis, 
  - Uma descrição da página, 
  - A autoridade do site,
  - A configuração do Safe Search. 

  `Exemplo:`
  ```html
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="Author: T.V. Author, Illustrator: P. Picture, Category: Books, Price: $5.99, Length: 567 pages">
        <meta name="google-site-verification" content="=nxGUDJ$QpAZ5l9Bsjdi102tLVC21AIh5d1Nl23908vVuFHs34=">
        <title>Document</title>
        <meta name="robots" content="noindex,nofollow">
        <meta name="rating" content="adult">
      </head>
      <body>
      </body>
    </html>
  ```

### `Título e descrição`

- O Title deve ser único para cada página e definir claramente o objetivo da página. 
- Evite repetir títulos em outras páginas do seu site, pois isso diminui a relevância para o SEO. 
- O Description não afeta o ranqueamento nas pesquisas, mas é útil para explicar o conteúdo da página.
  - Não repetir nas suas páginas para manter a relevância da página para o SEO.
- Use a ferramenta [mangools](https://mangools.com/free-seo-tools/serp-simulator?ref=menu-kw) para verificar se o título e a descrição estão adequados. 
- O Title e o Description são metatags que devem ser colocadas no cabeçalho da página.

`Exemplo:`
  ```html
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="Presenteie quem você ama ou renove o guarda-roupa com a Loja Pink Padme. Aliando experiência, modernidade e preços acessíveis para toda a família.">
        <title>Loja de roupas em Taubaté | P.P</title>
      </head>
      <body>
      </body>
    </html>
  ```
#### `Google modifica títulos e descrições`

  O Google pode alterar títulos que sejam:
  - clickbaits, ou seja, títulos que não correspondem ao conteúdo da página. 
  - Pode modificar títulos que sejam muito longos ou que contenham apenas palavras-chave. 
  - Pode alterar as descrições das páginas para melhor atender aos usuários. 
  - É importante entender essas modificações e criar títulos coerentes para melhorar o SEO. 
  - Pode usar links internos da página para gerar títulos relevantes. 

  Por fim, a importância de criar uma Meta Description é para ajudar os usuários a entenderem o conteúdo da página.

### `Open Graph`

  Open Graph são as meta-tags para as mídias sociais. 
  Essas tags são importantes para controlar a aparência de um link compartilhado nas redes sociais, como:
  - Facebook
  - LinkedIn
  - Twitter

  O objetivo é tornar o conteúdo mais atrativo e explicativo, gerando engajamento e mais cliques para a página. 
  Existem várias meta-tags disponíveis, mas as principais são:
  - `og:title` — serve para fazer a indicação do título da página que será mostrada na mídia social;
  - `og:description` — é útil para descrever de forma abreviada. Aparece logo abaixo do título;
  - `og:image` — indica a imagem que será apresentada na hora de linkar o conteúdo na rede social;
  - `og:type` — descreve o tipo de site de web que está sendo compartilhado;
  - `og:url` — apresenta a url da página disponibilizada na rede social.

  ![imgOg:Tags](/assets/ogTags.webp)

  ```html
    <meta property="og:title" content="descrever o título do artigo" />
    <meta property="og:type" content="tipo de conteúdo" />
    <meta property="og:image" content="url da imagem"/>
    <meta property="og:image:width" content="1200"/>
    <meta property="og:image:height" content="630"/>
    <meta property="og:url" content="url do conteúdo"/>
    <meta property="og:description" content="descrição do conteúdo"/>
  ```

  Além disso, também temos o Twitter Card, que funciona de forma semelhante ao Open Graph.

  ```html
    <meta name="twitter:card" content="summary" />
    <meta name="twitter:title" content="descrever o título do artigo" />
    <meta name="twitter:description" content="descrição do conteúdo" />
    <meta name="twitter:url" content="url do conteúdo" />
    <meta name="twitter:site" content="@siteexample" />
    <meta name="twitter:creator" content="@userexample" />
    <meta name="twitter:image" content="https://images.com/image.jpg" />
  ```

  É importante testar as tags usando ferramentas como o [Facebook Debugger](https://webcode.tools/open-graph-generator/article) e o [Post Inspector](https://www.linkedin.com/post-inspector/) do LinkedIn para garantir que o compartilhamento esteja correto.

### `Tags de Texto`

  As tags de texto são como a organização de um livro, e é importante estruturá-las corretamente para que o motor de busca entenda o conteúdo da página. 

  - O `<h1>` é o título principal da página e deve ser semelhante ao título do head. 
  - Os `<h2>` são subtítulos e podem ter sub-blocos com `<h3>`. 
  - Os parágrafos são marcados com a tag `<p>`. 
  - A tag `<strong>` é usada para dar ênfase ao texto. 
  - A tag `<a>` é usada para criar links internos e externos.

  Quanto mais links e menos dependência de estilos, melhor para o SEO.

### `Navegação`

  É fundamental que os visitantes consigam se encontrar facilmente e que o robô de busca também entenda a relevância das páginas. 
  Como a navegação pode ser organizada de forma eficiente:

  ![imageNavegation](/assets/navegation.jpg)

  Para ser eficiente o usuário deve conseguir chegar ao destino em poucos cliques.

  ![imageNavegation](/assets/responsive-navbar.png)
  
  `Navegação mobile friendly:`

  No mobile é necessário usar um icon para guardar todos os items da navegação, como se fosse uma gaveta.
  
  ![imageNavegation](/assets/MobileFriendly.jpg)

  #### `Breadcrumbs:`

  Uma `navegação de trilha` fornece links para cada página anterior pela qual o usuário navegou e mostra a localização atual do usuário em um site.
  - Ajudam tanto os usuários quanto os motores de busca. 
  - É como migalhas pelo caminho

  `Exemplo:`
  ![imageNavegation](/assets/Breadcrumbs.png)
  Para mais informações acesse a [Central de Pesquisa Google](https://developers.google.com/search/docs/appearance/structured-data/breadcrumb?hl=pt-br)
  
  `Página 404 coerente:`
  - Não pode ser o fim da navegação.
  - Precisa ter um link de redirecionamento

  ![imageNavegation](/assets/404.webp)

  `Navegação de Rodapé:`

  A navegação de rodapé é uma função que permite que os usuários interajam 
  com um segmento de detalhes de um formulário. 
  O rodapé de um site, ou footer, é a área final das páginas de um site e 
  geralmente contém informações como:
  -  Endereço
  -  Contato
  -  Links para páginas importantes
  -  Políticas de privacidade
  -  Termos e condições de troca e devolução
  -  Selos de segurança
  -  Redes sociais

  ![imageNavegation](/assets/bootstrap-footer.jpg)

  #### `Recomendações sobre navegação`

  - Não coloque qualquer coisa na navegação principal
    - Tem que ser simples.
    - Tem que ser fácil para o usuário navegar.
  - Planejar a hierarquia da navegação
    - Tópicos
    - Categorias
  - Utilizar textos e HTML semântico
    - `<nav>`
    - `<ul>`
    - `<li>`
    - `<a>`
    ```html
      <nav class="container">
        <ul class="header">
          <li><a href="#">Home</a></li>
          <li><a href="News">News</a></li>
          <li><a href="Blog">Blog</a></li>
          <li><a href="Courses">Courses</a></li>
          <li><a href="ContactUs">Contact Us</a></li>
        </ul>
      </nav>
    ```
  - Página exclusiva
    - Lista estruturada que lista todas as páginas do seu site
    - É um mapa do site em HTML para o usuário

### `Otimização de imagens`

  - Imagens são pesadas e podem deixar o site lento, então é importante trabalhar com tamanhos adequados e responsivos.

  - Além disso, é recomendado utilizar formatos mais modernos, como `avif` e `webp`, que reduzem o tamanho da imagem sem perder qualidade. 

  - A estratégia de `Lazy Loading` também é útil, carregando as imagens apenas quando são visíveis na página. 

  - Definir largura e altura da imagem ajuda a evitar problemas de layout. 

  - Atributos como:
    - source
    - alt
    - source set `conjunto de imagens`
    - sizes 
    - loading `lazy | eager`
    - decoding `sync | async | auto`
    - fetch priority `high | low | auto`
  
    também são importantes para otimizar as imagens. 

    ```html
      <img 
        src="/assets/foto_example.avif"
        alt="Taynara Veloso"
        srcset="/assets/foto_example.avif 320w /assets/foto_example.avif 402w"
        sizes="(min-width: 402px) 402px, 100vw"
        width="402"
        height="402"
        loading="lazy"
        decoding="async"
        fetchpriority="high" 
      />
    ```

### `Lazy Load Third Party Content (Carregamento lento de conteúdo de terceiros)`

  Lazy Load é uma estratégia para carregar e ler conteúdos de terceiros, como embeds do YouTube ou integrações com redes sociais.

  [Carregamento lento de conteúdo de terceiros](https://developer.chrome.com/docs/lighthouse/performance/third-party-facades?hl=pt-br):

    significa atrasar o carregamento de conteúdo externo, como vídeos incorporados ou postagens em mídias sociais, até que o usuário realmente precise vê-lo na página, normalmente rolando perto dele, melhorando assim a velocidade de carregamento inicial da página, carregando apenas o conteúdo crítico primeiro. 

  `Benefícios:`

  Reduz o tempo de carregamento inicial da página, especialmente ao lidar com grandes scripts de terceiros que não são imediatamente visíveis para o usuário. 

  #### Como funciona:
  `Espaços reservados:` 

    Um elemento de espaço reservado é exibido no local onde o conteúdo de terceiros estará, que se parece com o conteúdo real, mas não exige o carregamento de scripts pesados. 

  `Gatilho de interação do usuário:` 

    Quando o usuário interage com o espaço reservado (como clicar nele ou rolar perto dele), o conteúdo real de terceiros é carregado dinamicamente.

  A ideia é usar uma `fachada`, um elemento estático que se parece com o conteúdo desejado, mas sem as funcionalidades completas. Isso adia o carregamento e permite identificar e tratar o tipo de conteúdo. 
  
  Para identificar, podemos usar o [pagespeed.web.dev.](https://pagespeed.web.dev/) 
  
  Ao aplicar o Lazy Load, podemos melhorar o desempenho do site e a pontuação de performance.

  ![imageNavegation](/assets/lazyload-facade-example.jpg)

### `Mobile Friendly`

  O Google dá grande importância ao conteúdo otimizado para dispositivos móveis, através da iniciativa Mobile First Indexing. 
  
  Recomenda-se o uso de estratégias como responsividade e [AMP (Accelerated Mobile Pages)](https://developers.google.com/amp?hl=pt-br) para melhorar a experiência do usuário em dispositivos móveis. 
  
  É essencial ter uma meta tag viewport e evitar bloqueios de recursos no robots.txt. 
  
  A ferramenta [Lighthouse](https://pagespeed.web.dev/) pode ser usada para analisar e melhorar a performance do site em dispositivos móveis. 
  
  Ao implementar essas estratégias, seu site estará mais amigável para dispositivos móveis e será melhor indexado pelo Google.