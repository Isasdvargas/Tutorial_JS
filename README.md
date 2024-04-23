# Tutorial JavaScript

## O que queremos aprender?

1. Criar páginas web dinâmicas e interativas.
2. Manipular o conteúdo e estilo de uma página (DOM).
3. Lidar com programação assíncrona.
4. Gerenciar eventos do usuário.
5. Trabalhar com dados de diferentes fontes.
6. Aplicar padrões de design e boas práticas de programação.
7. Utilizar ferramentas e frameworks do ecossistema JavaScript

## O que é javaScript?

JavaScript é uma linguagem de programação usada para adicionar interatividade e dinamismo às páginas da web. Ela permite que os desenvolvedores controlem o comportamento dos elementos da página, respondam a eventos do usuário e realizem operações como enviar e receber dados do servidor. É amplamente utilizada no desenvolvimento web, móvel e em outras áreas da computação.

## Configuração do Ambiente 

1. **Node.js e npm**: Plataforma e gerenciador de pacotes.
2. **Editor de código**: Visual Studio Code, Sublime Text, etc.
3. **Git**: Controle de versão.
4. **npm init**: Iniciar um projeto e criar package.json.
5. **npm install**: Instalar dependências.

## Sintaxe Básica 

1. **Variáveis**: var, let, const para declarar.
2. **Tipos de dados**: Números, strings, booleanos, arrays, objetos, funções, null, undefined.
3. **Operadores**: Aritméticos, de comparação, lógicos.
4. **Estruturas de controle**: if, else, else if, for, while.
5. **Funções**: Definidas com function, podem ter parâmetros e retornar valores.
6. **Objetos**: Coleções de chave-valor.
7. **Arrays**: Listas ordenadas de valores.

## Variáveis

1. **var**: Escopo global ou local, pode ser redeclarada e atualizada.
    ```
    var num = 27
    ```

2. **let**: Escopo de bloco, não pode ser redeclarada no mesmo escopo, pode ser atualizada.
   
    ```
    let carro = "Preto"
    ```

3. **const**: Escopo de bloco, valor constante, não pode ser reatribuída ou redeclarada.
    ```
    const nome = "Isadora"
    ```

## Tipos de dados 

1. **Number**: Números inteiros ou de ponto flutuante.
2. **String**: Sequências de caracteres.
3. **Boolean**: Valor verdadeiro ou falso.
4. **Array**: Coleção ordenada de valores.
5. **Object**: Coleção de pares chave-valor.
6. **Function**: Bloco de código reutilizável.
7. **Null**: Valor nulo intencionalmente definido.
8. **Undefined**: Valor atribuído a uma variável não inicializada.

## Funções

* Crie funções usando a palavra "Function"
* Passagem de parâmetros para as funçôes
* Retornando valores com "Return";

  exemplo:

  ```
  function saudacao{
  console.log("Olá mundo");
  return "Saudação feita";
  }
  ```

## Estruturas de Controle

* Utilizando condicionais  "if", "else", "if" e "else".

  exemplo

  ```
  if (a>b){
      console.log("A é maior que B")
  }else if (a<b){
      console.log("B é maior que A")
  }else{
      console.log("A é igual a B")
  }
  ```
  
*  Criando loops com "for" e "while".
* Utilizando instruções "swhitch".

## Eventos de Manupulação 

Um evento de manipulação em JavaScript é uma ação que ocorre em um elemento HTML, como um clique do mouse, pressionamento de tecla, movimento do mouse, etc. Esses eventos são acionados pelo navegador quando uma interação do usuário ocorre. O JavaScript pode ser usado para "ouvir" esses eventos e responder a eles executando determinado código, como alterar o conteúdo da página, animar elementos, validar formulários, etc.
