# 1. DevOps

> Oct 24, 2020

*Devops integrantes developers and operation teams in order to improve collaboration and productivity by automating infraestructure, automating workflows and continuously measuring application performance*

**DevOps** no es una persona o un rol dentro de la compañia. DevOps es una **mentalidad**, una forma de tener una cultura en el equipo mediante la automatización de las prácticas (tests, deplyments, etc) en procesos de CI/CD. Un DevOps mide productividad de los fixes, el tiempo del request al producto, el tiempo de arreglo de problemas de operaciones. 

Uno de los videos que mas me djo en claro el concepto de devops es el siguiente: [Enlace](https://www.youtube.com/watch?v=_I94-tJlovg).

Uno de los principales puntos de ventaja (tanto competitivamente como internamente) es la reducción de tiempos para lanzar soluciones al mercado. Junto con eso, la mejora permite que haya un mejor enfoque en el producto y el negocio en general.


**Las nuevas herramientas** necesarias en un equipo orientado a devops son muy importantes y una de ellas es *Jenkins* y una herramienta que controle el codigo fuente (como *Github*) lo que permitirá manejar, documentar todos los cambios al códgio fuente. A si mismo se necesitarán herramientas para hacer deployment.

En conclusión, DevOps es una **filosofía** de desarrollo que nos permite inovar de forma más rápida, y muchisimo mejor de cara a las necesidades 

De primera vista una de las impresiones que me dio Maven es que era parecido a **npm**, sin embargo, luego de usarlo durante algunos días y de probar varios proyectos con el me he dado cuenta de que es muchisimo más que un administrador de dependencias. Maven es una herramienta que sirve en general para el **manejo de nuestros proyectos en Java** permitiendonos administrar dependencias, compilar y empaquetar. 

**Maven** resuelve muchisimos problemas en cuanto a empaquetado se refiere y con unas simples lineas en la terminal nos genera una estructura para nuestro proyecto. La documentación más importante que he encontrado:

El comando principal que usa Maven es **mvn** el cual es la base de todos los demás. Uno de los comandos más importantes de Maven es sin duda el de **creación de proyectos**. 


En donde **archetype:generate** nos indica que estamos generando un proyecto nuevo. **-DgroupId=com.mycompany.app** menciona la estructura que tendrá tu proyecto (Y por ende como se diferencia de los demás) mientras que **-DartifactId=my-app** genera el nombre de nuestro compilado. 

Este comando lo que hará es permitirnos elegir de manera interactiva algunas especificacions de nuestro proyecto, tales como la versión, el autor, etc. Agregrando el siguiente parametro al comando, podemos desactivar estas solicitudes y las asumirá por defecto:


Finalmente otro de los parametros importantes que debemos considerar es el **-DarchetypeArtifactId=maven-archetype-quickstart** el cual indicará que tipo de aplicación generamos. Por ejemplo, si quisieramos generar una estructura para una *WebApp* nosotros usariamos: 
