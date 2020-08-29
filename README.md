# -SA-Practica3
Práctica # 3: Coreografía de Servicios

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

La Practica3_SA esta compuesta por 3 programas(servicios), un cliente, un restaurante y un servidor de repartidores; con el objetivo de simular un servicio de crowdsourcing de comida a domicilio.

Con las siguientes acciones:

  1. Solicitud de comida por parte del cliente.
  2. Recepción de órdenes en el restaurante.
  3. Servicio de entrega por el repartidor.
  
## Funciones del Cliente
El servidor del cliente corre sobre el puerto 5000.

### Hacer pedido
Realiza una peticion post con la informacion necesaria para realizar una peticion al servicio del Restaurante.

## Funciones del Restaurante
Este servicio actua como un cliente y un servidor, corre sobre el puerto 6000.

## Funciones del servicio de Repartidores
Este servicio actua como un servidor, corre sobre el puerto 7000.
