
--------------------------------------------------------------------------

#### \<video>
Permite insertar contenido de video en un documento HTML. Tiene los mismos atributos que [[IV Elemento de audio|audio]] y:

- height: Altura a la que el video se renderizará
- width: Anchura a la que el video se renderizará
- poster: Imagen que sustituye al video

```HTML
<body>
	<video src = "URL del fichero de video“ 
			height="alto" width="ancho”
		poster="imagenAlternativa.jpg"
		controls
		autoplay
		loop
		preload = "auto|metadata|none”
	/>
</body>
```

