  <head>
       <ul> <h1> RESUMO FRONT-END CSS </h1> </ul>
  </head>

    - O que é o CSS? é um jeito de especificar como os elementos HTML serão apresentados.
    - Sintaxe:  style="propriedade(color): valor(red)";
                <elemento style="color: red;">
                Conteúdo
                </elemento>
              
                <elemento style="
                  color: red;
                  background-color: black;
                ">
                  Conteúdo
                </elemento>
                
    - tag <style> coloca por padrão no <head>:    <style>
                                                    elemento {
                                                    color: red;
                                                    }
                                                  </style>
    - tag <link> qual arquivo que estamos importando, qual o tipo de arquivo que estamos importando
           exemplo: <link href="styles.css" rel="stylesheet">
           
    - seletores básicos:  seletor por elemento
                          id: identificador, tem que ser unico (#)
                          seletor de classe: pode ser reutilizada por varios elementos (.)
    - seletor global: * seleciona todos os elementos e aplica uma regra de estilo
    
