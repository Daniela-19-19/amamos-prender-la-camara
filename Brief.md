BRIEF DE PRODUCTO

Looped

“Streaming musical con conexión real entre artistas y fans.”

| Categoría | Plataforma de streaming musical con interacción artista-fan acotada |
|---|---|
| Contexto | Proyecto académico — materia de Lenguajes Digitales |
| Plataforma | Aplicación móvil — iOS y Android |
| Equipo | Lukas L., Nicolás C., Daniela A. — Lenguajes Digitales |

Cómo leer este documento

Este brief distingue explícitamente entre hechos (datos observables o de mercado citados), hipótesis (afirmaciones sobre usuarios o comportamiento aún no validadas con investigación propia) y supuestos de diseño (decisiones que este documento toma para poder avanzar, sujetas a revisión). Cada etiqueta se marca así:

HECHO   HIPÓTESIS   SUPUESTO DE DISEÑO   PENDIENTE DE VALIDACIÓN


## 1. PROBLEMA


### Punto de dolor (síntesis)

Fans y artistas independientes quieren una relación de reconocimiento mutuo, pero hoy solo pueden tenerla fuera del streaming y sin ningún límite — lo que la vuelve invisible para el fan e insostenible para el artista.


### Definición del problema

Los fans de artistas independientes o emergentes no tienen una forma estructurada de sentirse reconocidos por esos artistas dentro de la misma plataforma donde escuchan su música; para lograrlo, hoy dependen de canales externos (Instagram, TikTok, Discord) donde compiten por atención sin garantía de ser vistos.  [HIPÓTESIS]

Los artistas independientes quieren construir una relación directa y monetizable con su audiencia, pero evitan los canales de mensajería abierta porque no pueden sostener un volumen ilimitado de interacción sin que consuma su tiempo o se vuelva difícil de moderar.  [HIPÓTESIS]

Las plataformas líderes de streaming (Spotify, Apple Music, YouTube Music, Deezer) están diseñadas alrededor de la escucha y el descubrimiento, y no ofrecen mecanismos nativos de interacción directa artista-fan dentro de la misma app.  [HECHO (observación de producto — no cuantificado)]

Weverse y Bubble ofrecen interacción directa artista-fan, pero no operan como plataformas de streaming musical completo y están asociadas principalmente al ecosistema K-pop, lo que limita su aplicabilidad a otros géneros.  [HECHO (observación de producto)]


### La oportunidad

La intersección que Looped busca ocupar es:

STREAMING MUSICAL  +  INTERACCIÓN REAL  +  CONTROL DE ESCALA

Pregunta central de diseño: ¿cómo permitir una relación más cercana entre fan y artista sin comprometer el tiempo, la privacidad y la capacidad de gestión del artista?


> **Punto débil identificado**
> - El problema está construido sobre dos personas hipotéticas (Valentina y Simón) y sobre la observación de que otras plataformas no resuelven esto — no sobre entrevistas o encuestas propias con fans o artistas reales.
> - No hay evidencia todavía de que “sentirse visto por el artista” sea una necesidad no satisfecha lo bastante fuerte como para cambiar de app o pagar por ella; podría ser un deseo latente pero de baja prioridad frente al simple consumo musical.
> - Recomendación: antes de avanzar a diseño visual, validar el problema con 8-12 entrevistas cualitativas por lado (fans y artistas independientes) enfocadas en frecuencia real de intentos de contacto, canales usados hoy y frustración específica.


### Riesgo prioritario identificado por el equipo

Ante la pregunta “¿qué es lo primero que tememos que salga mal si lanzamos mañana sin validar más?”, el equipo definió una jerarquía explícita de riesgo, que este brief adopta como criterio de validación:

Riesgo principal (mata el concepto): que la necesidad de cercanía no sea lo bastante fuerte como para que fans y artistas cambien un hábito ya instalado — por ejemplo, que a los fans les guste la idea pero no usen la función con frecuencia, o que los artistas no estén dispuestos a dedicar tiempo incluso con cupos definidos.

Riesgo secundario (limita el negocio, no el concepto): la viabilidad técnica y legal del catálogo musical. Se reconoce como real, pero el equipo decide deliberadamente separarlo de la validación de experiencia — no se resuelve en esta fase del MVP académico.

Esta jerarquía de riesgo es una decisión del equipo, no un hallazgo de investigación: ordena qué se valida primero, pero no reemplaza la validación misma.  [SUPUESTO DE DISEÑO — decisión del equipo]


### Regla de decisión ante resultados ambiguos en las entrevistas

El equipo definió explícitamente qué hacer si las 8-12 entrevistas recomendadas no confirman ni refutan claramente la necesidad, para no dejar esa situación sin protocolo:

No: “las entrevistas fueron ambiguas → construimos el MVP completo igual”.

Sí: “las entrevistas fueron ambiguas → afinamos la hipótesis → corremos una prueba pequeña y específica → recién entonces desarrollamos el MVP”.

El concepto de Looped combina en realidad dos hipótesis distintas —que el fan quiere más cercanía y que el artista la quiere solo si controla su tiempo— y un resultado ambiguo no obliga a abandonar el concepto completo: obliga a probar cada hipótesis por separado, empezando por el núcleo (streaming + conexión real + control del artista) antes de invertir en funcionalidades secundarias como insignias, comunidades o salas de escucha.

Un resultado ambiguo en entrevistas no es lo mismo que un resultado negativo; tratarlos igual (abandonando el concepto) sería sobre-reaccionar tanto como ignorarlo (construyendo igual) sería sub-reaccionar.  [SUPUESTO DE DISEÑO — decisión del equipo]


