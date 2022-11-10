## Despliegue de apps Spring Boot en Heroku

Preparación previa:
Crear archivo `system.properties` en el proyecto con el contenido:

```
java.runtime.version=17
```

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
3. Subir el proyecto a GitHub desde IntelliJ IDEA, desde la opción:
   a. GIT o (VCS)
   b. Share project on GitHub
4. Desde Heroku, crear app y elegir método de deploy a través de GitHub y buscar el repositorio subido
5. Habilitar el deploy automático y ejecutar el deploy