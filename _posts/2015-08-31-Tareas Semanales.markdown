---
layout: default
title:  "Ciclos"
date:   2015-08-31 00:00:07
categories: posts
---

# Ciclos

## Ciclo 1

La siguiente es la distribución de tareas del ciclo 1 para el equipo de desarrollo.

[Tareas ciclo1](https://docs.google.com/spreadsheets/d/14Re4MI1rdxEbGsIuDLv_oj2KlumaGstapvi19gIuKo0/edit?usp=sharing "Tareas ciclo1")


### Cierre de ciclo

[Conclusiones ciclo 1](https://docs.google.com/presentation/d/1g5UzcYH4Qz4lw9r8Eyu8MHv7IrxCKqJwW8yT1JW-40E/edit?usp=sharing)

## Ciclo 2


Al realizar el levantamiento de tiempos y número de líneas de código generadas luego del primer ciclo, encontramos que para los 5 requerimientos desarrollados se habían empleado: 

* 39 horas para la parte del front-end y 594 líneas de código.
* 35 horas en back-end y servicios y 870 líneas de código.

Se empieza a hacer evidente que la dificultad tecnológica basada en tiempos de desarrollo se encuentra orientada a la parte del front-end, por lo que se deberá trabajar mucho sobre la capacitación del equipo en esta parte.

Adicionalmente, estimamos 5 requerimientos para el ciclo 2, todos en su gran mayoría pequeños en back-end y servicios y algunos medianos en front-end.

Al realizar la regresión lineal incluyendo el proyecto histórico No. 6 (Ciclo 1) y basados en la estimación del nuevo ciclo 2, se visualiza en  la gráfica que para las 610 líneas de código estimadas en front-end según la clasificación, el equipo se tomará aproximadamente 31 +/- 4.08 horas en desarrollarlas, con un intervalo de confianza del 70%. Al interpretar el valor del rango de 4.08 horas, podemos afirmar que es una estimación acertada y confiable y que estará muy ajustada al valor real que registrará el equipo. De igual manera, para la parte de back-end se visualiza en la gráfica que para las 1500 líneas estimadas según la clasificación el equipo se tomará 141 +/- 16 horas en desarrollarlas.

La anterior estimación servirá como insumo de la planeación del ciclo 2 y nos dará elementos confiables para asignar o no más tareas.

[Estimación ciclo 2](https://drive.google.com/file/d/0B1LKklBsJa3neHVEaDBBV2xEZjQ/view?usp=sharing)

### Cierre de ciclo

### Objetivos, metricas y evaluación

![Vista despliegue]({{ site.url }}{{site.baseurl}}/assets/ciclo2/ObjetivosCiclo2.png)

### Tamaño Real (LOCS) nueva entrada en el archivo de estimación.

En el siguiente archivo ya se incluye el ciclo 2 como datos históricos, preparando la regresión para un nuevo estimado futuro.

[Nueva entrada archivo estimación](https://drive.google.com/file/d/0B1LKklBsJa3nTkhqYnRyUWZuTEk/view?usp=sharing)

### % Error de Estimación de tamaño

Luego de culminar la fase de desarrollo y validación del proyecto, encontramos que para el ciclo 2 el equipo invertio un total de:

*  60 horas de desarrollo
*  16.5 horas de planeación, seguimiento y control
*  7 horas en corrección de bug, ciclo 1

Para un total de 83.5 horas invertidas entre todo el equipo. Al comparar dicho valor con las estimación realizada al inicio del ciclo se encuentra que:

* En front-end el equipo invirtió 28.1 horas para desarrollar 771 LOCS, lo que está correlacionado con las  31 +/- 4.08 horas y con las 610 LOCS planeadas, se entiende entonces que el modelo está cada vez más afinado en cuanto al front-end se trata y que en definitiva debe serguirse usando sin mayores ajustes.

* En back-end el equipo invirtió 32 horas para 683 LOCS, lo que en definitiva no esta correlacionado con las 141 +/- 16 horas, ni con las 1500 LOCS planeadas, en ese sentido es importante hace un ajuste mayor para que el modelo pueda seguirse usando de una forma más asertiva.

### Requerimientos Planteados vs Terminados

[Gráfica de planeados vs Terminados](https://docs.google.com/spreadsheets/d/1Dy6jvOLEXV6xR40aLhJGvpo8SqrUcJW0XhgR6akrCkA/edit?usp=sharing)

### Valor Ganado

![Valor Ganado]({{ site.url }}{{site.baseurl}}/assets/ciclo2/valorGanado.png)

## Ciclo 3

### Lanzamiento

*  [Nuevos Integrantes]({{ site.url }}{{site.baseurl}})
*  [Objetivos]({{ site.url }}{{site.baseurl}}/posts/2015/08/31/Objetivos.html)
*  Plan de acción - Nuevo integrantes
	*  Se realizará un sesión de integración con los nuevos miembros. En esta reunión se explicarán los principales aspectos a tener en cuenta en el desarrollo del proyecto. 
	*  Se espera que los nuevos integrantes revisen por su propia cuenta la información publicada en la wiki y en la carpeta de Google Drive.
	*  Los nuevos miembros deberán intentar compilar el producto por su propia cuenta. En caso de presentar inconvenientes, los antiguos miembros deberán ayudarlos. 
*  [DoD](https://docs.google.com/document/d/1e3ga3i8LHuFEvA-bIsMqZKeXr0gYDTVHjoMtjFE5Ap4/edit?usp=sharing)


### Estrategia

*  [Requerimientos]({{ site.url }}{{site.baseurl}}/posts/2015/08/31/Requerimientos%20Funcionales.html)
*  [Estimación de Tamaño y Esfuerzo](https://docs.google.com/spreadsheets/d/1ayouEV0mTv4BDxmHkgNkj5bFRYHMZQRWHE_a_FyYsvQ/edit?usp=sharing)
	
	Para el ciclo 3 se espera un tamaño de 460 LOC de Front, 1100 LOC de Back y 200 LOC de Servicios REST. Con base a la estimación PROBE se otuvo un total de 24 horas en Front y 120  horasde Back y Servicios. Adicionalmente, cpn base en el análisis de impacto del control de cambios se espera un esfuerzo de 23 horas. Por tanto, se estima un esfuerzo del ciclo de 163 horas.

*  [Alcance Ciclo 3 y 4]({{ site.url }}{{site.baseurl}}/posts/2015/08/31/Alcance%20Global.html)

### Proceso de Desarrollo

*  [Pruebas automatizadas](http://157.253.238.75:9000/dashboard/index/19062)
*  [Proceso de control de cambios](https://docs.google.com/spreadsheets/d/18pyr4Jx-RNRQWNpAwN0-070Ma5AlvjJwqeFIqNwEn_c/edit?usp=sharing)

### Conclusión

1. [**Análisis de evaluaciones de pares**](https://docs.google.com/document/d/1XrhJOlSjr3A4MZhL8RPtVbescqBXF42Kh3OkP87lJNM/edit?usp=sharing)

2. **Métricas de producto**

	* [Totalizar líneas de código (Front, Service, Back y pruebas)](https://docs.google.com/spreadsheets/d/1joXWp3k7vkwwvfEreoT11u_YUBL88TdAPK9VOZ8oYrY/edit?usp=sharing)
	* % de requerimientos completados

En el ciclo 3 se plantearon 4 requerimiento por desarrollar y 2 cambios, de los cuales **satisfactoriamente se implementaron y completaron el 100 %** de estos. Sin embargo, cabe resaltar que de los requerimientos implementados no fue posible realizar pruebas tanto de servicio como funcionales.  
Igualmente, no se agregaron pruebas de lógica sobre requerimientos de los ciclos 1 y 2. Lo anterior, debido a la dificultad de configuración de las diferentes pruebas lo que consumió gran parte del tiempo.
En cuanto al avance de los requerimientos totales del ciclo, se ha desarrollado el 78.26 % de los requerimientos planteados en la aplicación mpUsedVehcles.

* Cubrimiento de las pruebas

![Cubrimienrto ciclo 3]({{ site.url }}{{site.baseurl}}/assets/ciclo3/cubrimiento.png)

En cuanto al cubrimiento del código, dado que no fue posible avanzar en pruebas de requerimientos de los ciclos pasados y que la configuración de las pruebas de servicio y funcionales requirieron mas tiempo del planeado, el porcentaje de cubrimiento es inferior al 70 %. Tan solo se logro cubrir un 36.3 % de incluye pruebas de lógica de 3 requerimientos, pruebas de servicio de 2 requerimientos y 1 prueba funcional.
Pese al porcentaje obtenido, vemos una oportunidad y avance en las pruebas y calidad del código, pues la curva de aprendizaje de las nuevas tecnologías de las pruebas fue abarcada en este ciclo y ya tenemos un conocimiento para avanzar en el siguiente.


3. **Métricas del proceso**

* Análisis de valor ganado

![Analisis ganado ciclo 3]({{ site.url }}{{site.baseurl}}/assets/ciclo3/valorGanado.png)

* Productividad del equipo

	No fue posible obtener el 100 % del valor ganado al finalizar el ciclo dado que se esperaba cumplir con las pruebas de Lógica, Servicios y Funcionalidad en todos los requerimientos y cambios. Las pruebas, como se menciona anteriormente tuvieron una gran dificultad en su configuración y no fue posible aumentar el cubrimiento del código. Sin embargo, sí fue posible completar todos los requerimientos y cambios planeados para el ciclo 3. 
	
	Así mismo, se presentó un problema de seguimiento de las actividades en Youtrack lo que generó que en gran parte los tiempos se hayas actualizado al entre la semana 2 y 3. Esto último dificulta observar el valor ganad para cada semana. Adicionalmente, dado que teníamos como proposito finalizar los requerimientos solo cuando se obtuvieran las pruebas, tan sólo hasta los últimos días se modificó el estado de las tareas a finalizado. 
	
	El poco seguimiento de las actividades también impacto en que algunos miembros no subieron sus tiempos de reuniones los cuales son significativos para el ciclo.
	
	Finalmente, se obtuvo un esfuerzo total de 176.25 horas, es decir se obtuvo un error de estimación del 8 %. Cabe destacar que no fue posible culminar las tareas de pruebas sobre los nuevos requerimientos. Adicionalmente el tiempo estimado era mucho mayor al esperado (9 horas por miembro cada semana).

4. **Estrella de mar**

	* [Individual](https://docs.google.com/spreadsheets/d/1DaYuyrtKkcW4-KschbRKO6uCC-bYroytknorLzyT7XI/edit?usp=sharing)
	* Grupal
	![Estrella de Mar]({{ site.url }}{{site.baseurl}}/assets/ciclo3/EstrellaMar.png)
	* [Reflexión](https://docs.google.com/document/d/1z65MxoLctaMyUXq0Dt-IlQb8f-_w1Z58MDcOP-IuafE/edit?usp=sharing)

5. **Plan de mejora**

	De acuerdo a los resultados obtenidos y a la retrospectiva de la estrella de mar, se plantean las siguientes mejoras para el ciclo 4:
	
	1.	Realizar el correspondiente seguimiento de Youtrack cada semana, para identificar avances y posibles riesgos que se puedan presentar.
	2.	Comunicar tareas de configuración a tiempo (por Whatsapp) para asegurar que no se realice un trabajo repetidas veces.
	3.	Revisar el cambio de las métricas antes de subir los cambios a Github y luego de realizar los cambios, para identificar posibles aumentos a la deuda técnica.
	4.	Planear con anticipación el desarrollo de las pruebas, en especial para el ciclo 4 se espera que todos los nuevos requerimientos tengan pruebas de lógica, persistencia y servicios.
	5.	Se asignarán nuevas tareas de deuda técnica y de usabilidad con base en las encuestas recibidas y los resultados de Sonar.


*  [Presentación](https://docs.google.com/presentation/d/1Ajiv8MKhjHTsToQL-YA_xA0GQBtzPPLm-f1Nz4kXIAQ/edit?usp=sharing)
  

## Ciclo 4

### Lanzamiento

*  [Roles de integrantes]({{ site.url }}{{site.baseurl}})
*  [Objetivos]({{ site.url }}{{site.baseurl}}/posts/2015/08/31/Objetivos.html)
  
### Estrategia

*  [Estimación de Tamaño y Esfuerzo](https://docs.google.com/spreadsheets/d/1tWjSqYlVkoIaf0q8_vQTk5HoAzJyClC7EeRfPZfYB14/edit?usp=sharing)
*  [Milestones por semana](https://docs.google.com/spreadsheets/d/1IMwHfd94kPURtAM-Y_4CIJ_WPvW6r2YKlk2NqanLr5I/edit?usp=sharing)
*  [Requerimientos]({{ site.url }}{{site.baseurl}}/posts/2015/08/31/Requerimientos%20Funcionales.html)
*  [Alcance Ciclo 3 y 4]({{ site.url }}{{site.baseurl}}/posts/2015/08/31/Alcance%20Global.html)

### Proceso de Desarrollo

*  [Pruebas automatizadas](http://157.253.238.75:9000/dashboard/index/19062)
*  [Proceso de control de cambios](https://docs.google.com/spreadsheets/d/17ifCcd6X_F5zkxI_1Y37qqczVfWUs_n0PIMjZh9UoZU/edit#gid=259233180)
*  [Mockups](https://docs.google.com/document/d/18ZojRT5FtnHAx2zanAIVAVb_fc9wIsw5td7L_caHnI4/edit)

### Conclusión

1. [**Análisis de evaluaciones de pares**](https://docs.google.com/document/d/1_4CUfzocbwErz_3DdsO497fhYV58WfMlm5vEATRZ3bs/edit?usp=sharing)
2. **Métricas de producto**

* [Totalizar líneas de código (Front, Service, Back y pruebas)](https://docs.google.com/spreadsheets/d/1tWjSqYlVkoIaf0q8_vQTk5HoAzJyClC7EeRfPZfYB14/edit#gid=2115328777)

* **Porcentaje de requerimientos completos**

En el ciclo 4 se plantearon 4 requerimiento por desarrollar,1 cambios y desarrollo de deuda técnica y usabilidad, de los cuales **satisfactoriamente se implementaron y completaron el 100 %** de estos. Sin embargo, cabe resaltar que de los requerimientos implementados no fue posible realizar pruebas tanto de servicio como funcionales.  
Igualmente, no se agregaron pruebas de lógica sobre requerimientos de los ciclos 1 y 2. Lo anterior, debido a que los requerimientos nos llevaron más tiempo del esperado. Igualmente, no hubó tanto compromiso de lso integrantes como en ciclos anteriores.
En cuanto al avance de los requerimientos totales del ciclo, se ha desarrollado el 95.65 % de los requerimientos planteados en la aplicación mpUsedVehcles.

* **Cubrimiento de las pruebas**


![cubrimiento proyecto]({{ site.url }}{{site.baseurl}}/assets/ciclo4/Pruebasciclo4.PNG)
Figura 1. Cubrimiento de pruebas del ciclo 4

Por problemas de organización no fue posible aumentar considerablemente el cubrimiento de las pruebas. Por otro lado, no fue posible utilizar la automatización de las pruebas de lógica, persistencia y servicios, pues en nuestro caso al implementarlas nos salían varios errores en la compilación en Travis. Por lo anterior, fue necesario continuar con las pruebas manuales. Otro aspecto que incluyó en las pruebas fue que no se asignaron puntualmente tareas de pruebas sobre los componentes desarrollados en ciclos anteriores. Para una próxima oportunidad se recomienda asignar no solo nuevos requerimientos sino deuda técnica a todos los integrantes del equipo.

![cubrimiento proyecto]({{ site.url }}{{site.baseurl}}/assets/ciclo4/Pruebasciclo4_web.PNG)

Figura 2. Cubirimeinto de pruebas en web

![cubrimiento proyecto]({{ site.url }}{{site.baseurl}}/assets/ciclo4/Pruebasciclo4_logica.PNG)

Figura 3. Cubirimeinto de pruebas en logica

Con respecto a la comparación entre pruebas de Back y Front/Service, es posible ver que aún falta mayor dedicación y compromiso para implementar este tipo de pruebas. Dado que varios de los miembros no habían trabajado sobre estas, no logramos tomarnos el tiempo de mejorar esta métrica.

* **Reporte de costos de calidad**

Con base en los tiempos que nos llevó corregir errores en de ciclos anteriores con respecto a los tiempos de corregir errores durante etapas tempranas y la prevención del mismo podemos decir lo siguiente:

	*	En caso que los errores sean mínimos, ej. Falta un “;”, el tiempo de corregir el error en etapas tempranas versus corregir el error en etapas más avanzadas o en diferentes ciclos, vemos que es el mismo tiempo. Es decir, el costo de la No conformidad es igual al costo de la conformidad.

	*	Sin embargo, en caso que se prevenga el error, es más costos la No conformidad que la conformidad. En general por cada “;” que estemos pendientes de agregar el tiempo es de milésimas de segundo (ms). Comparada con el tiempo que le lleva la no conformidad del mismo, en este caso el tiempo puede aumentar a unos 10 minutos teniendo en cuenta que se debe localizar el archivo a modificar.

	*	Con respecto a las pruebas, detectamos que es bastante costoso la conformidad del mismo, es decir, los tiempos aumentan e incluso se duplican o triplican al agregar pruebas a cada detalle del código. En este caso, es preferible la no conformidad, en donde se ataquen varias pruebas de códigos atrasados y estables. Este último proceso se puede automatizar.
En general, a nosotros el tiempo de corrección de defectos o No Conformidad para este ciclo tuvo un costo de alrededor de 40 horas .Sin embargo, con este tiempo aún no se logró mejorar la calidad del código. Se recomienda identificar unas buenas prácticas para todos los miembros del equipo de modo que se reduzca el costo con la conformidad del mismo.

* [Reporte de Deuda Técnica](https://docs.google.com/document/d/1o-46114uP65nyw1YL9yC19LjF06rr0f6GKQej0BePTE/edit?usp=sharing)
 

3. **Métricas de proceso**

* [Analisis valor ganado ciclo 4](https://docs.google.com/spreadsheets/d/1IMwHfd94kPURtAM-Y_4CIJ_WPvW6r2YKlk2NqanLr5I/edit?usp=sharing)

* Productividad del equipo

	No fue posible obtener el 100 % del valor ganado al finalizar el ciclo dado que se esperaba cumplir con las pruebas de Lógica, Servicios y Funcionalidad en todos los requerimientos y cambios. En este caso no se desarrollaron los requerimientos con tiempo, por lo cual no fue posible emplear tiempo para las pruebas, en especial de servicio y funcionalidad. 
	Con respecto al valor ganado, este fue al finalizar el ciclo de 87.62 %, no hubo un desarrollo incremental adecuado de semana a semana. En este caso para la semana 2 tan solo se tiene un valor ganado de 34.27 %.

	Finalmente, se obtuvo un esfuerzo total de 154.5 horas, es decir se obtuvo un error de estimación del 3.13 %. Cabe destacar que no fue posible culminar las tareas de pruebas sobre los nuevos requerimientos. Adicionalmente el tiempo estimado era mucho mayor al esperado (9 horas por miembro cada semana). Igualmente, faltaron varios tiempos que no se llenaron en youtrack con respecto a tareas de proceso.

4. **Retrospectiva de la estrella de mar**

	* [Individual y Grupal](https://docs.google.com/spreadsheets/d/1tYMKNKHek6Jt3Un-oEl-er-H4PWlcBHXXn5753jI5eo/edit?usp=sharing)
	* [Reflexión](https://docs.google.com/document/d/1z65MxoLctaMyUXq0Dt-IlQb8f-_w1Z58MDcOP-IuafE/edit?usp=sharing)

5. **Lecciones aprendidas y aspectos por mejorar**

* [Lecciones aprendidas y apesctos de mejora](https://docs.google.com/document/d/1fTliO0M1MosnXuQkzKu92CuSidkn77xBmGF1wwikHDc/edit?usp=sharing)

*  [Presentación](https://drive.google.com/file/d/0B86H59_O12Mcc2Q5aDBCTlloLVE/view?usp=sharing)

