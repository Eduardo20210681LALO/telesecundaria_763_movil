# telesecundaria_763_movil
telesecundaria_763_movil

##Objetivo del Proyecto##
El proyecto ***PORTAL VIRTUAL PARA LA TELESECUNDARIA 763*** es una plataforma educativa diseñada para facilitar los procesos de captura de información de los alumnos de esta institución. Los principales usuarios son los docentes, junto con el personal administrativo y directivo. Los módulos principales del portal incluyen la captura de calificaciones, la descarga de calificaciones en formato Excel, y la visualización de estadísticas gráficas, brindando una herramienta integral para la gestión y análisis de la información académica.


## Alcance del Proyecto
El proyecto consiste en desarrollar una aplicación móvil que integre un sistema de suscripción por periodo y una pasarela de pagos segura y efectiva. Esta aplicación está dirigida exclusivamente a docentes, administrativos y directivos, permitiéndoles, tras completar un periodo de prueba, realizar diversas acciones como cargar calificaciones, visualizar estadísticas y más. El objetivo es proporcionar una solución accesible y eficiente para la gestión educativa, garantizando una experiencia de usuario fluida y segura.


### Funcionalidades Clave ###
- ***Captura de Calificaciones mediante Excel***: Los docentes pueden registrar calificaciones a través de archivos Excel, agilizando el proceso y evitando la captura manual.
- ***Gestión de Alumnos***: Los profesores pueden gestionar a los alumnos por periodos, grupos y grados, permitiendo un seguimiento organizado de los estudiantes.
- ***Visualización de Estadísticas Gráficas***: El portal genera reportes basados en los resultados de las calificaciones, proporcionando gráficos que muestran el rendimiento académico de los alumnos.
- ***Sistema de Calificaciones***: Permite introducir y gestionar las calificaciones de cada alumno de manera eficiente y organizada.
- ***Notificaciones en Tiempo Real***: El personal administrativo recibe notificaciones sobre la gestión de usuarios y puede realizar acciones como actualizar periodos, gestionar nuevos alumnos, registrar bajas, y realizar otros cambios relevantes en tiempo real.


### Funcionalidades a Realizar ###
- ***Pasarela de pagos:*** Implementar una pasarela de pagos segura que permita a los usuarios suscribirse a los diferentes periodos.
- ***Proceso de prueba:*** Definir y gestionar un periodo de prueba en el que los usuarios puedan explorar la funcionalidad limitada de la aplicación antes de realizar la compra.
- ***Proceso de compra de un periodo:*** Permitir a los usuarios completar el proceso de compra de un periodo, lo que les otorgará acceso completo a todas las funcionalidades de la aplicación, como cargar calificaciones y visualizar estadísticas.



## Metodología de Trabajo
***Selección de Metodología de Desarrollo Ágil (Scrum)***
- Se ha seleccionado Extreme Programming (XP) como la metodología ágil para el desarrollo de la aplicación móvil debido a su enfoque en la entrega rápida de software funcional y la mejora continua.
- XP se basa en iteraciones cortas, lo que permite un desarrollo incremental del proyecto y garantiza que las funcionalidades se prueben y ajusten de manera constante. Esto es crucial para adaptarse a las necesidades educativas cambiantes y asegurar que los requisitos del cliente se cumplan en cada ciclo.
- XP promueve prácticas técnicas esenciales como el desarrollo orientado a pruebas (TDD), la programación en pareja (pair programming), la integración continua, y la retroalimentación frecuente con el cliente. Estas prácticas permiten mantener una alta calidad en el código y una rápida detección de errores, asegurando que el proyecto esté en constante evolución sin comprometer la estabilidad del software.
- XP facilita la colaboración constante entre desarrolladores y el cliente, asegurando que las funcionalidades más importantes se desarrollen primero y que el equipo esté alineado con los objetivos del proyecto. Esto permite una rápida respuesta a los problemas y cambios que puedan surgir durante el desarrollo, garantizando que las expectativas del cliente se cumplan de manera efectiva.

***Justificación:***
- XP es ideal para el desarrollo de la aplicación móvil debido a su enfoque en la entrega temprana y continua de valor al cliente. Las iteraciones cortas permiten ajustar el desarrollo de acuerdo con las prioridades del cliente y los requerimientos educativos, mejorando la adaptabilidad del proyecto.
- Las prácticas técnicas de XP, como TDD y pair programming, aseguran la calidad del código y permiten una rápida identificación y resolución de problemas, lo que resulta en un software más robusto y mantenible.
- La colaboración cercana con el cliente durante todo el ciclo de desarrollo garantiza que el producto final cumpla con sus necesidades, ofreciendo flexibilidad, eficiencia y un proceso de desarrollo ágil.


## Herramienta de Control de Versiones ##
- Para el control de versiones, se utilizará Git en conjunto con GitHub como plataforma de repositorio remoto.
- Esta combinación permitirá gestionar las diferentes ramas y versiones del proyecto de manera eficiente, además de facilitar la colaboración entre los miembros del equipo y automatizar procesos mediante la integración continua.

***Flujo de Trabajo***
1. **Crear una nueva rama** para cada funcionalidad o tarea específica.
```bash
git checkout -b feature/branches o alguna otro nombre en especifico.
```
2. **Hacer commits** frecuentes de los cambios.
```bash
git add .
git commit -m "Descripción del cambio realizado"
```
3. **Abrir un pull request** para revisión de código por otro miembro del equipo.
```bash
git checkout main
```
4. **Integrar la rama** en `main` después de que las pruebas automáticas pasen y el código sea aprobado.
```bash
git merge feature/branches u otro nombre de la funcionalidad creada.
```


## Estrategia de Despliegue
Para el despliegue del proyecto, se ha seleccionado la estrategia de **Rolling**, que permite realizar actualizaciones de la aplicación sin tiempos de inactividad.

### Entornos de Despliegue Definidos:
- ***Desarrollo:*** Donde se realizan pruebas locales y los desarrolladores pueden integrar nuevas funcionalidades.
- ***Staging (Preproducción):*** Un entorno que replica la configuración de producción para realizar pruebas finales antes del despliegue definitivo.
- ***Producción:*** El entorno en el cual el sistema está disponible para los usuarios finales y donde se despliegan las versiones estables del proyecto.


## Proceso de CI/CD
Se utiliza **Integración Continua (CI)** para asegurar que cada cambio que se integra al tronco principal pase por un proceso automatizado de pruebas. Cuando todas las pruebas pasan, el código se despliega automáticamente en los entornos de **Staging** y posteriormente en **Producción**.

## Instrucciones para Contribuir

1. **Clonar el repositorio**: Esto descargará una copia del código fuente en tu máquina local.
```bash
git clone https://github.com//Eduardo20210681LALO/telesecundaria_763_movil
```
2. **Entrar en el directorio del proyecto**: Accede al directorio clonado donde está el código del proyecto.
```bash
cd telesecundaria_763_movil
```
3. **Instalar dependencias**: Esto instalará todas las dependencias necesarias del proyecto especificadas en package.json.
```bash
npm install
```
4. **Ejecutar el proyecto en modo desarrollo**: Inicia el servidor en modo desarrollo. Esto te permitirá ver la aplicación en tiempo real y se recargará automáticamente cuando realices cambios en el código.
```bash
npm run dev
```
5. **Ejecutar las pruebas**: Corre las pruebas automatizadas del proyecto para asegurarse de que todo funcione correctamente.
```bash
npm run test
```
