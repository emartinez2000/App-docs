# ITACA — Manual de Usuario

*Revisión documental — 20 de septiembre de 2026; aplicación en pruebas.*

Este manual refleja las decisiones confirmadas y las limitaciones conocidas. Su fuente se mantiene en el repositorio de ITACA y se publica online en App-docs.

ITACA es una app para **preparar, vivir y recordar tus viajes**: guarda lugares favoritos, identifica monumentos con la cámara, interpreta y traduce con Gemini el texto visible, organiza rutas y visitas, y comparte tus descubrimientos con otros viajeros.

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
- **Modo Paseo**: el modo "de calle". La cámara está siempre lista para identificar un monumento o cartel mediante Gemini y consultar qué tienes cerca. Es el modo que llevarás abierto mientras caminas.

Para cambiar de modo usa el botón de la **esquina superior derecha**: en Paseo verás el icono de una persona caminando (te lleva a Preparación) y en Preparación un icono de lápiz con lista (te lleva a Paseo).

En **iPhone** la app arranca en modo Paseo; en **iPad** arranca en modo Preparación. En Mac (app de iPad en Mac) solo está disponible Preparación, también al regresar de una visita. En iPad se mantienen ambos modos y toda la funcionalidad.

### El favorito

La unidad básica de ITACA es el **favorito**: un lugar con su nombre, dirección, coordenadas, fotos, información descriptiva, enlaces y tus notas personales. Cada favorito pertenece a un **viaje** (el campo "Viaje" que ves en el modo Preparación), lo que te permite mantener separados los lugares de distintos viajes.

### Gemini

ITACA usa la inteligencia artificial **Gemini** de Google para identificar lugares a partir de fotos, generar descripciones e historia, sugerir qué ver dentro de un monumento y responder a tus preguntas. Siempre que veas el icono de **chispas** (✨), hay una consulta a Gemini detrás.

---

## 2. Modo Preparación

La pantalla principal del modo Preparación muestra el nombre del viaje actual (editable, máximo 20 caracteres) y un menú con estas opciones:

### 2.1 Añadir enlace Google

Pega un enlace de Google Maps (largo o corto, del tipo `maps.app.goo.gl/...`) y ITACA lo resuelve automáticamente: obtiene el nombre del lugar, la dirección, las coordenadas, el tipo de lugar y hasta dos fotos de Google. Antes de guardar verás una vista previa donde puedes añadir un **nombre personalizado** y un **comentario**.

> **La forma más rápida**: ni siquiera necesitas copiar y pegar. Desde Google Maps, pulsa **Compartir** en cualquier lugar y elige **ITACA** en la hoja de compartir. Puedes escribir una nota en ese momento, que quedará guardada como comentario del favorito. Al abrir ITACA se procesa el enlace y se crea el lugar si la resolución y el guardado tienen éxito.

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

> **Recomendación**: antes de usar la foto + ✨, abre los **prismáticos**, elige la fuente **Google** en el desplegable de iconos y comprueba si el lugar ya aparece cerca. La lista se carga con información mínima y una portada. Si lo encuentras, pulsa **+**, confirma tus comentarios y **Añadir**: en ese momento ITACA solicita los detalles y hasta dos fotos completas disponibles antes de guardarlo. Si esa consulta falla, puedes reintentar o aceptar de forma explícita guardar solo los datos básicos y la portada mostrada. Si más adelante quieres historia o curiosidades, abre la ficha y pulsa el botón **ⓘ** para pedir información a Gemini. Este flujo suele ser más rápido y preciso que identificar únicamente por imagen.

El botón **info** (círculo con "i") es el corazón del modo Paseo cuando no encuentras el lugar en Google o quieres identificarlo directamente por foto:

1. Apunta al monumento, edificio o lugar y pulsa el botón. Se captura una foto.
2. En la pantalla de revisión puedes:
   - Pulsar **✨ (chispas)** para preguntar a Gemini directamente.
   - Pulsar **añadir foto** para capturar una **segunda foto** desde otro ángulo (a veces ayuda a Gemini a identificar mejor el lugar).
   - Pulsar **papelera** para descartar y volver a la cámara.
