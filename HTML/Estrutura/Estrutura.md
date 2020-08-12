### Estrutura 

Toda página HTML, possui uma estrutura básica que por sua vez é constituída de elementos HTML, estes elementos são feitos do que  chamamos de tags(etiquetas). As tags podem vir em pares , a *<strong>tag de abertura</strong>* e a *<strong>tag de fechamento</strong>*, esta última possui uma barra invertida. Há também tags que não necessitam de um fechamento elas atuam sozinhas dentro do corpo do documento. As tags agem como containers, elas delimitam um determinado trecho e agem sobre esse trecho modificando-o.
  ______
  ______

#### Alguns exemplos de tags

```html 
<html>a tag html indica que tudo entre a tag de abertura e fechamento é um código HTML
      <head>
          Contem informações sobre a página
            <title>Titulo da página</title>
      </head>

      <body>
      
      A tag body delimita o conteúdo principal da página web
      <h1> Indica o nível mais alto de um cabeçalho que pode ir até 6</h1>
      <p>Esta tag delimita um paragráfo</p>
      Esse é um exemplo de tag que não precisa de fechamento<br>
      ela serve para quebrar a linha
  
      </body>

 </html>

```
______
______

#### Atributos:
Os atributos nos fornece mais informação sobre um elemento HTML, os atributos são inseridos na tag de abertura  e são divididos em duas partes? Nome e valor separados pelo sinal de igualdade

*<strong>Exemplo</strong>*
```html
      <p lang=”en-us”>O texto deste parágŕafo está em inglês graças ao atributo lang</p>
      <h1 align = "center"> Este cabeçalho está alinhado ao centro</h1>

```
:bell: *Obs: O valor de um atributo deve estar entre aspas*

______


#### Principais Elementos:<br>
##### <body>
Este é o que podemos chamar de corpo da página, todo o conteúdo do site está dentro desta tag, ela delimita o bruto de informações que um site pode mostrar na tela.

##### <head><br>
Este elemento vem antes do <body>, é no head que inserimos informações sobre a página como por exemplo o título definido pela tag <title>.

##### <title><br>
O conteúdo delimitado por esse elemento é mostrado no topo do browser






