# PortsSquiScan

## Descripción

Este es un escáner de puertos escrito en Python que te permite verificar la disponibilidad de puertos en una dirección IP específica a través de un Squid proxy. Puedes elegir entre escanear los puertos más comunes o especificar un conjunto personalizado de puertos a escanear.

## Características

- Escaneo de puertos TCP en una dirección IP.
- Opción para escanear los 50, 100, 500 o 1000 puertos más comunes.
- Posibilidad de especificar puertos personalizados.
- Interfaz de usuario sencilla y amigable.

## Requisitos

- Python 3.x
- Librería `requests` (puedes instalarla usando `pip install requests`).

## Uso

1. Ejecuta el script `PortSquidScan.py`.
2. Sigue las instrucciones en pantalla para ingresar la dirección IP a escanear y seleccionar el conjunto de puertos.
3. El script mostrará los puertos abiertos en la dirección IP especificada.

## Ejemplo de Uso

```bash
python3 PortSquidScan.py

or

./ PortSquidScan.py

