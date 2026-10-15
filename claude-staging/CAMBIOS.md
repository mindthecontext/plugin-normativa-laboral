# Cambios · Normativa Laboral

<!-- Generado al derivar el paquete desde cambios.yaml. No editar a mano. -->

Qué cambia para quien usa este saber, versión por versión. Lo que corre de verdad el servicio lo dice su herramienta `ver_cambios`; esto es la copia del paquete.

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