3. Gemini responde con: un **resumen en una frase**, un **resumen**, una **explicación** detallada y **referencias**. También reconoce el texto visible y, cuando corresponde, incluye su traducción en el apartado **Traducción**. Propone hasta tres **sugerencias de preguntas** para seguir profundizando.
4. Puedes **escuchar la respuesta** con el botón del altavoz (lectura en voz alta, con controles de pausa, frase anterior/siguiente y volumen). Si llevas AirPods conectados, la lectura empieza automáticamente.
5. Para preguntar algo más, usa el botón **"¿Quieres saber alguna otra cosa sobre este sitio?"**: puedes continuar la conversación dentro de ITACA, o saltar a las apps de Gemini o ChatGPT con el contexto copiado.
6. Cuando termines, pulsa **guardar** (bandeja con flecha) para crear el favorito con toda la información, o **papelera** para descartar la sesión.

> **Sobre la ubicación**: ITACA captura tu posición GPS en el momento de pulsar ✨, no al hacer las fotos. Esa coordenada se conserva al guardar, salvo que aceptes incorporar una coincidencia de Google: en ese caso se guardan las coordenadas y dirección del establecimiento. Sin aceptar esa coincidencia, si haces una foto, caminas y luego preguntas, se registra la posición del momento de la consulta.

### 3.2 Texto visible y traducción

No existe un botón de traductor ni un OCR independiente. Usa el mismo botón **info** y el mismo flujo de identificación para fotografiar carteles, paneles, menús o cartelas. Gemini reconoce directamente el texto visible en una o dos imágenes y utiliza ese contenido para identificar y explicar el lugar.

El idioma probable configurado para el viaje se utiliza únicamente como pista. Gemini debe decidir el idioma a partir de la imagen. Los idiomas incluidos en **Do not translate languages** se conservan tal cual; los demás se traducen al idioma de la aplicación, actualmente español, dentro del apartado **Traducción** de la explicación detallada.

Esta función requiere conexión porque forma parte de la consulta a Gemini. Si guardas el resultado, la traducción se conserva como parte normal de la información del favorito o Subitem.

### 3.3 Qué hay cerca: los prismáticos

