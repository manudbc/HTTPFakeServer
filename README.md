# HTTPFakeServer
Servidor http para analisis de malware, tambien se puede usar para transferiri archivos, la idea es poder forzar las respuestas que devuelve el servidor para poder igual el comportamiento a los servidores de internet.

En desarrollo:

python HTTPFakeServer.py -h
  -h, --help            show this help message and exit
  -p PORT, --port=PORT  TCP port number
  -i INTERFACE, --int=INTERFACE Interface IP listening

python HTTPFakeServer.py -p 80 -i 192.168.1.1

python HTTPFakeServer.py 
Default port 80
Default interface 0.0.0.0
