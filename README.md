Proyecto base para la asignatura Programación Orientada a Objetos (Unidad 2)

# Objetivos
- Implementar nuevas clases ("Actor", "Temporada", "Investigador") y dos subclases de "ContenidoAudiovisual" ("Videodeyoutube" y "Cortometraje")
- Demostrar relaciones POO: asociación, agregación y composición.
- Proveer un demo funcional ("Main") que crea y manipula objetos.

# Estructura
- "src/main/java/com/ups/poo/" : contiene las clases Java.
- "Main" : clase con método `main` para ejecución de ejemplo.

## Cómo compilar y ejecutar (línea de comandos)
1. Sitúese en la carpeta "src/main/java/".
2. Compilar:
   "javac com/ups/poo/*.java "
3. Ejecutar:
   "java com.ups.poo.MainDemo"

# Clases añadidas y relaciones
- "Actor" : agregado a "Pelicula" (agregación).
- "Temporada" : creada por "SerieDeTV" (composición).
- "Investigador" : asociado a "Documental" (asociación).
- "VideoYouTube", "Cortometraje" : nuevas subclases de "ContenidoAudiovisual".

# Mejoras posibles
- Añadir serialización / persistencia.
- Pruebas unitarias (JUnit).
- Interfaz gráfica simple para crear contenidos.
