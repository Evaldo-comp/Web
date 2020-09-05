### IMAGENS
Para adicionar imagens em uma página html utilizamos a tag ```<img>```, essa tag por sua vez  precisa de dois atributos para funcionar corretamente, são eles ```src``` que indica o caminho onde está situada a imagem e ```alt```, que define uma descrição para a imagem.

##### Exemplo:
```html
<img src = "images/img01.jpg" alt = "pôr do sol"/>
```
#### height e width
São dois atributos utilizados dentro da tag ```<img>``` que serve para modificar a altura e largura da imagem, respectivamente.

#### figure:
  
O elemento ```<figure >``` foi introduzido no HTML5 e serve como um container de imagens, juntamente com essa nova tag podemos adicionar o ```<figcaption>``` que adiciona uma legenda a imagem, basta digitar o texto que você quer na legenda entre as tags ```<figcaption></figcaption>```.

##### Exemplo:
```html
<!DOCTYPE html>
<html lang = 'pt-br'>
	<head>
		<meta charset="utf-8">
		<title>Imagens</title>
	</head>

	<body>
		<div class="container">
			
			<figure>
			<h1 >Pôr do Sol</h1>
			<img src="https://1.bp.blogspot.com/-GeQtQYjc49w/XrRsUqb4WDI/AAAAAAABHEs/OyaH74pnOJUlx7bhO8hy6AfLBvKApjxYwCLcBGAsYHQ/s1600/IMG_3580.JPG" alt="por do sol" width="200" height="200"></br>
			<figcaption>Pôr do sol em Fortaleza</figcaption>
			</figure>
		</div>

	</body>
</html>
```

No Browzer:
![]()



