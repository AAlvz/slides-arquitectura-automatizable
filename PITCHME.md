---

 ### Arquitectura Automatizable
 ### (@_aalvz)
 ### (GH: AgusRumayor)

 <span style="color:gray">Tinkerware</span>

---

## ¿Soy arquitecto de software?


+++

## Subes cosas al repositorio?
### Entonces... lo más probable es que sí.

+++

### ¿Cuándo y en qué puntos se hace arquitectura?
![cloud](assets/arq_cloud.png)

+++

## Puntos que ve un arquitecto
* Escalabilidad
* Seguridad
* Disponibilidad
* Mantenibilidad
* Desempeño
* Confiabilidad
* Usabilidad
* Estresabilidad

---

## Habilidades de un arquitecto de software

* Metodologías
* Tecnologías
* Planeación
* Diseño
* Dominio

+++

## Metodologías


+++

## Tecnologías

+++

## Planeación
![yoda](yoda.jpg)

+++

## Diseño

+++

## Dominio

+++

![AgusRumayor](assets/chart_AgusRumayor.png)

+++

![AAlvz](assets/chartAalvz.png)

---

## Estilos/Patrones/Tecnologías

+++

## Estilos

+++

## Patrones

+++

## Tecnologías

---


---

## Por qué Automatizar la arquitectura?

---

Esta es una Arquitectura. TW. Explicar.

---

Es necesario montarla. Obviamente considerando las caracteristicas que definen a una Organizacion de TI de Alto Rendimiento.

Cuales son?

---

# Caracteristicas

- Nivel alto de servicio. Servicio de Calidad
- Disponiblidad
  - Medibles en : Tiempo Promedio de Reparacion. y Tiempo Promedio Antes de Fallos
- Confiabilidad
  - Medible en: Tasa de cambios exitosos
- Invertir tiempo en etapas tempranas del ciclo de vida del dpto de TI.
  - Medible en: Cantidad de recursos y personas enfocados actividades de Pre-Produccion, administracion de releases, testing...
- Integrar Operaciones y seguridad
  - Medible en: Cantidad de Deploys que cumplen con requerimientos de seguirdad y que son aprovados.
  - resulta en Menos trabajo despues de Deploy.
- Cantidad baja de Trabajo no Planeado (Apagar incendios)
  - Organizaciones de alto desempeño >> 5% de trabajo no planeado
  - Organizaciones tipicas >> 35% - 45% trabajo no planeado.

3 principales:
  - Cultura de administracion de cambios.
    - "Este cambio. Es necesario?"
    - "La unica cantidad de cambios aceptables sin autorizacion es ZERO".
  - Cultura de Causalidad
    - 80% de fallos son debido a cambios.
    - 80% del MTTR de esos fallos es tratando de encontrar qué cambió
    - Tener una buena administracion de cambios, ayuda a encontrar una posible solucion al problema mas del 80% de las veces, acertando el  90% de las veces a la primera.
    - Debemos mantener eso de guiarse por el sentimiento y la intuición? "...Vamos a ver si esto funciona".... "Y si reinicias este server?" .. Solo resulta en resoluciones mas largas
     y tasas de reparacion mas bajas. 
  - Cultura de Mejora continua.
    - Encontrar problemas antes de que sean problemas
    - Controles para prevenir

---

80% del downtime y fallos (obviamente no planeados) son causados por actividades de nosotros mismos:
Errores humanos, problemas dentro del proceso: Practicas pobres de administrcion de cambios.
20% es causado por fallas de tecnologia y desastres.

---

Que significa?

