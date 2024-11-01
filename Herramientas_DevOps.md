# Herramientas DevOps

En cultura DevOps se trabaja con una serie de herramientas que nos ayuda en nuestras funciones.

![Herramientas DevOps](Imagenes/herramientas.jpg)

* [Filosofía DevOps](Filosofia_DevOps.md)
* [Oferta de empleo](Oferta_Empleo.md)

## Integración continua

Cuando hablamos de la **integración continua** tenemos a ***Jenkins***, es la herramienta de integración continua más conocida del mercado, está desarrollada en Java, es compatibles con múltiples sistemas de control de versiones.
Al ser de código abierto nos permite tenerlo de manera local simplemente cumpliendo ciertas especificaciones en nuestras máquinas, y al mismo tiempo, podemos configurarlo en entornos productivos.

Jenkins es una herramienta que nos ayuda a **automatizar compilaciones y pruebas**. Puedes configurar Jenkins para que compile el código, ejecute pruebas y genere reportes automáticamente cada vez que hay un cambio en el repositorio de código.
Por otra parte, podemos hacer integración continua (CI), entrega de despliegue continua (CD), automatización de DevOps y gestión de plugins.

## Entrega continua

Como herramienta también podemos usar Jenkins, sin embargo, tenemos a ***Azure DevOps***, nos ayuda en la automatización de despliegues. Con **Azure Pipelines** nos permite crear pipelines de CD que despliegan automáticamente el código en diversos entornos (desarrollo, pruebas, pre-producción y producción) tan pronto como pasa las pruebas o se cumple una serie de criterios.

## Infraestructura como código

Siendo la más popular tenemos a ***Terraform***, Una herramienta de código abierto que permite definir y aprovisionar infraestructura en múltiples proveedores de servicios en la nube.
Terraform utiliza el lenguaje de configuración de HashiCorp (HCL), que es fácil de leer y escribir, lo que simplifica la definición de la infraestructura.

## Monitorización y registros

Siendo de las más populares, ***Prometheus*** es una herramienta de monitoreo de código abierto que es especialmente popular en entornos de contenedores y microservicios. Se integra bien con Kubernetes.
También tenemos a otro muy popular que es ***Grafana*** es utilizada para la visualización de datos de monitoreo. Se puede integrar con *Prometheus* y otras fuentes de datos.

## Cultura colaborativa DevOps

En esta fase tenemos varias herramientas, unas muy utilizadas es ***GibHub*** y ***GitLab***.
**GitHub** es una plataforma de control de versiones que permite a los desarrolladores colaborar en el código, revisar cambios y gestionar proyectos.

**GitLab** nos Ofrece características similares a GitHub, con un enfoque en la integración continua y la entrega continua (CI/CD).

### Cuadro de herramientas

| Conceptos | Herramientas DevOps |
|-----------|---------------------|
|Planificación| GitHub|
|Gestión de código | Git, GitHub |
| Automatización de pruebas | Junit, TestNG |
| Integración y entrega continua | Azure Devops, Jenkins|
|Gestión de configuración | Aseble, Chef |
| Monitorización | Prometheu, Grafana |
|Contenedores y orquestación | Docker, Kubernete|
