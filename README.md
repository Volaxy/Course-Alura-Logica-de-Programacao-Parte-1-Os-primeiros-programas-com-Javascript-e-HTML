# Alura Logica de programação I: Os primeiros programas com Javascript e HTML

Curso da Alura sobre lógica de programação com HTML e Javascript.

URL do Curso -> [Lógica de programação I: Os primeiros programas com Javascript e HTML](https://www.alura.com.br/curso-online-logica-programacao-javascript-html)
![Lógica de programação I: Os primeiros programas com Javascript e HTML](https://www.alura.com.br/assets/api/share/curso-logica-programacao-javascript-html.png)
***
## Links Úteis
* [Notepad++](https://notepad-plus-plus.org/) - Editor de texto alternativo.
* [Sublime](https://www.sublimetext.com/) - Editor de texto com texto colorido.
* [Google Chrome](https://www.google.com/intl/pt-BR/chrome/) - Navegador recomendado para depuração de código no browser.

## Siglas
* HTML - *Hyper Text Markup Language* - Linguagem de Marcação de Hipertexto.

## Atalhos
* CTRL + O - Dentro do navegador, abrirá o explorador de arquivos e irá pedir para escolher um arquivo para ser aberto.

## 01 - Começe a Programar Hoje
* Aprendemos que desenvolver **não** exige um ambiente complexo;
* É possível utilizar o próprio navegador, e todo sistema operacional possui um. O navegador recomendado é o **Google Chrome**;
* Podemos utilizar um editor de texto padrão. Nós usaremos o **Sublime Text**, disponível para todas as plataformas;
* Compreendemos que o HTML é uma linguagem de marcação, pois ela possibilita marcar conteúdos por meio de *tags*;
* Algumas tags não possuem marcação, como o **`<br>`**, que serve para pular uma linha;
* A *tag* **`<a>`** nos permite sair de uma página e mudar para outra;
* O HTML é estático, isto é, não muda. Não podemos fazer nada muito sofisticado com ele. Por esse motivo o navegador entende também a linguagem JavaScript, que é uma linguagem de programação dinâmica, com a qual podemos desenvolver de maneira mais avançada;
* Para o navegador interpretar uma instrução JavaScript, não basta colocarmos a instrução JavaScript direto no HTML. Temos que utilizar a *tag* **`<script>`**. Dessa forma o navegador saberá que deve processar essa parte do código como linguagem JavaScript e não como HTML;
* A primeira instrução que vimos do JavaScript foi o **`alert`**, que recebe como parâmetro um texto;
* Por último, aprendemos que todo texto em JavaScript vem entre aspas.

## 02 - Comunique-se com o Usuário
* As convenções podem ser seguidas para o programador, ele pode não seguir elas, mas será mal visto.
* A convenção é sempre utilizar letras minúsculas para as tags *HTML*.
* O JavaScript é **case sensitive**, que faz distinção entre letras *MAIÚSCULAS* e *minúsculas*.
* Um **parâmetro** é delimitado por `()` com algum valor entre os *parênteses*.
* A recomendação é usar o `;` no final de cada linha de comando para evitar futuros problemas com a ausência do `;` no código.
* O mundo JavaScript é delimitado pelo marcador `<script>` e `</script>`, e o mundo HTML é tudo que está fora do escopo dessas duas *tags*;
* A função **`document.write()`** permite através do mundo JavaScript, escrever coisas no mundo HTML.
* Se um conjunto de caracteres não está entre aspas, e for um tipo *numérico*, o JavaScript interpretará como número.
* Em funções como **`document.write()`**, é possível fazer contas de + (soma), - (subtração), X (multiplicação) e / (divisão).
* Quando se tem operação entre `"18"` e `"20"`, o JavaScript os interpreta como texto e junta as 2 **Strings**, formando `"1820"`, por exemplo, assim como `"18"` e `20`, ele converte o `20` para **String**.
* As regras de *matemática* para operadores (+, -, *, /) também se aplicam em programação, com * e / sendo feitos antes da + e -, e as operações sendo feitas da esquerda para a direita.
* É possível delimitar uma operação com **`()`** para priorizar operações dentro dos parênteses.

## 03 - Torne seu Programa Dinâmico com Variáveis
* Na programação, uma **variável** é um objeto (uma posição, frequentemente localizada na memória) capaz de reter e representar um valor ou expressão.
* Para declarar uma variável em JavaScript usamos a sintaxe `var ano`.
* Para atribuir um valor à uma **variável**, colocamos um `=` depois da declaração para atribuir um valor.
* O jeito correto de se falar uma atribuição de uma variável com `=` é *"x RECEBE ..."*.
* O processo do JavaScript para diferenciar valores de variáveis é feito vendo se o trecho está entre aspas, e se estiver, é uma string, caso negativo, será feita uma próxima pergunta: trata-se de um número? Caso a resposta seja "não", significa que se trata de uma variável.
* A função **`Math.round()`** arredonda um número passado pelos `()`.
* As variáveis melhoram a legibilidade do código, além de facilitar sua manutenção.
* Uma convenção usada no mundo da programação é a seguinte: O nome de uma variável sempre se iniciará com uma letra minúscula. Se a variável contém duas palavras, por exemplo "idade + (nome)", a próxima palavra deve ser escrita com a primeira letra MAIÚSCULA. Este padrão recebe o nome de **camelCase**.

## 04 - Crie suas Próprias Funcionalidades
* **Funções** são instruções que são executadas sempre que um código às invoca.
* Funções são definidas no JavaScript como: `function NOME_DA_FUNCAO() { INSTRUÇÕES }`.
* Tudo que estiver entre as `{}` pertence à função.
* Se estamos em um bloco, utilizamos "Tab" para criar um espaçamento na linha e, assim, o código ficará indentado e teremos uma melhor noção de hierarquia.
* Para comentar uma linha de código em JavaScript, usamos `//` na linha que queremos comentar.
* **Comentários** não são interpretados pelo JavaScript.
* Funções podem receber **parâmetros**.
* Um **parâmetro** é uma variável que é declarada entre os `()` de uma função.
* Uma **função** pode conter uma instrução chamando outra **função**.

## 05 - Pratique Resolvendo Problemas do seu Dia a Dia
* É importante conhecer o problema que desejamos resolver para criarmos programas que saibam resolve-los.
* Para retornar algum valor como resultado da função, usamos o **`return`**.
* Sempre que fazemos uma operação matemática com valores não definidos temos o resultado **`NaN`**.
* Dado um trecho de código, por exemplo: `mostra("O meu IMC é " + calculaImc(1.63, 48));`. É importante entender que a concatenação não é feita com a função, mas sim com seu retorno.
* A função **`prompt()`** no JavaScript recebe (ou não) um parâmetro de entrada, e retorna o valor digitado pelo usuário no pop-up exibido na tela.

## 06 - Execute Códigos Diferentes Dependendo da Condição
* O retorno do valor digitado na função **`prompt()`** sempre será no formato *texto*.
* Quando uma variável do tipo *texto* contém um número dentro dele, e acontece uma operação de `-`, `/` ou `*`, o JavaScript converte o conteúdo do *texto* para um *número* e executa a operação.
* A função **`parseInt()`** do JavaScript, recebe um valor (*texto* ou *número*) e transforma em um *número inteiro*.
* Para testarmos uma igualdade em JavaScript, utilizamos **`==`**.
* O **`if`** testa se uma condição é *verdadeira* ou *falsa*, e se for *verdadeira*, ela executa as instruções dentro do **`if`**.
* Os caracteres **`&&`** significam *e* na hora da comparação, se uma das condições for *falsa*, o bloco correspondente não será executado.
* Os caracteres **`!=`** significam *diferente* e verifica se um parâmetro não é igual ao outro.
* O **`else`** vem depois do fechamento das `{}` do *if*, e se a condição do *if* for falsa, as instruções dentro das `{}` do **`else`** serão executadas.
* A função **`Math.random()`** sorteia um número aleatório entre 0 e 1.
* A função **`console.log()`** mostra alguma coisa passada como parâmetro no *console* do navegador.

## 07 - Repita Tarefas
* A instrução **`while`** repete um determinado trecho de código entre as `{}` até que a condição de repetição descrita nos `()` do **`while`** se torne *falsa*.
* A função **`isNaN()`** verifica se um determinado valor é **`Nan`** e retorna *true* ou *false*.
* O laço **`for`** contém três partes `for(Parte 1; Parte 2; Parte 3)`, onde:
    * Parte 1: Geralmente contém a inicialização da variável que será o contador da instrução **`for`**.
    * Parte 2: Verifica a condição retornando *true* ou *false*, determinando se irá executar as instruções do laço ou não.
    * Parte 3: Contém o incremento ou decremento da variável de contagem do laço.
* O **pós-incremento**, significa um sinal de `++` logo após uma variável, incrementando seu valor por 1, exemplo: `(variavel++) = (variavel = variavel + 1)`.
* O **`break`** força a "quebra" do loop em que ele está inserido.
* Para que as *casas decimais* de um número sejam mantidas, usa-se o **`parseFloat()`**, convertendo o parâmetro para o tipo *float*.

## 08 - Interaja de Maneira Diferente com o Usuário
* A tag **`<input/>`** cria um campo para entrada de texto no navegador.
* A tag **`<button></button>`** cria um botão no navegador, onde entre a abertura e o fechamento da tag, podemos inserir uma frase para aparecer dentro do botão.
* A função **`document.querySelector()`**, recebe como parâmetro o nome da *tag* que desejamos "pegar" no mundo HTML, e retorna uma *referência* para aquela *tag*.
* Utilizamos o **`input.value`** (com "input" sendo um nome de variável qualquer contendo uma referência para um elemento HTML) no mundo JavaScript para saber o valor que está armazenado na *tag* HTML.
* A função **`button.onclick`** (com "button" sendo um nome de variável referenciando um botão) armazena uma função que será executada ao clicar no botão correspondente onde foi atrelada a função.
* Ao digitar o nome de uma função no console do navegador com os `()`, a função é executada, mas ao digitar somente o nome da função excluindo os `()`, o console mostra a função por completo, sem executa-la.
* A função **`input.focus()`** permite que a entrada de teclado do usuário fique focada no input em que a função é executada.

## 09 - Trabalhe com Muitos Dados
* Para declarar um **array**, coloca-se `var array = []`, onde dentro dos `[]`, colocamos os valores separados por `,`, `[1, 2, 3, ...]`.
* Uma convenção utilizada para a nomenclatura de **arrays**, é sempre declarar a variável no *plural*.
* Para acessar um elemento dentro de um **array**, basta digitar o nome do *array* e entre `[]` a posição que se quer acessar, (**OBS.: As posições dentro de um array sempre começam a partir da posição 0**).
* Para verificar o tamanho de um **array**, usamos o **`array.length`**, onde ele retorna o número de elementos contidos no **array**.
* Ao inserir os elementos em um **array** no JavaScript, podemos inserir qualquer tipo de dado além do tipo do primeiro inserido.
* A função **`array.push()`**, insere novos dados no **array**.