
--------------------------------------------------------------------------

#### \<table>

- \<tr>: filas de tabla (table row).

- \<th>: celdas de cabecera (table header).

- \<td>: celdas de datos (table data).

- \<caption>: título de la tabla.


![Pasted image 20260207212737.png](Pasted%20image%2020260207212737.png)


--------------------------------------------------------------------------

# Rowspan y colspan

![Pasted image 20260207212920.png](Pasted%20image%2020260207212920.png)

```HTML
<table border = "2">
	<tr>
		<thcolspan="2" rowspan="2"/>
		<thcolspan="2"> Horario</th>
	</tr>
	<tr>
		<th>Mañana</th>
		<th>Tarde</th>
	</tr>
	<tr>
		<throwspan="2"> Grupos</th>
		<th>G1</th>
		<td>20</td>
		<td>50</td>
	</tr>
	<tr>
		<th>G2</th>
		<td>34</td>
		<td>45</td>
	</tr>
</table>
```

![Pasted image 20260207213106.png](Pasted%20image%2020260207213106.png)

--------------------------------------------------------------------------


- Las tablas HTML deben usarse sólo para mostrar tablas de datos o información
- Usar etiquetas \<table> para dar formato a la página es una práctica obsoleta, usar _grid_ o _flexbox_ en CSS en su lugar


