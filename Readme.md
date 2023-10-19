# Como hacer un cartucho de Wherigo con preguntas en 5 minutos
Con esta plantilla podrás crear un Wherigo de preguntas en 30 minutos sin saber programar.								
El formato del cartucho será una pregunta con tres posibles respuestas y una imagen.								
Antes de empezar tenemos que:
- Instalar el programa [Urwigo](https://www.urwigo.cz/?page_id=6) en nuestro ordenador.
- Tener pensadas todas las preguntas y respuestas y seleccionadas las imágenes.							
1.	Empezamos en la hoja preguntas de google sheet.	
	- Abrir la [hoja de calculo de google](https://docs.google.com/spreadsheets/d/1o1DaymnPEKW84qOImNBNVAuXHimWy2jl0JQt28LZTeg/edit?usp=sharing).		
	- Crear una copia del fichero en nuestro google usando *Archivo/Hacer una copia*
	- Tenemos tres hojas: la primera con las **Instrucciones**, la segunda con las **Preguntas** que tenemos que rellenar y la tercera para hacer la **Descarga**.		
	
2. En la hoja **Instrucciones** Rellenar los campos 	**Bienvenida** con lo que aparecerá como presentación del cartucho y la casilla **Enlace** que será un enlace o texto que aparecerá cuando teminen el cartucho..
	- Rellenar las preguntas y respuestas en la hoja **Preguntas**.
	- En la columna **Pregunta** ponemos cada una de las preguntas que queemos hacer, no se pueden usar las comillas dobles **"** solo comilla simples**'**.
	- En las columnas **OPCIÓN1**, **OPCIÓN2**, **OPCIÓN3** rellenamos cada una de las posibles respuestas a la pregunta de la fila correspondiente.
	- En la columna **CORRECTA** ponemos el número correspondiente a la opción correcta.
	- En la columna coordenadas ponemos las coordenadas finales de ese caché en formato de google: 40.123456,-3.123456. Si solo hay una coordenada, ponerla en la última pregunta y dejar las demás en blanco.

3.	Pasamos a la hoja **Descargar**							
	- Estando en esta hoja en el menú **Archivo/Descargar** seleccionamos valores separados por tabuladores (tsv) y descargamos el fichero.						

	![Descargar](Imagenes/Descargar%20tsv.png)	

4. [Descargamos la carpeta Templates](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/marianoqnk/QuestionsWherigo/tree/main/Templates) con todos sus ficheros en nuestro ordenador.
	- Descomprimimos en nuestro directorio de trabajo					
	- Renombramos el fichero descargado a "Wpreguntas.lua".

5. Imagenes: tienen que estar todas en la misma carpeta que el cartucho .
	- Todas las imágenes tienen que estar en formato jpg.
	- Los nombres de las imágenes deben constar de tres números del 001, 002,...,  010, 011, ..., 101, y así hasta el final.						
	- Conviene que el tamaño de las imágenes sea lo mas reducido posible para que ocupen poco espacio en memoria Vamos a la página : [BulkResizePhoto](https://bulkresizephotos.com/es?padding=true&type=exact&value=800). Subimos nuestras imágenes y les cambiamos la resolución a alrededor de 460x340 que para Android es más que suficiente. Utilizamos la opción fijar ancho a 460 y la calidad de la imagen al 50%. Tambienm podemos utilizar cualquier otro programa de imágenes que nos permita bajar la resolución un trabaje por lotes, como Photoshop o su alternativa gratuita, Gimp.	
	- Una vez que tenemos las imagenes las ponemos en la carpeta que hemos creado. Se sobreescribiran los fichero que ya existen, pero lo importante es que conserve el nombre.
	- Añadimos un fichero de imagen que se llama logo.jpg con la imagen que queremos que sea el logo de nuestro cartucho.
6. Una vez lo tenemos todo en la carpeta abrimos el fichero **Questions Wherigo.urwigo** con Urwigo, apareceremos en la pantalla de inicio.
![Pantalla de inicio](./Imagenes/Cambiar%20inicio.png) 		
	- Aquí cambiamos los campo que creamos necesarios: name, description, version, company, author. El logo debe aparecer con el que hemos colocado en nuestro fichero.
	- La plantilla está preparada con diez imágenes, si necesitamos más debemos crearlas nosotros. Para ello vamos a la opción media y le damos añadir vamos rellenando numeraciones consecutivas y asociando el fichero correspondiente.
	- Una vez tenemos todo vamos a **Build/Run/UTF-8** debe compilar nuestro cartucho sin errores y ejecutarlo en el emulador.

								

														
					
# Vídeos
[Wherig for dummies: Introducción](https://youtu.be/KxPzrrLustY).

[Wherig for dummies I: Guia de Getafe](https://youtu.be/L6rr626Fhi4).

[Wherig for dummies II:  Lobo Oveja Lechuga](https://youtu.be/4yx4_0dHh14).
								
# Manuales

[Manual pdf Wherigo for Dimmies](Wherigo%20for%20dummies%20manual.pdf)
								