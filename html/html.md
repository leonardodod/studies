<!DOCTYPE html> // Especificar o tipo de documento.

<html lang="pt-BR"> // <html> Indica o início do documento em html, já o lang="pt-BR" serve para apontar a língua em que o documento estará.
</html> // </html> Indica o fim do documento em html.
   
<head> // Início do cabeçalho.
</head> // Fim do cabeçalho.
   
<body> // Início do corpo do código.
</body> // Fim do corpo do código.

<title> // Início do título do site.
</title> // Fim do título do site.

<meta charset="utf-8"> // Configuração de caracteres, existem diversos conjuntos de caracteres, utf-8 é um conjunto que abrange muitas línguas.

<p> // Início do parágrafo.
</p> // Fim do parágrafo.

&euro; // Cria o caractere € por exemplo.

// Utilizar o & permite selecionar dentre vários caracteres no seu código e que por ventura não tenha em seu teclado.

-> Html é um conjunto do body e do head;

- head é a parte pensante da página, onde ficam os metadados, metadados são informações sobre a página e o conteúdo publicado.

O head possui 5 elementos, sendo eles;

- title element
- base element
- link element
- meta element
- style element

<style> // Início do elemento de estilo.
</style> // Fim do elemento de estilo.

// Dentro do campo estilo, podem ser definidos elementos de CSS, tais como a cor do fundo da página, a fonte e a cor das letras.

background: #FFFF; // Selecionar a cor de fundo dentre várias outras, representadas através de códigos hexadecimais.

font-family: Arial; // Selecionar a fonte das letras.

color: #FFF; // Selecionar a cor das letras.

<script> // Início do script.
</script> // Fim do script.

// Dentro do campo script, criamos as funções e também "chamamos" as que já estão criadas.

function () {} // Comando para criar uma função básica.

// Dentro dele podemos utilizar o seguinte como exemplo.

nome.innerHTML = ""; // Escrever algo dentro de um elemento.

window.onload // Este comando é acionado quando a página é carregada.

window.onload = nomeDaFunção; // Faz com que ao carregar página, a função definida seja executada (chamada)

id = "objeto" // Identifica o objeto para que o mesmo possa ser usado como um valor em uma função.

<meta> // Dados sobre outros dados, um item de um metadado pode dizer do que se trata aquela informação,normalmente uma informação inteligível por um PC.

// Utilizamos o metadado como Tags também, por exemplo nos diversos casos abaixo;

<meta name= "author" content= "Leonardo de Oliveira Dias"> // Relaciona a informação "Autor" com a informação "Leonardo de Oliveira Dias".
<meta name= "generator" content= "Visual Studio Code"> // "generator" e "VS Code" para indicar a partir de onde foi gerado.
<meta name= "Keywords" content= "html, css, js"> // Indicar quais as palavras chaves do site, no caso de pesquisa.
<meta name= "description" content= "Descrição da página"> // Literalmente, a descrição do que se trata a página.

function sorteioNumero() {
resultado.innerHTML = Math.random() \* 50;

// Esta função faz o seguinte,

1. É chamada pelo evento "window.onload = sorteioNumero;"
2. Math.random() \* 50 irá gerar um número aleatório e após isto o multiplica por 50.
3. Este resultado é atribuido ao parágrafo no body, por conta do "<p id="resultado"></p>"
4. A operação é refeita por conta do metadado "<meta http-equiv="refresh" content="4" />" atualizando o número que é exibido para o usuário.