## 2. OBJETIVO DE NEGOCIO

Desarrollar un modelo de plataforma de streaming que genere ingresos recurrentes mientras aumenta el valor percibido de la relación artista-fan.


### Modelo de negocio propuesto

Freemium con anuncios (capa gratuita de entrada).

Suscripción Premium sin anuncios.

Fan club por artista (pago recurrente a un artista específico).

Comisión sobre tips (propinas directas de fan a artista).

Comisión sobre merchandising vendido dentro de la plataforma.


### Mecanismo priorizado para validar en el MVP: Fan Club

De los cinco mecanismos, el equipo decidió que el Fan Club por artista es el único que debe probarse en esta primera fase, porque es el único directamente atado a la propuesta de valor diferencial de Looped — la cercanía artista-fan — y no simplemente a la posibilidad de cobrar por streaming.

Si un fan paga por un nivel mayor de cercanía o contenido exclusivo de un artista específico, eso valida que la relación artista-fan tiene valor económico real, que es lo que distingue a Looped de cualquier otro servicio de streaming.

Premium, publicidad, tips y merchandising quedan como fuentes de ingreso adicionales para fases posteriores, pero ninguno de los cuatro prueba por sí mismo el diferencial del producto.

El Fan Club solo puede probarse honestamente después de que el mecanismo de interacción (preguntas votadas + cupo) ya esté generando cercanía real; no es un experimento independiente del flujo del MVP, depende de él. La secuencia correcta es: primero validar que la interacción se usa y se siente valiosa, después ofrecer el Fan Club como forma de profundizarla.  [SUPUESTO DE DISEÑO — secuencia de validación]


### Beneficio del Fan Club — definición cerrada para el MVP

El equipo cerró el contenido del beneficio para no dejarlo abierto durante la construcción: Fan Club = contenido exclusivo del artista + prioridad de acceso en las interacciones limitadas.

Contenido exclusivo: formato simple tipo “detrás de la canción” (texto, audio o imagen corta), no un módulo editorial completo. Es una versión acotada de la funcionalidad marcada “fuera” en la tabla de alcance del MVP (sección 6) — entra únicamente como parte del beneficio del Fan Club, no como sección independiente de contenido.

Prioridad de acceso: los suscriptores de Fan Club obtienen prioridad de voto o visibilidad dentro del mismo cupo de preguntas ya definido en el flujo del MVP (sección 6) — no habilita sesiones AMA en vivo, que permanecen fuera del MVP.

La intención explícita es acotar el alcance: el Fan Club no desbloquea una cantidad indefinida de funcionalidades, sino que prueba una única hipótesis de negocio — si los fans están dispuestos a pagar por mayor cercanía y acceso exclusivo al artista.

El artista de prueba no define qué es el beneficio (eso ya está cerrado); ayuda a validar si este formato resulta viable y atractivo desde su perspectiva, y qué contenido específico produciría sin que le aumente significativamente la carga de trabajo. Esto es distinto de las preguntas de descubrimiento sobre el mecanismo de cupos (sección 10), que sí siguen abiertas.  [SUPUESTO DE DISEÑO — decisión del equipo]


### Objetivos comerciales

Generar ingresos recurrentes mediante suscripciones.

Lograr mayor tiempo de uso que la competencia directa, partiendo de la hipótesis de que la interacción retiene más que la escucha sola.

Atraer inicialmente artistas independientes y emergentes, donde Looped enfrenta menor competencia por su atención que en el segmento de artistas ya establecidos.

Permitir monetización directa del artista sobre su comunidad.

Crear efecto de red mediante el historial construido entre fans y artistas.


### Ejemplo ilustrativo de ingresos (Fan Club, piloto)


> **Cifra ilustrativa — no es una proyección financiera real**
> - 100.000 fans activos × 5% de conversión a Fan Club × USD 4/mes = USD 20.000 de MRR (ingreso recurrente mensual) en el piloto.
> - Esta cifra sirve únicamente para dimensionar el orden de magnitud del modelo si el mecanismo funciona; no está basada en datos reales de conversión, precio o tamaño de audiencia — los tres supuestos (5% de conversión, USD 4/mes, 100.000 fans activos) están pendientes de validar.


### Lectura crítica

La priorización del Fan Club como único mecanismo a validar en el MVP resuelve la ambigüedad original de tener cinco mecanismos igual de “prioritarios”. El umbral que distingue una señal positiva de una negativa ahora tiene una propuesta concreta (≥ 5% de conversión, ver sección 7) — sigue sin venir de datos propios, pero ya no es una pregunta abierta.  [SUPUESTO DE DISEÑO — propuesta pendiente de validar]

El modelo depende de artistas independientes que, por definición, tienen audiencias pequeñas; esto entra en tensión con la meta de “efecto de red”, que normalmente requiere volumen. El efecto de red aquí no sería “más usuarios en general” sino “historial acumulado entre un fan y su artista” — es un efecto de red distinto (de profundidad, no de escala) y debería nombrarse así explícitamente para no generar expectativas de crecimiento tipo red social masiva.  [SUPUESTO DE DISEÑO]

Nota sobre cifras: las cifras de mercado citadas en este documento (sección de Información Adicional) se usan únicamente como contexto de oportunidad, no como proyecciones de ingresos de Looped. Ningún cálculo de ingresos, usuarios o conversión en este brief debe leerse como proyección financiera real; donde se mencionan números son ejemplos ilustrativos para fines de diseño y priorización.


## 3. USUARIO


