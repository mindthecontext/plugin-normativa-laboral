# Cambios · Normativa Laboral

<!-- Generado al derivar el paquete desde cambios.yaml. No editar a mano. -->

Qué cambia para quien usa este saber, versión por versión. Lo que corre de verdad el servicio lo dice su herramienta `ver_cambios`; esto es la copia del paquete.

## v0.36.0 · 2026-11-26

Las respuestas llevan ahora un aviso de licencia en lugar del aviso de uso interno: «Pronunciamientos publicados por la Dirección del Trabajo en www.dt.gob.cl. Licencia de reutilización con la Dirección del Trabajo en trámite.» La cobertura declara la licencia como en trámite. Sin cambios en los textos, los pronunciamientos ni la búsqueda.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.35.0 · 2026-11-26

Cada artículo dice ahora de dónde salió el texto de su norma: del XML de intercambio de la BCN, de la vista de impresión de su visor web (con la fecha en que se leyó) o, en el caso del DFL 5 de 1992, del PDF que exporta LeyChile. Antes todos los artículos mostraban la misma frase general, que hablaba del XML y del visor web aunque el DFL 5 sale del PDF. Si el artículo es una versión que rige más adelante, la fuente lo dice con su fecha; si es un artículo del XML corregido con el visor, también lo dice. Sin cambios en los textos, los pronunciamientos ni la búsqueda.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.34.0 · 2026-11-26

Suma el texto del DFL 5 de 1992 (publicado el 09-03-1993), el texto refundido de la ley de subvenciones que la Dirección del Trabajo cita en 32 pronunciamientos y que el saber no traía: 52 artículos más (34.549 en 790 normas). El visor de la BCN lo entregaba con las referencias marginales (a la izquierda del texto, como «-Art. 1 D.L. N° 3.476») mezcladas línea por línea con el texto, y por eso no se servía. Esta vez se leyó del PDF que exporta LeyChile: se separó la columna de texto de la de referencias por su posición en la página y se comprobó contra el visor, palabra por palabra, que no se pierde ninguna que no sea una referencia; los artículos 10, 11, 12, 13 y 17, que son los que la DT cita, están. La numeración es la de ese texto refundido, que la BCN registra reemplazado desde el 21-07-1996 (lo refundió el DFL 2 de 1996, que el saber ya trae, y a éste el DFL 2 de 1998, vigente): cada artículo avisa que no es el texto vigente. El «DFL 5 de 1992» y el «DFL 5 de 1993» llegan al mismo texto. Con eso el texto está disponible para 21.885 de las 22.381 citas (97,8 %; antes 97,6 %). La búsqueda y los pronunciamientos no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.33.0 (acierto en los diez primeros 49,5 %, MRR 0,223). Límites: el texto sale de un PDF que no tiene una segunda lectura con la que compararlo más allá del visor; los cuadros de valores de los artículos 9 y 12 quedan como un solo párrafo con sus filas seguidas; el texto trae tal cual algunas palabras pegadas que ya traía la BCN («reajustaráen», «losrequisitos»); y la Ley 18.620 y la 18.175 siguen sin texto.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.33.0 · 2026-11-25

Suma el texto de 10 normas más que la Dirección del Trabajo cita y que el saber todavía no traía (1.129 artículos más: 34.497 en 789 normas). Son las candidatas que la 0.32.0 no alcanzó a revisar; cada una se aceptó sólo si la ficha de la BCN coincide con el número y con el año que cita la DT y su materia es la del pronunciamiento que la cita: el DFL 3 de 2006 (texto refundido de la Ley de Propiedad Industrial, con el secreto industrial que la DT cita para las cláusulas de confidencialidad), el DFL 1 de 2017 (texto refundido de la Ley 20.640, de elecciones primarias, que la DT cita para el feriado de esas votaciones), el Decreto 977 de 1996 (Reglamento Sanitario de los Alimentos), el 943 de 2011 (reglamento del trabajo penitenciario), el 3 de 2015 (comités paritarios de faena portuaria), el 49 de 1999 (curso básico de seguridad de faenas portuarias), el 14 de 2023 (registro electrónico laboral), el 30 de 2018 (establecimientos rurales de desempeño difícil), el 502 de 1978 (Ley General de Cooperativas; la BCN lo registra modificado por el DFL 5 que lo reemplazó, que no está en este saber, y cada artículo lo avisa) y el Decreto 101 de 1918, que ordena las excepciones al descanso dominical y que la DT cita en 30 pronunciamientos. El Decreto 101 de 1918 no tiene artículos: se sirve por secciones, con las secciones I a VII como 1 a 7 y su introducción como 0, y la ubicación de cada una lo dice. Además, los ocho pronunciamientos que citan el «decreto 5» sin año junto a la Ley 21.308 (concurso interno de la atención primaria de salud) llegan ahora a su reglamento, el Decreto 5 de 2021, que el saber ya traía. Con eso el texto está disponible para 21.853 de las 22.382 citas (97,6 %; antes 97,3 %). La búsqueda y los pronunciamientos no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.32.0 (acierto en los diez primeros 49,5 %, MRR 0,223). Límites: el texto sale del visor web de la BCN y no tiene una segunda lectura con la que compararlo; del DFL 3 de 2006 faltan los artículos 53 Bis 1 a 53 Bis 5 (protección suplementaria), que el lector no distingue entre sí. Siguen sin texto las normas citadas sin año («decreto 3», «dfl 1»), las que comparten número y año con otros decretos, el DFL 5 de 1993 (la BCN lo entrega con dos columnas entrelazadas), las leyes 18.620, 18.175 y 18.892 y nueve decretos de un solo párrafo dispositivo sin artículos numerados.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.32.0 · 2026-11-25

Suma el texto de 74 decretos, decretos con fuerza de ley y decretos leyes que la Dirección del Trabajo cita y que el saber todavía no traía (53 decretos, 15 DFL y 6 decretos leyes; 2.880 artículos más: 33.368 en 779 normas). Hasta ahora se creía que la BCN no ubica un decreto por su número; sí lo hace en su búsqueda avanzada, por tipo, número y año de publicación. Cada uno se aceptó sólo si la ficha de la BCN coincide con el número y con el año (de promulgación o de publicación) que cita la DT y su materia es la del pronunciamiento que lo cita: el Decreto 324 de Salud (reglamento de la Ley 19.813, de la asignación de desarrollo y estímulo), el 98 de 1997 (reglamento del estatuto de capacitación), el 319 de 2007 (reglamento del art. 183-C del Código del Trabajo), el 101 de 2004 (trabajo a bordo de naves de pesca), el 212 de 1992 (transporte), el DFL 1 de 1993 (Ferrocarriles del Estado), el DL 2.859 (Gendarmería) y las prórrogas del estado de excepción de 2020, entre otros. Con eso, `ver_articulo` responde por 763 de las 1.103 normas que los pronunciamientos anclan y el texto está disponible para 21.780 de las 22.382 citas (97,3 %; antes 96,2 %). El mismo decreto citado con su año de promulgación, con el de publicación o sin año llega ahora a un solo texto (el «Decreto 324» sin año, el «de 2002» y el «de 2003»; el 101 de 2004, 2005 y 2006; el 319 de 2006 y 2007; el 586 de 1964 y 1965; el 789 de 1992 y 1993; y tres que ya estaban con otro año: el 352, el 390 y el 466). Cuatro están derogados (el 264 de 1991, el Reglamento de Extranjería de 1984, el 745 de 1992 y el DL 194) y se sirven con su fecha de derogación; cuatro son textos refundidos reemplazados por otro (el DFL 2 de 1989 de subvenciones, el DFL 341 de 1977 de zonas francas, el Decreto 252 de 1976 del estatuto de los médicos y el DFL 34 de 1931 pesquero) y cada artículo lo avisa. También se corrige la ubicación de 19 artículos transitorios que ya se servían (16 de la Ley de la Renta y 3 de la Ley 15.720), que quedaban bajo el título anterior en vez de «Disposiciones transitorias»; su texto no cambia. La búsqueda y los pronunciamientos no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.31.0 (acierto en los diez primeros 49,5 %, MRR 0,223). Límites: el texto sale del visor web de la BCN y no tiene una segunda lectura con la que compararlo. Se hallaron pero no se sirven el DFL 5 de 1993 (subvenciones: la BCN lo entrega con notas del margen mezcladas en el texto), los DFL 1 de 1982 y 4 de 2006 (Ley General de Servicios Eléctricos: sus artículos «71-1», «10-1»… no se distinguen del 71 y del 10) y nueve decretos de un solo párrafo dispositivo, sin artículos numerados (95 de 1995, 1.897 de 1965, 869 de 1998, 812 de 1979, 28 de 2012, 1.578 y 2.097 de 2020, y 50 y 56 de 2023). Siguen sin texto 340 normas citadas (602 citas, 2,7 %): decretos que la DT cita sin año, números con varios decretos del mismo año de los que no se pudo saber cuál cita la DT, y los que la BCN no tiene.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.31.0 · 2026-11-25

