# Invitación — Egreso de Karen De Freitas

Página de invitación a la fiesta sorpresa por su egreso de **abogada y escribana
pública** (Facultad de Derecho, UdelaR).

Es un solo archivo: [`index.html`](index.html), con HTML, CSS y JS adentro. No
hay que instalar ni compilar nada — se abre con doble clic.

## Antes de compartirla: completar los datos

Dentro de `index.html` quedan tres datos entre corchetes. Buscá `[` y reemplazá:

| Marcador | Qué va |
|---|---|
| `[FECHA DE LA FIESTA]` | Día de la fiesta |
| `[HORA — antes que Karen]` | Hora de llegada de los invitados |
| `[DIRECCIÓN DEL SALÓN]` | Dónde es |

## Cómo se guardan las confirmaciones

El formulario de la página es propio, pero envía a un Google Form
(«Egreso Karen»), que no se ve en ningún momento. El envío viaja a un iframe
oculto, así que la página no se recarga: aparece el cartel de confirmación y la
respuesta queda guardada.

Los tres campos están mapeados así:

| Campo en la página | Campo en el Google Form |
|---|---|
| Nombre y apellido | `entry.469026367` |
| ¿Contamos con vos? (Si / No) | `entry.967123086` |
| Mensaje para Karen | `entry.132387428` |

Si alguna vez se rehace el formulario de Google, hay que actualizar esos tres
`name=` en `index.html`, porque son los que identifican cada pregunta.

Si se corta la conexión, la página lo detecta y ofrece el formulario de Google
directo como respaldo, en lugar de dar por buena una respuesta que no llegó.

## Publicarla

Está pensada para GitHub Pages: en **Settings → Pages**, rama `main`, carpeta
`/ (root)`. Queda en `https://braiantuck.github.io/Karen_Egreso/`, que es la
dirección que ya figura en las etiquetas de vista previa para WhatsApp.

## Créditos

Los emblemas de la balanza y la pluma son grabados de Pearson Scott Foresman
(Wikimedia Commons, dominio público), recoloreados al dorado de la página.
Tipografías: Cinzel, Cormorant Garamond y Jost, vía Google Fonts.
