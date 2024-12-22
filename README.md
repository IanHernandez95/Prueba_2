# Ejercicio 2 - Prueba 2 Devops

Este repo contiene la parte 2 de la prueba intermedia del curso devops

Este ejercicio consiste en implementar un despliegue automatizado en microservicios ECS

Las tareas de Este Ejercicio Son

1. Crear un Cluster de ECS con al menos 1 tarea que ejecute la API
2. Implementar un pipeline de CI/CD con github actions que:
  - Construya una imagen Docker desde el repositorio.
  - Empuje la imagen a un repositorio de contenedores ECR
  - Despliegue automáticamente la nueva imagen en ECS tras cada cambio en el código.