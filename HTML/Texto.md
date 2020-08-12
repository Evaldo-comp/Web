### Tags para manipulação de TEXTO
#### Headings ou Cabeçalhos
A nomenclatura que vamos utilizar é *** cabeçalhos ***, eles possuem basicamente 6 níveis, e servem para diferenciar seções da página, a tag utilizada 
para implementar os diferentes níveis de cabeçalho é a ```<h1>````e ```</h1>```, altrando apenas o número após o h para determinar o nível.


*** Exemplo ***
```html
 <h1> Esse é o cabeçalho principal</h1>
 <h2> Esse é o segundo nível </h2>
.
.
.
<h6> Esse é o último nível</h6>
```

#### Parágrafos
Os parágrafos são delimitados pela tag ```<p>``` de abertura e a tag de fechamento ```</p>```.
```html
<p> Isso é um parágrafo</p>
```

#### Bold/Negrito 
As tags ```<b></b>``` deixam todo o conteúdo entre elas em ***negrito***.

<p>Nem tudo merece ser <b> destacado </b></p>

Italic <i>
As tags <i></i> deixam o conteúdo entre elas com  aparência de itálico

O prefeito falou:<i>” não tenho culpa disso”</i>. e então abandonou a seção

Sobrescrito e Subscrito

Em algumas ocasiões será necessário alterar o nível de uma letra ou número em relação a outra, como por exemplo mostrar a formula da agua h20 ou um potencia 2³
para isso temos as tags <sup></sup> Elas sobrescrevem um elemento

a fórmula é E - MC<sup>2</sup>

Para subscrever utilizamos a tags tags <sub></sub>
A fórmula da água é H<sub>2</sub>o

Quebra de linha e separador horizontal
Caso você queira pular uma linha no meio da anterior , precisará utilizar uma tag específica para isso, pois como o html desconsidera espaços, se você fizer dentro do conteúdo, sem utilizar a tag , o browser não irá mostrar a quebra, apenas um texto sequencial dentro do parágrafo. Para quebrar a linha utilize a tag única <br />

<p>.Esse texto continua<br />
na próxima linha</p>

a ag <hr /  > gera uma linha horizontal que nesse momento inicial de aprendizagem pode ser utilizado para separar seções do site 


Marcações semânticas
há alguns elementos que não irão alterar a estrutura propriamente dita, mas a forma como reconhecemos um determinado trecho do conteúdo o significado ou contexto diferenciado que é dado a este elemento

<strong>
Essa tag serve para indicar que um elemento é muito importante e merece se destacado

<p><strong>Atenção</strong>: Desliguem os celulares</p>

.Ênfase
para dar ênfase a um elemento textual basta colocá-lo entre as tags <em></em> o resultado será igual ao itálico mas o significado semântico de ambos são diferentes.

então ele disse:<em>Não ligo</em>

Citações
Existem duas formas de fazermos citações dentro de uma página web, a primeira é direcionada a citações longas , para isso utilizando <blockquote>

<blockquote cite = “origem da citação”> <p>corpo da citação</p><blockquote>.

para citações curtas podemos utilizar a tag <q>
<p>essa é <q>um citação curta</q></p>

Abreviações e Acrônimos
para abreviar algum nome utiliza-se a tag<abb> dentro dela é possível inserir o atributo title que serve para especificar o nome completo  que foi abreviado

<p><abbr title = “Engenheiro”>Eng</abbr>José alves da Silva</p>

Para siglas ou acrônimos como também é chamado pode se utilizar a mesma tag que imellmeta as abreviações

<p><abbr title=”Estados Unidos da américa ”>EUA<abbr></p>

Citações
Esse elemento semântico serve para indicar a origem de determinado citações, um livro, um filme etc.

<p><cite>origem da citação</cite>citação</p>

Definição
quando você vai definir algo, ha uma tag especifica para destacar o elemtno que eta sendo definido
<p><dfn>Metro</dfn>é uma unidade de medida</p>

O elemento <address>
essa tag serve para indicar contatos e informações sobre o autor da página
<address>
    <p>Rua tal número tal</p>
<address>

Alteração de conteúdo

Existem alguns artifícios para indicar que determinado conteúdo da página foi modificado, seja eliminado ou inseridos

a tag <ins> é utilizada para indicar a inserção de um elemento
a tag<del> indica que um elemento foi eliminado

<p>Esse elemento foi <ins>inserido</ins> e este foi <del>deletado<>/del</p>

