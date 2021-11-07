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