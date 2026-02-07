Son soluciones genéricas y reutilizables que se pueden aplicar a problemas habituales 

--------------------------------------------------------------------------

## Patrones comunes

### Patrón cliente-servidor con 3 capas

![[Pasted image 20260129133357.png]]

- Capa de Presentación
	Genera la interfaz con la información que genera la capa lógica de negocio

- Capa de Lógica de Negocio
	Responde a peticiones del usuario accediendo a las capas de presentación y de datos

- Capa de datos
	Proporciona acceso de los datos dentro de una base de datos a la capa de lógica de negocio

### Patrón modelo-vista-controlador

![[Pasted image 20260129133921.png]]

- Modelo
	Accede a los datos de una base de datos

- Vista
	Presenta los datos al usuario. Redirige peticiones de este al controlador

- Controlador
	Responde las peticiones del usuario, enviando peticiones de acceso a datos y/o mostrar una nueva vista