### Segmento general

Fans, 16-30 años: siguen artistas emergentes o de alcance medio; hoy interactúan con ellos por redes sociales (Instagram, TikTok, Discord) por falta de una opción mejor dentro del streaming.

Artistas independientes: sin gran disquera detrás; buscan cercanía real con su público y monetización directa. Hoy operan sin equipo de soporte para gestionar esa interacción.


### Fan — Valentina, 22 años

Estudiante universitaria, escucha música más de 3 horas al día.

Sigue aproximadamente 15-20 artistas.

Quiere descubrir artistas antes que otros y sentirse reconocida por los que apoya.

Hoy se siente anónima: cambia constantemente de app para interactuar y no sabe si el artista realmente ve sus comentarios.


### Artista — Simón, 27 años

Músico independiente, sin estructura de disquera o equipo de soporte.

Quiere construir comunidad real y monetizar directamente su audiencia.

Le cuesta diferenciar fans genuinamente interesados de spam.

No quiere que interactuar con su comunidad se vuelva una carga de tiempo ilimitada.


### Usuario prioritario para el MVP: el ARTISTA

Looped es un producto de dos lados, pero para el MVP el diseño debe organizarse alrededor del artista, no del fan, por tres razones concretas:

Escasez real: hay muchos más fans potenciales que artistas dispuestos a probar una plataforma nueva. El recurso limitante del sistema es la disposición y el tiempo del artista, no la demanda del fan.

El diferenciador vive en las reglas del artista: la propuesta de valor completa de Looped depende de que el artista configure cupos y límites. Si esa herramienta no es simple y confiable, no hay nada distinto que ofrecerle al fan frente a Instagram o Discord.

Problema de arranque en frío (cold start): sin artistas activos generando espacios de interacción limitada, la experiencia del fan queda vacía. El diseño y la construcción deben empezar por garantizar que un artista pueda configurar su cupo en minutos y sentir control real desde el primer uso.

Esto no significa que el fan sea secundario en la experiencia final: significa que las decisiones de MVP (qué construir primero, qué simplificar) deben resolverse primero a favor de que el artista pueda operar su lado del sistema sin fricción.


> **Punto débil identificado**
> - Ambas personas (Valentina y Simón) están descritas con intenciones y frustraciones, pero sin ninguna cita, dato de encuesta o fuente que las respalde; son arquetipos de diseño, no hallazgos de research.
> - Pendiente de validación: tamaño real del segmento de artistas independientes dispuestos a adoptar una plataforma nueva, y su disposición real a dedicar tiempo semanal a responder fans a cambio de ingresos inciertos.


## 4. OBJETIVO DE EXPERIENCIA


### Para el fan

Sentirse más cerca del artista que escucha, sin salir de la plataforma de streaming.


### Para el artista

Interactuar con su comunidad y fortalecer la relación con sus fans sin perder el control sobre su tiempo.


### Principio rector

“La cercanía se gana con la interacción y la escucha, no solamente pagando.”

Los niveles de fan deben poder subir mediante escucha real, participación y aportes valiosos a la comunidad, no exclusivamente mediante pago.


### Qué debe poder hacer el usuario al finalizar una sesión

El fan debe poder señalar que sabe exactamente qué hizo para acercarse al artista hoy (por ejemplo: envió o votó una pregunta, avanzó de nivel) y ver si el artista lo tomó en cuenta.

El artista debe poder cerrar su sesión de interacción sabiendo cuánto tiempo le tomó, cuántas personas alcanzó y que no quedó una cola de pendientes creciendo sin control.


### Acción principal que demuestra que la experiencia funciona

Que un fan reciba una respuesta o reconocimiento visible por parte del artista dentro de un cupo limitado (por ejemplo, su pregunta fue respondida) y que ese reconocimiento sea directamente atribuible a su nivel de participación, no a un pago.  [SUPUESTO DE DISEÑO — métrica de comportamiento propuesta]


## 5. PROPUESTA DE VALOR

“Tu relación con el artista vive donde vive tu música.”


### Cuál es la ventaja real (más allá de “Spotify con redes sociales”)

La ventaja competitiva de Looped no es sumar funciones sociales a un reproductor. Es un mecanismo de diseño específico: convertir la atención escasa del artista en un recurso estructurado y distribuido de forma justa, en lugar de un buzón abierto donde gana quien manda más mensajes.

En Instagram, TikTok o Discord, la interacción es de suma cero y ruidosa: cientos de fans compiten por la misma bandeja de entrada sin orden ni garantía de respuesta. Eso genera frustración en el fan (no sabe si fue visto) y sobrecarga en el artista (no puede filtrar).

En Looped, la interacción está pre-acotada por diseño (cupos, votación, niveles). Esto convierte la escasez de atención del artista en una señal de valor en vez de un problema de escala: si tu pregunta fue respondida, importa precisamente porque el espacio era limitado.

Al vivir dentro del mismo lugar donde el fan ya escucha música, se elimina el costo de cambiar de app — un costo de fricción real y medible que hoy paga cualquier fan que quiere interactuar con un artista (abrir Discord, buscar el perfil de IG, etc.).


### Comparación

| Característica | Streaming tradicional | Weverse / Bubble | Looped |
|---|---|---|---|
| Catálogo musical completo | Sí | No | Sí |
| Interacción real con artistas | No | Sí | Sí |
| Protección del tiempo del artista | No aplica | Parcial | Sí |
| Todos los géneros | Sí | Limitado | Sí |
| Cercanía ganada por participación | No | Parcial | Sí |


