# Metal Cornellà

Arcade de acción (*run & gun*) ambientado en Cornellà de Llobregat: de l'Almeda a l'Estadi, rescatando vecinos y frenando a la Brigada del Formigó.

**Jugar:** https://cheims.github.io/metal-cornella/

## Controles
| Acción | Teclado | Móvil |
|---|---|---|
| Mover / apuntar | Flechas o WASD | Stick |
| Saltar | Espacio o K | SALTO |
| Disparar | Z o J | FUEGO |
| Escudo (mantener) | X o I | ESCUDO |
| Granada | C o L | BOMBA |
| Pausa · Sonido · Pantalla completa | P · M · F | Botones superiores |

**Vida:** 5 corazones por vida; cada golpe quita uno. El bocata recupera un corazón.
**Escudo:** bloquea balas y proyectiles que llegan de frente. Gasta energía mientras lo mantienes y con cada bloqueo; si se vacía, se rompe y tarda unos segundos en volver. Con el escudo alzado no puedes disparar.

También funciona con mando. En el móvil se puede instalar: *Añadir a pantalla de inicio*.

## Personajes
Al pulsar Enter eliges vecino en una pantalla de selección (20 s para decidir). Cada uno tiene velocidad, salto y escudo del 1 al 5.

| Personaje | Cómo es | Vel. | Salto | Escudo |
|---|---|---|---|---|
| Don Andrés | Traje, bici larga y 3 hijos detrás | 3 | 2 | 5 |
| Borja Kenyata | Informático runner con gorra roja y una B | 5 | 4 | 1 |
| Cheims 4matic | Informático con su PC en la mano | 3 | 3 | 4 |
| AlbertoJuice | Calavera con traje de rayas blancas y negras | 4 | 4 | 2 |
| Toni Dimoni | Disfrazado de demonio | 3 | 5 | 2 |
| Salvatore autobusero | Conduce el bus asomado a la ventana y grita «Més pagues i més gruixudes!» | 4 | 1 | 5 |
| Joseph Rotondas | Moto de 3 ruedas, planos y maletín | 5 | 2 | 3 |
| Alberto Mikolápiz | Disfrazado de lápiz | 3 | 4 | 3 |
| Olmito carriles bici | Alto, delgado y en bici | 5 | 3 | 2 |
| Dices | Bici con remolque y 3 hijos | 4 | 2 | 4 |

## Recorrido
Av. de l'Almeda → Plaça de Catalunya → Parc de Can Mercader (Palau y Torre de la Miranda) → Museu de les Aigües → Citilab → L'Estadi.

## Música
Banda sonora chiptune original de estilo arcade, sintetizada en el navegador: un tema principal en Mi menor y otro más rápido para el jefe final.

## Técnica
Un solo `index.html` con HTML5 Canvas. Todo el arte, la música y los efectos se generan por código; no usa recursos de terceros. Los lugares de Cornellà están dibujados como interpretación libre en píxel. Juego original inspirado en los arcades de los 90, sin relación con SNK ni con Metal Slug.
