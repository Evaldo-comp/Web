# Conceitos e Definições

## :large_blue_diamond: O que é o CSS?:

CSS é a sigla da expressão inglês (*Cascading Style Sheet*), que traduzindo significa uma folha de estilo em cascata, mas por que em casacata? por que a forma como
as modifcações são organizadas dentro de uma folha de estilo segue um certo nivel de hieraquia descenbte, considerando a prioridade destes itens dentro do HTML
e essa configiração de cima para baixo, um embaixo do outro leva a analogia de cascata. O CSS serve basicamente para melhorarmos a apresetção do nosso conteúdo WEB, claro que se nos aprofundarmos conseguirmos extrair muito mai9s desta linguagem.

## Regras CSS
Uma regra CSS é a menor parte de uma folha de estilo que consegue causar alguma modificação na apresentação de um site, por exemplo uma regra que altera a cordo background, ou que fixa o rodapé da página. 

<p align="center">
  <img src="https://github.com/Evaldo-comp/Web/blob/master/CSS/img/regra_css.png",  width="500px", height="500px">
</p>

**Seletor:** É o elemento do HTML ao qual a regra será aplicada

**Declaração:** A declaração é composta pela propriedade e pelo valor

**Propriedade:** Determina qual característica do selector será modificada

**Valor:** Indica como, ou o quanto essa propriedade será estilizada.

Uma regra CSS pode ter uma ou várias declarações como podemos observar no exemplo
```CSS
p {
    color: red;
    align = "center";
    font-size: 14px;
    }
```

O trecho acima possui três declarações dentro de uma gragra que estiliza um único elemento do HTML, no caso um paragráfo, 

Quando uma declaração se encaixa em mais de um seletor, estes podem ser agrupados e separados por vígula.
```CSS
p, h1, a { font-size: 12px; }
```
---
:pen: Dica: Valores como palavras compostas:<br>
São dois casos possiveis: 

Palavras compostas sem hífem: Utiliza-se aspas duplas ou simples no valor
```CSS
p {font-family: "Times New Roman";}
```
Palavras compostas com hífem
```CSS
p{font-family:sans-serif;}
```
---
## Cometários
O CSS assim como toda lingagem de programção possui uma forma deinserirmos comentarioos do coprpo do código:
**Cometáios de linha única**
```CSS
/* Esse é um cometário de linha única que não será renderizado pelo navegador*/
```
**Comentário em bloco**
```CSS
/* O que está
dentro deste
bloco 
não interfere na 
estilização
*/
```


