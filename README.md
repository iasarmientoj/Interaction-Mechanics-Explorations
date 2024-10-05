# Interaction-Mechanics-Explorations
Este repositorio contiene una serie de pruebas y exploraciones de diversas mecánicas de interacción de personajes en Unity. El proyecto abarca la implementación de interacciones como combate, disparos, empujar objetos, enfrentamientos con enemigos, y mucho más.

---

## Anotaciones escenas
### Scene 1
_Descripción:_ El personaje puede disparar proyectiles (pistolas, flechas, bolas de energía) hacia enemigos u objetos.

![Scene 1](/IME/Assets/Scenes/miniaturas/Scene%201.png "Scene 1")

_Detalles:_ 
- Implementación de disparos con raycasts o proyectiles físicos.
- Diferentes tipos de armas con propiedades como daño y velocidad.
- Detección de colisiones y registro de impacto en enemigos.
- Control de munición y recarga de armas.
- Animaciones de disparo y efectos visuales (muzzle flash, explosiones).
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [UNITY FPS SHOOTING in 10 MINUTES - Unity Tutorial](https://www.youtube.com/watch?v=Tl2DbeJ38to)


### Scene 2
_Descripción:_ Combate cuerpo a cuerpo con golpes, patadas, combos y bloqueos para enfrentamientos cercanos.

![Scene 2](/IME/Assets/Scenes/miniaturas/Scene%202.png "Scene 2")

_Detalles:_ 
- Animaciones de ataque sincronizadas con colisiones en hitboxes.
- Sistema de combos y secuencias de ataque con distintas teclas.
- Bloqueo de ataques y contrataques.
- Efectos visuales y sonoros para cada tipo de ataque o golpe.
- Sistema de detección de daño basado en distancias y zonas de impacto.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [How to Create COMBAT SYSTEM in Unity](https://www.youtube.com/watch?v=Gz0d8A_9Hds)


### Scene 3
_Descripción:_ Empujar y arrastrar objetos para resolver puzles o abrir caminos.

![Scene 3](/IME/Assets/Scenes/miniaturas/Scene%203.png "Scene 3")

_Detalles:_ 
- Física aplicada al objeto usando rigidbody y colisionadores.
- Restricciones de movimiento en el plano X,Z o según sea necesario.
- Fuerza aplicada al objeto para empujarlo en la dirección del movimiento del personaje.
- Feedback visual del objeto empujado (brillo, sonido).
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [PUSHING AND PULLING OBJECTS - Unity Tutorial](https://www.youtube.com/watch?v=tbXkwEHpU9I)


### Scene 4
_Descripción:_ El personaje puede interactuar con NPCs para hablar, comerciar o recibir misiones.

![Scene 4](/IME/Assets/Scenes/miniaturas/Scene%204.png "Scene 4")

_Detalles:_ 
- Sistema de diálogo con múltiples opciones y respuestas.
- Detección de proximidad para iniciar la interacción.
- Funcionalidades de comercio (compra y venta de ítems).
- Mecanismo de asignación y seguimiento de misiones.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [INTERACTION SYSTEM in Unity - Tutorial](https://www.youtube.com/watch?v=jOfA8KoVJDY)


### Scene 5
_Descripción:_ El personaje puede activar interruptores, botones o palancas para desencadenar eventos en el entorno.

![Scene 5](/IME/Assets/Scenes/miniaturas/Scene%205.png "Scene 5")

_Detalles:_ 
- Detección de interacción con objetos activables (interruptores).
- Cambio de estado del objeto y activación de mecanismos (puertas, trampas).
- Sincronización de animaciones y efectos de sonido para la activación.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [ACTIVATING MECHANISMS in Unity](https://www.youtube.com/watch?v=Kz_fjZjiNJU)


### Scene 6
_Descripción:_ El personaje puede escalar paredes, saltar sobre objetos o sortear obstáculos en el entorno.

![Scene 6](/IME/Assets/Scenes/miniaturas/Scene%206.png "Scene 6")

_Detalles:_ 
- Mecánica de escalada con detección de superficies escalables.
- Animaciones de escalada y salto ajustadas según la altura.
- Física de salto y control del movimiento en el aire.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [How to Make a CLIMBING SYSTEM in Unity](https://www.youtube.com/watch?v=9b8Fyb4TD1E)


### Scene 7
_Descripción:_ El personaje puede recoger armas, herramientas o ítems dispersos por el entorno.

![Scene 7](/IME/Assets/Scenes/miniaturas/Scene%207.png "Scene 7")

_Detalles:_ 
- Sistema de inventario para registrar ítems recogidos.
- Detección de proximidad para recoger objetos.
- Distintas interacciones según el tipo de ítem (equipar armas, usar consumibles).
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [PICK UP ITEMS in Unity](https://www.youtube.com/watch?v=eDzu9W_JIck)


### Scene 8
_Descripción:_ El personaje puede usar habilidades especiales como teletransportarse, volverse invisible o activar escudos.

![Scene 8](/IME/Assets/Scenes/miniaturas/Scene%208.png "Scene 8")

_Detalles:_ 
- Sistema de energía o cooldown para gestionar habilidades.
- Efectos visuales y de sonido personalizados para cada habilidad.
- Impacto de las habilidades en el entorno y enemigos.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [SPECIAL ABILITIES in Unity](https://www.youtube.com/watch?v=jBwjqOjZNgA)


### Scene 9
_Descripción:_ El personaje puede enfrentarse a enemigos que tienen detección, ataques e inteligencia artificial.

![Scene 9](/IME/Assets/Scenes/miniaturas/Scene%209.png "Scene 9")

_Detalles:_ 
- Inteligencia artificial para enemigos (detección de jugador, patrones de ataque).
- Registro de daño y respuesta al recibir golpes.
- Animaciones y efectos visuales para ataques de enemigos.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [Enemy AI in Unity](https://www.youtube.com/watch?v=UjkSFoLxesw)


### Scene 10
_Descripción:_ El personaje puede desactivar trampas o mecanismos peligrosos en el entorno.

![Scene 10](/IME/Assets/Scenes/miniaturas/Scene%2010.png "Scene 10")

_Detalles:_ 
- Detección de trampas activadas y su estado.
- Interacción para desarmar o activar/desactivar trampas.
- Animaciones y efectos visuales de desactivación.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [DISARMING TRAPS in Unity](https://www.youtube.com/watch?v=qszdVmAYwCI)


### Scene 11
_Descripción:_ El personaje puede trepar o balancearse en cuerdas o lianas para desplazarse en plataformas.

![Scene 11](/IME/Assets/Scenes/miniaturas/Scene%2011.png "Scene 11")

_Detalles:_ 
- Mecánica de trepar y balanceo en objetos móviles.
- Animaciones de agarre, trepado y balanceo sincronizadas con la física.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [CLIMB AND SWING SYSTEM in Unity](https://www.youtube.com/watch?v=6HPTk0RgkRo)


### Scene 12
_Descripción:_ El personaje puede entrar y manejar vehículos o monturas en el entorno.

![Scene 12](/IME/Assets/Scenes/miniaturas/Scene%2012.png "Scene 12")

_Detalles:_ 
- Mecánica de entrada y salida de vehículos.
- Control del vehículo con física personalizada.
- Transición entre montura y movimiento a pie.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [VEHICLE CONTROLS in Unity](https://www.youtube.com/watch?v=Ql0WttJcGkM)


### Scene 13
_Descripción:_ El personaje puede recoger objetos del entorno y lanzarlos hacia enemigos u objetivos.

![Scene 13](/IME/Assets/Scenes/miniaturas/Scene%2013.png "Scene 13")

_Detalles:_ 
- Sistema de interacción para recoger y lanzar objetos.
- Mecánica de tiro parabólico y registro de impacto en objetos lanzados.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [THROWING OBJECTS in Unity](https://www.youtube.com/watch?v=GslCMLimRRw)


### Scene 14
_Descripción:_ El personaje puede recoger monedas dispersas en el entorno para sumar puntos o activar recompensas.

![Scene 14](/IME/Assets/Scenes/miniaturas/Scene%2014.png "Scene 14")

_Detalles:_ 
- Detección de proximidad para recoger monedas al contacto.
- Incremento de un contador de monedas o puntos.
- Efectos visuales y de sonido al recoger las monedas.
- Opcional: Animación de recolección o partículas que sigan al personaje al recogerlas.
  
_Tutoriales guía:_ 
- []()

_Resultado final:_ 
- [COLLECTING COINS in Unity](https://www.youtube.com/watch?v=OZVV9JsjIdw)