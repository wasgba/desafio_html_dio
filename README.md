# desafio_html_dio
foi feito uma pagina html para descrever o que foi visto durante o modulo de html  na pratica 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <!-- Definindo o charset UTF-8 para garantir a correta exibição de caracteres especiais em português -->
    <meta charset="UTF-8">
    <!-- Meta tag para garantir que o layout será responsivo em dispositivos móveis -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aprendendo HTML na Prática</title>
</head>
<body>
    <!-- Cabeçalho principal da página -->
    <h1>Módulo 1 - Primeiros Passos com HTML</h1>
    <hr />

    <!-- Índice de navegação -->
    <h2 id="indice">Índice</h2>
    <p><strong><u>INSTRUÇÕES:</u></strong> Para aprender a instalar e configurar o ambiente de desenvolvimento, entender o funcionamento do inspetor de elementos do navegador e criar sua primeira página HTML.</p>
    
    <!-- Breve resumo sobre a história dos computadores -->
    <p><strong>Antes, vamos fazer um breve resumo sobre "A História dos Computadores":</strong> A história dos computadores é marcada por grandes avanços tecnológicos que transformaram a maneira como vivemos. No início, dispositivos mecânicos como o ábaco eram usados para cálculos simples. Em 1837, Charles Babbage projetou uma "Máquina Analítica", o primeiro conceito de um computador programável. Anos depois, Ada Lovelace, considerada a primeira programadora, escreveu algoritmos para essa máquina.</p>
    <p>Durante a Segunda Guerra Mundial, a necessidade de cálculos complexos impulsionou o desenvolvimento de máquinas eletrônicas. Em 1943, o Colossus, o primeiro computador digital eletrônico programável, foi construído para decifrar códigos. Em 1946, o ENIAC foi desenvolvido nos EUA, marcando o nascimento dos computadores de grande escala.</p>
    <p>Nos anos 1950 e 1960, surgiram os primeiros computadores comerciais e mainframes, acessíveis apenas para grandes empresas e instituições.</p>
    <p>Na década de 1990, a internet se popularizou, conectando milhões de computadores ao redor do mundo e revolucionando a comunicação e o acesso à informação. Hoje, os computadores são essenciais em praticamente todas as áreas da sociedade, e avanços em inteligência artificial e computação quântica prometem moldar o futuro da tecnologia.</p>

    <!-- Links para navegação dentro da página -->
    <ul>
        <li><a href="#Ferramentas-utilizadas">Ferramentas utilizadas</a></li>
        <li><a href="#Usando-o-Inspetor-de-Elementos">Usando o Inspetor de Elementos</a></li>
        <li><a href="#Estrutura-basica-html">Estrutura básica do HTML</a></li>
        <li><a href="#Falando-sobre-tags">Falando sobre Tags</a></li>
        <li><a href="#Atributos-basicos">Atributos básicos</a></li>
        <li><a href="#Textos-no-html">Textos no HTML</a></li>
        <li><a href="#Listas-ordenadas-e-nao-ordenadas">Listas ordenadas e não ordenadas</a></li>
        <li><a href="#Links">Links de referências</a></li>
    </ul>

    <h2 id="Ferramentas-utilizadas"><strong>Ferramentas utilizadas</strong></h2>
    <p>Para desenvolver nosso projeto de forma prática e eficiente, usaremos algumas ferramentas essenciais. Primeiramente, utilizaremos o <strong>Visual Studio Code</strong> (VS Code), que é um editor de código aberto, gratuito e amplamente utilizado. Por ser <i>open source</i> e multiplataforma, ele é compatível tanto com Linux quanto com Windows, proporcionando comodidade para todos os tipos de ambiente de desenvolvimento. O VS Code possui uma interface intuitiva e oferece uma vasta gama de extensões, o que permite personalizar e otimizar o ambiente de acordo com nossas necessidades.</p>
    <p>Além do editor de código, o navegador <strong>Google Chrome</strong> será outra ferramenta fundamental para visualizar e testar nosso projeto. O Chrome é amplamente usado para desenvolvimento web por conta de suas <i>ferramentas de desenvolvedor</i> integradas, que permitem executar o código, monitorar o desempenho, depurar erros e testar o layout responsivo.</p>
    <p><a href="#indice">Voltar ao índice</a></p>

    <h2 id="Usando-o-Inspetor-de-Elementos"> <strong>Inspetor de elementos </strong></h2>
    <p><strong><u>O INSPETOR DE ELEMENTOS:</u></strong> é uma ferramenta essencial integrada nos navegadores modernos, como o Google Chrome, que permite visualizar e editar o código HTML, CSS e JavaScript de uma página web em tempo real. Através dele, é possível explorar a estrutura HTML da página, modificar elementos específicos, ajustar estilos e testar alterações diretamente no navegador, sem a necessidade de editar os arquivos originais. Essa funcionalidade é extremamente útil para desenvolvedores, pois permite depurar o layout, analisar o comportamento dos scripts e verificar a responsividade de uma página em diferentes dispositivos.</p>
    <p><a href="#indice">Voltar ao índice</a></p>

    <h2 id="Estrutura-basica-html"><strong>Estrutura básica do HTML</strong></h2>
    <p>As estruturas básicas do HTML são compostas por um conjunto de elementos essenciais para criar uma página web simples e funcional. Cada página HTML começa com a declaração <code>&lt;!DOCTYPE html&gt;</code>, que informa ao navegador que o documento usa a versão HTML5. Em seguida, a tag <code>&lt;html&gt;</code> envolve todo o conteúdo da página. Dentro dela, a tag <code>&lt;head&gt;</code> contém metadados como o <code>&lt;title&gt;</code>, que define o título da página exibido na aba do navegador, e a tag <code>&lt;meta charset="UTF-8"&gt;</code>, que define a codificação de caracteres para evitar problemas de exibição. A tag <code>&lt;body&gt;</code>, por sua vez, é onde fica o conteúdo visível da página, como textos, imagens, links e listas.</p>

    <p>Para escrever uma página básica em HTML, você pode usar uma estrutura como esta:</p>
    <pre><code>&lt;!DOCTYPE html&gt;
        &lt;html lang="pt-BR"&gt;
            &lt;head&gt;
                &lt;meta charset="UTF-8"&gt;
                &lt;title&gt;Minha Primeira Página&lt;/title&gt;
            &lt;/head&gt;
            &lt;body&gt;
                &lt;h1&gt;Bem-vindo ao meu site!&lt;/h1&gt;
                &lt;p&gt;Este é o meu primeiro parágrafo em HTML.&lt;/p&gt;
            &lt;/body&gt;
        &lt;/html&gt;
        </code></pre>
        <p>Nesse exemplo, o título da página é "Minha Primeira Página", que aparece na aba do navegador. No corpo, &lt;h1&gt; define um título principal, e &lt;p&gt; é usado para criar um parágrafo.</p>      
    <p><a href="#indice">Voltar ao índice</a></p>

    <h2 id="Falando-sobre-tags"><strong>Falando sobre tags</strong></h2>
    <p>As tags de formatação de texto são essenciais para definir a estrutura do conteúdo em uma página HTML. As tags <code>&lt;h1&gt;, &lt;h2&gt;, &lt;h3&gt;, &lt;h4&gt;</code> são usadas para criar títulos e legendas. O <code>&lt;p&gt;</code> é usado para definir parágrafos de texto. As tags <code>&lt;strong&gt;, &lt;i&gt;,</code> e <code>&lt;u&gt;</code> são usadas para formatação de texto (negrito, itálico e sublinhado, respectivamente). Mais abaixo, mostramos um exemplo prático para explicar essas tags.</p>
    
    <pre><code>&lt;!DOCTYPE html&gt;
    &lt;html lang="pt-BR"&gt;
        &lt;head&gt;
            &lt;meta charset="UTF-8"&gt;
            &lt;title&gt;Exemplo de Formatação em HTML&lt;/title&gt;
        &lt;/head&gt;
        &lt;body&gt;
            &lt;h1&gt;Guia de Formatação HTML&lt;/h1&gt;
            &lt;h2&gt;Introdução ao HTML&lt;/h2&gt;
            &lt;p&gt;O HTML é a base para criar páginas web. Este documento serve como um exemplo das principais tags de texto.&lt;/p&gt;
            &lt;h3&gt;Estrutura de Cabeçalhos&lt;/h3&gt;
            &lt;h4&gt;Usando Cabeçalhos para Organizar Títulos&lt;/h4&gt;
            &lt;p&gt;&lt;strong&gt;Negrito:&lt;/strong&gt; O texto em negrito chama mais atenção.&lt;/p&gt;
            &lt;p&gt;&lt;i&gt;Itálico:&lt;/i&gt; O texto em itálico é usado para destacar algo ou referenciar uma citação.&lt;/p&gt;
            &lt;p&gt;&lt;u&gt;Sublinhado:&lt;/u&gt; O texto sublinhado pode ser usado para destacar informações importantes.&lt;/p&gt;
        &lt;/body&gt;
    &lt;/html&gt;</code></pre>

    <p><a href="#indice">Voltar ao índice</a></p>
  
    <h2 id="Atributos-basicos"><strong>Atributos básicos</strong></h2>
    <p>Os atributos são propriedades adicionais que as tags podem ter para definir comportamentos específicos ou adicionar características aos elementos. Por exemplo, a tag &lt;a&gt; possui o atributo <code>href</code>, que define o link de destino. Outro exemplo seria o atributo <code>src</code> nas tags de imagem, como <code>&lt;img&gt;</code>, que especifica a fonte do arquivo de imagem. Exemplo:</p>
    <pre><code>&lt;a href="https://www.exemplo.com"&gt;Clique aqui&lt;/a&gt;</code></pre>
  
    <p><a href="#indice">Voltar ao índice</a></p>

    <h2 id="Textos-no-html"><strong>Textos no HTML</strong></h2>
    <p>Em HTML, o texto pode ser incluído de diversas formas. Para criar títulos e subtítulos, usamos as tags <code>&lt;h1&gt;</code> a <code>&lt;h6&gt;</code>. Já para parágrafos, usamos a tag <code>&lt;p&gt;</code>. O HTML também suporta outros tipos de formatação, como listas e links.</p>

    <p><a href="#indice">Voltar ao índice</a></p>

    <h2 id="Listas-ordenadas-e-nao-ordenadas"><strong>Listas ordenadas e não ordenadas</strong></h2>
    <p>As listas são muito úteis quando precisamos apresentar informações de maneira organizada. Existem dois tipos principais de listas: ordenadas e não ordenadas. As listas ordenadas são numeradas, e as não ordenadas utilizam marcadores. Veja os exemplos abaixo:</p>
    <h3>Lista ordenada:</h3>
    <pre><code>&lt;ol&gt;
        &lt;li&gt;Item 1&lt;/li&gt;
        &lt;li&gt;Item 2&lt;/li&gt;
    &lt;/ol&gt;</code></pre>

    <h3>Lista não ordenada:</h3>
    <pre><code>&lt;ul&gt;
        &lt;li&gt;Item A&lt;/li&gt;
        &lt;li&gt;Item B&lt;/li&gt;
    &lt;/ul&gt;</code></pre>

    <p><a href="#indice">Voltar ao índice</a></p>

    <h2 id="Links"><strong>Links de referências</strong></h2>
    <p>Links podem ser inseridos usando a tag <code>&lt;a&gt;</code>. O atributo <code>href</code> é usado para definir a URL de destino, e dentro da tag <code>&lt;a&gt;</code>, pode-se adicionar o texto que será clicável. Veja um exemplo:</p>

    <pre><code>&lt;a href="https://www.google.com"&gt;Visite o Google&lt;/a&gt;</code></pre>

    <p><a href="#indice">Voltar ao índice</a></p>
</body>
</html>

