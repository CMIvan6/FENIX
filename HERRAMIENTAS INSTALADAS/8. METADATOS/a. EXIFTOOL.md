# **EXIFTOOL**

Esta es una potente herramienta enfocada a la extracción de metadatos a partir de una gran diversidad de archivos como pueden ser imágenes, documentos de texto, etc.

- *INSTALACIÓN*

Acceder a https://exiftool.org/ y descargar el archivo correspondiente.

    $ cd ~/Desktop
    $ gzip -dc Image-ExifTool-12.87.tar.gz | tar -xf -
    $ cd Image-ExifTool-12.87
    $ ./exiftool t/images/ExifTool.jpg                

- *FUNCIONAMIENTO*
Comando para ver la ayuda de la herramienta:

        exiftool -h

Para utilizar ExifTool, se requiere especificar el archivo y las flags necesarias. A continuación, se muestran algunos ejemplos de las flags disponibles:

-all=: Borra todos los metadatos.

-tagsFromFile: Copia metadatos de otro archivo.

-csv: Exporta los metadatos en formato CSV.

-json: Exporta los metadatos en formato JSON.

- *EJEMPLO USO PRÁCTICO*



- *ENLACES EXTERNOS*

  - Github: https://github.com/exiftool/exiftool
  - Página oficial: https://exiftool.org/