El botón de los **prismáticos** abre lugares cercanos. En Google se ordenan por **distancia andando** cuando está disponible; los resultados sin ese dato se recolocan siguiendo sus predecesores en la respuesta de Google. Los favoritos usan distancia local y las rutas conservan el orden de sus pasos. El radio Google delimita un círculo de búsqueda, no la longitud máxima del recorrido a pie.

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
- **Botón info (ⓘ)**: pide a Gemini información sobre el lugar. Si ya tienes información guardada, ofrece **«Reemplazar información»** o **«Preguntar algo adicional»**. Reemplazar cambia la explicación solo cuando guardas la nueva; descartar conserva la anterior. Preguntar añade una ampliación. Tus notas, fotos, enlaces y preparación de visita se conservan en ambos casos. Si falla guardar, el resultado permanece abierto con un aviso y puedes reintentar.
- **Botón visita (puerta abierta)**: inicia el flujo de visita (ver [sección 5](#5-visitas-y-subitems)).
- **Botón altavoz**: lee en voz alta la información del lugar. Perfecto para escuchar la historia del sitio mientras caminas hacia él.
- **Enlaces**: las referencias que devolvió Gemini y los enlaces que añadas tú.
- **Mis notas**: tus comentarios personales.

### 4.3 Editar un favorito

Desde el lápiz puedes modificar todos los campos: nombres (Google y personal), dirección, tipos, enlaces, información corta y larga, comentarios y el estado visto/no visto. El menú de foto permite añadir imágenes desde Fotos, desde un archivo, o haciendo una foto, además de cambiar la portada o borrar fotos.

La portada es una instantánea independiente del álbum. Si borras la foto que usaste para crearla, la portada se conserva mientras quede alguna otra foto; al borrar la última foto también se elimina la portada. **Cancelar** descarta tanto los cambios de fotos como los de portada realizados en esa edición.

---

## 5. Visitas y subitems

Las **visitas** son la funcionalidad estrella para museos, catedrales, yacimientos y, en general, cualquier lugar grande con cosas que ver dentro.

### 5.1 Qué es un subitem

Un **subitem** es un "favorito hijo": una obra, una sala, una capilla o un rincón **dentro** de un favorito. Tiene la misma estructura que un favorito (nombre, fotos, información de Gemini, audio, enlaces, notas) pero queda agrupado bajo su lugar padre, de modo que tu lista principal no se llena de entradas sueltas.

### 5.2 Preparar e iniciar una visita

1. Abre la ficha del lugar (por ejemplo, el Museo del Prado) y pulsa el botón de la **puerta abierta**.
2. La primera vez, ITACA pide a Gemini unas **sugerencias de visita**: qué obras o zonas no deberías perderte. Esas sugerencias se guardan y se convierten automáticamente en subitems.
3. Se abre la **lista de visita**: la ficha del lugar arriba, las sugerencias de Gemini y la lista de subitems.
4. Pulsa **"Iniciar visita"**. La visita queda activa. Se cierran las pantallas del flujo y se vuelve a Paseo en iPhone/iPad o Preparación en Mac. Una banda identifica el lugar de la visita activa.

### 5.3 Durante la visita

Con la visita activa, los elementos guardados mediante la vista previa quedan **dentro del lugar visitado** como subitems:

- Haz una foto a un cuadro y pregunta a Gemini con ✨: al guardarlo se crea un subitem del museo.
- Fotografía la cartela de una obra y pregunta a Gemini: el texto y su traducción quedan en el mismo Subitem cuando corresponde.
- Los **prismáticos** abren la lista de la visita, para repasar las sugerencias y lo que ya has guardado.

Añadir manualmente o pegar un enlace en Preparación también crea un Subitem. **Compartir desde la app Google Maps e importar `.itaca` siguen creando favoritos independientes**, aunque haya visita activa: es el comportamiento previsto.

Las consultas fotográficas a Gemini incluyen nombre y dirección del lugar de la visita. Al consultar un Subitem también se incluye su nombre. Esto ayuda a interpretar la obra o cartela dentro de su museo, pero no garantiza que la identificación sea correcta.

En la barra superior verás el botón de **salir de la visita**. Al pulsarlo (o desde la lista de visita con "Finalizar visita") ITACA te pide confirmación y vuelve al funcionamiento normal.

### 5.4 Después de la visita

Los subitems permanecen guardados al finalizar la visita; borrar el lugar padre también los elimina. Es tu **recuerdo estructurado de la visita**: cada obra con su foto, su explicación y tus notas. Los subitems se exploran igual que un favorito (con Gemini, audio y fotos), aunque no pueden enviarse de forma individual ni iniciar visitas propias.

---

## 6. Rutas

Una **ruta** es una secuencia ordenada de favoritos: el itinerario de un día, un paseo temático, etc.

- **Crear o editar**: en modo Preparación, selecciona favoritos en la lista y usa **"Seleccion" → Añadir a ruta**, o entra en **Editar ruta** desde el menú principal. Puedes ponerle nombre, **reordenar los pasos** arrastrando y eliminar la ruta. Una ruta admite hasta 51 pasos.
- **Seguir la ruta**: en modo Paseo, abre los prismáticos y elige la fuente **Ruta** en el desplegable de iconos. Verás los pasos en orden, con su distancia. Combínalo con el botón de Google Maps de cada ficha para navegar de un paso al siguiente.

> **Consejo**: crea una ruta por día de viaje ("Día 1 — Centro histórico", "Día 2 — Museos") y así cada mañana solo tienes que abrir los prismáticos y seguir el orden.

---

## 7. Compartir favoritos: ficheros .itaca

ITACA permite intercambiar favoritos entre dispositivos y usuarios mediante ficheros **`.itaca`**: un paquete para **compartir copias** con fotos, subitems y enlaces. No es una copia de seguridad integral ni restaura identidades o sesiones de visita.

Los Subitems conservan sus nombres, textos, comentarios, Visto, ubicación, datos Google, categoría, fecha, fotos, enlaces y portada. La copia recibe identidades nuevas y no incluye el historial ni la sesión de visita del emisor. Antes de mostrar el contenido, ITACA valida manifiesto, identidades, rutas, tamaños y recursos. Si el paquete está incompleto o alterado, avisa y no guarda una copia parcial.

### 7.1 Exportar varios favoritos

1. En modo Preparación, abre la **Lista de favoritos**.
2. Marca los lugares que quieras (círculo a la derecha de cada ficha).
3. Menú **"Seleccion" → Exportar**.
4. Escribe un comentario opcional (por ejemplo: "Mis imprescindibles de Roma").
5. En iPhone/iPad se genera el fichero y se abre la hoja de compartir. En Mac se abre un selector para guardar una copia del archivo.

### 7.2 Enviar un solo favorito

Desliza la ficha hacia la izquierda y pulsa **Enviar** (avión de papel). Mismo proceso, con un único favorito y sus Subitems.

### 7.3 Importar

1. En modo Preparación, pulsa **Importar de fichero .itaca** y elige el fichero. (Atajo: si tocas un `.itaca` en la app Archivos, ITACA se abre directamente en la pantalla de importación.)
2. ITACA muestra el **contenido del fichero**: la lista de lugares y el comentario del remitente.
3. Marca los que te interesen y pulsa **"Importar seleccionados"**.

> La importación siempre **crea copias nuevas**: si importas dos veces el mismo fichero tendrás los lugares duplicados. Revisa antes de importar.

Las rutas incluidas también se copian de forma independiente: nunca se mezclan automáticamente con una ruta del mismo nombre que ya tengas en ese viaje. ITACA conserva el orden relativo de los lugares elegidos. Si seleccionas solo parte de los miembros disponibles, la nueva ruta aparece con el sufijo **«(parcial)»** y la confirmación de importación lo avisa. Un favorito que pertenecía a varias rutas mantiene esas pertenencias en las nuevas copias.

---

## 8. Ajustes

Los Ajustes se abren con el **engranaje** de la esquina superior izquierda, en ambos modos.

### Parámetros del viaje
- **Trip name**: el viaje activo. Todos los favoritos nuevos se asignan a este viaje.
- **Probable language**: el idioma que probablemente encontrarás en los textos del destino (código ISO, p. ej. `it` para italiano). Gemini lo usa como pista, pero debe determinar el idioma a partir de la imagen.
- **Country**: el país del viaje.

### Texto en las fotografías
- **Do not translate languages**: lista de idiomas cuyo texto quieres conservar sin traducir. El resto se traduce al idioma de la aplicación, actualmente español, cuando Gemini identifica una fotografía.

### Audio
- **Voces**: elige la voz para la lectura en voz alta en español y en inglés. Para una calidad notablemente mejor, descarga las voces **"Enhanced"** o **"Premium"** en Ajustes de iOS → Accesibilidad → Contenido leído → Voces.
- **Volumen por defecto** de la lectura.

---

## 9. Sincronización con iCloud

ITACA está configurada para **sincronizar favoritos, fotos, subitems y enlaces con iCloud** entre tus dispositivos (iPhone, iPad, Mac) que usen la misma cuenta de Apple. Los cambios pueden tardar en aparecer en otro dispositivo; su funcionamiento efectivo sigue pendiente de verificación en esta versión de pruebas.

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
10. **Exporta tu viaje al terminarlo** como `.itaca` y guárdalo en Archivos o envíatelo por correo: es una copia para compartir, no una copia de seguridad integral.
11. **Configura los idiomas antes de salir**: indica el idioma probable del viaje y cuáles no quieres que Gemini traduzca. El reconocimiento y la traducción forman parte de la consulta online a Gemini.

---

## 11. Preguntas frecuentes

**¿ITACA funciona sin conexión?**
Parcialmente. Tus favoritos con su información y fotos están disponibles localmente. La identificación y traducción de texto mediante Gemini, la resolución de enlaces de Google Maps y la búsqueda Nearby requieren conexión.

**¿Qué modo debo usar en Mac?**
Preparación. El acceso a Paseo está deshabilitado en Mac. Esta limitación no afecta al iPad.

**Compartí un enlace desde Google Maps y no veo el favorito.**
El favorito se crea al **abrir ITACA** después de compartir. Abre la app y espera unos segundos; necesita conexión para resolver el enlace.

**¿Puedo recuperar un favorito borrado?**
No hay papelera. Si lo compartiste antes en un `.itaca`, puedes importar una copia con el contenido que transporta el paquete. Los Subitems conservan sus campos propios y recursos incluidos, pero el paquete no recupera la identidad original, la sesión ni el historial de visita.

**He importado un fichero dos veces y tengo duplicados.**
Es el comportamiento esperado: la importación siempre crea copias nuevas. Borra los duplicados desde la lista (selección múltiple → Borrar).

**La lectura en voz alta suena robótica.**
Descarga una voz "Enhanced" o "Premium" en Ajustes de iOS → Accesibilidad → Contenido leído → Voces, y selecciónala en los Ajustes de ITACA.

**¿Gemini se equivoca a veces?**
Sí, como toda IA puede cometer errores, especialmente con lugares poco conocidos. Contrasta los datos importantes (horarios, precios) con las referencias que acompañan a la respuesta.


## Comportamiento de guardado y límites de la versión de pruebas

- Las preguntas adicionales se guardan como ampliaciones, conservando la respuesta inicial.
- Guardar espera a que termine Gemini. Si falla el detalle, puedes guardar la información recibida; se muestra un aviso de que estará incompleta.
- Borrar el lugar de una visita activa finaliza también esa sesión cuando el borrado se guarda correctamente.
- Solo se exige compatibilidad con el almacén y los paquetes actuales de pruebas; no con versiones anteriores.

Estas instrucciones corresponden a las correcciones del 20 de septiembre de 2026. La sincronización y los recorridos visuales entre dispositivos requieren comprobación en uso.

Los enlaces compartidos desde Google Maps se retiran de la cola únicamente cuando se han guardado. Si hay un fallo, el aviso permite reintentar o dejarlos para la próxima apertura de la app. Guardar desde la vista previa confirma la persistencia antes de volver al inicio del modo actual; si la visita cambió mientras estaba abierta, pide revisar el destino.

Los ajustes de viaje, idiomas y audio son comunes a Paseo y Preparación: cambiar de modo conserva los cambios. El texto no excluido se traduce al idioma de la app, actualmente español. En las fichas, **Reemplazar información** cambia la explicación al guardar; **Preguntar algo adicional** añade una ampliación. Un fallo de guardado mantiene la respuesta abierta para reintentar.

## Guardados, coincidencias y recuperación

En los editores de favoritos y Subitems, **Guardar** confirma juntos los cambios de texto, fotos, portada y enlaces. Hasta entonces son una edición pendiente. **Cancelar** los descarta; no hay cierre deslizando la pantalla. Si falla guardar, se muestra el error y se conserva la edición para reintentar. Las capturas añadidas directamente desde una ficha también ofrecen reintento o descarte explícito si falla su guardado.

Cambiar **Visto**, cambiar de viaje una selección y añadir un resultado Nearby tampoco se muestran como completados si falla la persistencia. El aviso permite reintentar sin duplicar el lugar ni perder la selección o el valor anterior.

Al resolver un enlace de Google Maps, si el candidato está fuera de 500 metros de las coordenadas de referencia, se muestra la distancia aproximada, nombre, dirección y origen. También se pide revisión si faltan coordenadas de referencia. **Aceptar este lugar** permite continuar. **No aceptar; conservar enlace** mantiene el texto pegado o el enlace y su nota en la cola de compartidos para revisarlo después; no crea un favorito con esa coincidencia. La distancia indicada no es una ruta andando. Los candidatos dudosos de una identificación con Gemini vienen desmarcados: puedes conservar la ubicación de consulta o aceptar expresamente los datos Google.

Si falla la creación de la lista de sugerencias de visita, se muestra el error sin dar por preparada la lista. Reintentar vuelve a guardar los hijos y su estado conjuntamente. Un error al leer el padre se distingue de un lugar que ya no existe.

Si ITACA no puede abrir su almacén, muestra el diagnóstico y **Reintentar**. No borra ni sustituye los datos por una base vacía. Un fallo persistente puede necesitar diagnóstico adicional; el botón no repara automáticamente un almacén dañado. La sincronización real entre dispositivos continúa pendiente de validación.
