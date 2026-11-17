# Capitales de Europa

Juego familiar: se propone un país o una capital de Europa, el jugador elige la respuesta entre 10 opciones y después marca el país en el mapa.

- Dos formas de jugar:
  - **Por turnos**, de 1 a 6 jugadores en un mismo dispositivo (ordenador, tele, tableta o móvil).
  - **A la vez**, hasta 8 jugadores, cada uno con su dispositivo: uno crea una sala y los demás entran con el código de 4 letras o con el enlace. Todos reciben la misma pregunta con las mismas 10 opciones (del nivel de quien crea la sala) y responden al mismo tiempo. Al terminar cada pregunta aparece el ranking con quién ha acertado la respuesta y el mapa.
- Cada jugador elige su nivel (fácil, medio o difícil), para que pequeños y mayores compitan juntos.
- Tres modos: adivinar la capital del país, adivinar el país de la capital, o mezclado.
- Cada pregunta tiene dos pantallas: en la primera se elige la respuesta entre 10 opciones (2 puntos) y en la segunda se marca el país en el mapa (1 punto más).
- El mapa se puede acercar con la rueda del ratón o pellizcando.

## Cómo jugar

Abre `index.html` en el navegador. Necesita conexión a internet: el mapa y la librería de dibujo (D3) se cargan desde una CDN, y las banderas desde flagcdn.com.

El modo «a la vez» conecta los dispositivos directamente entre sí con [PeerJS](https://peerjs.com/) (WebRTC) y usa su servidor público gratuito solo para que se encuentren. No hay servidor propio ni se guarda nada. Quien crea la sala debe mantener la página abierta durante la partida.

## Publicarlo con GitHub Pages

1. Sube `index.html` a un repositorio.
2. En el repositorio: **Settings → Pages → Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. El juego quedará en `https://<usuario>.github.io/<repositorio>/`.