> **Punto débil identificado**
> - La fila “Protección del tiempo del artista: Sí” para Looped es una promesa de diseño, no un hecho verificado; se sostiene únicamente si los cupos configurables realmente se cumplen y se moderan bien.
> - Falta evidencia de que los fans valoren más una respuesta acotada y “justa” que el acceso ilimitado (aunque incierto) que ya tienen hoy en redes abiertas; esto debe probarse, no asumirse.


## 6. ALCANCE / MVP


### Problema concreto que debe resolver la primera versión

Probar si un mecanismo de interacción asíncrono y acotado (preguntas votadas por fans, respondidas por el artista dentro de un cupo) genera una sensación real de reconocimiento en el fan y es sostenible en tiempo para el artista, y si esa cercanía sostiene un modelo de monetización simple vía Fan Club — sin construir todavía el resto del ecosistema social ni los demás mecanismos de monetización.


### Qué entra y qué queda fuera del MVP

| Funcionalidad | MVP | Justificación |
|---|---|---|
| Catálogo y reproducción (streaming) | Dentro | Es la base de retención diaria y el motivo de apertura de la app; sin esto no hay producto de streaming. |
| Niveles de fan por escucha real | Dentro | Es el mecanismo que prueba la hipótesis central: la cercanía se gana, no se compra. Es barato de construir (cálculo sobre datos de escucha ya existentes). |
| Preguntas votadas por fans + cupo de respuesta del artista | Dentro | Único mecanismo de interacción del MVP. Es asíncrono (no requiere infraestructura en vivo), fácil de moderar y demuestra el valor central: reconocimiento gestionado. |
| Fan Club por artista (contenido exclusivo + prioridad de acceso en el cupo) | Dentro | Es el único mecanismo de monetización que el equipo decidió validar en esta fase (sección 2). Sin incluirlo, el MVP no podría medir la capa de negocio del marco de decisión (sección 8): si la cercanía generada tiene valor económico capturable. |
| Cupos de mensajería configurables (DM 1 a 1) | Fuera | Redundante con preguntas votadas para una primera versión; añade complejidad de moderación y expectativas de respuesta individual que son más difíciles de acotar. |
| Salas de escucha en vivo | Fuera | Alto costo técnico (infraestructura en tiempo real, sincronización de audio) para un proyecto académico; no es indispensable para probar la hipótesis de cercanía gestionada. |
| Sesiones AMA en vivo programadas | Fuera | Variante en vivo de las preguntas votadas; se puede posponer a una fase 2 una vez validado el modelo asíncrono. La “prioridad” que ofrece el Fan Club (fila arriba) es prioridad dentro del cupo asíncrono existente, no una sesión en vivo nueva. |
| Contenido “Detrás de la canción” | Fuera (versión mínima dentro) | Como sección independiente de contenido compite por tiempo de desarrollo sin validar la hipótesis principal. Una versión mínima (una publicación simple) entra únicamente como el contenido exclusivo del Fan Club — ver fila Fan Club arriba. |
| Colecciones públicas, reposts, feed social | Fuera | Convierte el producto en una red social de música; desvía el foco del MVP (relación artista-fan) hacia un feed fan-a-fan no priorizado en el problema. |
| Insignias | Fuera (versión mínima dentro) | Una insignia simple ligada al nivel de fan puede quedar dentro como refuerzo visual de reconocimiento; un sistema extenso de logros queda fuera. |
| Comunidades moderadas (foros) | Fuera | Requiere moderación a escala que el equipo académico no puede sostener; no es el mecanismo que se quiere validar primero. |
| Reputación de comentarios | Fuera | Depende de un volumen de comentarios que el MVP no va a generar todavía; es una funcionalidad de madurez, no de validación inicial. |
| Tips y comisión de merchandising | Fuera | Son mecanismos de monetización de fase 2; el MVP debe validar primero si la interacción genera valor percibido antes de cobrar por ella. |


### Flujo principal del MVP

1. El fan escucha catálogo normalmente dentro de la app (streaming estándar).

2. La escucha real y la participación acumulan nivel de fan por artista.

3. El artista abre un cupo de preguntas (por ejemplo: “10 preguntas esta semana”).

4. Los fans envían y votan preguntas dentro del cupo abierto.

5. El artista responde (texto o audio corto) a las preguntas priorizadas por votos, hasta agotar su cupo.

6. Las respuestas quedan visibles en el perfil del artista para todos los fans que participaron.

7. Los fans con Fan Club activo ven contenido exclusivo simple del artista (tipo “detrás de la canción”) y obtienen prioridad de voto/visibilidad dentro del mismo cupo de preguntas — esto permite medir la capa de negocio del marco de decisión (sección 8).


> **Punto débil identificado**
> - El listado original de funcionalidades mezclaba mecanismos de complejidad muy distinta (salas en vivo vs. insignias) sin criterio explícito de priorización; este brief aplica como criterio único: ¿esta función es indispensable para probar que la cercanía gestionada funciona, o es una mejora sobre una hipótesis todavía no validada?
> - Recomendación: no empezar a diseñar pantallas de UI hasta confirmar, con al menos un artista real, que el flujo de cupos es operable en la práctica (cuánto tiempo le toma responder 10 preguntas, por ejemplo).


## 7. CRITERIOS DE ÉXITO

Se proponen 7 criterios, agrupados en tres tipos, evitando métricas vanidosas como número de descargas.

