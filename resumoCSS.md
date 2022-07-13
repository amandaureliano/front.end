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
           
    - seletores básicos:  seletor por elemento.
                          id: identificador, tem que ser unico (#).
                          seletor de classe: pode ser reutilizada por varios elementos (.).
    - seletor global: * seleciona todos os elementos e aplica uma regra de estilo.
    
    - ordem de prioridade: se algum elemento tiver um estilo inline (ele vai prevalecer).
                           tag style e arquivos css importados: tem a mesma ordem de prioridade (efeito cascata).
                            efeito cascata: prevalece o que está por ultimo.
    
    - herança: estilo já pré definido.
    
    - especificidade: maior especificidade prevalece.
        selector specificity: (0, 0, 0) serve como desempate, começando pelo primeiro numero da esquerda
    
    - combinadores de seletores:  , combinador ou (separa elementos seletores)
                                  > descendente direto
                                  ( ) descendente qualquer
                                  e, elementos, classes, , espaço, id tudo junto
                                  
    - box model:  junção de propreidades que servem para alinhar os elementos (varias posições com varios tamanhos)
                  margin > border > padding > content - width(tamanho)
    - box model is border-box: calcula o tamanho total
    div{
          widht: 300px;
          height: 200px;
          padding: 15px;
          border: 5px solid grey;
          margin: 30 px;
            -moz-box-sizing: content-box;
            box-sizing: content-box;
       }        
    - box model is content-box: calcula primeiro o conteudo e depois o padding, a borda e a margem
    div{
          widht: 300px;
          height: 200px;
          padding: 15px;
          border: 5px solid grey;
          margin: 30 px;
            -moz-box-sizing: border-box;
            -webkit-box-sizing: border-box;
            box-sizing: border-box;
       }     
       
    - bordas arredondadas: border-radius: 10px;
    
    - reset de margins e paddings: * {
                                      margin: 0;
                                      padding: 0;
                                     }
    exemplo, padding: 15px 10px 30px 20px; (top, right, bottom, left)
             padding: 15px 20px; (top-bottom, right-left)
