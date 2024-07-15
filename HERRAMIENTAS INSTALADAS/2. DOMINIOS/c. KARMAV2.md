# **KARMAV2**

Herramienta que permite la recopilación de información técnica a partir de un dominio como filtraciones de datos e información oculta, direcciones IP, infraestructura interna, etc.
Para la utilización de KARMAV2 es necesaria la API key de Shodan Premium.

- *INSTALACIÓN*

      $ git clone https://github.com/Dheerajmadhukar/karma_v2.git
      $ python3 -m pip install shodan mmh3
      $ apt install jq -y
      $ go install -v github.com/tomnomnom/httprobe@master
      $ git clone https://github.com/codingo/Interlace.git & install accordingly
      $ go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest
      $ apt install lolcat -y
      $ go install -v github.com/tomnomnom/anew@master

      $ cat > .token
        "Insertar la API key de Shodan"

  - *FUNCIONAMIENTO*
Comando para ver la ayuda de la herramienta

          bash karma_v2 -h
Para utilizar KARMAV2, se requiere especificar el dominio y las flags necesarias.
A continuación, se muestran algunos ejemplos de las flags disponibles en KARMAV2:

-d: Define el dominio objetivo.

-ip: Muestra las direcciones IP relacionadas con el dominio.

-asn: Realiza un escaneo ASN.

-cve: Busca vulnerabilidades relacionadas con CVEs.

-favicon: Obtiene y analiza el hash del favicon.

-leaks: Busca fugas de información.

- *EJEMPLO USO PRÁCTICO*



- *ENLACES EXTERNOS*

  - Github: https://github.com/Dheerajmadhukar/karma_v2
