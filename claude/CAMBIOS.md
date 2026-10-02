# Cambios · Normativa Laboral

<!-- Generado al derivar el paquete desde cambios.yaml. No editar a mano. -->

Qué cambia para quien usa este saber, versión por versión. Lo que corre de verdad el servicio lo dice su herramienta `ver_cambios`; esto es la copia del paquete.

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
