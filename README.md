# Sorteo de Instagram · Alfil Juvenil × Black Sunrise

Herramienta web para hacer un sorteo en directo entre los comentarios de una publicación de Instagram. La usamos para un sorteo conjunto de Alfil Juvenil y Black Sunrise, proyectándola en pantalla.

## Cómo se usa

1. **Sacar los comentarios**: abre la publicación en Instagram desde el ordenador (con la sesión iniciada), abre la consola del navegador y pega el script que aparece en el paso 1 de la web. El script recorre todos los comentarios y los copia.
2. **Cargar**: pega el resultado en el paso 2.
3. **Sortear**: abre la vista de proyección (`#proyectar`) y dale a "Sacar comentario". Si la persona cumple las bases, la marcas como ganadora. Si no, sacas otro.

## Reglas que aplica

- Cada comentario que mencione al menos a una persona cuenta como una papeleta.
- No cuentan las respuestas a otros comentarios ni los comentarios repetidos del mismo usuario.
- Se excluyen las cuentas organizadoras (se puede cambiar en Ajustes).
- Cada persona solo puede ganar un premio, y quien se descarta no vuelve a salir.
- El azar sale de `crypto.getRandomValues`, no de `Math.random`.

Hecho en HTML, CSS y JavaScript puros, en un solo archivo y sin dependencias. Los ganadores se guardan en el `localStorage` del navegador.
