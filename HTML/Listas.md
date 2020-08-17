### LISTAS

Em html temos três tipos de listas:<br>
- Listas ordenadas
- Listas não ordenadas
- Listas de definição<br>
A diferença entre cada uma delas pode ser melhor percebida nos exemplos seguintes.

***Exemplo de lista Ordenada***:
```html
<ol>
    <li>Matemática</li>
    <li>língua Portuguesa</li>
    <li>Geografia</li>
    <li>Química</li>
    <li>História</li>
</ol>
```

:planet: ***No Browzer:***

![lista Ordenada](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Lista%20Ordenada.png)


***Exemplo de lista Não Ordenada***:
```html
<ul>
    <li>Segunda</li>
    <li>Terça</li>
    <li>Quarta</li>
    <li>Quinta</li>
    <li>Sexta</li>
    <li>Sábado</li>
    <li>Domingos</li>
</ul>
```


:planet: ***No Browzer:***

![lista Não Ordenada](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Lista_%20n%C3%A3o_%20Ordenada.png)


#### Listas de definição
o nome é autoexplicativo, são listas criadas para facilitar a organização entre dois elementos, um a ser definido e a definição do mesmo. Essa lista é gerada a partir da tag
```<dl></dl>``` cada termo a ser definido dentro desta lista deve vir entre as tags ```<dt></dt>``` e a definição propriamente dita deve ser colocada entre as tags ```<dd></dd>```.

***Exemplo:***
```html
<dl>
   <dt>HTML</dt>
       <dd>
HTML é uma linguagem de marcação utilizada na construção de páginas na Web.
       </dd>
   <dt>CSS</dt>
       <dd>
 Cascading Style Sheets é um mecanismo para adicionar estilo a um documento web.
       </dd>
   <dt>JavaScript</dt>
       <dd>
JavaScript é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma.
       </dd>
</dl>
```


:planet: ***No Browzer:***

![lista de Definição](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/lista_de_definicao.png)


