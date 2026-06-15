# ITACA — Manual de Usuario

*Versión 1.0 — Junio 2026*

ITACA es una app para **preparar, vivir y recordar tus viajes**: guarda lugares favoritos, identifica monumentos con la cámara, traduce carteles, organiza rutas y visitas, y comparte tus descubrimientos con otros viajeros.

---

## Índice

1. [Conceptos básicos](#1-conceptos-básicos)
2. [Modo Preparación](#2-modo-preparación)
3. [Modo Paseo](#3-modo-paseo)
4. [La ficha de un favorito](#4-la-ficha-de-un-favorito)
5. [Visitas y subitems](#5-visitas-y-subitems)
6. [Rutas](#6-rutas)
7. [Compartir favoritos: ficheros .itaca](#7-compartir-favoritos-ficheros-itaca)
8. [Ajustes](#8-ajustes)
9. [Sincronización con iCloud](#9-sincronización-con-icloud)
10. [Consejos de buen uso](#10-consejos-de-buen-uso)
11. [Preguntas frecuentes](#11-preguntas-frecuentes)

---

## 1. Conceptos básicos

### Los dos modos

ITACA funciona en dos modos, pensados para dos momentos distintos del viaje:

- **Modo Preparación**: el modo "de escritorio". Aquí añades lugares, organizas tu lista de favoritos, creas rutas e importas o exportas favoritos. Es el modo ideal en casa antes del viaje, o en el hotel planificando el día siguiente.
- **Modo Paseo**: el modo "de calle". La cámara está siempre lista para identificar un monumento, traducir un cartel o consultar qué tienes cerca. Es el modo que llevarás abierto mientras caminas.

Para cambiar de modo usa el botón de la **esquina superior derecha**: en Paseo verás el icono de una persona caminando (te lleva a Preparación) y en Preparación un icono de lápiz con lista (te lleva a Paseo).

En **iPhone** la app arranca en modo Paseo; en **iPad** arranca en modo Preparación. En Mac (app de iPad en Mac) solo está disponible el modo Preparación, ya que el modo Paseo requiere cámara.

### El favorito

La unidad básica de ITACA es el **favorito**: un lugar con su nombre, dirección, coordenadas, fotos, información descriptiva, enlaces y tus notas personales. Cada favorito pertenece a un **viaje** (el campo "Viaje" que ves en el modo Preparación), lo que te permite mantener separados los lugares de distintos viajes.

### Gemini

ITACA usa la inteligencia artificial **Gemini** de Google para identificar lugares a partir de fotos, generar descripciones e historia, sugerir qué ver dentro de un monumento y responder a tus preguntas. Siempre que veas el icono de **chispas** (✨), hay una consulta a Gemini detrás.

---

## 2. Modo Preparación

La pantalla principal del modo Preparación muestra el nombre del viaje actual (editable, máximo 20 caracteres) y un menú con estas opciones:

### 2.1 Añadir enlace Google

Pega un enlace de Google Maps (largo o corto, del tipo `maps.app.goo.gl/...`) y ITACA lo resuelve automáticamente: obtiene el nombre del lugar, la dirección, las coordenadas, el tipo de lugar y hasta dos fotos de Google. Antes de guardar verás una vista previa donde puedes añadir un **nombre personalizado** y un **comentario**.

> **La forma más rápida**: ni siquiera necesitas copiar y pegar. Desde Google Maps, pulsa **Compartir** en cualquier lugar y elige **ITACA** en la hoja de compartir. Puedes escribir una nota en ese momento, que quedará guardada como comentario del favorito. La próxima vez que abras ITACA, el lugar ya estará creado.

### 2.2 Añadir lugar manualmente

Crea un favorito en tu **posición GPS actual**, sin necesidad de enlace. ITACA te preguntará si quieres hacer una foto para asociarla al lugar. Es útil para sitios que no están en Google Maps: un mirador, un rincón con encanto, el portal de tu apartamento.

### 2.3 Lista de favoritos

Abre la lista completa de favoritos del viaje actual. Desde aquí puedes:

- **Filtrar** por nombre, por **tipo de lugar** (museo, restaurante, iglesia…) y por visto / no visto. El panel de filtros se abre con el icono del embudo, arriba a la derecha. Para el tipo, pulsa el control desplegable: se abre un selector donde puedes marcar **una o varias categorías** a la vez, usar **Limpiar** para volver a "Todos" y **OK** para cerrar.
- **Abrir una ficha** tocándola (ver [sección 4](#4-la-ficha-de-un-favorito)).
- **Seleccionar varios favoritos** marcando el círculo a la derecha de cada ficha. Con la selección hecha, el menú **"Seleccion"** ofrece:
  - **Borrar**: elimina los favoritos seleccionados.
  - **Exportar**: genera un fichero `.itaca` con los seleccionados (ver [sección 7](#7-compartir-favoritos-ficheros-itaca)).
  - **Cambiar viaje**: mueve los seleccionados a otro viaje.
  - **Añadir a ruta**: los incorpora a una ruta existente o nueva.

### 2.4 Editar ruta

Crea y modifica rutas con tus favoritos (ver [sección 6](#6-rutas)).

### 2.5 Gestionar tipos

ITACA clasifica los lugares en categorías propias ("ItacaTypes": museo, restaurante, monumento…) a partir de los tipos que devuelve Google. En esta pantalla puedes ajustar ese mapeo si alguna categoría no se asigna como esperas. La mayoría de usuarios no necesitará tocar esto.

### 2.6 Importar de fichero .itaca

Importa favoritos que te haya enviado otro usuario (ver [sección 7](#7-compartir-favoritos-ficheros-itaca)).

---

## 3. Modo Paseo

En el modo Paseo la pantalla es la **cámara en vivo**, con una barra de botones abajo y los ajustes y el cambio de modo arriba.

### 3.1 Identificar un lugar: foto + Gemini

> **Recomendación**: antes de usar la foto + ✨, abre los **prismáticos**, elige la fuente **Google** en el desplegable de iconos y comprueba si el lugar ya aparece cerca. Si lo encuentras, añádelo con el botón **+**: tendrás nombre, dirección y fotos oficiales de Google en un solo toque. Si más adelante quieres historia o curiosidades, abre la ficha y pulsa el botón **ⓘ** para pedir información a Gemini. Este flujo suele ser más rápido y preciso que identificar únicamente por imagen.

El botón **info** (círculo con "i") es el corazón del modo Paseo cuando no encuentras el lugar en Google o quieres identificarlo directamente por foto:

1. Apunta al monumento, edificio o lugar y pulsa el botón. Se captura una foto.
2. En la pantalla de revisión puedes:
   - Pulsar **✨ (chispas)** para preguntar a Gemini directamente.
   - Pulsar **añadir foto** para capturar una **segunda foto** desde otro ángulo (a veces ayuda a Gemini a identificar mejor el lugar).
   - Pulsar **papelera** para descartar y volver a la cámara.
3. Gemini responde con: un **resumen en una frase**, un **resumen**, una **explicación** detallada y **referencias**. También propone hasta tres **sugerencias de preguntas** para seguir profundizando.
4. Puedes **escuchar la respuesta** con el botón del altavoz (lectura en voz alta, con controles de pausa, frase anterior/siguiente y volumen). Si llevas AirPods conectados, la lectura empieza automáticamente.
5. Para preguntar algo más, usa el botón **"¿Quieres saber alguna otra cosa sobre este sitio?"**: puedes continuar la conversación dentro de ITACA, o saltar a las apps de Gemini o ChatGPT con el contexto copiado.
6. Cuando termines, pulsa **guardar** (bandeja con flecha) para crear el favorito con toda la información, o **papelera** para descartar la sesión.

> **Sobre la ubicación**: ITACA captura tu posición GPS en el momento de pulsar ✨, no al hacer las fotos. Esa misma coordenada se usa al guardar el lugar. Si haces una foto, caminas y luego preguntas, la posición registrada será la del momento de la consulta.

### 3.2 Traducir un cartel: OCR

El botón de la **burbuja con caracteres** captura una foto y reconoce el texto que aparece en ella (carteles, paneles informativos, menús…):

- Los bloques de texto detectados se marcan sobre la imagen. **Toca un bloque** para traducirlo (si hay tres bloques o menos, se traducen automáticamente).
- Puedes **arrastrar un rectángulo** para seleccionar varios bloques a la vez, y **agruparlos** con el botón de agrupar para que se traduzcan como un único texto.
- Con el texto traducido puedes:
  - Pulsar **✨** para pedir a Gemini más contexto sobre lo que dice el cartel (combina el texto con la foto).
  - Pulsar **guardar** para crear un favorito con la foto del cartel y su traducción.

Los idiomas de origen y destino se configuran en Ajustes (ver [sección 8](#8-ajustes)). La traducción funciona **sin conexión** una vez descargados los modelos de idioma.

### 3.3 Qué hay cerca: los prismáticos

El botón de los **prismáticos** abre la lista de lugares cercanos, ordenados por distancia.

En la **barra superior** de esa lista tienes, de izquierda a derecha: el botón para cerrar, los controles de **distancia** y **fuente**, y el botón de **filtros**:

#### Distancia

Un botón muestra el radio activo (**100 m**, **200 m**, **500 m**, **1 km** o **∞**). Al pulsarlo se despliega un menú con todas las opciones; la elegida queda resaltada. El menú se superpone a la lista sin desplazarla. En la fuente **Google**, la opción **∞** no está disponible.

#### Fuente de lugares

Junto a la distancia, un segundo botón muestra el **icono de la fuente activa**. Al pulsarlo se despliegan cuatro opciones:

- **Ruta** (icono morado): los pasos de tu ruta activa, en orden. Si tienes varias rutas, debajo del desplegable aparece un selector para elegir cuál.
- **Favoritos** (corazón rojo): tus favoritos del viaje actual.
- **Google** ("G" verde): lugares de Google Places a tu alrededor, aunque no los tengas guardados. Junto a cada resultado hay un botón **+** para añadirlo a favoritos al instante.
- **Actualizar** (flecha circular): vuelve a cargar los lugares de Google (mantiene la fuente Google).

#### Filtros

El icono del **embudo** (arriba a la derecha) abre el panel de filtros de contenido. Según la fuente activa verás:

- **Favoritos** o **Ruta**: nombre, tipo y visto / no visto.
- **Google**: solo tipo.

Si alguno de esos filtros no está en su valor por defecto, el botón del embudo se muestra en **naranja** con un pulso suave para avisarte de que la lista está filtrada.

**Filtro por tipo**: en el panel, pulsa el control de **Tipo**. Se abre un selector con todas las categorías Itaca (museo, restaurante, monumento…). Puedes marcar **varias a la vez**; **Limpiar** quita la selección y **OK** cierra el selector. En **Google**, si no eliges ningún tipo, la búsqueda usa **POI** por defecto.

Tocar una ficha abre su vista de exploración.

> Si hay una **visita activa** (ver [sección 5](#5-visitas-y-subitems)), los prismáticos abren directamente la lista de esa visita en lugar de la lista general.

---

## 4. La ficha de un favorito

### 4.1 La tarjeta en la lista

Cada favorito se muestra como una tarjeta con su foto de portada (thumbnail), nombre, dirección y distancia. Sobre la tarjeta:

- **Toca la foto** para abrir el visor de fotos: navega por el álbum del lugar (fotos de Google y tuyas), **añade fotos** con la cámara y elige cuál usar como portada.
- **Toca el resto de la tarjeta** para abrir la vista de exploración.
- **Desliza hacia la izquierda** (iPhone/iPad) para revelar cuatro acciones rápidas:
  - **Mapa**: abre el lugar en Google Maps (ideal para navegar hasta él).
  - **Enviar** (avión de papel): exporta solo ese favorito como fichero `.itaca` para compartirlo.
  - **Editar** (lápiz).
  - **Borrar** (papelera, con confirmación).

### 4.2 La vista de exploración

Es la pantalla principal de un favorito. Contiene:

- Nombre, dirección y el badge **Visto / No visto** (tócalo para cambiarlo: así llevas la cuenta de lo que ya has visitado).
- **Botón Google Maps**: abre el lugar en Google Maps.
- **Botón info (ⓘ)**: pide a Gemini información sobre el lugar. Si ya tienes información guardada, te preguntará si quieres **borrar la anterior** o **preguntar algo adicional** que se añadirá como ampliación.
- **Botón visita (puerta abierta)**: inicia el flujo de visita (ver [sección 5](#5-visitas-y-subitems)).
- **Botón altavoz**: lee en voz alta la información del lugar. Perfecto para escuchar la historia del sitio mientras caminas hacia él.
- **Enlaces**: las referencias que devolvió Gemini y los enlaces que añadas tú.
- **Mis notas**: tus comentarios personales.

### 4.3 Editar un favorito

Desde el lápiz puedes modificar todos los campos: nombres (Google y personal), dirección, tipos, enlaces, información corta y larga, comentarios y el estado visto/no visto. El menú de foto permite añadir imágenes desde Fotos, desde un archivo, o haciendo una foto, además de cambiar la portada o borrar fotos.

---

## 5. Visitas y subitems

Las **visitas** son la funcionalidad estrella para museos, catedrales, yacimientos y, en general, cualquier lugar grande con cosas que ver dentro.

### 5.1 Qué es un subitem

Un **subitem** es un "favorito hijo": una obra, una sala, una capilla o un rincón **dentro** de un favorito. Tiene la misma estructura que un favorito (nombre, fotos, información de Gemini, audio, enlaces, notas) pero queda agrupado bajo su lugar padre, de modo que tu lista principal no se llena de entradas sueltas.

### 5.2 Preparar e iniciar una visita

1. Abre la ficha del lugar (por ejemplo, el Museo del Prado) y pulsa el botón de la **puerta abierta**.
2. La primera vez, ITACA pide a Gemini unas **sugerencias de visita**: qué obras o zonas no deberías perderte. Esas sugerencias se guardan y se convierten automáticamente en subitems.
3. Se abre la **lista de visita**: la ficha del lugar arriba, las sugerencias de Gemini y la lista de subitems.
4. Pulsa **"Iniciar visita"**. ITACA vuelve a la cámara del modo Paseo, con la visita activa.

### 5.3 Durante la visita

Con la visita activa, todo lo que guardes queda **dentro del lugar visitado** como subitem:

- Haz una foto a un cuadro y pregunta a Gemini con ✨: al guardarlo se crea un subitem del museo.
- Traduce la cartela de una obra con el OCR: lo mismo.
- Los **prismáticos** abren la lista de la visita, para repasar las sugerencias y lo que ya has guardado.

En la barra superior verás el botón de **salir de la visita**. Al pulsarlo (o desde la lista de visita con "Finalizar visita") ITACA te pide confirmación y vuelve al funcionamiento normal.

### 5.4 Después de la visita

Los subitems quedan guardados para siempre en la ficha del lugar. Es tu **recuerdo estructurado de la visita**: cada obra con su foto, su explicación y tus notas. Los subitems se exploran igual que un favorito (con Gemini, audio y fotos), aunque no pueden enviarse de forma individual ni iniciar visitas propias.

---

## 6. Rutas

Una **ruta** es una secuencia ordenada de favoritos: el itinerario de un día, un paseo temático, etc.

- **Crear o editar**: en modo Preparación, selecciona favoritos en la lista y usa **"Seleccion" → Añadir a ruta**, o entra en **Editar ruta** desde el menú principal. Puedes ponerle nombre, **reordenar los pasos** arrastrando y eliminar la ruta. Una ruta admite hasta 51 pasos.
- **Seguir la ruta**: en modo Paseo, abre los prismáticos y elige la fuente **Ruta** en el desplegable de iconos. Verás los pasos en orden, con su distancia. Combínalo con el botón de Google Maps de cada ficha para navegar de un paso al siguiente.

> **Consejo**: crea una ruta por día de viaje ("Día 1 — Centro histórico", "Día 2 — Museos") y así cada mañana solo tienes que abrir los prismáticos y seguir el orden.

---

## 7. Compartir favoritos: ficheros .itaca

ITACA permite intercambiar favoritos entre dispositivos y usuarios mediante ficheros **`.itaca`**: un paquete que contiene los lugares con todos sus datos, **incluidas las fotos**, los subitems y los enlaces.

### 7.1 Exportar varios favoritos

1. En modo Preparación, abre la **Lista de favoritos**.
2. Marca los lugares que quieras (círculo a la derecha de cada ficha).
3. Menú **"Seleccion" → Exportar**.
4. Escribe un comentario opcional (por ejemplo: "Mis imprescindibles de Roma").
5. Se genera el fichero `.itaca` y se abre la hoja de compartir: envíalo por WhatsApp, AirDrop, correo o guárdalo en Archivos.

### 7.2 Enviar un solo favorito

Desliza la ficha hacia la izquierda y pulsa **Enviar** (avión de papel). Mismo proceso, con un único lugar.

### 7.3 Importar

1. En modo Preparación, pulsa **Importar de fichero .itaca** y elige el fichero. (Atajo: si tocas un `.itaca` en la app Archivos, ITACA se abre directamente en la pantalla de importación.)
2. ITACA muestra el **contenido del fichero**: la lista de lugares y el comentario del remitente.
3. Marca los que te interesen y pulsa **"Importar seleccionados"**.

> La importación siempre **crea copias nuevas**: si importas dos veces el mismo fichero tendrás los lugares duplicados. Revisa antes de importar.

---

## 8. Ajustes

Los Ajustes se abren con el **engranaje** de la esquina superior izquierda, en ambos modos.

### Parámetros del viaje
- **Trip name**: el viaje activo. Todos los favoritos nuevos se asignan a este viaje.
- **Probable language**: el idioma que probablemente encontrarás en los carteles del destino (código ISO, p. ej. `it` para italiano). Es el idioma de origen del traductor.
- **Country**: el país del viaje.

### Traducción
- **Translate to**: tu idioma, al que se traducirán los carteles (p. ej. `es`).
- **Do not translate languages**: lista de idiomas que no quieres que se traduzcan (por ejemplo, si lees inglés sin problema, añade `en` y el OCR te mostrará esos textos tal cual).

### Audio
- **Voces**: elige la voz para la lectura en voz alta en español y en inglés. Para una calidad notablemente mejor, descarga las voces **"Enhanced"** o **"Premium"** en Ajustes de iOS → Accesibilidad → Contenido leído → Voces.
- **Volumen por defecto** de la lectura.

---

## 9. Sincronización con iCloud

Tus favoritos, fotos, subitems y enlaces se **sincronizan automáticamente con iCloud** entre tus dispositivos (iPhone, iPad, Mac) que usen la misma cuenta de Apple. No necesitas hacer nada: añade un lugar en el iPad por la noche y lo tendrás en el iPhone por la mañana.

- La sincronización requiere sesión iniciada en iCloud. Sin cuenta, ITACA funciona igualmente pero solo en local.
- Los ficheros `.itaca` son independientes de iCloud: sirven para pasar favoritos **a otras personas** o entre cuentas distintas.

---

## 10. Consejos de buen uso

1. **Antes de identificar un lugar por foto, busca con Google.** Abre los prismáticos, elige la fuente **Google** y, si el sitio aparece en la lista, añádelo con **+**. Después, si quieres más contexto, abre la ficha y pide información a Gemini con **ⓘ**. Es más eficiente que empezar por la cámara y ✨.
2. **Crea un favorito "Viaje a…" por cada viaje**, con la palabra *Planning* en tus comentarios, y úsalo como cuaderno general: reservas, horarios, teléfonos útiles. Haz lo mismo con un favorito genérico por ciudad o zona. Buscando "Planning" en tus notas los encontrarás siempre al instante.
3. **Prepara antes, disfruta después.** Las semanas previas al viaje, cada vez que veas un sitio interesante en Google Maps, compártelo a ITACA con una nota. Al llegar, tu mapa de favoritos ya estará hecho y el modo Paseo hará el resto.
4. **Pide la información de Gemini con antelación** (botón ⓘ de cada ficha) cuando tengas wifi, por ejemplo en el hotel. Así durante el paseo solo tendrás que pulsar el altavoz y escuchar.
5. **Dos fotos mejor que una** cuando un monumento sea difícil de identificar: captura una vista general y un detalle (una placa, una inscripción) antes de pulsar ✨.
6. **Pulsa ✨ donde quieras registrar el lugar**: la posición GPS se toma en ese momento, no al hacer la foto. Si haces la foto y te alejas, pregunta antes de irte.
7. **Usa las visitas en sitios grandes.** En un museo, inicia la visita al entrar: todo lo que fotografíes y preguntes quedará ordenado dentro del museo, no desperdigado por tu lista.
8. **Marca "Visto"** lo que ya hayas visitado y filtra por "No vistos" en los prismáticos (embudo → vistos): verás solo lo que te queda por descubrir cerca.
9. **Descarga las voces Enhanced** de iOS y lleva auriculares: escuchar la historia de un lugar mientras te acercas a él es la mejor forma de usar ITACA.
10. **Exporta tu viaje al terminarlo** como `.itaca` y guárdalo en Archivos o envíatelo por correo: es tu copia de seguridad y un regalo perfecto para el próximo amigo que visite ese destino.
11. **Configura los idiomas antes de salir** (Probable language y Translate to) y abre el traductor una vez con wifi para que se descarguen los modelos: después funcionará sin conexión.

---

## 11. Preguntas frecuentes

**¿ITACA funciona sin conexión?**
Parcialmente. La traducción de carteles funciona sin conexión (una vez descargados los modelos), y tus favoritos con su información y fotos están siempre disponibles. Gemini, la resolución de enlaces de Google Maps y la búsqueda Nearby requieren conexión.

**¿Por qué no encuentro el modo Paseo en mi Mac?**
El modo Paseo necesita cámara y GPS; en Mac solo está disponible el modo Preparación.

**Compartí un enlace desde Google Maps y no veo el favorito.**
El favorito se crea al **abrir ITACA** después de compartir. Abre la app y espera unos segundos; necesita conexión para resolver el enlace.

**¿Puedo recuperar un favorito borrado?**
No hay papelera. Si lo exportaste antes en un `.itaca`, puedes reimportarlo desde ahí.

**He importado un fichero dos veces y tengo duplicados.**
Es el comportamiento esperado: la importación siempre crea copias nuevas. Borra los duplicados desde la lista (selección múltiple → Borrar).

**La lectura en voz alta suena robótica.**
Descarga una voz "Enhanced" o "Premium" en Ajustes de iOS → Accesibilidad → Contenido leído → Voces, y selecciónala en los Ajustes de ITACA.

**¿Gemini se equivoca a veces?**
Sí, como toda IA puede cometer errores, especialmente con lugares poco conocidos. Contrasta los datos importantes (horarios, precios) con las referencias que acompañan a la respuesta.