Suma el texto de 212 leyes que la Dirección del Trabajo cita en un solo pronunciamiento cada una y que el saber todavía no traía (5.123 artículos más: 30.488 en 705 normas). Con eso, `ver_articulo` responde por 689 de las 1.113 normas que los pronunciamientos anclan, y el texto está disponible para 21.544 de las 22.384 citas (96,2 %; antes 95,3 %). Entre las nuevas hay leyes grandes (la 20.780, de reforma tributaria, con 42 artículos propios; la 21.442, nueva ley de copropiedad; la 18.216, de penas sustitutivas) y cinco derogadas, que se sirven porque la DT las cita y avisan la fecha de derogación (las leyes 10.518, 15.020 y 16.455, de 1981 y 1984; la 19.366, de 2005; la 19.303, de 2025). Cuando una ley trae dentro, entre comillas, el texto de otra o repite números de artículo, se omite lo que choca: en la Ley 20.190 se omiten la Ley de prenda sin desplazamiento y la agencia de créditos o garantías que inserta; en la 18.216, los artículos 10 a 12 derogados que la BCN conserva con el rótulo «DEROGADO»; en la 21.442, el artículo segundo, que modifica otra ley; y en las leyes 11.595 y 16.781, los artículos que reinician la numeración se sirven como transitorios. La búsqueda y los pronunciamientos no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.30.0 (acierto en los diez primeros 49,5 %, MRR 0,223). Límites: el texto sale del visor web de la BCN (el servicio XML dejó de responder) y no tiene una segunda lectura con la que compararlo, a diferencia del Código del Trabajo, el Código Civil y la Constitución. Cuatro leyes citadas una vez no están, porque la BCN no las entrega por su número (la 7.918, la 10.069, la 10.304 y la 21.903), y siguen sin texto 424 normas citadas, sobre todo decretos y DFL, que la BCN no ubica por número y año (840 citas, 3,8 %).

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.30.0 · 2026-11-24

Corrige un artículo más del Código Civil y comprueba contra el visor web de la BCN casi todo lo que antes quedaba sin comprobar. LO ENCONTRADO: la comparación de la 0.27.0 sólo cubría los artículos con número simple, y al revisar cuánto cubría de verdad resultó que el archivo contaba como «cotejados» todos los artículos de cada norma, también los que no se pudieron comparar (unos 290 de 4.066). Ahora la comparación llega a los artículos transitorios (el Código del Trabajo trae 23, y sus números se repiten con los del cuerpo del Código), a los de dos letras (183-AA a 183-AE), a los de número con guion (Código Civil, 548-1 y 1792-1 a 1792-27) y al Código Civil entero (el visor trae después del Código otras leyes con los mismos «Artículo 1», «Artículo 2»; se cortan donde el Código termina). Pasa de 3.770 a 4.054 artículos comparados de 4.066 (99,7 %); los 12 que quedan son 9 artículos completados desde otra fuente y 3 cuyo rótulo no calza con ninguno del visor. Resultado: todo lo nuevo coincide con el visor salvo un artículo, el 6 del Código Civil, que traía «Eldecreto supremo promulgatorio…» con las palabras pegadas y sin el salto de párrafo. Ahora `ver_articulo` sirve el texto del visor, lo avisa y conserva el original del XML en `texto_bcn`. Son 52 los artículos corregidos con el visor (14 del Código del Trabajo, 13 del Código Civil y 25 de la Constitución). La búsqueda y los pronunciamientos no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.29.0 (acierto en los diez primeros 49,5 %, MRR 0,223). Límites: sólo se comparan las normas que se leyeron del visor para cotejar (el Código del Trabajo, el Código Civil, la Constitución y diez leyes); el resto del articulado sale tal como lo entrega la BCN, y un texto que sí aparece tal cual en el visor no se toca.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.29.0 · 2026-11-24

El saber trae el texto de 92 leyes más que la DT cita en dos pronunciamientos cada una: pasa de 23.455 a 25.365 artículos y de 401 a 493 normas. 169 pronunciamientos citan alguna de ellas, pero casi todos las nombran sin decir artículo: las citas con artículo que ahora se resuelven contra el texto suben de 31.118 a 31.182. LO ENCONTRADO: tres de las 92 están derogadas (las leyes 3.321, de 1917, 18.602 y 18.893) y cada artículo lo avisa. Tres traen la marca «refundida por» en la ficha de la BCN. La Ley 19.418 (juntas de vecinos) se sirve de su texto refundido, el Decreto 58 de 1997, y no de la ley: el refundido renumera (42 artículos tienen otro texto en el mismo número) y la DT cita su numeración (el artículo 32 que cita un ordinario de 2022 sobre la Comisión Fiscalizadora de Finanzas es el del refundido, el del balance anual, y no el de la ley, que trata de la disolución); la evidencia es una sola cita con artículo, y se dice. Las leyes 15.840 (Obras Públicas, refundida por el DFL 850 de 1998) y 3.321 sólo avisan, porque su refundido no está en el saber o ya está derogada. En las leyes 19.937, 20.416 y 18.840 la lectura traía dentro otros textos con sus propios «artículo 1», «artículo 2»: no se sirven, para que no pisen los números de la ley. La búsqueda y los pronunciamientos no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.28.0 (acierto en los diez primeros 49,5 %, MRR 0,223). Límites: la Ley 10.070 no está (la BCN no la entrega por su número); siguen sin texto las leyes citadas una sola vez, los decretos y DFL citados en dos pronunciamientos o menos y las normas que ya se declaraban fuera; las leyes que modifican a otras traen sus propios artículos, y la DT a veces cita el artículo de la ley modificada, de modo que algunas citas de estas 92 leyes siguen sin resolverse (por ejemplo la Ley 20.660, que tiene un solo artículo y modifica la Ley 19.419, y de la que la DT cita los artículos 10 y 11).

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.28.0 · 2026-11-24

Avisa cuándo una ley está refundida y trae el artículo del mismo número en el refundido. LO ENCONTRADO: un texto refundido renumera los artículos, y la Dirección del Trabajo cita unas veces la numeración de la ley y otras la del refundido. Se leyó la ficha de la BCN de los 390 textos que el saber sirve (290 leyes y 100 de otra clase) y 16 normas traen la marca «refundida por»: las leyes 18.700, 18.469, 18.933, 18.962, 20.370, 20.640, 18.290, 18.556, 18.603, 10.383 y 16.618, los decretos leyes 2.763, 1.446 y 3.476 y los DFL 1 de 1994 y 2 de 1996. Siete de ellas ya decían que su texto está sustituido; las otras nueve no avisaban nada (la Ley 20.370 sólo lo dice en su nombre). El caso con más peso es la Ley 18.700 (votaciones populares), citada en 66 citas de pronunciamientos: el feriado del día de elecciones es el artículo 169 de la ley y el 180 de su DFL 2 de 2017, y el permiso del trabajador para votar es el 155 de la ley y el 165 del refundido. Los pronunciamientos de 2020 en adelante sobre el voto citan los números del refundido; los anteriores, y varios de 2018 a 2024 sobre el feriado, los de la ley; así que el artículo 165 de la ley (sobre las municipalidades) figuraba con nueve citas de pronunciamientos que no tratan de él. Ahora `ver_articulo` lo avisa («la BCN anota que esta norma fue REFUNDIDA por…»), devuelve `refundida_por` y, cuando el refundido también está en el saber (Ley 18.700 con el DFL 2 de 2017; el DL 2.763 y las leyes 18.469 y 18.933 con el DFL 1 de 2005), el artículo del mismo número en `en_el_refundido`; y en el refundido, `citas_a_la_ley_original` trae los pronunciamientos que citan ese número de la ley. NO se movió ninguna cita: no hay forma segura de saber, para cada pronunciamiento, cuál de las dos numeraciones quiso decir, y se deja la lectura a quien consulta. La búsqueda y los pronunciamientos no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.27.0 (acierto en los diez primeros 49,5 %, MRR 0,223). Límites: la BCN anota la relación cuando la tiene registrada, así que una norma sin la marca puede igual tener un texto refundido; los refundidos de las leyes 18.962 (DFL 1 de 2006), 20.640, 18.290, 18.556, 18.603 y 10.383 no están en el saber.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.27.0 · 2026-11-24