| Tipo | Criterio | Qué demuestra | Umbral propuesto |
|---|---|---|---|
| Producto | % de fans que envían o votan preguntas cada semana | Que el mecanismo de interacción limitada genera participación real, no solo curiosidad inicial. | Sin número — se lee junto al umbral de recurrencia (3 semanas, sección 8) |
| Producto | Tasa de respuesta del artista dentro del cupo asignado | Que el cupo es manejable y el artista efectivamente lo usa (protección de tiempo funcionando). | Sin número — señal binaria: responde o no dentro del cupo |
| Producto | Retención D7 / D30 de fans que participaron vs. los que no | Si la interacción con el artista es lo que retiene, no solo el catálogo musical. | Sin número — falta línea base propia |
| Negocio | Conversión a Fan Club entre fans de nivel alto que ya interactuaron | Disposición a pagar específicamente por cercanía con el artista, no por catálogo sin anuncios (valida el diferencial, no el streaming). | ≥ 5% (propuesta) |
| Negocio | Artistas activos que regresan a responder un segundo ciclo de cupos | Que el valor percibido por el artista es suficiente para volver (lado de oferta sostenible). | ≥ 15 de 20-30 artistas del piloto (propuesta) |
| Experiencia | % de fans que reportan sentirse “reconocidos” (encuesta post-interacción) | Si se cumple el objetivo de experiencia declarado, no solo el objetivo de uso. | > 50% de encuestados (propuesta) |
| Experiencia | Tiempo semanal dedicado por el artista a responder cupos | Que el tiempo se mantiene dentro del límite configurado (evidencia de control real, no solo percibido). | Sin número — se compara contra el cupo que el propio artista configuró |


### Métrica guía (North Star)


> **Una sola métrica que amarra a las demás — propuesta, pendiente de validar**
> - % de fans activos que reciben al menos una respuesta visible de un artista cada 2 semanas.
> - Es la métrica que, si sube, indica que el producto está cumpliendo lo único que promete (que el fan se sienta visto); si baja, ninguna otra métrica del resto de la tabla compensa esa señal.
> - No reemplaza a las 7 métricas anteriores: es una forma de no perder el foco entre ellas, especialmente al presentar resultados del piloto.


> **Nota metodológica**
> - Estos criterios asumen que se puede instrumentar la app para medir escucha, envíos, votos y tiempos de respuesta desde el primer lanzamiento del MVP — esto debe confirmarse como requisito técnico, no darse por sentado.
> - Los umbrales marcados como “propuesta” (5% de conversión a Fan Club, 15 de 20-30 artistas en un segundo ciclo, >50% de fans que se sienten reconocidos) no vienen de datos propios ni de referencias de industria verificadas: son puntos de partida razonables para leer los resultados del piloto, sujetos a ajuste una vez existan datos reales. Los criterios sin umbral quedan así intencionalmente, porque fijar un número sin ninguna base sería inventar una cifra.


## 8. MARCO DE DECISIÓN DE VALIDACIÓN

No todos los resultados posibles del MVP tienen la misma gravedad. El equipo definió tres capas de validación independientes, para no tratar cualquier resultado débil como si tumbara todo el proyecto:

1. Validación del problema — ¿la necesidad de cercanía es real y frecuente? Se mide con uso de la función de interacción (envío y voto de preguntas), no con opiniones declaradas.

2. Validación de la solución — ¿el mecanismo de cupos y votación efectivamente genera esa cercanía sin sobrecargar al artista? Se mide con tasa de respuesta del artista dentro del cupo y con su disposición a repetir el ciclo.

3. Validación del negocio — ¿esa cercanía tiene valor económico capturable vía Fan Club? Se mide con conversión de fans de nivel alto a Fan Club.


### Por qué separar las tres capas

La razón principal es evitar una confusión de diagnóstico: un resultado débil en la capa de negocio no significa lo mismo que un resultado débil en la capa de problema, y el equipo debe reaccionar distinto a cada uno.


> **Regla de decisión adoptada por el equipo**
> - Si los fans usan la interacción pero no pagan por el Fan Club: el problema y la solución están validados, solo el modelo de captura de valor está mal calibrado. Se prueban alternativas (Premium, tips, publicidad, merchandising, patrocinios) sin tocar el concepto central de Looped.
> - Si los fans no usan la interacción, aunque digan que la idea les gusta: el riesgo es grave y afecta el núcleo del producto, porque la interacción es la propuesta de valor misma, no una función adicional.
> - En resumen: “no pagar” no equivale a “el producto no sirve”. “no usar la interacción” sí es la señal que pondría en duda el proyecto completo.

El equipo definió un umbral inicial para la capa 1: tres semanas consecutivas de uso del cupo por parte de fans y artista. No se eligió una semana porque puede estar influenciada por la novedad; tres semanas permiten observar si hay repetición. Durante ese periodo se mediría frecuencia de interacción, volumen de preguntas enviadas y votadas, y si el artista continúa usando el cupo sin abandonarlo.  [SUPUESTO DE DISEÑO — decisión del equipo]

Nota de redacción importante: el umbral debe leerse como “tres semanas nos permitirían detectar si existe un patrón de uso recurrente”, no como “después de tres semanas sabremos que funciona”. La primera formulación es un criterio de observación defendible; la segunda es una afirmación de certeza que el diseño del experimento no puede sostener.

El umbral de tres semanas resuelve la capa 1 (uso). La capa 3 (conversión a Fan Club) ahora tiene un umbral propuesto de 5% (ver sección 7) — sigue sin ser un dato validado, pero ya no queda como una pregunta completamente abierta.  [SUPUESTO DE DISEÑO — propuesta pendiente de validar]


## 9. HOJA DE RUTA

