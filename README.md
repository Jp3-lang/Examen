# Examen de Ingreso

Proyecto preparado para GitHub Pages + Firebase.

## Archivos

- `index.html` — examen para los alumnos.
- `admin.html` — panel de resultados.
- `matematicas.json` — banco de 225 preguntas.
- `espanol.json` — banco de 275 preguntas.

## Funcionamiento

Al iniciar el examen se cargan automáticamente los dos bancos JSON desde el mismo repositorio de GitHub Pages.

Se seleccionan al azar:
- 20 preguntas de Matemáticas.
- 20 preguntas de Español.

Cada examen tiene 20 minutos para Matemáticas y 20 minutos para Español.

Los resultados se guardan en la colección `resultados` de Firestore.

## Publicación en GitHub Pages

Los cuatro archivos deben quedar en la raíz del repositorio:

```text
index.html
admin.html
matematicas.json
espanol.json
```

No cambies los nombres de los archivos JSON.

Después de subirlos, GitHub Pages servirá los bancos JSON desde la misma dirección del examen.