Corrige 51 artículos del Código del Trabajo, el Código Civil y la Constitución cuyo texto traía un defecto que venía del XML de la BCN. LO ENCONTRADO: al cotejar lo que el saber sirve con el visor web oficial de la BCN, 51 artículos no coincidían: 14 del Código del Trabajo, 12 del Código Civil y 25 de la Constitución. Los defectos eran de cuatro clases: un número perdido (el art. 509 del Código del Trabajo decía «las penas previstas en el artículo del Código Penal» y es el 202); palabras perdidas (al art. 17 de la Constitución le faltaba «cumplida la condena», y el 222 del Código Civil dejaba «us» donde va «Los hijos deben respeto y obediencia a sus padres»); notas al margen metidas dentro del texto («CPR ART 1 D.O. 24.10.1980», «Ley N° 20.050 Art. 1…»); y palabras partidas o pegadas con un espacio («mu lta», «situad as», «deldesaparecido») o un carácter dañado («Reuni�nes», art. 369). Ahora `ver_articulo` sirve el texto del visor, lo avisa («el XML de la BCN traía un defecto en este artículo») y `incluir_original` devuelve el del XML. Se cotejaron además las leyes 16.744, 18.883, 19.296, 19.378, 19.464, 21.109, 21.561, 21.643, 21.645 y 21.755: ninguna tenía defectos. El cotejo cubre los artículos que el visor rotula sin ambigüedad (los de número simple y buena parte de los que llevan letra) y no los transitorios: otros artículos de esas tres normas pueden traer defectos que no se detectaron. Además «DFL 1-19.653» se lee ahora como el refundido de la Ley 18.575. Los pronunciamientos de la DT y las demás herramientas no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.26.0 (acierto en los diez primeros 49,5 %, MRR 0,223).

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.26.0 · 2026-11-24

El saber sirve por adelantado lo que la BCN ya publicó y rige después, y trae 19 normas que pesan para quien emplea aunque la DT casi no las cite. LO NUEVO: cuando una ley con vigencia diferida modifica una norma, la BCN publica la versión que rige desde esa fecha. `ver_articulo` la sirve ahora según la fecha de la consulta: antes de esa fecha avisa «ESTE ARTÍCULO CAMBIA» y trae el texto nuevo en `cambios_ya_publicados`; desde esa fecha sirve el nuevo y deja el anterior en `texto_anterior`; un artículo que la modificación agrega se sirve marcado «AÚN NO RIGE». Se leyeron 13 versiones de 11 normas (154 artículos que cambian o aparecen): la Ley 19.628 reescrita por la 21.719 desde el 01-12-2026 (84 artículos), el DL 3.500 de la reforma de pensiones desde el 01-04-2027 (46), el Código del Trabajo (los seis artículos 152 quinquies J a Ñ del trabajador adulto mayor desde el 01-06-2027 y el 415, de los juzgados de letras del trabajo, desde el 15-03-2027 y el 15-09-2027), el DL 824 de la renta desde el 01-01-2027 (8), la Ley 19.880 (su art. 53, que ya rige desde el 01-11-2026) y otras seis normas con uno o dos artículos. `listar_cobertura` trae el detalle en `cambios_ya_publicados`. Si la BCN anuncia una versión que el saber no leyó, el aviso de cada artículo lo dice. Entran además la reforma de pensiones (Ley 21.735), la ley de datos personales (21.719), el registro de deudores de pensiones de alimentos (21.389 y su reglamento) y la Ley 14.908, la Ley SANNA (21.063), la 21.133 (cotización de los trabajadores a honorarios), la 21.690, la 21.544, la ley y el reglamento de seguridad privada (21.659 y el Decreto 209 de 2024), los reglamentos de la Ley 16.744 (decretos 101, 109 y 67) y del teletrabajo (Decreto 18 de 2020) y los convenios 111, 155, 187 y 190 de la OIT. Pasa de 22.597 a 23.455 artículos, en 401 normas; las citas de la DT enlazadas con un artículo, de 31.111 a 31.118. Los pronunciamientos de la DT y las demás herramientas no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.25.0 (acierto en los diez primeros 49,5 %, MRR 0,223).

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.25.0 · 2026-11-23

El saber trae el texto de 98 normas más que la DT cita en tres o cuatro pronunciamientos: pasa de 19.693 a 22.597 artículos y de 284 a 382 normas. 291 pronunciamientos citan alguna de ellas, y las citas de la DT que encuentran su artículo pasan de 30.938 a 31.111. Entran el Convenio 189 de la OIT (trabajo decente para las trabajadoras y los trabajadores domésticos), la Convención Interamericana contra la discriminación de las personas con discapacidad (Decreto 99 de 2002), los reglamentos de farmacias (Decreto 466 de 1984), del peso máximo de carga (Decreto 63 de 2005) y del transporte de valores (Decreto 1.814 de 2014), el DFL 1.046 de 1977 (trabajos extraordinarios en el sector público), el DL 2.757 (asociaciones gremiales) y 86 leyes, entre ellas la de semana corrida de 1948 (8.961) y la de 2012 (20.613), violencia intrafamiliar (20.066), propiedad intelectual (17.336), probidad (20.880), lobby (20.730), licencias médicas (20.585), lactancia materna (21.155), plataformas digitales (21.431), teletrabajo de embarazadas (21.260 y 21.498), peso de las cargas (20.949), seguridad ante emergencias (21.012), permiso para mamografía y próstata (20.769), propinas (20.729), notarías (20.510 y 19.945), jornada escolar completa (19.532), Ley de Menores (16.618), Ley del Deporte, varias leyes orgánicas y de presupuestos, y cinco reajustes del ingreso mínimo. Entran marcados como DEROGADOS el DL 2.758 (negociación colectiva de 1979), el DL 1.446 (Estatuto de Capacitación anterior), el DL 2.465 (Sename), la Ley 19.325 (violencia intrafamiliar de 1994) y la Ley 19.537 (copropiedad). ALIAS: el «Decreto 2421» es la Ley 10.336 en su texto refundido; el «DFL 29» sin año o «de 2005», el Estatuto Administrativo; los «Decreto 44», «Decreto 93» y «Decreto 48» sin año, el de comités paritarios de 2024, el de vigilantes de 1985 y el reglamento portuario; y el «Decreto 90 de 2000», el «Decreto 594 de 2000» y el «Decreto 1094 de 1975» llegan a su norma (cambian las anclas de 36 pronunciamientos). El lector de convenios entiende ahora artículos en mayúsculas y en números romanos. Lo que queda sin texto son, sobre todo, normas que la DT cita en uno o dos pronunciamientos. Ningún artículo que ya estaba cambia, y el texto de los pronunciamientos tampoco: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.24.0 (acierto en los diez primeros 49,5 %, MRR 0,223), pregunta por pregunta, como se predijo antes de medir.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.24.0 · 2026-11-23