El equipo definió cuatro fases con tiempos y metas de escala concretas. Se documentan tal como están planeadas; son un plan del equipo, no un hallazgo validado — su cumplimiento depende de que las fases anteriores (y sus validaciones) se resuelvan a tiempo.

| FASE 1 · Meses 1-3 | FASE 2 · Meses 4-6 | FASE 3 · Meses 7-12 | FASE 4 · Año 2 |
|---|---|---|---|
| MVP: catálogo, perfiles y cupos básicos. | Piloto con 20-30 artistas independientes. | Fan Club, AMA y comunidades — beta pública. | Escala a más géneros y regiones. |


### Lectura crítica

La fase 3 confirma, con el propio plan del equipo, algo que este brief ya había establecido en la sección 6: AMA en vivo y comunidades moderadas están deliberadamente fuera del MVP (fase 1) y se introducen recién en la fase 3, una vez validado el modelo asíncrono. La hoja de ruta y la tabla de alcance del MVP son consistentes entre sí.  [HECHO — plan del equipo]

La fase 2 apunta a un piloto de 20-30 artistas independientes — una escala mayor que el “un solo artista de prueba” descrito en la sección 10. Esto implica que el plan de reclutamiento de un artista (sección 10) es el primer paso de una curva de reclutamiento mucho más grande, que todavía no tiene un plan definido para pasar de 1 a 20-30 artistas.  [PENDIENTE DE VALIDACIÓN]

Los tiempos de las cuatro fases (3, 3, 6 y 12 meses) no tienen todavía ningún respaldo de estimación de esfuerzo de desarrollo; se presentan como meta de planeación, no como estimación técnica validada.  [SUPUESTO DE DISEÑO]


## 10. VACÍOS DEL BRIEF Y VALIDACIONES NECESARIAS

Este brief está construido principalmente sobre hipótesis de diseño y arquetipos de usuario, no sobre investigación primaria. Antes de considerarlo definitivo, se necesita validar:


### Con fans reales

Si realmente sienten que hoy “no son vistos” por los artistas que siguen, y en qué canal ocurre esa frustración con más fuerza.

Qué tipo de interacción valoran más: respuesta directa, reconocimiento público, acceso a contenido exclusivo, o simplemente sentirse parte de una comunidad.

Qué límites de interacción aceptarían sin sentir que la relación es artificial (por ejemplo: ¿un cupo semanal se siente justo o frustrante?).

Disposición real a pagar específicamente por Fan Club (acceso a mayor cercanía/contenido exclusivo de un artista) — priorizada como el único mecanismo de monetización que se valida en esta fase; Premium, tips, publicidad y merch quedan fuera de la validación inicial.


### Con artistas independientes

Qué límites de tiempo o volumen necesitarían para sentir que la interacción es manejable.

Si estarían dispuestos a mover parte de su actividad de comunidad desde Instagram/Discord hacia una plataforma nueva, y bajo qué condiciones.

Cómo diferencian hoy, en la práctica, a un fan genuino de spam, y si un sistema de niveles resolvería ese problema.

El plan completo del equipo (fuera del MVP, fase 3 de la hoja de ruta) contempla comunidades moderadas por fans designados por el propio artista, no por el equipo del proyecto. Esto es distinto del plan de moderación manual definido para el MVP (más abajo, “Viabilidad de negocio y operación”), que sí corre a cargo del equipo mientras el volumen es bajo — son dos mecanismos de moderación para dos etapas distintas, y no deben confundirse.  [HECHO — plan del equipo]


> **Plan de reclutamiento del primer artista de prueba**
> - Todavía no hay un artista identificado ni confirmado para probar el flujo de cupos — se marca explícitamente como pendiente, no como resuelto.
> - Perfil buscado: artista independiente o emergente del entorno cercano al equipo, con comunidad pequeña o mediana, que gestione hoy sus interacciones principalmente por Instagram, TikTok o mensajes directos (no un artista ya establecido con equipo de gestión) — el mismo perfil que representa Simón, la persona ya definida en la sección 3.
> - Mostrarle un prototipo simple del sistema de cupos y preguntarle: ¿cuántos mensajes o preguntas respondería por semana?, ¿preferiría elegir personalmente quién puede contactarlo?, ¿le serviría que los fans votaran las preguntas?, ¿qué tipo de interacción ofrecería con gusto?, ¿qué condiciones necesitaría para sentirse cómodo usando el sistema?


### Qué hacer si el primer artista rechaza el mecanismo de cupos

El equipo definió una regla de decisión específica para este escenario, porque es el que más podría desviar el rumbo del proyecto: ante un rechazo del primer artista de prueba, se ajusta el mecanismo antes de considerar cambiar el segmento.

Primero se investiga el motivo puntual del rechazo — no es lo mismo que el artista no quiera mensajes directos, que no quiera responder individualmente, que le preocupe la privacidad, o que simplemente prefiera publicar contenido en vez de contestar preguntas.

Con ese motivo identificado, se explora si otra forma de interacción de baja carga (por ejemplo, contenido “detrás de la canción” o una cadencia distinta de respuesta) resuelve la misma necesidad de cercanía sin la fricción puntual que rechazó.

El segmento de artista independiente solo se pondría en duda si el mismo rechazo se repite en varios artistas, no a partir de un solo caso.

Nota de consistencia: el contenido “detrás de la canción” ya tiene una versión mínima dentro del MVP como parte del beneficio del Fan Club (sección 2), así que dejó de ser una tensión. AMA en vivo y comunidades moderadas, en cambio, siguen explícitamente fuera del alcance definido en la sección 6. Si la preferencia real del artista de prueba cae en alguna de esas dos, la decisión que sigue no es “añadirla en silencio” sino volver a la sección 6 y decidir conscientemente si el alcance del MVP debe ampliarse.  [SUPUESTO DE DISEÑO — tensión parcialmente resuelta]


