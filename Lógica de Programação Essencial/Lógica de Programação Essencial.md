**- LÓGICA DE PROGRAMAÇÃO ESSENCIAL:**

  **AULA 1 – INTRODUÇÃO À LÓGICA DE PROGRAMAÇÃO – Denilson Bonatti**

**- O QUE É LÓGICA?**

Programar é saber resolver problemas, não é somente saber codificar. 

O que é lógica? – Coerência de raciocínio, de ideias.

Lógica de programação significar apenas contextualizar a lógica na programação de computadores, buscando a melhor sequência de ações para solucionar um problema. (Essa sequência é chamada de algoritmo).

**- Metacognição:** “Pensar como você pensa”.

**Exemplo: Comprando camiseta**

Nesse caso: a 1ª camiseta custa R$50,00 e a 2ª também custa R$50,00, as duas juntas fica R$100,00. Na compra de 2 camisetas tem um desconto de 20%(R$20,00). Que de R$100,00 ficou por R$80,00.

**- Abstração**: Habilidade de concentrar aspectos essenciais de um contexto qualquer, ignorando características menos importantes.

**ALGORITMO E PSEUDOCÓDIGO?**

**- Algoritmo:** Sequência de passos para resolver um problema.

**- Pseudocódigo:** Forma genérica de escrever um algoritmo, utilizando uma linguagem simples (nativa, ou seja, em português a quem o escreve, de forma a ser entendida por qualquer pessoa).

**- Tipos de variáveis:** As variáveis e as constantes podem ser classificadas basicamente de quatro tipos: ***Numéricas, Caracteres, Alfanuméricas (letras e números) ou Lógicas (verdadeiro ou falso).\***

**- Constantes:** São valores imutáveis e não são alterados durante a vida útil do programa.

**TOMADAS DE DECISÕES E EXPRESSÕES – Lógica de Programação**

 

**- Expressões Aritméticas:** São expressões que utilizam operadores aritméticos e funções aritméticas envolvendo constantes e variáveis.

| **OPERADORES  ARITMÉTICOS** |       |
| --------------------------- | ----- |
| Soma                        | **+** |
| Subtração                   | **-** |
| Multiplicação               | ***** |
| Potenciação                 | **^** |
| Porcentagem                 | **%** |

 

**- Expressões Literais:** São expressões com constantes e/ou variáveis que tem como resultado valores literais. Iremos utilizar as expressões literais na atribuição de valor para uma variável ou constante.

nome=”José da Silva” (Criei uma variável nome, e atribuí José da Silva a ela, então ela passa a ter esse valor).

  

| **Exemplos de Expressões Aritméticas e Literais** |                                    |                                                              |       |                                   |
| ------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------ | ----- | --------------------------------- |
| **Variáveis**                                     | **Comando de atribuição/operação** | **Procedimento**                                             |       |                                   |
| A                                                 | B                                  | C                                                            | A = 2 | Armazenar o valor 2 na variável A |
|                                                   | B = A + 3                          | Somar o valor A (2) com 3 e armazenar em B (5)               |       |                                   |
|                                                   | C = A + B                          | Somar o valor de A (2) e o valor de B (5) e  armazenar em C (7). |       |                                   |
|                                                   |                                    |                                                              |       |                                   |

 

 

**- Expressões Relacionais:** São expressões compostas por outras expressões ou variáveis numéricas com operadores relacionais. As expressões relacionais retornam valores lógicos (verdadeiro / falso).

| **Operadores Relacionais** |                      |             |                       |
| -------------------------- | -------------------- | ----------- | --------------------- |
| **Símbolo**                | **Nome do Operador** | **Exemplo** | **Significado**       |
| **>**                      | Maior que            | x **>** y   | x é maior que y?      |
| **>=**                     | Maior ou igual       | x **>=** y  | x é maior ou igual y? |
| **<**                      | Menor que            | x **<** y   | x é menor que y?      |
| **<=**                     | Menor ou igual       | x **<=** y  | x é menor ou igual y? |
| **==**                     | Igualdade            | x **==** y  | x é igual y?          |
| **!=**                     | Diferente de         | x **!=** y  | x é diferente de y?   |

 

