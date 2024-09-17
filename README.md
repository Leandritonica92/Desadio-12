## Objetivo:

El objetivo de este desafío es poner en práctica lo visto sobre helm y desarrollar nuestro propio
helm chart, tomando como entrada lo visto en los desafíos 10 y 11.

## Escenario:

Nuestro equipo identificó que Kubernetes agrega mucho valor a la hora de mantener los
deployments de nuestra aplicación y ha estado analizando la manera en que gestionamos el
código de estos deployments.
Luego de varias reuniones, identificaron que los manifiestos duplican mucho código y que esto
se puede resolver utilizando algún sistema de templates. Durante este sprint, se nos asignó la
tarea de desarrollar un Helm chart para gestionar el deployment de la aplicación. Este chart
debe desplegar la aplicación y el servicio de base de datos MongoDB para almacenar los datos
de nuestra aplicación.
La aplicación que va a ser manejada por este proceso se encuentra en el siguiente enlace:



https://github.com/edgaregonzalez/devops-bootcamp/tree/main/Desafios/Fase3/educacionit-app


[![desafio-12-foto.png](https://i.postimg.cc/gJB6DWm8/desafio-12-foto.png)](https://postimg.cc/8JM5pxFz)
