# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Tras el desarrollo de la tarea, logré aprender sobre la creación de arquitecturas multi-contenedor mediante redes tipo bridge, la gestión de la persistencia de datos utilizando volúmenes nombrados y anónimos, la limitación de recursos del sistema, la implementación de verificaciones de salud (healthchecks), la construcción de imágenes personalizadas mediante Dockerfile con optimización de caché, y la configuración de políticas de reinicio.

Durante la fase de construcción de la imagen basada en CentOS 7, se presentó un error de incompatibilidad debido a que los repositorios oficiales llegaron al final de su ciclo de vida. Esto se solucionó modificando el Dockerfile para redirigir las fuentes de actualización hacia los repositorios históricos oficiales vault.centos.org mediante un comando de reemplazo de cadenas (sed), lo que permitió completar la instalación de dependencias y continuar con el flujo de la práctica de manera exitosa.
