# Diplomatura Linux y Redes (UTN) – material de estudio

Contenido de la app **Diplomatura Linux**: lecciones interactivas, exámenes de clase, repaso y simulacro LPIC.

- `content/manifest.json` y `content/clase-NN.json`: **lo que lee la app**. Si cambiás o agregás un archivo acá, la app lo baja sola la próxima vez que se abre con internet (y lo guarda para usarlo sin conexión).
- `app/`, `tools/`, `android/`: el motor, las herramientas para escribir/validar clases y el proyecto Android. No hace falta tocarlos para sumar clases.

Cada clase tiene un número de revisión (`rev`). La app solo descarga las clases cuya `rev` es mayor que la que ya tiene.
