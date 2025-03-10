---
date: "2019-05-05T00:00:00+01:00"
linktitle: Carga/Descarga de Waypoints de GPS
title: Carga/Descarga de Waypoints de GPS
type: book
weight: 4
---
### Cargar coordenadas con etiquetad de código (id de plantación) a una unidad GPS

1) Primero, descargue los datos de la plataforma con los Códigos y las coordenadas GPS.
2) Cree una nueva hoja de Excel y copie las siguientes columnas en ella:
a. Columna 1 = Latitud (grados decimales con signo)
b. Columna 2 = Longitud (grados decimales con signo)
c. Columna 3 = Identificador (cadena de texto)
d. Pero no incluyas ningún encabezado de columna
3) Guarde este archivo de Excel como * .csv (el nombre del archivo no importa)
4) Luego cargue el archivo en la aplicación GPSBabel para exportarlo como un archivo GPX.[Link](https://www.gpsbabel.org/screenshots.html)
5) Conecte la unidad GPS Garmin a la computadora
6) Copie y pegue el archivo * .gpx en la carpeta "GPX" de la unidad GPS.
7) Después de desconectar la unidad GPS y encenderla, es posible que se necesiten unos minutos para que todos los waypoints aparezcan en el mapa.

### Para crear y cargar waypoints a unidad desde ArcMap

1) Cree los puntos en ArcMap de la misma forma que puede crear y / o modificar cualquier shapefile nuevo en ArcMap (por ejemplo, con un generador de puntos aleatorios).
2) Si desea que los puntos de referencia tengan etiquetas, asegúrese de que haya una columna de texto en la tabla de atributos titulada "nombre".
3) Utilice la herramienta "FeaturesToGPX" que ya ha sido descargada. Ábrala con el catálogo.
4) Conecte la unidad GPS Garmin a la computadora
5) Copie y pegue el archivo * .gpx en la carpeta "GPX" de la unidad GPS.
6) Después de desconectar la unidad GPS y encenderla, es posible que se necesiten unos minutos para que todos los waypoints aparezcan en el mapa.

### Para descargar waypoints desde la unidad GPS Garmin y subir a ArcMap

1) Conecte la unidad GPS Garmin a la computadora
2) Copie y pegue el archivo * .gpx de la carpeta "GPX" de la unidad GPS en una carpeta de su computadora.
3) Luego cargue el archivo en la aplicación GPSBabel para exportarlo como un shapefile ESRI
a. [https://www.gpsbabel.org/screenshots.html](https://www.gpsbabel.org/screenshots.html)
b. [https://www.gpsbabel.org/htmldoc-1.6.0/fmt_shape.html](https://www.gpsbabel.org/htmldoc-1.6.0/fmt_shape.html)
4) Luego abra el shapefile con ArcMap usando el Catálogo.

<img src="/manuals/chapter1/Fig48.jpg" width=750 style="float: right; margin-top:1rem; margin-bottom:0rem;">

