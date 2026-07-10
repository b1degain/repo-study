Github Actions es una plataforma de integración y despliegue continuo CI/CD (Continuous Integration / Continuous Deployment) que permite automatizar procesos de compilación, pruebas y despliegue.

El flujo CI/CD consta en 8 secciones que se repetirán cíclicamente, 4 para CI y 4 para CD.

CI:

Plan: Toda la etapa previa donde planificamos los features que integraremos al proyecto.
Code: El código que hemos desarrollado.
Build: Compilar o Interpretar el código para dejarlo listo para ser usado por algún host o fuente.
Test: Correr todas las pruebas desarrolladas para asegurar que el código funcione correctamente.
CD:

Release: Enviar nuestra build a la locación remota donde se aloja el proyecto.
Deploy: Reconfigurar y relanzar los servicios del proyecto con los nuevos features.
Operate: Mantener el proyecto a flote.
Measure: Medir con métricas la calidad del servicio.
