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
    
