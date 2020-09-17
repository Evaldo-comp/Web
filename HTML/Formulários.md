### FORMULÁRIOS

Os formulários  são essenciais em qualquer website que precise coletar algum tipo de informação do usuário . Existem váŕias formas de coletar essas informações, tudo depende do tipo de dado.

##### Como os formulários funcionam:
As informações ao serem submetidas são enviadas a um  servidor, esse servidor processa as informações usando uma linguagem como PHP,  C# ou Java,  guarda as informações tratadas em um banco de dados e envia uma resposta baseada no que  for solicitado das informações armazenadas.

______

##### Adicionando Textos

#### Text input - (Single line):

Utilizado para coletar uma informação de texto curta, como por exemplo, nome ou e-mail.

##### Exemplo:
```html
<form action="http://www.servidor.php" method="get" >
	<p> Input do tipo Texto.</p>
	<input type="txt" name="">
</form>
```

:earth_americas: *No borowser*:

![Text Input](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/txtinput.png)

______

##### TextÁrea (mult-line):
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

______


#### Password input:

Caixa específica para coletar Senha.Quando o tipo do atributo type é password, é criado um box de linha única que recebe apenas caracteres, essa caixa esconde os dados digitados. Os atributos ```name```, ```size```, têm a mesma função que nos outros tipos de inputs, que são respectivamente nomear o elemento para ser direcionado corretamente para o servidor e indicar o tamanho da caixa, nesse caso temos ainda o ```maxlenght``` que indica o tamanho da senha.

##### Exemplo:
```html
<form action="http://www.servidor.php" method="get" >
	<p>Password
	
		<input type="password" name="password" size="15" maxlength="30">
	</p>
</form>
```

:earth_americas: *No Browzer:*

![Password](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/password.png)

______

#### Elementos de Seleção:

##### Radio button:

Utilizado em situações onde você só pode escolher uma das opções:

Radio buttons aceita apenas uma opção selecionada os atributos desse elemento são:

```name```:  É enviado ao servidor juntamente com o valor escolhido pelo usuário.

```value```: Armazena  a opção selecionada pelo usuário 

```Cheked```:Esse atributo deve ser utilizado ppara indicar qual o valor deve ser selecionado quando a página carregar

##### Exemplo:
```html
<form action="http://www.example.com/profile.php">
	<p>Por favor escolha o seu gênero:<br />
		<input type="radio" name="genero" value="masculino"
         	checked="checked" /> Masculino
		<input type="radio" name="genero" value="Feminino" />
         	Feminino
		<input type="radio" name="genero" value="Outro" />
         	Outro
	</p>
</form>
```


:earth_americas: *No Browzer:*

![RadioButton](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/radiobutton.png)


______


#### Checkboxes:

São utilizados quando são possíveis escolher mais de uma opção como resposta, ou seja quando são permitidos mais de uma campo selecionado.
Possui como atributos ```name```, ```value``` e ```checked``` que exerce basicamente a mesma função dos outros tipos de inputs.<br/>

##### Exemplo:
```html
<form action="http://www.example.com/profile.php">
<p>Selecione seu serviço de stream de vídeo favorito:<br />
<input type="checkbox" name="service"
         value="Netflix" checked="checked" /> Netflix
         <input type="checkbox" name="service"
         value="amazonPrime" /> Amazon Prime
<input type="checkbox" name="service"
             value="globoPlay" /> Globo Play</p>
</form>
```

:earth_americas: *No Browzer:*

![Checkbox](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/CHECKBOX.png)




https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/CHECKBOX.png





















