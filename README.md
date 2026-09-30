🍞🧀 Pan y Queso (Web Game)

One-Shot Vibecoding Project ⚡
Creado en un solo prompt usando la versión gratuita de Claude (Claude 5.5 Sonnet).

Una adaptación digital y multijugador del clásico juego de patio latinoamericano "Pan y Queso". Dos jugadores avanzan pie a pie frente a frente hasta que uno pisa al otro.

🚀 La Magia Detrás (Zero Backend / Serverless P2P)

La app fue generada en un único archivo index.html sin backend, sin bases de datos ni frameworks. Funciona mediante un modelo Peer-to-Peer (P2P) directo entre navegadores:

Host / Client Architecture: El primer jugador actúa como anfitrión guardando el estado de la partida y calculando las colisiones físicas, mientras el segundo se conecta vía WebRTC.

PeerJS (WebRTC): Conexión directa entre navegadores sin servidor intermedio.

SVG interactivo: Renderizado de la cancha, huellas y pies.

Web Audio & Web Speech API: Efectos de sonido sintetizados y síntesis de voz que pronuncia "Pan" y "Queso" dinámicamente en cada turno.

Geometría en JS: Detección de colisiones mediante intersección de rectángulos rotados para validar el "pisotón" ganador.

🎮 Cómo Probarlo
Ingresa a "https://luisabeccar.github.io/PanQueso/" y crea una nueva partida, el resto sera intuitivo.