![Kill all the humans}(https://memegenerator.net/img/instances/500x/50445790/kill-all-humans-for-a-better-tomorrow.jpg)

"Charles Darwin. Debemos estar atentos al cambio." Siempre hay modificaciones, parches, etc.  


Post it: ¨No Tocar¨

---

"Automatizar no da valor directo a mis clientes o a mi empresa"

---

Falso

Note:
Hacer Pruebas, automatizacion, nos da velocidad.

Si se crea, prueba y entrega mas rapido, se aprende y se mejora mucho mas rapido.

---

Tiempos de Deploy - 200x
Tiempos de Entrega - 2555x

---

Equivale a Un gran valor de Negocio que afecta directamente a los Clientes.

---

No es necesario sacrificar confiabilidad.

Tasa de cambios exitosos - 3x
Recuperacion de errores - 24x

---

![](https://www.r1soft.com/hubfs/SBM_Images/Logos/PhoenixNAP-Global-Logo.png?t=1508856451440)

"Nos dimos cuenta de que entre mas servicios levantabamos, mas procesos manuales entraban"

---

"Hicimos este año mas de 800,000 cambios. Ahorramos, de manera conservadora, 1,000,000 USD"

Cambios Rapidos, Continuos y Confiables.

Note:
Teniamos que migrar un sistema Legacy. Normalmente toma tres o cuatro meses y tres o cuatro ingenieros.
Lo hicimos en 18 horas. Ahorrando por lo menos 100 000 USD

Sin contar a los developers que estan esperando dos meses a que les liberen algo, o la semana de deploy que debe hacer

---

![](http://logok.org/wp-content/uploads/2014/05/Walmart-Logo-slogan.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/Getty_Images_Logo.svg/2000px-Getty_Images_Logo.svg.png)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/2000px-Netflix_2015_logo.svg.png)
![](https://www.festisite.com/static/partylogo/img/logos/google.png)

---

Todo esta en las metricas:

 - Deploys
 - Descargas
 - Uptime
 - Cambios

---

Equivale a:

 - Mejores productos
 - Mejor Panorama.

# COMPETITIVIDAD. 

---

# Precauciones de Automatizacion

"Si tienes un desastre. Vas a tener un desastre automatizado."

Si no pueden ejecutar el proceso de manera manual y saber cada detalle de este proceso, no intenten automatizarlo.
Solo lograrian automatizar confusion.


Note:

Esto es algo muy comun... leo.

---

General Motors Case.
![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Logo_of_General_Motors.svg/1200px-Logo_of_General_Motors.svg.png)

- Automatizar Manufactura. 
- Mejor Calidad. Mejores Costos.

---

- $44 B USD = Fabrica del Futuro
![](http://www.carlogos.org/logo/Toyota-logo-1989-2560x1440.png)
![](http://www.carlogos.org/logo/Nissan-symbol-2012-1920x1080.png)

Note:
Querian automatizar la manufactura de autos en 1980.
GM intenta resolver sus problemas de calidad con automatizacion.
Gastaron 44 Billones de dolares para construir la "fabrica del futuro".
Eso era suficiente para haber comprado Toyota. y Nissan. Juntos. (Sin obtener la calidad que buscaban. Ni los costos que buscaban).

---

Consistencia de la practica tiene que ir antes de la Automatizacon

---

## Por donde comienzo a automatizar? 

---

1. Seguridad? ...

1. Disponibilidad!

1. Desempeño!!

1. Usabilidad

---

# Recap

En este punto;

 - Creamos un catalogo de servicios que documentan los servicios mas criticos que tenemos
 - Documentamos como trabajan esos servicios en la infraestructuras y qué componentes los mantienen

Debemos:

 - Tener una base de datos de configuraciones para mapear los servicios y sus relaciones.
 - Tener metricas y herramientas PARA mejorar la toma de decisiones
 PARA incrementar la tasa de cambios existosos y PARA disminuir trabajo NO planeado.
 - Creamos una lista de proyectos prorizados PARA reemplazar artefactos fragiles con infraestructura estable.
 - Identificar artefctos frágiles con tasas bajas de exito después de cambios y que tengan un alto índice de MTTR (Media Time To Recover) ya que contribuyen al trabajo no planeado. Y todos ellos estan llenos de post its de ¨No tocar¨.
 - Ahora tenemos que crear builds repetibles, Focus en infra fragil.
    - Definir mecanismos de builds
    - Documentacion estable y actualizable
    - Imagenes de sistema.

 De aqui resulta un proceso repetible para construir infraestructura desde cero.

Al hacer la infraestructura mas facil  de reconstruir y reparar atacamos varios puntos;
  1. Si algo sale mal en produccion, no lo reparamos, en lugar de eso, nos quitamos el problema de encima y reprovisionamos desde cero. Sin embargo, en este punto, el exito depende completamente de nuestra habilidad de manejar los cambios que sucedan en produccion con aquellos que tengamos registrados como nuevos para que no cambien radicalmente con aquellos que se reemplacen al hacer un reprovisionamiento. 

- Tasas altas de server/admin
- Baja cantidad de Trabajo No Planeado
- Habilidad para mantener y administrar cambios en configuraciones. 


Reemplazar Trabajo NO planeado por tareas previas 

El punto es pover nuestro Senior IT Operations de una posicion reactiva y de lucha contra incendios a un rol proactivo de funciones de administracion de releases en donde trabajan constantemente en integrar los releases que van a ser entregados a produccion.

De esta manera, se trabaja en operaciones tempranas del ciclo de vida de desarrollo, en donde el costo por errores es mucho mas bajo.

Asi, el principal rol del equipo de administracion de releases es construir los mecanismos para hacer el mejor deploy con las mejores configuraciones a produccion. Asi ellos no hacen los builds. Hacen Ingenieria de los builds. Es decir, los diseñan, pero no construyen el server.

OBJETIVO: Que sea mas barato reconstruir la infraestructura que repararla. Al presionar un solo boton.

Los siguientes beneficios son los mas importantes resultado de reconstruir en vez de reparar:

  - Reconstruir es una tarea que tiene tiempos muy especificos, medibles y por lo tanto mejorables. En cambio reparar fallos, SIEMPRE tiene un tiempo impredecible y normalmente toma mas tiempo de lo que estimamos.
  - Reconstruir infraestructura, implementa menos variabildad en la confuguracion, al contrario de lo que es un ciclo constante donde algo se rompe y se repara, lo que agrega mucha varianza en la configuracion y despues se vuelve complicado adentrarse.
  - Al tener un proceso automatizado de reconstruccion, documentado y menos complicado, incluso puede ser hecho por los Juniors, liberando aun Senior de ese trabajo, enfocandose a algo de mayor importancia e incluso de lucha contra incendios.
  - Al liberar a un senior (despues de arreglar fallos) pueden seguir trabajando en nuevos proyectos y sus builds, lo que arreglara otros problemas ligados.

De esta manera, al trabajar proactivamente en proyectos que reduzcan el trabajo no  planeado, se va eliminando sistematicamente las diferentes fuentes de desastres antes de que ataquen.

Todo esto reduce la complejidad y el costo, ademas de mejorar la administracion. 
