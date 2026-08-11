# Examen de Ingreso

Proyecto para GitHub Pages + Firebase.

## Archivos

- `index.html` — examen para alumnos.
- `admin.html` — panel del administrador.
- `matematicas.json` — banco de 225 preguntas.
- `espanol.json` — banco de 275 preguntas.

## Enlaces de un solo uso

El examen utiliza cuatro códigos únicos. Después de que un alumno termina y se guarda su resultado, ese código queda marcado como utilizado en Firestore y ya no puede volver a presentar el examen con ese enlace.

Códigos:

1. `bDMvieU2zAYCeuY4`
2. `LJFGjb38ZxzLXekg`
3. `mBtjZALsa0XcK0gy`
4. `Z7YpiNDS3jvYl3lZ`

Después de publicar GitHub Pages, agrega cada código a la URL usando:

`?codigo=CODIGO`

Ejemplo:

`https://TU-USUARIO.github.io/TU-REPOSITORIO/?codigo=bDMvieU2zAYCeuY4`

No compartas los cuatro enlaces públicamente; entrega uno a cada alumno.