El saber trae el texto de 73 normas más que la DT cita en cinco o más pronunciamientos: pasa de 15.575 a 19.693 artículos y de 211 a 284 normas. 411 pronunciamientos citan alguna de ellas, y las citas de la DT que encuentran su artículo pasan de 30.682 a 30.938. Entran el Código Tributario; la Ley de Migración y Extranjería (21.325) y el DL 1.094 que reemplazó (derogado desde el 12-02-2022); la Convención de la ONU sobre los Derechos de las Personas con Discapacidad (Decreto 201 de 2008); el reglamento general de la Ley 19.378 (Decreto 2.296 de 1995) y el de la Ley 20.157 (Decreto 47 de 2007); el calendario escolar (Decreto 289 de 2010), el decreto de necesidades educativas especiales (170 de 2009), el de fines educativos (582 de 2015) y el de la remuneración total mínima docente (14 de 2021); el de dotaciones de seguridad de las naves (31 de 1999); el estatuto de la Superintendencia de AFP (DFL 101 de 1980), el DFL 243 de 1953 y los DL 450, 1.953 y 2.950; y 51 leyes, entre ellas la de acoso sexual (20.005), la Ley Bustos (19.631), la de igualdad de remuneraciones (20.348), la de identidad de género (21.120), la Ley TEA (21.545), la de obra o faena (21.122), la de peso máximo de carga (20.001), la del derecho a amamantar (20.166), la de muerte gestacional (21.371), la del Convenio sobre el Trabajo Marítimo (21.376), la de artes y espectáculos (19.889), la de Alta Dirección Pública (19.882), las de sociedades anónimas y mercado de valores, la del Ministerio Público y siete reajustes del sector público. Entran también, marcados como DEROGADOS, el Código del Trabajo de 1931 (DFL 178, hasta el 06-07-1987), el Estatuto Administrativo de 1960 (DFL 338, hasta el 23-09-1989) y el Decreto 37 de 2021 (registro del término de la relación laboral, hasta el 08-06-2023). Tres textos que la DT cita con su propia numeración se sirven aunque otro refundido los reemplazó, y cada artículo lo advierte («NO ES EL TEXTO VIGENTE»): el DL 2.763 y la Ley 18.933 (refundidos en el DFL 1 de 2005, de Salud) y la Ley de Tránsito (18.290). ALIAS: el «DFL 725» es el Código Sanitario; el «Decreto 2222 de 1978», la Ley de Navegación; los decretos 289, 170 y 2.296 sin año llegan a su norma, y el «DFL 1 de 2006» junto al Código Sanitario o las leyes de salud se lee como el DFL 1 de 2005 de Salud, que se publicó en 2006 (cambian las anclas de 47 pronunciamientos). Además el lector de la BCN dejó de tomar por encabezado de transitorios un título que sólo dice «transitoria» (el «Párrafo II Permanencia transitoria» de la Ley de Migración volvía transitorios todos sus artículos siguientes); ningún artículo que ya estaba cambia por eso. Quedan sin texto la Ley 18.892 de Pesca (la BCN trae el texto original con numeración repetida) y las normas que la DT cita en menos de cinco pronunciamientos. El texto de los pronunciamientos no cambia: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.23.0 (acierto en los diez primeros 49,5 %, MRR 0,223), pregunta por pregunta, como se predijo antes de medir.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.23.0 · 2026-11-23

El saber trae el texto de 79 normas más que la DT cita en ocho o más pronunciamientos: pasa de 11.889 a 15.575 artículos y de 132 a 211 normas. 712 pronunciamientos citan alguna de ellas, y las citas de la DT que encuentran su artículo pasan de 30.166 a 30.682. Entran el reglamento de la investigación del acoso y la violencia en el trabajo de la Ley Karin (Decreto 21 de 2024), el de los sistemas excepcionales de jornada (Decreto 48 de 2023), el del art. 66 bis de la Ley 16.744 sobre seguridad en obras con subcontratistas (Decreto 76 de 2006), los de trabajadores agrícolas (Decreto 45 de 1986), trabajo a bordo de naves (Decreto 26 de 1987), función docente (Decreto 352 de 2003) y vigilantes privados (decretos 1.773 de 1994 y 93 de 1985), la alerta sanitaria del Covid-19 (Decreto 4 de 2020), el DFL 150 de 1981 (asignación familiar y subsidio de cesantía), el DFL 1 de 2005 de Salud (Fonasa, isapres y licencias), la Ley sobre Impuesto a la Renta (DL 824), los DL 670, 1.263, 1.608, 3.476 y 3.551, siete convenios de la OIT promulgados por el Decreto 1.907 de 1998 (entre ellos el 156, sobre trabajadores con responsabilidades familiares, y el 103, de protección de la maternidad) y 48 leyes, entre ellas la de transparencia (20.285), la de reorganización y liquidación de empresas (20.720), la antidiscriminación (20.609), la de derechos de los pacientes (20.584), la reforma previsional (20.255), la de adopción (19.620), la de la EIRL (19.857), las de teleoperadores, tripulantes de vuelo y casa particular, el postnatal parental y once reajustes del sector público. Cuatro textos que la DT cita con su propia numeración se sirven aunque otro refundido los reemplazó, y cada artículo lo advierte («NO ES EL TEXTO VIGENTE»): el Código del Trabajo de 1994 (DFL 1 de 1994), la ley de subvenciones de 1996 (DFL 2 de 1996), la LOCE (Ley 18.962) y la Ley 18.469. El Decreto 214 de 1965 (barcos pesqueros) entra marcado como DEROGADO desde el 10-05-2005. ALIAS: el «Decreto 48 de 1986» se lee en su texto refundido, el Decreto 90 de 1999; las citas sin año a los decretos 45, 76 y 352, y las que usan el año de publicación (Decreto 453 de 1992, 64 de 2018, 48 de 2024, DFL 150 de 1982), llegan a su norma, y el DFL 29 de 2004 al Estatuto Administrativo. «DFL 1 de 2006» se lee como la Ley de Municipalidades cuando el pronunciamiento cita leyes de la Administración, y el «DFL 1 de 2005» como el de Educación (que no tiene texto) cuando cita leyes de educación (cambian las anclas de 107 pronunciamientos). Siguen sin texto el Convenio 111 de la OIT, la Ley 18.620 (Código del Trabajo de 1987), el DFL 5 de 1993, el DFL 1 de 2005 de Educación, la Ley de Quiebras (la BCN sólo trae notas) y el Decreto 101 de 1918 (no tiene artículos). Ningún artículo que ya estaba cambia, y el texto de los pronunciamientos tampoco: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.22.1 (acierto en los diez primeros 49,5 %, MRR 0,223), pregunta por pregunta, como se predijo antes de medir.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.22.1 · 2026-11-23

Corrige un dato de la procedencia de los artículos: la fuente que declaran `ver_articulo` y el manifiesto decía que 74 normas se leyeron del visor web de la BCN, y desde la 0.22.0 son 118. Ahora la cifra se cuenta desde los datos al construirlos y no se escribe a mano. El texto de los artículos, los pronunciamientos de la DT y la búsqueda no cambian.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.22.0 · 2026-11-23

El saber trae el texto de 44 normas más que la DT cita y no tenía: pasa de 8.536 a 11.889 artículos y de 88 a 132 normas. 765 pronunciamientos citan alguna de ellas, y las citas de la DT que encuentran su artículo pasan de 29.646 a 30.166. Entran el Código Penal, el Código de Procedimiento Civil, la Ley de Navegación (DL 2.222), el DL 3.501 (cotizaciones previsionales), los convenios 131, 135 y 140 de la OIT (del Decreto 649 de 2000; el 135 protege a los representantes de los trabajadores en la empresa y lo citan 42 pronunciamientos), la Ley 21.327 de modernización de la DT, la Ley General de Educación en su texto original (Ley 20.370) y en el refundido (DFL 2 de 2009), el DFL 2 de 2017 que refunde la Ley 18.700 (permisos para votar y feriado electoral), la Ley 15.076 en su texto refundido (DFL 1 de 2001, de Salud), los reglamentos de la inclusión laboral (Decreto 64 de 2017), del retiro en atención primaria (Decreto 26 de 2016) y en educación (Decreto 35 de 2017), el del trabajo portuario (Decreto 90 de 1999) y el de prevención de riesgos de 1969 (Decreto 40), que entra marcado como DEROGADO desde el 01-02-2025, y 27 leyes más (entre ellas la 20.845 de inclusión escolar, la 20.248 de subvención preferencial, la 19.886 de compras públicas, la 17.322 de cobranza de cotizaciones, la 20.830 de unión civil, la 20.760 de multiplicidad de razones sociales y la 19.010 de terminación del contrato de 1990). ALIAS: las citas a «Decreto 40» y «Decreto 594» sin año llegan al de 1969 y al de 1999; «Decreto 26», «Decreto 64» y «DFL 1 de 2001» sin año se resuelven mirando qué otras normas cita el mismo pronunciamiento, porque la DT usa cada número para dos decretos distintos (cambian las anclas de 90 pronunciamientos). Siguen sin texto el Convenio 111 de la OIT (la BCN no publica su texto), el DFL 5 de 1993, el DFL 1 de 2005 y el Decreto 101 de 1918. Ningún artículo que ya estaba cambia, y el texto de los pronunciamientos tampoco: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.21.0 (acierto en los diez primeros 49,5 %, MRR 0,223), como se predijo antes de medir; sólo cambia, a mejor, el nombre con que se muestran dos anclas.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.21.0 · 2026-11-23

