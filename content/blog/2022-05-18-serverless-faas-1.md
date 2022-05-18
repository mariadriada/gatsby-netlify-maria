---
layout: blog
title: Serverless (FaaS)
date: 2022-05-18T23:32:29.069Z
thumbnail: /statics/uploads/makeitreal.png
---
<!--StartFragment-->

Serverless es una nueva tendencia en el despliegue de aplicaciones que cada día adquiere más fuerza. En este post vamos a ver qué es, cómo funciona y cuál es la relación entre Serverless y FaaS (Functions as a Service).

La forma tradicional de desplegar aplicaciones es alquilar un servidor (p.e. una máquina virtual de [AWS EC2](https://aws.amazon.com/ec2/)) o un contenedor (p.e. [Heroku](https://heroku.com/)) y pagar por horas o meses por tener nuestra aplicación disponible.

Una desventaja de este modelo es el desperdicio de recursos: si nuestra aplicación no está recibiendo tráfico o ejecutando alguna tarea estamos pagando por recursos que no están siendo utilizados.

Otra desventaja es que si recibimos un pico de tráfico o de tareas vamos a tener que reaccionar para incrementar la capacidad o configurar alguna forma de escalamiento automático.

Serverless elimina estas desventajas. Por un lado, sólo pagamos por el tráfico o las tareas que ejecutemos y, por otro lado, el proveedor se encarga de escalar automáticamente la infraestructura a medida que incrementa el tráfico.

<!--EndFragment-->