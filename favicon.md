# Cómo generar un favicon

1. Ir a [Favicon Generator](https://realfavicongenerator.net/)

2. Selecciona la imagen

![selectImage](images/selectImage.png)

3. Especifica los ajustes necesarios

![ajustesFavicon1](images/ajustesFavicon1.png)
![ajustesFavicon2](images/ajustesFavicon2.png)
![ajustesFavicon3](images/ajustesFavicon3.png)
![ajustesFavicon4](images/ajustesFavicon4.png)
![ajustesFavicon5](images/ajustesFavicon5.png)
![ajustesFavicon6](images/ajustesFavicon6.png)

4. Ir a **Favicon Generator Options** en la misma página
y genera el favicon

**Nota:** Asegúrate de realizar los ajustes necesarios

![generarFavicon](images/generarFavicon.png)

5. Descarga el paquete

![descargarFavicon](images/descargarFavicon.png)

**Nota:** Una vez descargado el paquete, extrae los archivos y colócalos
en la raíz del sitio web. Es decir, colocarlos al mismo nivel del `index.html`

![archivosFavicon](images/archivosFavicon.png)

6. Copia las líneas de código que indican y pégalas en `head` en el `index.html`

```
	<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
	<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
	<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
	<link rel="manifest" href="/site.webmanifest">
	<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
	<meta name="msapplication-TileColor" content="#da532c">
	<meta name="theme-color" content="#ffffff">

```

7. [Check your Favicon](https://realfavicongenerator.net/favicon_checker)