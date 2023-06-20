SUPSI 2022-23  
Corso d’interaction design, CV427.01  
Docenti: A. Gysin, G. Profeta  

Elaborato 2: Antologia a due mani 

# Posate e bacchette
Autore: Arianna Stöckli
[MediaPipe demo-ES6](https://ariannastockli.github.io/Posate_e_bacchette/)


## Introduzione e tema
Il progetto consisteva nel fare una ricerca testuale e iconografica di oggetti, segni e gesti legati all’uso delle mani. 
Le posate sono strumenti fondamentali per l'alimentazione quotidiana nel mondo occidentale. Questo sito esplora la storia, l'evoluzione, il design e l'utilizzo delle posate e bacchette. Saranno esaminati gli aspetti culturali e curiosi legati alle posate, insieme ai materiali usati, alle forme e alle tendenze attuali nel design delle posate.


## Riferimenti progettuali
Dolor sit amet consectetur adipiscing elit duis tristique. 


## Design dell’interfraccia e modalià di interazione
Il sito si sviluppa interamente su una pagina, attraverso la navbar posizionata in cima è possibile raggiungere facilmente tutti i capitoli della ricerca. Grazie al pulsante “indice” è possibile raggiungere la pagina principale con tutti i progetti.

Il layout è suddiviso in due colonne principali. La colonna a sinistra che contiene il contenuto dettagliato della ricerca sulle posate e a destra le immagini correlate. 
Quando la visualizzazione viene ridimensionata su dispositivi mobili o schermi più piccoli, la colonna si trasforma in un layout singolo, con il testo posizionato sopra e le immagini disposte sotto.


## Tecnologia usata
Nunc consequat interdum varius sit amet mattis vulputate. Vehicula ipsum a arcu cursus vitae congue. Odio ut sem nulla pharetra. Accumsan lacus vel facilisis volutpat est velit egestas dui id. Quisque egestas diam in arcu cursus. Eget nulla facilisi etiam dignissim diam. 


```JavaScript
const image = new Image();
image.onload = () => {
	gl.bindTexture(gl.TEXTURE_2D, texture);
	gl.texImage2D(
		gl.TEXTURE_2D,
		level,
		internalFormat,
		srcFormat,
		srcType,
		image
	);
	if (isPowerOf2(image.width) && isPowerOf2(image.height)) {
		gl.generateMipmap(gl.TEXTURE_2D);
	} else {
		gl.texParameteri(gl.TEXTURE_2D, gl.TEXTURE_WRAP_S, gl.CLAMP_TO_EDGE);
		gl.texParameteri(gl.TEXTURE_2D, gl.TEXTURE_WRAP_T, gl.CLAMP_TO_EDGE);
		gl.texParameteri(gl.TEXTURE_2D, gl.TEXTURE_MIN_FILTER, gl.LINEAR);
	}
};
image.src = url;
```

## Target e contesto d’uso
Sed enim ut sem viverra aliquet eget sit. Iaculis at erat pellentesque adipiscing commodo. Et pharetra pharetra massa massa ultricies mi quis hendrerit dolor.
