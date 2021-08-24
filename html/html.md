# Códigos HTML

## Estruturação

| Code     | Description                  |
| -------- | ---------------------------- |
| < html>  | Início do documento em html. |
| < /html> | Fim do documento em html.    |
| < head>  | Início do cabeçalho.         |
| < /head> | Fim do cabeçalho.            |
| < body>  | Início do corpo do código.   |
| < /body> | Fim do corpo do código.      |

## Configurações do documento

| Code                    | Description                                                                                |
| ----------------------- | ------------------------------------------------------------------------------------------ |
| < !DOCTYPE html>        | Especificar o tipo de documento.                                                           |
| < html lang="pt-BR">    | lang="pt-BR" indica o idioma do documento.                                                 |
| < meta charset="utf-8"> | UTF-8 adiciona um pacote de caracteres para que os mesmos possam ser reconhecidos no site. |

## Estilização

| Code                                | Description                                                        |
| ----------------------------------- | ------------------------------------------------------------------ |
| < p>                                | Início do parágrafo.                                               |
| < /p>                               | Fim do parágrafo.                                                  |
| &euro                               | Permite adicionar diversos caracteres diferentes.                  |
| < body>                             | Início do corpo do código.                                         |
| < /body>                            | Fim do corpo do código.                                            |
| < style>                            | Início do elemento de estilo.                                      |
| < /style>                           | Fim do elemento de estilo.                                         |
| < script>                           | Início do script.                                                  |
| < /script>                          | Fim do script.                                                     |
| # Heading level 1                   | <h1>Minha vontade de estudar.</h1>                                 |
| ## Heading level 2                  | <h2>Muito grande.</h2>                                             |
| ### Heading level 3                 | <h3>Grande.</h3>                                                   |
| #### Heading level 4                | <h4>Normal.</h4>                                                   |
| ##### Heading level 5               | <h5>Pequeno.</h5>                                                  |
| ###### Heading level 6              | <h6>Bem pequeno.</h6>                                              |
| < hgroup>< /hgroup>                 | Agrupar os textos de cabeçalho.                                    |
| < br />                             | Quebra de linha.                                                   |
| < b>< /b>                           | <b>Em destaque</b>                                                 |
| < i>< /i>                           | Em itálico</p>                                                     |
| < u>< /u>                           | Texto em sublinhado.                                               |
| < sub>< /sub>                       | Texto em subscrito.                                                |
| < sup>< /sup>                       | Texto em superescrito.                                             |
| < s>< /s>                           | Texto em riscado.                                                  |
| Code                                | Description                                                        |
| background: #FFFF;                  | Selecionar a cor de fundo em hexadecimal.                          |
| font-family: Arial;                 | Selecionar a fonte das letras.                                     |
| color: #FFF;                        | Selecionar a cor das letras.                                       |
| < image src="diretório">            | Adiciona uma imagem.                                               |
| < image src="" width="">            | Define a largura da imagem.                                        |
| < image src="" heigth="">           | Define a altura da imagem.                                         |
| < image src="" title="">            | Nome da imagem.                                                    |
| < image src="" alt="">              | Mesmo que o title, porém com duas funções a mais.                  |
| < image src="" style="">            | Atribue elementos de estilo na tag.                                |
| < style="" "float:left">            | Força a imagem a ficar na esquerda.                                |
| < style="" "margin-right:1px">      | Coloca uma margem de 1 pixeis na direção desejada.                 |
| < style="" "margin-left:1px">       | Coloca uma margem de 1 pixeis na direção desejada.                 |
| < style="" "margin-bottom:1px">     | Coloca uma margem de 1 pixeis na direção desejada.                 |
| < style="" "margin-top:1px">        | Coloca uma margem de 1 pixeis na direção desejada.                 |
| < style="" "border:1px solid #000"> | Coloca uma borda na imagem de 1 píxel de espessura e da cor preta. |
| < image src="" class="">            | Permite criar predefinições de estilo.                             |
| < figure> < figcaption>             | Colocar rodapé na imagem.                                          |
| < a href="">< /a>                   | Adicionar hiperlinks.                                              |
| < a href="" target="\_blank">       | Faz com que o hiperlink abra em uma nova guia ou aba.              |
| < a href="#id_name">                | Cria um hiperlink com a tag que possua o respectivo id.            |

