### FORMULÁRIOS

Os formulários  são essenciais em qualquer website que precise coletar algum tipo de informação do usuário . Existem váŕias formas de coletar essas informações, tudo depende do tipo de dado.

##### Como os formulários funcionam:
As informações ao serem submetidas são enviadas a um  servidor, esse servidor processa as informações usando uma linguagem como PHP,  C# ou Java,  guarda as informações tratadas em um banco de dados e envia uma resposta baseada no que  for solicitado das informações armazenadas.


##### Adicionando Textos

Text input - single line: Utilizado para coletar uma informação de texto curta, como por exemplo, nome ou e-mail.

##### Exemplo:
```html
<form action="http://www.servidor.php" method="get" >
	<p> Input do tipo Texto.</p>
	<input type="txt" name="">
</form>
```

:earth_americas: *No borowser*:

![Text Input](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/txtinput.png)

##### Text - Área (mult-line):
 Utilizado para coletar mensagens de texto maiores, como comentários ou mensagens.
 
 ##### Exemplos:
 ```html
<form action="http://www.servidor.php" method="get" >
	<p> Input do tipo Text Área.</p>
	<textarea name="sugestões">Deixe aqui suas sugestões</textarea>
</form>
```
:earth_americas: *No Browser*:

![Text Área](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/textarea1.png)

#### Password input:

Caixa específica para coletar Senha.Quando o tipo do atributo type é password, é criado um box de linha única que recebe apenas caracteres, essa caixa esconde os dados digitados. Os atributos ```name```, ```size```, têm a mesma função que nos outros tipos de inputs, que são respectivamente nomear o elemento para ser direcionado corretamente para o servidor e indicar o tamanho da caixa, respectivamente, nesse caso temos ainda o ```maxlenght``` que indica o tamanho da senha.

##### Exemplo:
```html
<form action="http://www.servidor.php" method="get" >
	<p>Password
	
		<input type="password" name="password" size="15" maxlength="30">
	</p>
</form>
```


:earth_americas: ##### No Browzer:

![Password](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/password.png)













