### TABELAS

Tabelas são bastante utilizadas para organizar conteúdo em colunas e linhas. Para criar uma tabela em html, utilizamos o elemento ```<table>``` tudo entre as tags ```<table></table>``` são considerados elementos estruturais da tabela.

#### ```<tr>``` - Table Row
Para inserir uma linha basta utilizar a tag ```<tr></tr>```.

#### ```<td>``` - Table Data
Para construir uma célula, usamos ```<td></td>```.

#### ```<th>``` - Table Head
Esse elemento é utilizado para inserir um cabeçalho da tabela, ele pode ser utilizado com elemento ```<td>```.
  
#### Mesclando células:
Para mesclar células, usamos o atributo ```colspan```, esse atributo pode ser usado juntamente com as tags ```<th>``` e ```<td>```.

#### Mesclando colunas
Para mesclar colunas usamos o atributo ```rowspan``` que também pode ser usado nas tags ```<th>``` ou ```<td>```.

Existem alguns elemetnos mais sofisticados que servem para indicar o tipo de conteúdo dentro de uma tabela, são eles:

 - ```<thead>```
Os título da tabela deve estar dentro deste elemento

 - ```<tbody>```
O corpo, conteúdo principal da tabela, deve estar dentro desta tag

 - ```<tfoot>```
Essa tag irá guardar o rodapé da tabela

##### Exemplo:

```html
<body>
		<table border="1px">
			<thead>
				<tr><th colspan="4">Clubes por Região</th></tr>
			</thead>
			
			<tbody>
			<tr>
			    <td>Norte</td>
			    <td>Sul</td>
			    <td>Nordeste</td>
			    <td>Sudeste</td>
			</tr>

			<tr>
			    <td>Ypiranga</td>
			    <td>Grêmio</td>
			    <td>Ceará</td>
			    <td>Palmeiras</td>
			</tr>

			<tr>
			    <td>Santana</td>
			    <td>Inter</td>
			    <td>Fortaleza</td>
			    <td>São Paulo</td>
			</tr>
			<tfoot>
				<tr><td colspan = "5">Fonte: wikpédia</td></tr>
			</tfoot>
		    </tbody>

		</table>

	</body>
```

:eart: No Browzer 
![Tabela](https://github.com/Evaldo-comp/Web/blob/master/HTML/Exemplos/Capturas/tabela.png)


:house:[HOME]()






  
  





