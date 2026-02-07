
--------------------------------------------------------------------------

#### \<audio>
Permite insertar contenido de audio en un documento HTML

Atributos:
- src: Se establece la URL del fichero de audio
- controls: Ordena al navegador que presente controles de reproducción
- autoplay: Comienza la reproducción una vez se cargue la página sin el permiso del usuario
- loop: Vuelve a reproducir el audio cuando éste termine
- preload: Indica si ha de descargarse el fichero completo, sólo los datos de cabecera o no descargar nada hasta que el usuario solicite la reproducción

```HTML
<body>
	<audio src="URL del fichero de audio" 
controls
	autoplay loop 
preload="auto|metadata|none" />
</body>
```

