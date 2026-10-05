# Chispa

**Chispa** es una mascota animada 100% original en un solo archivo HTML, sin dependencias ni assets externos. Todo el dibujo es SVG inline y los sonidos se sintetizan con WebAudio.

## Verla

- Abre `index.html` en cualquier navegador, o
- Súbelo a GitHub y activa **GitHub Pages** para verla en vivo desde tu iPhone.

## Interacciones

- **Mirada**: mueve el cursor o el dedo sobre ella y te sigue con los ojos. Si no hay movimiento, mira sola a puntos aleatorios.
- **Tócala**: se aplasta y se enoja un poquito. Tócala 3 veces seguidas y se marea.
- **Botones**: Feliz (salta de alegría con confeti), Dormir (se duerme con "Zzz"), Marear, Enamorar (corazones), Sorprender y Calmar.
- **Sonido**: botón para activar/silenciar.

## Personalizar

Todo está comentado en español dentro del archivo:

- **Color del cuerpo**: busca el gradiente `chispaBody` en el `<defs>` del SVG.
- **Tamaño**: cambia el `viewBox` o el ancho del `.chispa-stage`.
- **Comportamientos**: el motor está en el `<script>` final — secciones `EMOTES` (emociones), `sfx` (sonidos) y las funciones `doHappy`, `doSleepy`, etc.
- **Nombre**: reemplaza "Chispa" en el título y los textos.

## Licencia

MIT — úsala libremente en tus proyectos. Ver `LICENSE`.
