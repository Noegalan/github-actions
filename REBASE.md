## Limpieza de commits con git rebase -i

En esta tarea se ha trabajado con el objetivo de mejorar la claridad del historial de commits utilizando la herramienta `git rebase -i`.

En primer lugar, se han creado varios commits con mensajes poco descriptivos como “cambios”, “arreglos” y “cosas”, simulando un historial desordenado y poco claro.

Posteriormente, se ha utilizado el comando:

`git rebase -i HEAD~3`

para iniciar un rebase interactivo sobre los últimos tres commits.

Durante este proceso, se han realizado las siguientes acciones:

- Se ha utilizado la opción **reword** para modificar el mensaje del commit principal.
- Se han utilizado varias opciones **squash** para fusionar los commits restantes en uno solo.

De esta forma, varios commits con mensajes poco claros se han unificado en un único commit con un mensaje descriptivo y coherente.

Una vez finalizado el proceso, se ha utilizado el comando:

`git push --force`

para actualizar el repositorio remoto, ya que el historial de commits había sido reescrito.

Este procedimiento permite mantener un historial más limpio, claro y profesional, facilitando la comprensión de los cambios realizados en el proyecto.