### Viabilidad de negocio y operación

El acceso al catálogo musical requiere licencias y acuerdos con sellos, distribuidoras o proveedores autorizados; es una gestión de estrategia de negocio con apoyo técnico, no solo un tema de desarrollo. El equipo todavía no ha contactado a ninguna disquera, distribuidor o entidad de licenciamiento.  [PENDIENTE DE VALIDACIÓN]

Decisión de alcance: para el MVP académico, esta validación se separa deliberadamente de la validación de experiencia. El prototipo usará un catálogo simulado o contenido autorizado para demo, y el licenciamiento comercial se declara como condición de viabilidad a resolver antes de cualquier lanzamiento real — no como objetivo de este MVP. Frente a la pregunta “¿cómo van a conseguir toda la música?”, la respuesta del equipo es: “es una condición de viabilidad que identificamos, pero no es lo que queremos validar primero con el prototipo.”

Moderación de contenido: quién y cómo se modera el contenido enviado por fans (preguntas, comentarios) a escala, especialmente en un contexto académico sin equipo de moderación.

Decisión de alcance para el MVP: dado que el volumen está naturalmente acotado por el cupo del artista (ej. 10 preguntas semanales), la moderación puede hacerse manualmente por el propio equipo del proyecto antes de que las preguntas lleguen a votación pública, sin necesidad de un sistema automatizado. Esto es viable únicamente mientras el número de artistas activos en la prueba sea pequeño; deja de serlo si el MVP escala más allá del piloto académico.  [SUPUESTO DE DISEÑO]

Viabilidad técnica del MVP propuesto (streaming con licenciamiento + sistema de cupos) dentro del tiempo y recursos disponibles para el proyecto de la materia.

Verificación de las cifras de mercado citadas (tamaño de mercado global, proyección a 2033, número de suscriptores IFPI, tamaño del mercado de fandom K-pop, usuarios de Weverse, suscriptores de Bubble): se citan tal como fueron provistas, pero no fueron verificadas de forma independiente en este ejercicio y deberían confirmarse contra la fuente original antes de usarse en una entrega formal.


## 11. PUNTOS DE DOLOR AMPLIADOS Y REPOSICIONAMIENTO

Esta sección se agregó después de que el equipo identificó cinco puntos de dolor adicionales. Tres de ellos (2, 3 y 4 abajo) apuntan a un problema distinto al que el resto de este brief había resuelto hasta ahora: cambian el enfoque competitivo de “streaming completo con interacción acotada” a “streaming donde el acceso y la visibilidad son justos entre artistas grandes y emergentes”.


### Los cinco puntos de dolor

| Pain | Por qué importa | Feature diferencial propuesta |
|---|---|---|
| 1. Fragmentación de plataformas | Los fans deben salir a Instagram, TikTok o Discord para conectar de verdad con su artista | Ya resuelto en el MVP: el cupo vive dentro del streaming (sin cambios) |
| 2. Release al alcance de grandes | El algoritmo y la visibilidad hoy favorecen a quien ya tiene más oyentes | Ventana de visibilidad pareja por release, igual para artistas grandes y emergentes (fuera del MVP) |
| 3. Estigmatización de género | Ciertos géneros o escenas quedan relegados en el descubrimiento | Descubrimiento que no lidera con el género como filtro por defecto (fuera del MVP) |
| 4. Conocimiento de artistas emergentes | Es difícil para un fan encontrar artistas independientes nuevos | Insignia de “Fan fundador”: reconocimiento a quien sigue a un artista antes de cierto umbral de seguidores (SÍ entra al MVP) |
| 5. Conexión artista-fan potencial | Falta un puente entre un oyente casual y convertirse en fan real | Cupo de “primer contacto” para quien todavía no sigue al artista (fuera del MVP) |


### Tensión que queda abierta

Los pains 2, 3 y 4 apuntan al descubrimiento como corazón del producto; todo lo construido hasta ahora en este brief (cupos, niveles, Fan Club) apunta a la interacción entre un fan y un artista que ya sigue. El equipo decidió mantener la interacción como núcleo del MVP —ya validada en el resto de este documento— e incorporar del descubrimiento únicamente la pieza más barata de construir (Fan fundador), dejando el resto para fases posteriores de la hoja de ruta.  [SUPUESTO DE DISEÑO — decisión del equipo]


### Actualización a la propuesta de valor

“No competimos en catálogo. Competimos en que un artista emergente tenga las mismas herramientas de visibilidad y conexión que uno grande, y en que un fan pueda descubrir música fuera de lo que el algoritmo ya le mostró.”

Esto no reemplaza la propuesta de valor original (sección 5) —la sigue sosteniendo— pero le agrega un segundo eje: además de que “la cercanía se gana, no se paga”, ahora también “la visibilidad se gana por calidad, no por tamaño previo”.


### Cambios al alcance del MVP

- Se agrega al MVP: insignia de “Fan fundador” — quien sigue o interactúa con un artista antes de que este alcance cierto umbral de seguidores recibe un reconocimiento visible y permanente en su perfil.
- Quedan fuera del MVP, para fase 2-3 de la hoja de ruta (sección 9): ventana de visibilidad pareja para releases, descubrimiento sin género como filtro por defecto, y cupo de “primer contacto” para fans que todavía no siguen al artista.

