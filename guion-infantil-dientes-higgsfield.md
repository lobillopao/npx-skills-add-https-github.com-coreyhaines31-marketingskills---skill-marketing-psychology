# Video infantil estilo canción para bebés — "A lavarse los dientes"

Formato: 16:9 horizontal, 2:00 min, 15 escenas de 8 s. Canción original, personajes originales (no se usan los personajes ni la marca de CoComelon: están registrados y YouTube los reclama).

## La fórmula del canal (lo que se replica)

- Una sola rutina diaria por video (baño, dientes, comida, dormir), contada como canción.
- Bebé protagonista + familia + mascota. Todos sonríen todo el tiempo.
- Estribillo que se repite 3 o 4 veces, palabras cortas, onomatopeyas, conteos ("uno, dos, tres").
- Cambio de plano cada 3 a 5 segundos, cámara lenta y suave, nada brusco.
- Animación 3D redondeada, cabezas grandes, ojos enormes y brillantes, colores saturados pastel, sets limpios con pocos objetos.

## Personajes (bloques fijos para pegar en los prompts)

[LULA]
> a 2-year-old toddler girl, 3D animated, oversized round head, huge glossy brown eyes, chubby rosy cheeks, two tiny pigtails with red bows, light brown skin, yellow overalls with a star on the chest, white t-shirt

[PIPO]
> a small fluffy white puppy with one brown ear, 3D animated, big round black eyes, red collar with a yellow bell

[MAMÁ]
> a young mother, 3D animated, kind smile, curly dark hair in a bun, light brown skin, mint green sweater

[PAPÁ]
> a young father, 3D animated, short black hair, round glasses, friendly smile, blue striped shirt

[ESTILO]
> 3D animated preschool nursery rhyme style, soft rounded shapes, oversized heads, big glossy eyes, bright saturated pastel colors, soft global illumination, clean simple set with few props, warm and cheerful, high quality children's animation render, 16:9

## Configuración

**Imágenes (Higgsfield)**
- Modelo: GPT Image 2.5 (`gpt_image_2_5`), 16:9.
- Paso 1: generá la hoja de personajes (prompt abajo). Elegí la mejor.
- Paso 2: en todas las escenas cargá esa hoja como `image_references`. Así Lula, Pipo y la familia salen iguales en todo el video.

**Prompt hoja de personajes:**
> Character reference sheet on a plain white background: [LULA] shown front view, side view and back view; [PIPO] front and side view; [MAMÁ] front view; [PAPÁ] front view. All characters in a neutral standing pose, same scale, labeled with no text. [ESTILO]

**Video (Seedance 2.0)**
- Modelo: `seedance_2_0`. Imagen de la escena como `start_image` + hoja de personajes como `image_references`.
- Pruebas: `mode: fast`, 720p. Final: `mode: std`, 1080p.
- Duración: 8 s. Aspecto: 16:9.
- `generate_audio: false` (la canción va en edición). Si querés que muevan la boca al ritmo, cortá el pedazo de canción de esa escena y pasalo como `audio_references` con `generate_audio: true`.

**Música:** Higgsfield no genera canciones. Hacela en Suno con este estilo:
> children's nursery rhyme, bright ukulele and xylophone, glockenspiel, soft claps, 110 bpm, happy female lead vocal with toddler backing voices, simple melody, Spanish lyrics

## Letra completa (2:00)

**Intro (0:00-0:16)**
MAMÁ (hablado): ¡Lula! ¿Terminaste de cenar? ¡Es hora de lavarse los dientes!
LULA: ¡Sííí!

**Estribillo (0:16-0:32)**
Cepillo, cepillo, chiqui-chiqui-chá,
los dientes brillan, ¡ja, ja, ja!
Arriba y abajo, lo hago yo,
¡mis dientes limpios, qué lindos son!

**Estrofa 1 (0:32-0:48)**
Pongo pasta poquitita,
como un guisante, así, así.
Abro grande la boquita:
¡aaaah! ¡Mírame a mí!

