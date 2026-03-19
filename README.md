## Cliente Gateway
el gateway es el punto de comunicación entre nuestros clientes y nuestros servicios.
 Es el encargado de recibir las peticiones, enviarlas a los servicios correspondientes y devolver la respuesta al cliente.

 ## Dev

 1. clonar
 2. instalar y crear el .env
 3. levantar los microservicios
 4. levantar el proyecto con `npm run start:dev`

 ## Nats
 ```
 docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
 ```