### Validaciones nuevas que esto agrega

- ¿Los fans valoran ser “fan fundador” lo suficiente como para buscar activamente artistas nuevos, o es un reconocimiento que no cambia su comportamiento real de descubrimiento?
¿Qué tan grande debe ser el umbral de seguidores para que “fan fundador” siga sintiéndose exclusivo y no se banalice? No hay un número propuesto todavía.  [PENDIENTE DE VALIDACIÓN]

- Los pains 2 y 3 (visibilidad pareja, género) requieren decisiones de diseño sobre el algoritmo de descubrimiento que este brief todavía no ha tomado —quedan como pendientes de diseño, no solo de validación con usuarios.

## 12. DISEÑO DETALLADO: DESCUBRIMIENTO, PRIMER CONTACTO Y VISIBILIDAD JUSTA

Esta sección documenta el diseño concreto —flujo y wireframes de baja fidelidad— de las tres funcionalidades que la sección 11 había dejado fuera del MVP, para fase 2-3. Ya existen como pantallas navegables; eso no equivale a que estén validadas.


### Nuevo centro de descubrimiento

El punto de entrada del fan deja de ser un catálogo organizado por género o recomendaciones (lógica de streaming genérico) y pasa a ser una pantalla “Descubrir” con tres módulos:

- En ventana: releases con visibilidad pareja (ver más abajo).
- Conexiones activas: artistas con cupo abierto o respondiendo ahora mismo — sin filtro de género como entrada.
- Primer contacto: artistas que el fan todavía no sigue.
El género queda como filtro opcional dentro de estos módulos, nunca como el primer paso obligatorio para descubrir.  [SUPUESTO DE DISEÑO]


### Primer contacto — mecanismo detallado

Nueva decisión en el perfil del artista: ¿ya sigues a este artista? Si la respuesta es no, el fan puede enviar una única pregunta de bienvenida dentro de un cupo especial reducido, separado del cupo normal de preguntas. Si el artista responde, se invita al fan a seguirlo y pasa a ser un fan regular dentro del flujo ya existente.

Este cupo adicional le suma trabajo al artista, justo lo que el brief original se propuso proteger. No hay evidencia todavía de que un artista quiera destinar tiempo extra a un cupo de bienvenida distinto del normal.  [HIPÓTESIS]


### Fan fundador — momento exacto en el flujo

Se otorga cuando el fan visita el perfil de un artista que está por debajo de su umbral de seguidores. No es un logro por nivel de escucha acumulada: es un reconocimiento por descubrimiento temprano, entregado en el momento mismo del primer contacto o la primera visita.

Sigue sin definirse un número para “umbral de seguidores” — el mismo vacío que ya señalaba la sección 11.  [PENDIENTE DE VALIDACIÓN]


### Ventana de visibilidad justa — especificación

Cuando un artista publica un release, entra automáticamente a una ventana de 48 horas de visibilidad pareja frente a artistas grandes, dentro del módulo “En ventana” — mismo tratamiento sin importar el tamaño de su audiencia. Al cerrarse la ventana, el release pasa al descubrimiento normal por conexión activa.

Las 48 horas son una cifra de referencia tomada de la ventana de Bandcamp Friday (ver más abajo), no de datos propios de Looped.  [SUPUESTO DE DISEÑO]


### Tensión sin resolver: ¿esto sigue fuera del MVP?

La sección 11 dejó estas tres funcionalidades explícitamente fuera del MVP, para fase 2-3. Ahora ya existen como flujo completo y wireframes navegables, pero tener el diseño listo no es lo mismo que haberlo validado. El equipo debe decidir explícitamente si las adelanta al MVP porque ya están diseñadas, o si las mantiene en fase 2-3 para terminar de validar primero el mecanismo de cupos sin distraer el alcance. Este brief no toma esa decisión por el equipo.  [SUPUESTO DE DISEÑO — decisión pendiente del equipo]


### Brainstorming y referentes que respaldan estas decisiones

| Fuente | Qué valida |
|---|---|
| Bandcamp Friday | Que una ventana de visibilidad pareja, de tiempo fijo, es un mecanismo real y no solo una idea de diseño |
| Product Hunt | Que un ranking por el día (no por historial) puede convivir con creadores grandes y pequeños en la misma vitrina |
| Kickstarter (early backer) | Que un reconocimiento permanente por apoyo temprano —como Fan fundador— ya funciona en otro contexto |
| TikTok / Pinterest | Que el descubrimiento puede organizarse sin pedir una categoría o género como primer paso |
| LinkedIn / Cameo | Que un primer mensaje acotado y con expectativa clara —como el cupo de primer contacto— es un patrón ya aceptado |


### Validaciones nuevas que esto agrega

- ¿Los artistas aceptarían un cupo adicional de primer contacto, separado del normal, o lo sentirían como más carga en vez de menos?
- ¿48 horas es la duración adecuada para la ventana de visibilidad, o debería variar según el tipo de release?
¿La entrada de estas tres funcionalidades al MVP se decide antes o después del piloto del mecanismo de cupos? Sigue sin resolverse.  [PENDIENTE DE VALIDACIÓN]


## 13. BRIEF EN UNA SOLA FRASE


> **Looped es una plataforma de streaming musical para fans de 16 a 30 años que hoy no tienen forma estructurada de sentirse reconocidos por los artistas independientes que siguen, y lo resuelve integrando la música y la interacción en un mismo lugar mediante espacios de contacto limitados y configurables por el artista — a diferencia de la mensajería abierta e ilimitada de las redes sociales actuales.**