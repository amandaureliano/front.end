  <head>
       <ul> <h1> EXEMPLOS FRONT-END CSS </h1> </ul>
  </head>

    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <tittle>Aula</tittle>
      </head> 
                                                                        
      <body> 
        <h1> style="color: red";">Olá, mundo</h1> 
      </body>
    </html>



    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <tittle>Aula</tittle>
    
        <style>
         h1 {
            color: red;
        </style>   
      </head> 
                                                                        
      <body> 
        <h1>Olá, mundo</h1> 
      </body>
    </html>

                                                                        

    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <tittle>Aula</tittle>
        <link href="styles.css" rel="stylesheet">   
      </head> 
                                                                        
      <body> 
        <h1>Olá, mundo</h1> 
      </body>
    </html>
 
        
        
    - Exercicio 1:
    html: 
    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <link href="styles.css" rel="stylesheet">   
      </head> 
                                                                        
      <body> 
        <header>
          Logo
        </header>
        <section>
          <h1>Novo produto muito inovador</h1>
          <a href="#">Saiba mais</a>
        </section>
      </body>
    </html>
        
    css: 
    header {
      color:blue;
    }

    h1 {
      color: red;
    }

    a {
      color: green;
    }
        
        

    - Exercicio 2:
    html: 
    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <link href="styles.css" rel="stylesheet">   
      </head> 
                                                                        
      <body> 
          <h1>Olá, mundo</h1>
          <h1 class="laranja">Olá, mundo</h1>
          <h1 id="roxo">Olá, mundo</h1>
         <h2>Olá, mundo</h2>
      </body>
    </html>
        
    css:
    * {
      background-color: black;
    }

    h1 {
      color: red;
    }

    h1.laranja {
      color: orange;
    }

    h1#roxo {
      color: purple;
    }

    h2 {
      color: blue;
    }

        
        
    - Exercicio 3:
    html: 
    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <link href="styles.css" rel="stylesheet">   
      </head> 
                                                                        
      <body> 
        <h1 class="vermelho">Este texto é vermelho (red)</h1>
        <h1 class="amarelo">Este texto é amarelo (yellow)</h1>
        <h1 class="verde">Este texto é verde (green)</h1>
        <h1 class="azul">Este texto é azul (blue)</h1>
        <h1 class="laranja">Este texto é laranja (orange)</h1>
        <h1 class="roxo">Este texto é roxo (purple)</h1>
        <h1 class="branco">Este texto é branco (white)(black)</h1>
      </body>
    </html>
        
    css: 
    .vermelho {
      color: red;
    }

    .amarelo {
      color: yellow;
    }

    .verde {
      color: green;
    }

    .azul {
      color: blue;
    }

    .laranja {
      color: orange;
    }

    .roxo {
      color: purple;
    }

    .branco {
      color: white;
      background-color: black;
    }
    
    
    
    - Exercicio 4: 
    html:
    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <link href="styles.css" rel="stylesheet">   
      </head> 
                                                                        
      <body> 
        <header>
            <h1>Olá, mundo</h1>
            <nav>
                <h1 class="vermelho">Olá mundo</h1>
            </nav>
        </header>
        <h1>Olá, mundo!</h1>
        <div>
            <h1>Olá, mundo!</h1>
        </div>
        <h2>Olá, mundo!</h2>
      </body>
    </html>
    
    css:
    header > h1 {
      color: green;
    }

    div h1 {
      color: purple;
    }

    h1, h2 {
      color: orange;
    }

    h1.vermelho {
      color: red;
    }
    
    
    
    - Exercicio 5:
    html: 
    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <link href="styles.css" rel="stylesheet">   
      </head> 
                                                                        
      <body> 
        <div class="vermelho">
            Olá
        </div>
        <div class="verde">
            Olá
        </div>
        <div class="azul">
            Olá
        </div>
      </body>
    </html>
                         
    css:
    body {
      margin: 0px;
    }

    div {
      height: 100px;
      width: 100px;
      border: 5px solid black;
      padding: 10px;
    }

    .vermelho {
      background-color: red;
      margin-bottom: 10px;
    }

    .verde {
      background-color: green;
      margin-bottom: 10px;
    }

    .azul {
      background-color: blue;
      margin-bottom: 10px;
    }
    


    - Exercicio 6:
    html:
    <!DOCTYPE html>
    <html lang="pt">
  
      <head>
        <meta charset="UTF-8">
        <meta name="viewport content="widht=device-widht, initial-scale=1.0">
        <link href="styles.css" rel="stylesheet">   
      </head> 
                                                                        
      <body> 
        <h1>Titulo</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Neque autem quisquam ducimus magni, ea vitae dolores vel 
        nesciunt, tempora temporibus natus iusto debitis mollitia labore corporis? Sed mollitia omnis ea.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum aliquam quisquam earum, neque at fugiat, explicabo 
        hic recusandae doloribus dolorum sunt numquam, eos officiis modi. Aperiam, minima. Aperiam, esse quam.</p>
        <a href="#">Link</a>
      </body>
    </html>
                   
    css:
    *{
      margin: 0;
      padding: 0;
    }

    h1 {
      background-color: red;
      padding: 15px 10px;
    }

    p {
      background-color: blue;
      color: white;
      margin: 20px 0px;
      padding: 5px 10px;
    }

    a {
      padding-left: 10px;
    }
