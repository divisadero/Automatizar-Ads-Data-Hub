# Automatizar-Ads-Data-Hub
Como usar la API de Ads Data Hub

Pasos Automatizacion Ads Data Hub



Prerrequisitos: python2

Descargar libreria de muestra: https://developers.google.com/ads-data-hub/samples/sample-files/full-circle-query-v2-python-examples.tar.gz

Habilitar Full Circle Query API en las APIs del proyecto asociado

Seguir instrucciones README en esa carpeta

Crear API Key desde APIs->Credentials del proyecto asociado.

Crear un OAuth 2.0 client ID desde APIs->Credentials->OAuth Client ID->Application Type->Other del proyecto asociado, descargando json con credenciales.

Instalar Paquetes python: pip2 install -r requirements.txt

En samples_util.py actualizar CLIENT_SECRETS_FILE con direccion de credenciales json

Actualizar las variables de los archivos python con los datos correspondientes a tus identificadores y necesidades.

Correr archivos como: python2 list_customers.py 
