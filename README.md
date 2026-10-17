# Fútbol Zamora

Dos juegos sobre la **Primera Provincial de Aficionados de Zamora**, con sus
dieciséis equipos, sus plantillas reales y los nombres de sus campos.

- **Fútbol Manager Zamora** — manager de los de toda la vida: alineaciones,
  táctica, mercado, copa, prensa y una directiva que pide cuentas.
- **Fútbol Arcade Zamora** — partido rápido, uno o dos jugadores, con copa y
  liga propias.

Los dos leen los mismos equipos, así que nunca cuentan cosas distintas.

## Jugar

Se juega en el navegador, en el móvil o en el ordenador. Se entra por el
manager y desde su cabecera se salta al arcade.

Hay 336 jugadores, cada uno con su cara. Las partidas se guardan solas en el
navegador, en tres ranuras, y se pueden descargar para llevárselas a otro
sitio.

### Mando

Los dos juegos se manejan con mando además de con teclado y pantalla táctil.
Basta con enchufarlo y pulsar un botón.

## Los archivos

| archivo | qué es |
|---|---|
| `index.html` | el manager, y la puerta de entrada |
| `futbol_arcade_zamora.html` | el arcade |
| `datos_zamora.json` | los 16 equipos y los 336 jugadores |
| `campos_zamora.json` | el nombre del campo de cada equipo |

Los cuatro van **en la misma carpeta y sin cambiarles el nombre**.

El manager lleva los equipos dentro además de leer el archivo, así que
funciona aunque se abra suelto. El arcade sí necesita estar servido por web:
abierto a doble clic desde el disco, el navegador no le deja leer el JSON y
el propio juego lo avisa.

## Si se tocan las plantillas

`datos_zamora.json` manda sobre lo que lleve dentro el manager. Al cambiar una
plantilla hay que regenerar ese archivo, o los dos juegos contarán cosas
distintas y el jugador verá la versión antigua.
