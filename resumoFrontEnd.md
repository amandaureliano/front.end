<html>

   <head>
       <ul> <h1> RESUMO FRONT-END </h1> </ul>
    </head>

<body>

    - Diferença entre Back-end e Front-end?

    Back-end é o que está sob controle da empresa (servidor).
    Front-end é o que está sob controle do consumidor (mobile, desktop, outros(smarts)).

    Sistemas Operacionais (SO): ios, android, windows, mac, linux. </h4> </p> </ul>

    - Diferença de Nativo e Multiplataforma:
    
    Nativo: são rapidas, tem acesso a todas as funcionalidades do dispositivo. Porém, precisam
    ser refeitas para cada SO.
    Multiplataforma: funcionam em 2+ plataformas, evitando retrabalho. Não constumam ter acesso
    á todas as funcionalidades do dispositivo e não costumam ter a mesma velocidade.

    A forma mais comum de fazer aplicações multiplataforma é usando a web.
    
        WEB: varias especificações (define uma linguagem, determinando como ela se escreve e como
        ela é executada).
        HTML: conteudo.
        CSS: estilo.
        JAVASCRIPT: comportamento.


    - O minimo para rodar uma pagina html:
        <!DOCTYPE html> sempre no começo e fora do <html> ela serve para dizer que está sendo
        utilizado a versão mais atualizada do html.
            <html>
                <head>
                     <tittle></tittle>: Titulo
                     <meta charset=”utf-8”> é sempre colocado por padrão
                     <meta name=”viewport” content=”width=device-widht, initial-scale=1.0”> é sempre colocado por padrão no cabeçalho.
                </head> vai guardar algumas informações sobre a nossa pagina
                
                <body>
                    Olá, mundo!
                </body> todo o conteudo que será mostrado em tela
            </html> servir para conter todo o nosso conteudo html


    <h1>Titulo</h1>
    <h2>Sub titulo</h2>
    <h3>Sub titulo menor que o anterior</h3>
    <h4>Sub titulo menor que o anterior</h4>
    <h5>Sub titulo menor que o anterior</h5>
    <h6>Sub titulo menor que todos</h6> </ul>

    <p>paragrafos</p>

    <ul>lista nao ordenada
        <li> item da lista </li>
    </ul>


    - Elemento html: <elemento> tag que abre
          conteúdo : nosso conteudo ou outros elementos html
          </elemento> tag que fecha

    - Tag vazia: <vazio> ex: o elemento imagem nao tem nenhum conteudo dentro dele, ele tem atributos
    <img src=”imagem.png”> nome do atributo = valor do atributo

    - Lorem: texto feito só para preencher espaço.
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum quam ut cum labore at repellat a
    quaerat? Nihil necessitatibus obcaecati iste magnam, tenetur fugiat nesciunt, recusandae est alias, natus ad!
  
    Liver server: extensão no Vs Code.
    
    <div></div>: é um elemento de bloco que não tem um significado especial, usado para criar uma divisão na pagina (quebra de linha).  
    
    <span> </span>: é um elemento em linha (não tem quebra de linha).
    
    Elemento de bloco não fica dentro de elemento de linha, mas ocorre o contrario.

    - Elementos que tem significado:
      <header></header>: cabeçalho (logo, nome, info chaves, navegações, lista de links).
      <nav></nav>: elemento que agrega navegações, geralmente dentro do nav tem uma lista e dentro dos itens da lista, 
      terão botões ou links que façam a navegação na pagina, ou seja, serve para agregar navegações na pagina.
      <aside></aside>: parte da pagina que fica do lado esquerdo ou direito.
      <main></main>: categoriza o conteudo principal da pagina.
      <article></article>: artigo, qualquer parte de texto ou conteudo que podemos reutilizar em outro lugar, que ele por si só ja tem sentido.
      <section></section>: vai guardar seções da pagina, um agregado de coisas que queremos juntar.
      <footer></footer>: roda pé (link midias sociais, termos, contatos).

    - Atributos HTML: todos os elementos HTML podem ter atributos. Os atributos providenciam informações adicionais sobre elementos, são sempre 
      especificados na tag inicial. 
      A sintaxe gerealmente é: nome=”valor", porém existem atributos booleanos que usamos somente o nome. 
      ex: <a href=”https://www.google.com”>Link para o Google
                
         Globais:          hidden: navegador vai esconder esse elemento html 
                           ex: <p hidden>Este paragráfo está escondido
                           title: 
                           dir: maualmente se o texto é da direita para a esquerda, da esquerda para a direita ou automatico
                           lang: lingua 
                           
         Especificos:      src (img, video, audio)
                           href (a, link, area, …)
                           alt (img, input, area) : descrição do que tem na imagem
	                        ex: <img src=”sorriso.png” alt=”Uma pessoa sorrindo”
                           value (button, input, option, ...)

      Elementos de imagem: por padrão são elementos de linha.
      
    - Maneiras de colocar uma imagem no site:
    
         Url relativa: são caminhos que são escritos relativos ao arquivo que estamos acessando, 
         por exemplo nome da imagem e a extensão <img src="gato2.jpg">
         Url absoluta: são urls que você passa o caminho inteiro <img src="https://placekitten.com/400/400">
         
    - Links no html: <a atributo”onde vamos apontar”> </a> 
                 ex: <a href=”https://google.com”>Site do Google</a>
         
      lorem300: paragrafo com 300 palavras.
      lorem500: paragrafo com 500 palavras.
      
    - Atributo id: tem que ser unico, nenhum outro elemento pode ter o mesmo valor identificador.
         ex: <section id=”secao-introducao”>          <a href=”#secao-introducao”>Introdução</a>
                                                       # e o nome do id
         <a href=”#”>Voltar ao incio</a> : volta para o inicio da pagina.
         
    - Elementos para estilizar os textos e gerar acessibilidade:
    
         <strong></strong>: negrito (mais urgente).
	      <b></b>: negrito (não é algo urgente).
	      <i></i>: italico (tom de voz ou emoção diferente).
	      <em></em>:italico (dar um enfase no texto).

    - Charset ascii: código que representa alguma letra ou outra informação(inventado no EUA)
    - Charset utf-8: universal
	- Viewport: area visivel do usuario.