Corrige la lectura de los artículos de las normas: aparecen 138 artículos que el saber tenía en sus archivos pero no servía, y pasa de 8.398 a 8.536 artículos. Las citas de la DT que enlaza con un artículo pasan de 29.572 a 29.646. LO QUE FALTABA: los artículos transitorios nombrados con un ordinal compuesto («decimotercero», «trigésimo segundo», «sexagésimo tercero») se tomaban por títulos y se perdían; eran 58 de la Ley 21.040 (Sistema de Educación Pública), 51 de la Ley 20.903 (Sistema de Desarrollo Profesional Docente), 8 de la 20.501 y 4 de la 20.529. Quien pedía, por ejemplo, el 33 transitorio de la 20.903 recibía «no está», aunque la DT lo cita. También se perdían el artículo transitorio sin número de nueve normas (entre ellas las leyes 19.504, 19.799, 20.281 y 20.919, el Decreto 453 y el Código Sanitario), que ahora se pide como «único» transitorio, y el «Artículo final» de las leyes 18.575, 18.700 y 18.834. En el Decreto 1.889 (carrera funcionaria de la atención primaria) faltaban los artículos 18, 22, 26, 32 y 58, que venían pegados al título de su párrafo; el 26 lo citan 19 pronunciamientos. Además, 62 artículos de ese decreto que ya estaban (del 19 al 84) y sus tres transitorios traen ahora el título y el párrafo en que están. Ningún artículo que ya estaba cambia de texto, y los pronunciamientos de la DT no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.20.0 (acierto en los diez primeros 49,5 %, MRR 0,223), como se predijo antes de medir.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.20.0 · 2026-11-23

El saber trae el texto de 15 normas más que la DT cita y corrige un error de numeración: pasa de 7.545 a 8.398 artículos, en 88 normas, y las citas de la DT que enlaza con un artículo pasan de 29.383 a 29.572. LA CORRECCIÓN: la Ley 10.336 (organización y atribuciones de la Contraloría) se servía en el texto de la ley original, y la DT cita el texto refundido (Decreto 2421 de 1964, de Hacienda). El artículo más citado, el 6 («Corresponderá exclusivamente al Contralor informar…», 24 pronunciamientos), es otro en la ley original; medido contra los resúmenes de los pronunciamientos que citan cada artículo, el refundido coincide casi el doble que la ley (0,14 contra 0,075). Ahora sale del refundido. La Ley 18.700 queda en el texto de la ley y no en su refundido (DFL 2 de 2017) porque la DT mezcla las dos numeraciones (el art. 169, del feriado de las elecciones, es el de la ley; el 165, de los permisos para votar, el del DFL 2): compara con el texto antes de citar. Entran el Código Sanitario (DFL 725 de 1967), el Decreto 594 de 1999 (condiciones sanitarias y ambientales en los lugares de trabajo), el Decreto 104 de 2020 (estado de catástrofe por el Covid-19), los convenios 87, 98, 105, 138 y 151 de la OIT (del texto que publican los decretos 227 de 1999 y 1539 de 2000), la Ley 20.123 (subcontratación), la 20.422 (discapacidad), la 20.529 (aseguramiento de la calidad de la educación), la 21.247, la 20.313, la 16.395 (Superintendencia de Seguridad Social) y la 18.593 (tribunales electorales regionales). Además el lector entiende ahora letras en minúscula («Artículo 109 a.-»), las subdivisiones con punto («110 a.1», que se anexan al artículo de arriba) y las repeticiones latinas largas («105 undecies», «105 terdecies»), que antes se confundían con otro artículo. Los convenios 111 y 135 de la OIT, el Decreto 26 de 2016, el Decreto 64 de 2017 y el DFL 5 de 1993 siguen sin texto. Los pronunciamientos de la DT y las demás herramientas no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.19.0 (acierto en los diez primeros 49,5 %, MRR 0,223), como se predijo antes de medir.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.19.0 · 2026-11-23

El saber trae el texto de 30 normas más que la DT cita y corrige un error de la 0.18.0: pasa de 5.793 a 7.545 artículos, en 73 normas, y las citas de la DT que enlaza con un artículo pasan de 28.014 a 29.383. LA CORRECCIÓN: la 0.18.0 trajo la Ley 18.575 (bases de la Administración del Estado) en el texto de la ley original, y la DT cita la numeración del texto refundido (DFL 1/19.653, de 2001). Se comprobó con tres artículos: la probidad («Contravienen especialmente…») es el art. 62 del refundido y el 64 en la ley original, y quien pedía el 62 recibía otro texto. Ahora sale del refundido, igual que las dos que entran en esta versión con el mismo problema: la Ley 18.695 de Municipalidades (DFL 1 de 2006; «El alcalde es la máxima autoridad» es el art. 56 y en la ley original el 47) y el Estatuto Administrativo, Ley 18.834 (DFL 29 de 2004; «Serán obligaciones de cada funcionario» es el art. 61 y en la ley original el 55). Entran además el DL 3.500 (sistema de pensiones), el DL 249 (escala única de sueldos), el DFL 44 de 1978 (subsidios por incapacidad laboral), el Decreto 3 de 1984 (licencias médicas), el Decreto 453 de 1991 (reglamento del Estatuto Docente), el Decreto 969 de 1933, el DFL 1-3.063 y 19 leyes: las de educación y atención primaria (20.501, 20.822, 20.919, 21.152, 19.813, 20.804, 20.976, 20.157, 20.250, 21.040, 19.504, 19.715 y 20.305), la 20.281 (salarios base), la 20.918 (turismo), la 21.232 y la 21.226 (de la crisis del Covid-19), la 19.628 (vida privada) y la 19.069 (organizaciones sindicales, de 1991). El DL 2.200 (contrato de trabajo de 1978) y el DL 3.607 (vigilantes privados) entran marcados como DEROGADOS, desde el 06-07-1987 y el 28-11-2025, según la ficha de la BCN. Además el lector de artículos entiende ahora «Art. 2.o» y el título pegado al primer artículo, y con eso aparecieron seis artículos del Decreto 1.889 y el art. 153 A de la Ley 18.700 que faltaban; las citas «DFL 1-3.063» con y sin punto de miles son una sola norma, y «Decreto 453» y «Decreto 969» sin año llegan a los de 1991 y 1933. Se leyeron del visor web de la BCN. Siguen sin texto los convenios 87, 98, 135 y 151 de la OIT, la Ley 20.123, el Decreto 26 de 2016, el DFL 5 de 1993 y otras que la DT cita menos. Los pronunciamientos de la DT y las demás herramientas no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.18.0 (acierto en los diez primeros 49,5 %, MRR 0,223), como se predijo antes de medir.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.18.0 · 2026-11-23

El saber trae el texto de 20 leyes más que la DT cita, cada una en 45 o más pronunciamientos: pasa de 4.835 a 5.793 artículos, en 43 normas. Son la Ley 20.940 (modernización de las relaciones laborales, la más citada sin texto: 317 pronunciamientos), la 19.759 (reforma laboral de 2001), la 20.823 (jornada) y la 21.220 (trabajo a distancia); la 21.227 (acceso excepcional al seguro de cesantía), la 21.342 (protocolo de seguridad sanitaria laboral), la 21.409 (descanso reparatorio) y la 21.015 (inclusión laboral de personas con discapacidad); las de educación 20.158, 20.903 (carrera docente), 19.410, 19.933 y 19.648; la 18.833 (cajas de compensación), la 19.518 (capacitación y empleo), la 19.799 (firma electrónica), la 19.973 (feriados), la 18.700 (votaciones populares), la 18.575 (bases generales de la Administración del Estado) y la 10.336 (Contraloría). Las citas de la DT que el saber enlaza con un artículo pasan de 26.837 a 28.014. Se leyeron del visor web de la BCN porque su servicio de descarga XML dejó de responder. Tres límites: las leyes que modifican otras (20.940, 19.759, 19.410, 20.903, 21.220) traen sus propios artículos, no el texto resultante, que está en la ley modificada cuando el saber la trae (el Código del Trabajo, el Estatuto Docente); la BCN entrega la Ley 10.336 como versión única fechada en 1952 y sin anotaciones de cambios, así que para saber si un artículo de esa ley sigue vigente hay que verificarlo en Ley Chile (cada artículo dice su fecha de versión); y siguen sin texto el DL 3.500, el DL 2.200, los convenios 87, 98 y 151 de la OIT, la Ley 20.123 y otras normas que la DT cita menos. Los pronunciamientos de la DT y las demás herramientas no cambian: lo medido, sin agentes, sobre las preguntas de prueba, es idéntico a la 0.17.0 (acierto en los diez primeros 49,5 %, MRR 0,223), como se predijo antes de medir. Y dos avisos dejan de decir algo que no sabían: cuando la DT cita un artículo con el nombre de una ley que modifica otras y ese artículo no está entre los de la ley (por ejemplo «Ley 20.903, artículo 33 transitorio»), `buscar_por_ancla` ya no afirma que el texto dejó de regir y remite a la ley modificada; y el aviso de un destino que no está en el corpus ya no dice que el catálogo parte en 1997 (desde la 0.17.0 trae 1990, 1995 y 1996; faltan 1991 a 1994 y lo anterior a 1990).

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.17.0 · 2026-11-23