### alt="" As outras duas funções são as seguintes:

1. Mostrar o nome da imagem caso a mesma não carregue completamente devido a problemas de conexão.
2. Permitir que softwares de auxílio à pessoas com deficiência visual, possam ler o nome da imagem para o usuário.

### Listas em html

```
{
<ul>Para listas não ordenadas.</ul>
    type="square" //Altera o * para quadrados minúsculos.
    type="circle" //Semelhante ao * porém é 'oco'/vazio.
}
```

```
{
<ol>Para listas ordenadas.</ul>
    type="1" //Sequência de 1,2,3...
    type="A" //Sequência de A,B,C...
    type="a" //Sequência de a,b,c...
    type="I" //Sequência de I,II,III...
    type="i" //Sequência de i,ii,iii...
}
```

```
{
<dl>Lista com descrição</dl>
    <dt>Título da descrição.</dt>
    <dd>A descrição em si.<dd>
}
```

### class

É possível criar classes e pré-definir as configurações de estilo no topo do código, para que assim que necessário, basta definir a classe na tag desejada. Exemplo de classe criada:

```
{
    <style>
        .img-prato {
            float:right;
            margin-left:10px;
            margin-bottom:20px;
            border:1px solid #000;
        }
    </style>
}
```

## Scripts (Head)

Html é um conjunto do body e do head, head é a parte pensante da página, onde ficam os metadados, metadados são informações sobre a página e o conteúdo publicado.

O head possui 5 elementos, sendo eles:

- title element
- base element
- link element
- meta element
- style element

Dentro do campo estilo, podem ser definidos elementos de CSS, tais como a cor do fundo da página, a fonte e a cor das letras. Mas dentro do campo script, criamos as funções e também "chamamos" as que já estão criadas.

| Code                          | Description                                                                       |
| ----------------------------- | --------------------------------------------------------------------------------- |
| function () {}                | Comando para criar uma função básica.                                             |
| nome.innerHTML = "";          | Escrever algo dentro de um elemento.                                              |
| window.onload = nomeDaFunção; | Este comando é acionado quando a página é carregada.                              |
| id = "objeto"                 | Identifica o objeto para que o mesmo possa ser usado como um valor em uma função. |

### Metadados

Utilizamos o metadado como Tags também, por exemplo nos diversos casos abaixo.

"<meta>" São dados sobre outros dados, um item de um metadado pode dizer do que se trata aquela informação.
(normalmente uma informação inteligível por um PC.)

| Code                                                        | Description                                                                  |
| ----------------------------------------------------------- | ---------------------------------------------------------------------------- |
| < meta name= "author" content= "Leonardo de Oliveira Dias"> | Relaciona a informação "Autor" com a informação "Leonardo de Oliveira Dias". |
| < meta name= "generator" content= "Visual Studio Code">     | "generator" e "VS Code" para indicar a partir de onde foi gerado.            |
| < meta name= "Keywords" content= "html, css, js">           | Indicar quais as palavras chaves do site, no caso de pesquisa.               |
| < meta name= "description" content= "Descrição da página">  | Literalmente, a descrição do que se trata a página.                          |

```

function sorteioNumero() {
resultado.innerHTML = Math.random() \* 50;

```

Esta função faz o seguinte,

1. É chamada pelo evento "window.onload = sorteioNumero;"
2. Math.random() \* 50 irá gerar um número aleatório e após isto o multiplica por 50.
3. Este resultado é atribuido ao parágrafo no body, por conta do "< p id="resultado">< /p>"
4. A operação é refeita por conta do metadado "< meta http-equiv="refresh" content="4" />" atualizando o número que é exibido para o usuário.

```

```
