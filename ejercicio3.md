# Ejercicio 3: Gestión de Ramas y Resolución de Conflictos en Git

En este ejercicio se detallan los pasos realizados para la gestión de ramas, fusión de cambios y resolución de conflictos utilizando Git y GitHub.

## 1. Creación de la primera rama
Para comenzar con el flujo de trabajo, se creó una nueva rama llamada `primera` a partir de la rama principal.

![Crear Rama](</repositorios/prueba_hugocolio/img/ejercicio 3/crear rama.png>)

## 2. Creación de fichero y fusión (Merge)
Se creó un nuevo archivo de texto dentro de la rama `primera`. Una vez guardados los cambios, se regresó a la rama principal para fusionar (`merge`) los contenidos de ambas ramas.

![Crear Fichero y Fusionar Rama](</repositorios/prueba_hugocolio/img/ejercicio 3/crear fichero y fusionar rama.png>)

## 3. Borrado de la rama
Una vez que la fusión se completó correctamente y los cambios quedaron integrados en la rama principal, se procedió a eliminar la rama `primera` para mantener el repositorio limpio.

![Borrar Rama](</repositorios/prueba_hugocolio/img/ejercicio 3/borrar rama.png>)

## 4. Creación de conflicto y resolución
Posteriormente, se creó una nueva rama llamada `segunda`. Para experimentar con los conflictos de Git, se modificó el mismo archivo tanto en la rama principal como en la rama `segunda`. Al intentar fusionarlas, Git detectó un conflicto que tuvo que ser resuelto manualmente.

![Solución de Conflicto](</repositorios/prueba_hugocolio/img/ejercicio 3/solucion de conflicto.png>)

## 5. Verificación en GitHub
Finalmente, tras subir los cambios al repositorio remoto, se comprobó en la interfaz de GitHub que la rama `segunda` está creada y publicada correctamente.

![Rama en GitHub](</repositorios/prueba_hugocolio/img/ejercicio 3/rama en github.png>)