El saber trae más de lo que la DT ha publicado y más de la ley que sus pronunciamientos citan. Pasa de 10.738 a 12.324 pronunciamientos. Se suman: 742 dictámenes de 1990, 1995 y 1996 (la cosecha anterior empezaba en 1997; el sitio de la DT no lista nada de 1991 a 1994 ni anterior a 1990); 753 ordinarios, casi todos de 2013 y 2014 (también de 2012 y 2015), que están en el sitio pero ningún listado por año trae, porque no existe listado de Ordinarios anterior a 2016: se hallaron recorriendo los números de documento entre 123.000 y 127.000; 61 ordinarios de septiembre a noviembre de 2026; y las 3 circulares, 9 órdenes de servicio y 18 resoluciones que el sitio expone por tipo (la DT publica ahí sólo 8 circulares y 12 órdenes de servicio, y ya están todas; la serie completa no está publicada). Las resoluciones son un tipo nuevo. Los cuerpos en PDF se leen por OCR, como antes: 764 más, de los cuales 21 no se sirven porque el portal les adjunta el PDF de otro documento (ya son 43 en total). Con esto, 2013 pasa de 63 a 490 documentos, 2014 de 88 a 332 y 1995 y 1996 de casi ninguno a 340 y 348; y un dictamen que antes aparecía como «no está en el corpus» porque era de 1995 (el 4551/222) ahora se enlaza. Además trae el texto vigente de nueve normas que la DT cita mucho y el saber no tenía (696 artículos), leído del visor web de la BCN porque su servicio de descarga XML dejó de responder: el Estatuto Docente en su texto refundido (el DFL 1 de 1996, que es la numeración que citan los dictámenes), el DFL 2 de 1967 (ley orgánica de la DT), la Ley 19.728 del seguro de cesantía, el DFL 2 de 1998 de subvenciones, el DL 3.166, la Ley 21.530 y los decretos 1.889 de 1995 (carrera funcionaria de atención primaria) y 44 de 2024 (gestión preventiva de riesgos laborales). También el Decreto 54 de 1969 (comités paritarios), que aparece marcado como DEROGADO desde el 01-02-2025, porque el Decreto 44 lo derogó y el visor no lo marca. Las citas que usan otro nombre para la misma norma («DFL 1 de 1996» o «Ley 19.070», «Decreto 1.889» o «de 1995», el Decreto 44 «de 2023», año de su promulgación) llegan ahora al mismo lugar, y las citas de la DT que el saber resuelve contra un artículo de la ley pasan de 20.314 a 26.837. Lo medido, sin agentes, sobre las preguntas de prueba: el acierto en los diez primeros resultados queda igual (49,5 %) y el orden baja algo (el puntaje MRR pasa de 0,235 a 0,223: un poco más del punto que se había fijado aceptar, y 1,02 puntos si se comparan sólo las 93 preguntas de antes): con más documentos compitiendo, 12 preguntas bajan uno o dos lugares y 2 suben uno; ninguna sale de los diez primeros. Un dictamen de 1996 esperado por una de esas preguntas aparece ahora en el tercer lugar. Lo que sigue sin estar: los dictámenes de 1991 a 1994 y los anteriores a 1990, lo publicado después del 22-11-2026, los ordinarios ocultos que pudiera haber fuera de los números recorridos (unas 380 sondas al azar no encontraron otros), el texto de otras normas que la DT cita menos (la Ley 20.940, el DL 3.500, la 20.123) y la historia de los artículos. Como el cálculo de nombres públicos de la anonimización depende de todo el corpus, 41 documentos anteriores cambiaron de texto: por ejemplo, la firma del Director Nacional del Trabajo, que aparece en decenas de documentos, ahora se conserva. El servicio sigue siendo de uso interno: la DT no publica licencia de reutilización.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.11 · 2026-11-21

El art. 97 de la Ley 18.883 (asignaciones de los funcionarios municipales) sale ahora del visor web oficial de la BCN y no de leyes-cl.com, un sitio de un tercero. El texto servido no cambia: sin las anotaciones al margen que el visor intercala, el visor lo trae idéntico, palabra por palabra, en su última versión (01-09-2025). leyes-cl.com y la SUSESO quedan como fuentes que lo corroboran. Además se corrige el aviso de `ver_articulo` en cuatro artículos completados, que decía a la vez que el texto «no se cotejó» contra la BCN y que el visor de la BCN lo corroboraba: en el 97 ahora dice que el texto completo sale del visor oficial, y en el Código Civil 252 y 2183 y la Constitución 144 (que siguen saliendo de DerechoPedia o leyes-cl.com) dice que el texto completo se cotejó con el visor oficial y coincide, como ya se había verificado en la 0.16.9. El texto de esos artículos no cambia. Los pronunciamientos de la DT y las demás herramientas no cambian.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.10 · 2026-11-21

El visor web oficial de la BCN confirma los tres artículos del Código del Trabajo que la 0.16.6 había completado con el Código de la Dirección del Trabajo (art. 38, 40 bis E y 152 ter D). Comparados palabra por palabra con la versión vigente en el visor, coinciden: el 40 bis E y el 152 ter D son idénticos, y el art. 38 sólo difiere en una coma («incisos tercero, cuarto y quinto, las partes…» en la DT, sin coma en el visor). Las dos tablas de descanso de tripulantes del 152 ter D dan las mismas cifras en ambas fuentes, y el texto de la DT no trae modificaciones que todavía no rijan. El aviso de `ver_articulo` en esos tres artículos deja de decir que el resto «no se cotejó contra el texto oficial de la BCN» y pasa a decir que se cotejó y coincide; la nota del 152 ter D deja de pedir verificar las cifras. Los pronunciamientos de la DT y las demás herramientas no cambian.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.9 · 2026-11-21

Ya no queda ningún artículo cortado. Los dos que faltaban salen completos: el art. 2 de la Ley 21.109 (el XML de la BCN lo entregaba sin sus dos últimas frases: la denuncia conforme al art. 175 del Código Procesal Penal, que la obligación no se entiende satisfecha por acciones de terceros y la especial gravedad de la violencia contra los asistentes de la educación) y el art. 14 transitorio de la Ley 19.378 (la bonificación por una vez de 1995). Esta vez la fuente es oficial: el visor web de la BCN (Ley Chile) entrega el artículo completo, y la huella del texto coincide con la que se calculó sobre el visor; el 14 transitorio lo corrobora además la copia de la ley de la Municipalidad de Punta Arenas. Además, el visor oficial de la BCN confirma, comparado por oraciones, los cuatro artículos que la 0.16.7 había completado con fuentes de terceros (Código Civil 252 y 2183, Constitución 144 y Ley 18.883 art. 97): el 2183 idéntico y los otros tres con el mismo contenido, salvo las anotaciones al margen que el visor intercala en el texto. El aviso de esas recuperaciones deja de repetir que la fuente es de un tercero. Los pronunciamientos de la DT y las demás herramientas no cambian.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.8 · 2026-11-13

`ver_articulo` avisa, en los art. 431 y 445 del Código del Trabajo, que la Ley 21.780 (D.O. 13-11-2025, art. 49) cambiará la redacción de su inciso segundo («privilegio de pobreza» y las Corporaciones de Asistencia Judicial pasan a «beneficio de asistencia jurídica gratuita» y al Servicio Nacional de Acceso a la Justicia y Defensoría de Víctimas), pero que esa ley rige en forma gradual: desde mayo de 2027 en las regiones de Arica a Valparaíso, desde mayo de 2028 en la Metropolitana, O'Higgins, Maule y Magallanes, y desde noviembre de 2029 en las demás. Hoy sigue vigente la redacción que sirve el saber, que es la de la BCN; el Código del Trabajo que publica la DT ya trae la nueva. El aviso se ajusta solo a la fecha de la consulta. No se verificó si el art. 49 tiene una regla de entrada en vigencia propia distinta del cronograma de la ley. El texto de los artículos no cambia.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.7 · 2026-11-12

