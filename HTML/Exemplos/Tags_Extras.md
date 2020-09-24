### TAGS EXTRAS

#### DOCTYPES:

Devido às várias versões já lançadas de HTML. toda página deve começar uma tag ```doctype```, elas servem para ajudar na renderização página pelo browser, indicando qual versão do html está sendo utilizada naquele documento.
```HTML
<!DOCTYPE html>
```
#### Comentários:

Comentários são úteis para ajudar a legibilidade do código e facilitar a manutenção do mesmo,  para adicionar um comentários basta colocá lo entre dentro dessa estrutura ```<!-- →>```, tudo o que estiver dentro desta estrutura será ignorado pelo browser. Além da legibilidade, os comentários ajudam na documentação do site, mas é bom ficar atento para não abusar do seu uso, pois um código muito carregado de  comentários, mais atrapalha do que ajuda.
```html

<!-- Isso é um comentário e não apareceŕa para o usuário -->
```
#### IndentificadorID:<br/>
Um atributo  ID serve para identificar um elemento para outros elementos, essa identificação pode começar com uma letra ou underline, ou seja, nada de números ou qualquer outro caractere para iniciar a identificação de um elemento. É importante ficar atento a intenção destes elementos para  não ocorrer a duplicação de nome dentro da mesma página, ou do mesmo projeto, isso pode dificultar a manutenção do código.
```html

<p id = "paragrafo01">Donec ornare, leo ut dictum porttitor, sem dui tempus erat, sed molestie eros nisi et nunc. Phasellus ac massa metus. Aenean dictum, nisi in condimentum faucibus, justo velit semper ipsum, ut ornare tortor lorem et est.</p>
<p id = "Paragrafo02">Mauris vitae erat laoreet, euismod odio nec, ornare nibh. Suspendisse potenti. Vestibulum id dignissim sem. Morbi quis dui a massa malesuada feugiat vitae tincidunt neque. Nullam pellentesque mollis aliquam. </p>
```
#### Indentificador Class:<br/>
Funciona de forma semelhante ao ID, a diferença é que o id é indicado para a identificação de um único elemento, com  atributos que não irão se repetir, ou terão uma ocorrência modesta dentro do código, já o atributo class, serve para identificar elementos que irão compartilhar alguns atributos, facilitando, desta forma a formatação dos mesmo.
```html

<p class = "Paragrafo01">Donec ornare, leo ut dictum porttitor, sem dui tempus erat, sed molestie eros nisi et nunc. Phasellus ac massa metus. Aenean dictum, nisi in condimentum faucibus, justo velit semper ipsum, ut ornare tortor lorem et est.</p>
<p class = "Paragrafo02">Mauris vitae erat laoreet, euismod odio nec, ornare nibh. Suspendisse potenti. Vestibulum id dignissim sem. Morbi quis dui a massa malesuada feugiat vitae tincidunt neque. Nullam pellentesque mollis aliquam. </p>

```
#### Elementos de bloco

Alguns elementos quando são executados pelo browser sempre iniciam uma nova linha, estes elementos são chamados de elementos de bloco.```<h1>```, ```<p>```, ```<ul>``` e ```<li>```.
```html
<h1>Aniversariantes do mês</h1>
<p>Setembro</p>
<ul>
    <li>Rubens: 23 / 09 </li>
    <li>Pedro: 28 / 09 </li>
    <li>Ana: 30 / 09 </li>
</ul>
```

#### Elementos inLine:
Alguns elementos são utilizados dentro do conteúdo de forma a não interromper o fluxo do texto, esses elementos são conhecidas como inline,as tags abrem e fecham no decorrer do texto sem ser necessário quebrar o conteúdo em blocos: ```<a>```, ```<b>```, ```<em>```, e ```<img>```.
```html

Phasellus hendrerit, magna a <em>tincidunt ornare</em>, mi diam tempus nisi, et gravida elit nibh id dolor.
In nec ullamcorper libero, a iaculis <b>massa</b>. Praesent id erat a arcu hendrerit varius ac vitae arcu. 
Etiam fermentum dictum mollis. Integer in neque pharetra, semper tortor nec, ullamcorper arcu. Nunc maximus 
vel urna ut consequat. Etiam gravida faucibus porta.rmentum dictum mollis. Integer in neque pharetra, semper 
tortor nec, ullamcorper arcu. Nunc maximus vel urna ut consequat. Etiam gravida faucibus porta.
```
#### Agrupando texto e elementos em um bloco:<br/>
A tag ```<div>``` permite que possamos agrupar vários elementos em um mesmo nível, funcionando como uma espécie de caixa, ou divisória, ao se nomear essa div podemos usar o CSS para aplicar configurações comuns a todos os elementos dentro dela.
```html

<div id = “menu”>
    <h1>Menu</h1>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="galeria.html">Galeria</a></li>
        <li><a href="contatos.html">Contatos</a></li>
    </ul>
</div>
```
#### Agrupando textos e elementos inline:<br/>
O ```<span>``` funciona de forma semelhante ao ```<div>``` mas agrupando elementos inline sem a necessidade da formação de blocos.
```html
<p>Donec ornare, leo ut dictum porttitor, sem dui tempus erat, sed molestie eros nisi et nunc. Phasellus ac massa metus. Aenean <span class = "galeria">dictum, nisi in condimentum faucibus</span>, justo velit semper ipsum, ut ornare tortor lorem et est. Mauris vitae erat laoreet, euismod odio nec, ornare nibh. Suspendisse potenti. Vestibulum id dignissim sem.</p>
```
#### Iframes:<br/>
São como pequenas janelas com um determinado conteúdo dentro de sua página, esse conteúdo pode ser um mapa, vídeo, imagem e até mesmo outro texto em destaque.
Para criar um iframe e utilizar conteúdo ou serviço de outros sites devemos utilizar a tag ```<iframe>```. Segue alguns atributos que podem ser utilizados dentro desta tag