**Estrofa 2 (0:48-1:04)**
Los de arriba, chiqui-chiqui,
hacia abajo, uno, dos, tres.
¿Quién me ayuda? ¡Pipo ayuda!
Guau, guau, guau, ¡otra vez!

**Estribillo (1:04-1:12)** (con papá)

**Estrofa 3 (1:12-1:20)**
Los de abajo en circulitos,
como el tren: chu-chu, chu-chu.

**Estrofa 4 (1:20-1:36)**
La lengüita, cosquillitas, ji, ji, ji.
Agua en la boca, buches, buches,
y escupo: ¡ptuí!

**Estribillo final (1:36-1:52)** (toda la familia)

**Cierre (1:52-2:00)**
LULA (hablado): ¡Buenas noches, dientitos! ¡Chau, chau!

---

## Escenas

### 1 (0:00-0:08) Intro
**Imagen:** Exterior of a cozy colorful two-story house at dusk, round windows glowing warm yellow, soft purple sky with first stars, rounded trees and a little mailbox, [ESTILO]
**Seedance:** Slow gentle push-in toward the glowing window of the house. Stars twinkle softly, a light in the window turns on. Smooth slow camera, no characters moving.

### 2 (0:08-0:16) Mamá llama
**Imagen:** [LULA] sitting in a high chair at a bright dining table with an empty plate and a spoon, [MAMÁ] leaning toward her smiling and pointing toward the hallway, [PIPO] sitting on the floor next to the chair, warm kitchen, [ESTILO]
**Seedance:** Mom points toward the hallway and talks happily. Lula raises both arms excitedly. Pipo wags his tail fast. Gentle camera, smooth cheerful animation.

### 3 (0:16-0:24) Estribillo 1: corre al baño
**Imagen:** [LULA] running happily down a pastel hallway toward an open bathroom door, [PIPO] running behind her, bathroom light glowing, [ESTILO]
**Seedance:** Lula toddles quickly toward the bathroom with little bouncy steps, pigtails bouncing. Pipo hops behind her. Camera tracks sideways at her height. Joyful, bouncy rhythm.

### 4 (0:24-0:32) Estribillo 1: baile con cepillo
**Imagen:** [LULA] standing on a small blue step stool in front of a pastel bathroom sink holding a pink toothbrush up high like a trophy, [PIPO] sitting beside the stool looking up, round mirror, rubber duck on the counter, [ESTILO]
**Seedance:** Lula sways side to side to the music holding the toothbrush up, smiling with her eyes closed. Pipo tilts his head left and right in rhythm. Static camera, slight bounce, cheerful dance.

### 5 (0:32-0:40) Estrofa 1: la pasta
**Imagen:** Close-up of [LULA]'s small hands squeezing a tiny pea-sized drop of toothpaste onto a pink toothbrush, colorful toothpaste tube with a smiling face, [ESTILO]
**Seedance:** Her little hands squeeze the tube gently and a small pea-sized dot of toothpaste lands on the brush. A tiny sparkle appears on the toothpaste. Slow push-in, smooth and clear.

### 6 (0:40-0:48) Estrofa 1: boca grande
**Imagen:** [LULA] in front of the round bathroom mirror opening her mouth wide saying "aaah", her reflection visible, tiny white baby teeth, [ESTILO]
**Seedance:** Lula opens her mouth very wide, then giggles and points at herself in the mirror. Camera slowly moves from her face to her reflection. Playful, gentle.

### 7 (0:48-0:56) Estrofa 2: los de arriba
**Imagen:** [LULA] brushing her top teeth with a downward motion, holding up three fingers with the other hand, foam bubbles around her mouth, [ESTILO]
**Seedance:** Lula brushes her top teeth with slow downward strokes and counts with her free hand, raising one, two, three fingers. Small foam bubbles float up and pop. Static camera, rhythmic movement.