Cuatro artículos más que la BCN entregaba cortados a mitad de palabra salen completos: el art. 252 y el 2183 del Código Civil, el art. 144 de la Constitución (el del Consejo Constitucional de 2023) y el art. 97 de la Ley 18.883. A diferencia de los del Código del Trabajo, que se completaron con el Código de la Dirección del Trabajo, éstos vienen de fuentes de terceros y no oficiales (DerechoPedia y leyes-cl.com), y cada artículo lo dice y dice quién más lo corrobora: el 2183 coincide en las dos, el 97 lo corrobora la SUSESO, y el 252 y el 144 tienen una sola fuente. En todos, lo que la BCN sí entregó coincide con el comienzo del texto nuevo, pero el resto no se cotejó contra el texto oficial. Además, el aviso de «puede estar cortado» ya no sale en falso: el Código Civil 398, la Constitución 123, la Ley 16.744 art. 8 y la Ley 19.880 art. 19 bis terminan sin punto final y se confirmó que no están cortados. Siguen avisando la Ley 21.109 art. 2 y la Ley 19.378 art. 14 transitorio, que no se pudieron completar. Los pronunciamientos de la DT y las demás herramientas no cambian.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.6 · 2026-11-12

Tres artículos del Código del Trabajo que la BCN entregaba cortados a mitad de palabra salen ahora completos: el 38 (descanso en domingo y festivos y los sistemas excepcionales de jornada), el 40 bis E (jornada parcial alternativa de estudiantes) y el 152 ter D (descanso de tripulantes). Hasta ahora quien pedía el art. 38 recibía el texto hasta «los días sá» sin ningún aviso. El resto sale de la edición del Código de la Dirección del Trabajo, y cada artículo lo dice: lo que la BCN sí entregó coincide con el comienzo de ese texto, pero el resto no se cotejó contra el texto oficial de la BCN. Las tablas del 152 ter D vienen aplanadas por columnas: verifica las cifras antes de citarlas. Además, `ver_articulo` avisa cuando un artículo de otra ley termina sin puntuación final y puede estar cortado (Código Civil, Constitución y cuatro leyes más: están listados en el manifiesto). El criterio es estrecho y no prueba que no haya otros cortes. Los pronunciamientos de la DT y las demás herramientas no cambian.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.5 · 2026-11-07

Sólo cambia el texto de las skills. Dejan de decir que el saber es de uso interno, «solo staging, sin asientos de terceros» y que no debe promoverse a producción, porque ya no es así: pasan a decir que el acceso es restringido, por invitación, y que está en evaluación mientras se resuelve con asesoría legal el permiso de la DT. Las respuestas del servicio mantienen su aviso de uso interno. El saber entra al catálogo legal, el mismo del saber tributario. Los datos y las herramientas no cambian.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.4 · 2026-11-03

`buscar` ofrece la ficha en dos formas más de preguntar que la prueba a mano con preguntas de otros temas mostró que faltaban: quien pregunta por los «domingos y festivos» de ejecutivos de ventas con un bono por meta sin decir «semana corrida» (ficha de semana corrida), y quien pide teletrabajo porque cuida a su madre o a su padre (ficha de teletrabajo por cuidado). En esa misma prueba las preguntas de otros temas (horas extra, finiquito, licencia, lugar de trabajo, vacaciones, recargo dominical) no recibieron ficha, y siguen sin recibirla. Una pregunta sobre el feriado de vendedores con comisión sí recibe la ficha de semana corrida: es cercana, pero no es de ese tema, y la respuesta lo dice. Sólo cambian las frases con que se ofrece cada ficha, no su contenido.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.3 · 2026-11-03

La ficha de semana corrida atribuye cada regla a quien la dijo. La prueba a mano mostró que presentaba como del ORD 833 (2024) una doctrina que es del ORD 3262/66 (2008) y que el 833 reitera, y que parte de la afirmación sobre «devengarse diariamente» (que cuenta lo que el trabajador incorpora a su patrimonio día a día aunque se pague una vez al mes) no estaba en la cita que la acompañaba. Ahora la afirmación nombra las dos fechas, la cita del 3262/66 incluye esa frase, se suma cómo entiende la DT la remuneración variable, y la regla de las comisiones repartidas entre todos los vendedores se apoya también en el 3262/66. Las citas se volvieron a comprobar contra el corpus. Sólo cambia la ficha; sigue siendo un borrador sin validar por un abogado laboralista.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.2 · 2026-11-03

La ficha de cambio unilateral de turno o de jornada suma el ORD 2024 425 (08-07-2024), que reitera con claridad la regla: aunque el sistema de turnos esté pactado en el reglamento interno, el empleador no puede modificarlo sin la anuencia de los trabajadores, y cualquier cambio del régimen de jornada se hace por mutuo consentimiento. Sus dos pasajes se comprobaron contra el corpus; son de lectura OCR y están sólo en el cuerpo del documento, así que la ficha pide verificarlos contra el PDF. Es la ficha la que cambia: el resto del saber queda igual. Sigue siendo un borrador sin validar por un abogado laboralista.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.1 · 2026-11-03

`buscar` ofrece la ficha en más de las formas en que se pregunta. En la prueba a mano de la 0.16.0, dos de cinco preguntas que la ficha cubría no la recibieron: pasar a un trabajador de turno de día a turno de noche, y pedir teletrabajo para cuidar a un hijo. Se agregan frases clave a las fichas de turnos y de teletrabajo por cuidado, y las preguntas de ejemplo de cada ficha (que ahora se escriben completas, sin depender de la pregunta anterior) activan su propia ficha. Sigue siendo preferible no ofrecer una ficha que ofrecer la que no es: las consultas de otros temas (feriado, despido con licencia, sala cuna, equipos de teletrabajo) no reciben ficha. Las fichas siguen siendo borradores sin validar por un abogado laboralista.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.16.0 · 2026-11-03

Nueva herramienta `obtener_ficha`: para tres temas que el empleador consulta mucho —semana corrida (vendedores con comisiones), cambio unilateral de turno o de jornada, y teletrabajo por cuidado— entrega una FICHA con lo que la DT ha dicho, afirmación por afirmación, con el pasaje literal de cada pronunciamiento y su vigencia leída hoy; las tensiones que el corpus no resuelve (por ejemplo, el ORD 2658/31 de 2014 frente al 6519/2018 sobre modificar turnos del reglamento interno) y lo que la DT no resuelve. Es un BORRADOR sin validar por un abogado laboralista y cada respuesta lo dice: los pasajes se comprueban a máquina contra el corpus, pero la redacción de cada afirmación no está revisada. `buscar` avisa «hay una ficha» cuando la consulta contiene una de las frases clave de la ficha, y no ofrece ninguna si no. La skill `resolver-un-caso` indica abrirla primero, presentarla como borrador y verificar las citas. Los demás temas no tienen ficha: sigue siendo `buscar`. Trae además todo lo de la 0.15.2.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `obtener_ficha`, `ver_articulo`, `ver_cambios`, `ver_documento` · aparece `obtener_ficha`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.15.2 · 2026-11-03

`ver_articulo` avisa cuándo el texto del Código no es todavía el que rige. La Ley 21.561 baja la jornada por escalones y el Código muestra el valor final: el artículo 22 decía «cuarenta horas» cuando hoy rige el escalón de 42 (44 desde el 26-04-2024, 42 desde el 26-04-2026, 40 desde el 26-04-2028). Ahora la primera advertencia dice cuál rige a la fecha de la consulta. Lo mismo para los demás artículos que nombra el artículo primero transitorio de esa ley (22 bis, 31, 34 bis, 106, 109, 149, 152 ter D y 152 quáter Y), y para los que sólo cambian de jornada al quinto año. No se aplica a `buscar_por_ancla`. Además, las respuestas describen los datos por su fecha de generación («datos del 2026-10-15») y no por una etiqueta que se parecía a una versión del servicio, y quien opera el servicio puede fijar un tope al texto que entrega `ver_documento`; sin esa variable, el texto se entrega como antes. Y la vigencia dice más de lo que ya sabía: cuando un pronunciamiento confirma, precisa o reconsidera uno que NO está en el corpus (el ORD 199/2026 niega reconsiderar un dictamen de 1995), `ver_documento` muestra el destino y avisa que sólo se ve desde ese lado; y cuando reconsidera doctrina previa sin nombrarla (el ORD 253/21 sobre la rebaja a 42 horas), lo dice, y `buscar` avisa «tensión sin resolver» si entre los resultados hay anteriores sobre lo mismo. No decide cuál queda superado: lo declara.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.15.1 · 2026-10-15

