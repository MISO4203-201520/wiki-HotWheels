---
layout: default
title:  "Arquitectura"
date:   2015-08-31 00:00:05
categories: posts
---

#Arquitectura del sistema

##Vista funcional

![Vista funcional]({{ site.url }}{{site.baseurl}}/assets/ciclo1/Componentes.png)

En la arquitectura de la aplicación encontramos 3 capas: Frontend, la capa de servicios Restfull y por último la capa de persistencia.


##Vista de despliegue

![Vista despliegue]({{ site.url }}{{site.baseurl}}/assets/ciclo1/Despliegue.png)

El artefacto generado mpUsedVehicle.web.0.0.1-SNAPSHOT.war es desplegado en un servidor Glashfish 4.0, la aplicación se accede desde cualquier navegador web y la data se almacena en una base de datos PostgreSQL.

##Vista de desarrollo

![Vista despliegue]({{ site.url }}{{site.baseurl}}/assets/ciclo1/DiagramaClases-Entidades.png)

El proyecto principal se compone por dos módulos, el primero contiene la lógica de persistencia y el segundo es un módulo web donde se encuentra el Frontend. Mediante un archivo pom.xml se empaquetan ambos módulos en un artefacto WAR.