### 8 (0:56-1:04) Estrofa 2: Pipo ayuda
**Imagen:** [PIPO] sitting on the bathroom mat holding a tiny blue toothbrush in his mouth, tail mid-wag, [LULA] laughing in the background out of focus, [ESTILO]
**Seedance:** Pipo barks three times happily, the little toothbrush bouncing in his mouth, tail wagging fast. Lula claps in the background. Cute, bouncy animation.

### 9 (1:04-1:12) Estribillo 2: llega papá
**Imagen:** [PAPÁ] kneeling next to [LULA] at the sink, both holding toothbrushes up and smiling at each other, [PIPO] between them, [ESTILO]
**Seedance:** Dad and Lula sway side to side together and tap their toothbrushes like a toast. Pipo jumps once. Camera slowly pulls back to show all three. Joyful dance.

### 10 (1:12-1:20) Estrofa 3: el trencito
**Imagen:** [LULA] brushing her bottom teeth in little circles, a small colorful toy train on the bathroom counter going around a round track, [ESTILO]
**Seedance:** Lula brushes in small circles while the toy train goes around its track at the same rhythm, puffing tiny clouds of steam. Gentle camera arc. Playful.

### 11 (1:20-1:28) Estrofa 4: cosquillas
**Imagen:** [LULA] gently brushing her tongue, eyes squeezed shut, giggling, shoulders raised, [ESTILO]
**Seedance:** Lula brushes her tongue softly and bursts into giggles, shoulders shaking, little hearts pop above her head. Static close shot. Sweet, funny.

### 12 (1:28-1:36) Estrofa 4: buches y escupo
**Imagen:** [LULA] with puffed cheeks full of water holding a small yellow cup, leaning over the sink, [MAMÁ] smiling beside her, [ESTILO]
**Seedance:** Lula swishes water side to side with puffed cheeks, then leans down and spits into the sink with a tiny splash. Mom claps. Clean, gentle, child-friendly.

### 13 (1:36-1:44) Estribillo final: la familia
**Imagen:** [MAMÁ], [PAPÁ] and [LULA] standing together in front of a wide bathroom mirror, all brushing their teeth at the same time, [PIPO] on the stool, reflections visible, [ESTILO]
**Seedance:** The whole family brushes their teeth in sync, swaying left and right to the music. Pipo wags his tail in rhythm. Slow push-in toward the mirror. Warm, happy.

### 14 (1:44-1:52) Estribillo final: sonrisa
**Imagen:** Close-up of [LULA] showing a big bright smile with clean little teeth, a sparkle on her teeth, [ESTILO]
**Seedance:** Lula smiles wide toward the camera, a bright star sparkle shines on her teeth with a twinkle, she laughs and claps. Slow push-in. Magical, cheerful.

### 15 (1:52-2:00) Cierre
**Imagen:** [LULA] tucked into a small bed with star-printed sheets, [PIPO] curled up at her feet, a moon nightlight glowing, [ESTILO]
**Seedance:** Lula waves goodbye toward the camera, yawns and closes her eyes. Pipo snuggles closer. The nightlight dims softly. Slow pull-back. Calm, sleepy ending.

---

## Edición

1. Poné la canción de Suno en la línea de tiempo y cortá cada clip al tiempo de su escena.
2. Efectos de sonido arriba de la música: ladridos, "pop" de burbujas, "ding" de brillo, chu-chu del tren.
3. Letra en pantalla en el estribillo, tipografía redonda grande, palabra por palabra al ritmo (karaoke). Ayuda a que los papás canten.
4. Miniatura: escena 14 (sonrisa con brillo) + texto corto "¡A lavarse los dientes!".

## YouTube

- Marcá el video como "Hecho para niños" (es obligatorio por ley COPPA; si no lo marcás te pueden multar o bajar el canal).
- Activá la etiqueta de contenido alterado o sintético.
- Desde 2025 YouTube desmonetiza canales con videos IA repetitivos o hechos en serie. Para que no te pase: canción y rutina distinta en cada video, los mismos personajes, y que cada capítulo tenga algo nuevo (un personaje, un lugar).
