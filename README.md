# badvpn
Servicio BADVPN UDPGW 7300

# Descarga de Archivos é Instalacion:

* sudo su

* cd

* apt-get update && apt-get upgrade -y

# Copiar y Pegar Lo Siguiente:

* apt install make -y && apt install cmake -y && wget https://www.dropbox.com/s/gs3ooy2h9egmj8l/badvpn-master.zip && unzip badvpn-master.zip && cd badvpn-master && mkdir build && cd build && cmake .. -DBUILD_NOTHING_BY_DEFAULT=1 -DBUILD_UDPGW=1 && make install

* Seguido Lanzar el Siguiente Comando:

badvpn-udpgw --listen-addr 127.0.0.1:7300 --max-clients 512 --max-connections-for-client 10 > /dev/null &

* Despues de Cada Reinicio se Apaga el Servicio BADVPN-UDPGW 7300, Volver a Lanzar el Comando:

badvpn-udpgw --listen-addr 127.0.0.1:7300 --max-clients 512 --max-connections-for-client 10 > /dev/null &

* @XhokitoPe

* Compatible con Ununtu 14, 16, 18

* NUNCA DEJES DE APRENDER




