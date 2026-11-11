# Sorteo Alfil Juvenil × Black Sunrise

Herramienta para sortear premios entre los comentarios de una publicación de Instagram.

## Cómo se usa

1. **Sacar los comentarios:** abre la publicación en Instagram desde el ordenador, con la sesión iniciada, y abre la consola (`Cmd + Opción + J` en Chrome). Pega el script del paso 1 de la web y espera al mensaje "✅ Listo".
2. **Cargar:** pega lo que ha copiado el script en el paso 2 y dale a "Cargar comentarios".
3. **Sortear:** abre la pantalla de proyección (`#proyectar`) y dale a "Sacar comentario". Si la persona cumple las bases, márcala como ganadora; si no, saca otro.

## Reglas que aplica

- Cada comentario que mencione al menos a una persona es una papeleta.
- Se excluyen los comentarios de @alfiljuvenil y de @blacksunrisestudio (se puede cambiar en Ajustes).
- Cada persona solo puede ganar un premio, y quien se descarta no vuelve a salir.
- La elección es aleatoria, con `crypto.getRandomValues`.

Los ganadores y descartados se guardan en el navegador (localStorage), así que no se sincronizan entre ordenadores.

Hecho en HTML, CSS y JS puros, en un solo archivo y sin dependencias.
