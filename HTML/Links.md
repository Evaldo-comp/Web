### LINKS

Links são elementos que direcionam o usuário de lugar para outro, que pode ser dentro da mesma página a qual ele se encontra, pode ser para outra página, 
outro site no mesmo browser ou até mesmo outro site em browser diferente. A  tag utilizada para criarmos links é a ```<a></a>```, com o auxílio do atributo 
```href = ""```, nós indicamos qual o site destino daquele link.

#### Links para o mesmo site:
Se as páginas a qual você quer acessar estão dentro do mesmo folder, você irá utilizar URL's relativas, especificando apenas o nome do arquivo sem haver a
necessidade de inserir o domínio, se o arquivo não estiver no mesmo folder, você deverá especificar o caminho completo do arquivo dentro do seu computador.

***Exemplo:***
```html
<ul>
    <li><a href="Home">Home</a></li>
    <li><a href="Galeria">Galeria</a></li>
    <li><a href="Contatos">Contatos</a></li>
    <li><a href="Sobre Nós">Sobre nós</a></li>
</ul>
```
#### link para email:
É possível criar um link que levará o usuário para um aplicativo de e-mail ou abra seu e-mail no browser, para isso  o atributo href deve iniciar com ``m̀ailto``:.

***Exemplo:***
```html
<a href =”mailto:meuemail@gmail.com”>e mail</a>
```


#### Abrindo link em uma aba diferente da atual:
Ao clicar em um link, por padrão, ele irá abrir na página atual, acontece que o usuário pode não querer abandonar a página atual enquanto visita o conteúdo
do link, para isso devemos utilizar o atributo ```target`` seguido do valor ```-blank``

***Exemplo:***
```html
<a href=”link do site” target = “_blank”>galeria</a>
```


#### Abrindo link dentro da mesma página:
Para abrir um link dentro de uma mesma página, vocẽ deve indicar o local para qual será direcionado ao clicar no link, essa identificação é feito com o atributo
```id``,no atributo ```href``` do link a ser clicado deve-se colocar como valor o nome do id antecipado por ```#```, veja o exemplo:

***Exemplo:***
```html

		<h1>Conteúdo</h1>
		<p id = "Paragrafo01">	Nunc sit amet imperdiet nisi. Aenean eu lacus sapien. Praesent interdum leo et mauris consequat<br> 
			fermentum. Suspendisse posuere ut eros et volutpat. Vestibulum ac tristique massa. Pellentesque est <br>
			lacus, consequat vel auctor ut, semper quis nunc. Quisque sed nulla nunc. Integer dictum quam non <br>
			urna tristique vulputate. Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br> 
			Nam ullamcorper <br>non orci vitae interdum.</p>

		<p>	Nunc sit amet imperdiet nisi. Aenean eu lacus sapien. Praesent interdum leo et mauris consequat<br>
			fermentum. Suspendisse posuere ut eros et volutpat. Vestibulum ac tristique massa. Pellentesque est <br>
			lacus, consequat vel auctor ut, semper quis nunc. Quisque sed nulla nunc. Integer dictum quam non <br>
			urna tristique vulputate. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam ullamcorper <br>
			non orci vitae interdum.</p>

		<a href="#Paragrafo01">Voltar ao topo</a>
    ```
    
#### linkando uma parte específica de outra página:
A técnica é a mesma que anterior, a diferença é que inserimos a url da pagina, dentro dessa url o último elemento  que sinaliza a parte específica da página destino deve vir seguida de ```#```.

***Exemplo:***
```html
<a href=”http://www.meusite.com/#contados”></a>
<!--essa estrutura irá levar o usuário para a página de contatos deste site. -- >

```

:house:[HOME](https://github.com/Evaldo-comp/Web)







