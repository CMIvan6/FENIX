# **BING-IP2HOSTS**

Basado en el motor de búsqueda de Bing.com, permite recopilar información sobre los hosts, subdominios y dominios relacionados, así como aquellos que comparten alojamiento, a partir de una dirección IP.

- *INSTALACIÓN*

      $ sudo apt install bing-ip2hosts

- *FUNCIONAMIENTO*
Comando para ver la ayuda de la herramienta:

      ./bing-ip2hosts -h

Para utilizar Bing-IP2hosts, se requiere especificar la dirección IP o el nombre de host y las flags necesarias.
A continuación, se muestran algunos ejemplos de las flags disponibles en Bing-IP2hosts:

-o FILE: Especifica el archivo de salida para los nombres de host.

-i FILE: Define un archivo de entrada con una lista de direcciones IP o nombres de host.

-n NUM: Detiene el scraping después de que NUM páginas no devuelvan nuevos resultados (por defecto: 5).

-l: Selecciona el idioma para el parámetro setlang (por defecto: en-us).

-m: Selecciona el mercado para el parámetro setmkt.

-u: Muestra solo nombres de host (sin prefijos de URL).

-c: Salida en formato CSV.


- *EJEMPLO USO PRÁCTICO*



https://github.com/user-attachments/assets/0e4ad423-2969-446e-9b30-780bb2662d7f


- *ENLACES EXTERNOS*

  - Github: https://github.com/urbanadventurer/bing-ip2hosts
  - Kali Linux: https://www.kali.org/tools/bing-ip2hosts/