**- Tomadas de Decisão:** Quando escrevemos programas, geralmente ocorre a necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução. 

 

**COMO UTILIZAR A CONCATENAÇÃO**

**- Concatenação:** É um termo usado em computação para designar a operação de unir o conteúdo de duas *strings\*(sequência de caracteres).*

 

  **AULA 2 – INTRODUÇÃO AO PORTUGOL – Denilson Bonatti**

**- ESTRUTURA DE REPETIÇÃO**

*Estrutura de repetição juntamente com a tomada de decisão são 70% da programação.*

**Estrutura de Repetição:** Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez ao mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.

**- LINGUAGEM DE PROGRAMAÇÃO** 

Linguagem de programação é uma escrita formal que especifica um conjunto de regras para gerar programas(software). – Um software pode ser desenvolvido para rodar em um computador, dispositivo móvel ou em qualquer equipamento de permita execução. 

*Existem 2 tipos de linguagem de programação:* 

**- Alto nível:** Essas são quelas cuja sintaxe se aproxima mais na nossa linguagem e se distanciam mais da linguagem da máquina. Ex: Linguagem em C, PHP, Java Script, C++, Python, entre outras.

**- Baixo nível:** É aquela que se aproxima mais da linguagem de máquina. Essas são as que você precisa ter conhecimento direto da arquitetura do computador para fazer alguma coisa.

A linguagem de programação pode ser *Compilada* ou *Interpretada*: 

**- Compilada:** É uma linguagem de programação em que o código fonte, é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado de compilação.

**- Interpretadas:** É uma linguagem de programação em que o código fonte é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador. Ex: PHP, Java Script, Python, etc.

​      **- O QUE É PORTUGOL?**

Portugol é um pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independentemente de linguagem de programação. – Resolver o problema através da pseudolinguagem sem precisar de equipamento que irá executar o algoritmo.

**- DESVIOS CONDICIONAIS NO PORTUGOL**

**- Desvio Condicional (Se):** É utilizada a palavra reservada **se**, a condição a ser testada entre parênteses e as instruções que devem ser executadas entre chaves caso o desvio seja **verdadeiro**.

**Exemplo:**

***Se\*** *(media >=7) {*

*Escreva (“Parabéns !! Você foi aprovado.”)*

*}*

**- Desvio Condicional (Se-não):** Se a condição for **falsa** um outro conjunto de comandos deve ser executado.

**Exemplo:**

***Se\*** *(media >=7) {*

*Escreva (“Parabéns!! Você foi aprovado.”)*

*}*

***Senão\*** *{*

*Escreva (“Infelizmente você foi reprovado.”)*

*}*

***\**Para adicionar comentário no Portugol se usa o //.\*** 

**- Desvio Condicional (Caso**): Este comando é similar aos comandos **se** e **senão**, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o **se**, ele possui algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos.

**Exemplo:**

​      Inteiro valor = 0

​      Escolha (valor)

​      {

​      **caso 1:**      // testa se o valor é igual a 1

​      escreva (“OK! Abrir Netflix”)

​      **pare**

​      **caso 2:**      // testa se o valor é igual a 2

​      escreva (“OK! Abrir Amazon Prime”)

​      **pare**

​      **caso 3:**      // testa se o valor é igual a 3

​      escreva (“OK! Abrir HBO GO”)

​      **pare**

​      **caso 4:**      // testa se o valor é igual a 4

​      escreva (“Saindo do menu...”)

​      **pare**

 

​      **caso contrario:** 

​      escreva (“Você deve escolher as opções 1, 2, 3 ou 4”)

 

**- LAÇOS DE REPETIÇÃO NO PORTUGOL**

Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.

funcao inicio ()

{

​      inteiro contador, limite, resultado

​      contador = 0

​      limite = 10

​      faca

​      {

​            resultado = 9 * contador

​            escreva (“9 X” + contador + “=” + resultado + “\n”)

contador++

} enquanto (contador <= limite)

}

**- MATRIZES E VETORES**

Uma **matriz** é uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória.

A individualização de cada variável de um vetor é feita através do uso de índices.

Os **vetores** são matrizes de uma só dimensão.