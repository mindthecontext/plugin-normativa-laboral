# Cambios · Normativa Laboral

<!-- Generado al derivar el paquete desde cambios.yaml. No editar a mano. -->

Qué cambia para quien usa este saber, versión por versión. Lo que corre de verdad el servicio lo dice su herramienta `ver_cambios`; esto es la copia del paquete.

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
