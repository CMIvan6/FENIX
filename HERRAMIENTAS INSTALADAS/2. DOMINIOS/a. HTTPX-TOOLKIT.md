# **HTTPX-TOOLKIT**

Permite a los usuarios investigar y recopilar información detallada sobre servidores web, detectar vulnerabilidades y analizar el comportamiento de las aplicaciones web, mediante escaneos y pruabas HTTP/HTTPS.

- *INSTALACIÓN*

      sudo apt install httpx-toolkit

- *EJECUCIÓN Y FUNCIONAMIENTO*

      httpx-toolkit -h
En este momento, se observarán todas las posibilidades que ofrece la herramienta. Para ello, ha de existir un archivo .txt que contenga una lista enumerada de los dominios con los que se quiere trabajar. 
Entonces, se utiliza la expresión "-l *nombre archivo .txt* para que httpx-toolkit acceda a la lista.
Por último, se especifican las "flags" que se consideren oportunas y que van a permitir la obtención de los diferentes tipos de datos. Estos son varios ejemplos de la larga lista que existe:

-title: título visible en el dominio

-td: tecnología utilizada por el dominio

-ip: host ip

-server: nombre del servidor

-ss: captura de pantalla

-extract-fqdn: dominios y subdominios

-method: método de solicitud http

En este momento, la herramienta podrá acceder a cada uno de los dominios presentes en la lista y devolver cada uno de los resultados obtenidos acerca de las "flags" indicadas.

 
- *EJEMPLO USO PRÁCTICO*



- *ENLACES EXTERNOS*

  - Github: https://github.com/projectdiscovery/httpx
  - Kali Linux: https://www.kali.org/tools/httpx-toolkit/
