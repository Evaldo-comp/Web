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

:earth_americas: *No Browser*:

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
		<input type="radio" name="genero" value="masculino" checked="checked" />
         	 Masculino
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
	<input type="checkbox" name="service" value="Netflix" checked="checked" /> 
          Netflix
         <input type="checkbox" name="service" value="amazonPrime" />
          Amazon Prime
	<input type="checkbox" name="service" value="globoPlay" />
          Globo Play
    </p>
</form>
```

:earth_americas: *No Browzer:*

![Checkbox](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/CHECKBOX.png)

______

#### Drop Down:
Também chamado de caixa de seleção, esse elemento consiste em uma lista suspensa de itens que você pode escolher, essa caixa de seleção é criada a partir da tag ```<select>```, tem ```name``` e ```value``` como atributos com  a mesma função que exercem nos demais elementos: O drop down conta com um tag interna chamda ```<option>```, essa tag especifica quais opções o usuário pode selecionar dentro da lista, o nome destes elementos devem vir entre as tags ```<option></option>```.

##### Exemplo:
```html
<form action="http://www.example.com/profile.php">
  <p>Qual destes países foi o primeiro a sofrer com a pandemia?</p>
   <select name="paises">
      <option value="brasil">Brasil</option>
      <option value="china">China</option>
      <option value="EUA">EUA</option>
   </select>
</form>
```

______

#### ELEMENTOS DE SUBMISSÃO:

##### File input box:

Se você quiser que o usuário faça o upload de algum arquivo, foto, música, vídeo etc, esse é o elemento indicado para esta operação, dentro da tag principal ```<form>``` o atributo *method* deve estar inicializado com o valor *“post”*. Esse elemento conta com dois tipos de inputs expeciais. O primeiro deles  *"file"*, as estrutura completa completa fica assim: ```type = “file"```, ele cria uma caixa de texto com um botão que ao ser clicado abre a janela do gerenciador de arquivos do sistemas operacional. O outro é  ```“submit”```,  este elemento gera um botão usado para submeter o formulário aos servidor.

##### Exemplo:
```html
<form action="http://www.example.com/upload.php"
method="post">
    <p>Selecione uma imagem 3 x 4:</p>
    <input type="file" name="foto" /><br />
    <br/>
    <input type="submit" value="Upload" />
</form>
```

:earth_americas: *No Browzer:*

![File_Submit](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/file_submit.png)

______

#### Agrupando elementos de formulário:

Você pode agrupar   formulários relacionados utilizando o elemento ```<fieldset>```,a estrutura é bem simples,inicia-se com a tag de abertura ```<fieldset>``` e encerra-se com tag de fechamento ```</fieldset>```, entre essas tags os formulários são alocados utilizando sua estrutura padrão, pode-se adicionar uma tag extra para identificar o grupo, a tag ```<legend>``` faz esse trabalho.

##### Exemplo:
```html
<fieldset>
    <legend>Contact details</legend>
    <label>Email:<br />
    <input type="text" name="email" /></label><br />
    <label>Mobile:<br />
    <input type="text" name="mobile" /></label><br />
    <label>Telephone:<br />
    <input type="text" name="telephone" /></label>
</fieldset>
```

:earth_americas: *No Browzer:*

![fieldset](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/fieldset.png)


______


#### Validação de Formulário:

O usuário recebe um alerta se algo está faltando no formulário, ou alguma informação fornecida não corresponde ao formato esperado, esse tipo de alerta é chamado de validação de formulário, normalmente é realizada utilizando JavaScript, mas atualmente o HTML consegue fazer essa validação sem utilização de outra linguagem.

##### Exemplo:
```html
<form action="http://www.example.com/login/" method="post">
	<label for="username">Username:</label>
		<input type="text" name="username" required="required" /></title><br />
		<br/>
	<label for="password">Password:</label>
		<input type="password" name="password" required="required" />
		<br/>
		<input type="submit" value="Submit" />
</form>
```

______


#### DATE  input em HTML 5:
É um simples caminho fornecido pelo html 5 para coletar data sem necessariamente precisar utilizar um text input, para isso basta usar o atributo type com valor “date”. Da mesma forma podemos criar um elemento específico para coletor e-mail, url ou busca, basta modificar o valor de atributo type para ```“email”```,  ```“url”```, ou ```“search”``` respectivamente. Adicionalmente para tornar o formulário mais legível ao usuário pode-se utilizar o atributo placeholder, que mostra uma dica de preenchimento ao usuário, essa dica é equivalente. 

##### Exemplo:
```html
<form action="http://www.example.com/bookings/" method="post">
         
    <label for="username">Departure date:</label>
    <input type="date" name="depart" />
    <input type="submit" value="Submit" />
    	<br/>
	<br/>
    <input type="email" name="email" placeholder="identifcador@email.com" />
    <input type="submit" value="Submit" />
    	<br/>
	<br/>
    <input type="url" name="url"  placeholder="http://www.endereçodosite.com" />
    <input type="submit" value="Submit" />
</form>
```

:earth_americas: *No Browzer:*

![date](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/date.png)

______


:house:[HOME](https://github.com/Evaldo-comp/Web)

















