- <b>src:</b> Importa uma imagem através da url
- <b>height:</b> especifica a altura da janela do iframe em pixels
- <b>width:</b> Especifica a largura janela do iframe pixels
- <b>seamless:</b> é utilizado em iframes onde não é necessário barras de rolagem

#### Informação sobre suas páginas:<br/>
A tag ```<meta>``` tem como função fornecer informações sobre sua página web. Essa tag não visível ao usuário e não precisa de uma tag de fechamento mas é bastante útil para a equipe de  desenvolvimento e documentação de um projeto grande. Os atributos mais comuns são ```name``` e ```content``` que  são usados juntos. O nome é de sua escolha e o conteúdo é relacionado diretamente com o nome que você escolher, alguns nomes comumente utilizados são:<br/>
description: No conteúdo vem a descrição do conteúdo da sua página, isso é muito útil para sua página ser encontrada por máquinas de busca.

- <b>keywords:</b> identifica as palavras chaves que podem ajudar sua página a ser encontrada por motores de busca.

- <b>robots:</b> esse atributo indica se os motores de busca deve, adicionar sua página aos resultados de busca ou não.

- <b>author:</b> autoexplicativo

- <b>pragma:</b> Esse previne que o browser salve a página localmente

- <b>expires:</b> Normalmente os browzers guardam informações das páginas localmente em caches, esse atributo indica quando esse conteúdo devem expirar, ou seja, quando devem ser eliminados cache.
```html
!DOCTYPE html>
<html>
  <head>
         <title>Informações sobre sua página</title>
         <meta name="description"
             content="Uma simples página estática para meu portfólio" />
         <meta name="keywords"
             content="portfólio" />
         <meta name="robots"
             content="nofollow" />
         <meta http-equiv="author"
             content="Evaldo" />
         <meta http-equiv="pragma"
             content="no-cache" />
         <meta http-equiv="expires"
             content="Fri, 04 Abr 2021 23:59:59 GMT" />
  </head>
    <body>
    </body>
</html>
```
#### Caracteres Reservados:<br/> 
Alguns caracteres são reservados, ou seja,usados pelo html como por exemplo  ```<>``` utilizados para identificar as tags, por isso se esses caracteres forem digitados  irão causar um erro na apresentação do conteúdo ou simplesmente não aparecerão, se o objetivo é mostrar estes caracteres devemos utilizar códigos, seguem alguns deles:</br>
- ```<```     &lt:   ou  &#60:
- ```>```     &gt:   ou  &amp:
- ```&```     &amp:  ou  &#38:
- ```“```     &quot: ou  &#34

Para fazer uma conversão direta utilize esse site <br/> 
[Caracteres Especiais](https://www.freeformatter.com/html-escape.html#ad-output)

#### Adicionando Videos: <br/>
A tag ```<video>``` possui atributos que permitem controlar o player embutido na página.

- <b>src:</b> Atributo já conhecido por nós, também utilizado na tag de imagens, esse atributo é a abreviatura de source, logo, seu valor é a origem do vídeo, uma url ou o endereço do recurso no seu computador.<br/>
- <b>poster:</b>Esse atributo permite que você escolha uma imagem para ser visualizada no seu vídeo enquanto ele nao esta rodando, é uma espécie de capa<br/>
- <b>preload:</b> Esse atributo informa ao browser o que fazer quando a página carrega, os valores possíveis são:
  - none: A página só deve carregar o vídeo quando o usuário pressionar play
  - auto: A página deve rodar o vídeo quando a página carregar
  - metadata: O browser deve apenas carregar informações como largura , altura, duração e track list
  - controls: Quando usado esse atributo indica que o browser pode utilizar seus próprio controles para o player de vídeo
  - autoplay: autoexplicativo
  - loop: autoexplicativo
  
```html

<!DOCTYPE html>
<html>
<head>
         <title>Adicionando video</title>
</head>
<body>
         <video src="video/arriégua.mp4"
             poster="images/arriégua.jpg"
             width="400" height="300"
             preload
             controls
             loop>
             <p>Um vídeo arretado</p>
         </video>
</body>
</html>
```
 - Adicionando multiplos videos 

Para especificar o endereço dos múltiplos vídeos, deve-se utilizar a tag ```<source>``` que substitui a <src>, essa última vira atributo da tag <source>, outros atributos seguem abaixo:<br/>
- <b>type:</b> Informa ao browser o formato do vídeo
- <b>codec</b>: O codec que será utilizado para carregar o vídeo  fornecido dentro do atributo type

#### Adicionando Áudio na  sua página:<br/>
Para incluir áudio usa-se as tags ```<audio></audio>```, esse elemento funciona de forma semelhante ao que é usado para incluir videos, inclusive seus atributos, tem basicasnte a mesma função, por isso nao vou descrevê-las aqui um por um, apenas listá-los:
- autoplay<br/> 
- preload<br/>
- loop<br/>















