# **NMAP**

Esta es una de las herramientas más usadas en el escaneo de direcciones IP. A través de esta, recopila una gran cantidad de información acerca de los hosts, dominios asociados, sistemas operativos, puertos abiertos y posibles vulnerabilidades de la misma.

- *INSTALACIÓN*

      $ sudo apt install nmap

- *FUNCIONAMIENTO*

Para utilizar Nmap, se requiere especificar la IP o dominio y las flags necesarias.

-sS: Realiza un escaneo SYN (half-open scan).

-O: Detecta el sistema operativo del objetivo.

-sV: Detecta versiones de servicios.

-A: Realiza detección avanzada de sistemas y servicios, incluyendo -O y -sV.

-p: Especifica los puertos a escanear.

-T4: Ajusta la agresividad del escaneo.

- *EJEMPLO USO PRÁCTICO*



https://github.com/user-attachments/assets/c27cf9ba-c6ab-4a11-83a7-4d7bd27d6948



- *ENLACES EXTERNOS*

  - Github: https://github.com/nmap/nmap
  - Kali Linux: https://www.kali.org/tools/nmap/