Nueva herramienta `buscar_condenas`: la nómina que la DT publica cada semestre de empresas y organizaciones sindicales con sentencia FIRME por prácticas antisindicales o desleales (art. 294 bis), de 2005 a 2026: 984 condenas, con los hechos («reemplazo de trabajadores en huelga», «despido de dirigente con fuero»), la causa, el tribunal, la fecha, quién denunció y la multa, y el enlace al informe de la DT. Sirve para decir si una conducta ya terminó en condena y con qué multa. Y `buscar`, cuando la consulta es de libertad sindical, avisa cuántas condenas hay con hechos parecidos. No trae las sentencias. Los registros se extrajeron de tablas de PDF (algunos por OCR) y se validaron contra el informe: el 96 % trae la causa tal como figura en él, y los que no, van marcados como dudosos. Los infractores que son personas naturales se sirven sin nombre ni RUT.

- Herramientas: `buscar`, `buscar_condenas`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento` · aparece `buscar_condenas`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.15.0 · 2026-10-15

Sin cambios para quien lo usa: la etiqueta v0.15.0 se puso sobre la 0.14.0, antes de incorporar las condenas, y la verificación de staging la rechazó. Lo que iba a traer está en la 0.15.1.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.14.0 · 2026-10-12

Los pronunciamientos se sirven anonimizados, de cara a la Ley 21.719 (rige desde el 01-12-2026). Del texto y del resumen se quitan las personas naturales privadas —quien consulta, trabajadores, dirigentes, abogados y representantes de una parte, familiares— y sus correos, teléfonos, domicilios y RUT. Cada persona queda como [PERSONA_n], la misma en todo el documento, para que se siga entendiendo. Se conservan las empresas, los sindicatos, los organismos, los cargos, las normas, la firma del funcionario de la DT y el tachado de la propia DT. Medido contra 120 documentos al azar, revisados por quien no vio el resultado: se quita el 99,3 % de los nombres, y 117 de los 120 quedan sin ningún dato personal. La búsqueda responde igual que antes (medido sobre 93 preguntas). El enlace a dt.gob.cl sigue mostrando el documento original.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.13.1 · 2026-10-10

La skill `resolver-un-caso` nombra, antes de buscar, la institución del caso y su artículo, con un mapa verificado de las instituciones del Código del Trabajo que más se consultan. Cuando no hay un pronunciamiento del caso exacto, busca el criterio general de la institución y lo dice como tal. Y ordena lo que entrega por lo que decide: primero el que resuelve el supuesto exacto y sigue vigente, nunca primero uno solo relacionado o una declinación. Lo litigioso se responde en dos mitades: lo que la DT dijo sobre las formalidades, y que el fondo lo decide un tribunal. Medido en dos conjuntos ciegos nuevos, con GPT como agente y un juez independiente: con preguntas nuevas, el primer resultado responde en torno al 60 % de las veces. La diferencia con la skill anterior queda dentro del ruido de una corrida a otra (dos corridas idénticas difieren en 7 puntos), así que la mejora no está demostrada: se adopta por su contenido. Las herramientas y los datos no cambian. Y trae lo de la 0.13.0, que no llegó a quien usa el saber: la etiqueta v0.13.0 se publicó con el servidor anunciando todavía la versión 0.12.1, y la verificación de staging la rechazó.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.13.0 · 2026-10-08

`buscar` trae siempre `antes_de_concluir_que_no_esta`: los organismos a los que la propia DT remite cuando declina pronunciarse —tribunales, Contraloría, Superintendencia de Pensiones, SUSESO, salud, SII, Superintendencia de Educación—, con las materias de cada uno y cuántas veces lo hace en el corpus. Es una lista, no un juicio sobre la consulta: sirve para no responder «no encontré» cuando la materia es de otro. Avisa también que el saber no trae sentencias. Medido sobre las 24 preguntas de frontera de la evaluación (no ciegas): nombra al organismo en 23; la señal anterior acertaba 3. El orden de los resultados no cambia. Cuesta unos 2,3 KB por respuesta. Y el saber se presenta ahora para quien emplea —empleador, RRHH, contador— y su pregunta, cómo cumplir: «el criterio de la DT, con su vigencia». Lo litigioso queda dicho como de los tribunales.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.12.1 · 2026-10-03

Es la vigencia tipada de la 0.12.0, publicada de verdad: la etiqueta v0.12.0 se puso por error sobre el commit anterior y no llegó a quien usa el saber.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.12.0 · 2026-10-03  ·  ⚠ QUEMADA

> **Esta versión no debe servirse.** Etiquetada por error sobre el commit de la v0.10.1 (un git pull falló y la etiqueta se puso igual). El pipeline desplegó en staging el código de la 0.10.1 —el mismo que ya corría— y falló al publicar el paquete, así que no llegó a nadie. Su contenido está en la 0.12.1.

La vigencia dice ahora también qué criterios la DT CONFIRMÓ después (negó reconsiderarlos o los declaró vigentes: 218 enlaces) y cuáles PRECISÓ (complementó o aclaró: 32), además de los que superó (106). Cada documento trae su `ultima_senal`, lo último que la DT dijo de él en el corpus. Precisión medida por muestra: confirma 38 de 40, precisa 19 de 20.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.10.1 · 2026-10-02

`ver_articulo` trae el texto del Código Civil, la Constitución y las leyes que los dictámenes más aplican: 16.744, 18.883, 19.296, 19.378, 19.464, 19.880 y 21.109 (de 793 a 4.139 artículos). Entre el 96 y el 100 % de las citas de los dictámenes a esas normas llega a un artículo vigente. El Estatuto Docente no se incluyó: los dictámenes citan su texto refundido y la BCN entregó la ley original, con otra numeración.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.10.0 · 2026-10-02

Cada pronunciamiento dice si la DT declina pronunciarse (`declina_competencia`: total o parcial, por qué y a qué organismo remite, con la frase), y `buscar` trae una señal de `frontera` cuando varias declinaciones encabezan los resultados. Medido: la señal no se disparó en ninguna de las 6 preguntas de frontera de la evaluación (se predijo 3) y no dio falsos positivos; que no aparezca no prueba que la DT resuelva el punto.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.9.0 · 2026-10-02

`buscar_por_ancla` acepta la pregunta (`consulta`): ordena por pertinencia y no por fecha, y suma los dictámenes que mencionan el artículo en el cuerpo sin declararlo, marcados aparte. Medido sobre 60 preguntas escritas y etiquetadas por terceros: la línea base de la v0.8.0 está en evaluacion/resultados/.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## v0.8.0 · 2026-10-01

El servicio dice qué cambió de una versión a otra y en qué versión corre (`ver_cambios`). Para quien consulta la doctrina, nada más cambia.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_cambios`, `ver_documento` · aparece `ver_cambios`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

## Línea base · v0.7.0 · 2026-10-01

Así está el saber cuando empieza este registro. Responde con lo que pronunció la Dirección del Trabajo en 10.738 dictámenes y ordinarios (1990-2026), con cita, URL y señales de reconsideración; la vigencia nunca se declara. El 99,5 % tiene el cuerpo leído: 7.754 de la página y 2.935 por OCR de PDF escaneados, una clase aparte con su calidad medida que se verifica contra el PDF antes de citar un número o un pasaje. Trae 793 artículos del Código del Trabajo y de las leyes 21.561, 21.755, 21.645 y 21.643 en su versión vigente, y una puerta por artículo (`buscar_por_ancla`) que lee qué norma declara aplicar cada pronunciamiento. Es de uso interno: la DT no publica una licencia de reutilización.

- Herramientas: `buscar`, `buscar_por_ancla`, `listar_cobertura`, `ver_articulo`, `ver_documento`
- Skills: `empezar-aqui`, `resolver-un-caso`
- Datos: sin manifiesto

Antes de v0.7.0 no hay registro de cambios.
