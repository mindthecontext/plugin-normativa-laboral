---
description: Resuelve un caso laboral concreto con lo que pronunció la Dirección del Trabajo — «¿cómo debe una empresa bajar la jornada a 42 horas sin acuerdo?», «¿qué ha dicho la DT sobre el teletrabajo?», «¿se puede pactar horas extraordinarias así?». Va de la situación en palabras de quien la vive o la gestiona —el empleador, RRHH, el contador— hasta el pronunciamiento que la resuelve, con cita, vigencia y límites declarados. Úsala siempre que la respuesta deba apoyarse en lo que la DT pronunció y no en conocimiento general de derecho laboral.
---

# Resolver un caso

Esta puerta se abre cuando alguien describe **una situación**, no cuando pregunta por un número de
dictamen. El insumo es el caso tal como lo cuenta quien lo vive; la salida es qué pronunció la DT para
casos así, bajo qué condición, si sigue en pie, y qué queda fuera.

## Antes de buscar

1. Llama a `listar_cobertura`. Te dice hasta qué fecha llega el corpus, qué años cubre y cuántos
   pronunciamientos son solo resumen. **Es el límite de todo lo que vas a afirmar.**
2. Recuerda que este corpus es de **uso interno** y que **la vigencia nunca está declarada**. Nada de
   lo que sigue se puede presentar como «la doctrina vigente» sin decir cómo se comprobó.

## 1 · Si la pregunta ya nombra el artículo, entra por él

«¿Qué ha dicho la DT sobre el artículo 22?», «¿cómo aplica la DT el 152 quáter O bis?»: usa **`buscar_por_ancla`**
con la norma, el artículo y **la pregunta en `consulta`**. Trae los pronunciamientos que **declaran aplicarlo** en sus
fuentes legales, ordenados por pertinencia a la pregunta, y suma los que lo **mencionan en el cuerpo** sin declararlo,
marcados en `vinculo`: esos ábrelos antes de presentarlos como doctrina sobre el artículo. Sin `consulta` el orden es
por fecha, y la doctrina que fija un criterio suele ser antigua: en la primera medición, ordenar por fecha dejó el
dictamen que respondía en el último lugar. Lee sus advertencias: dice si el artículo **ya
no existe** en la versión vigente (lo citan dictámenes antiguos de artículos derogados) y cuántos pronunciamientos son
**anteriores a la versión vigente** del artículo, que pueden haber aplicado otro texto.

## 2 · Antes de buscar, nombra la institución y su artículo

Quien emplea cuenta un hecho («me descuentan un seguro que no firmé», «la esperé horas en el set»). La DT resuelve
**instituciones**: descuentos, jornada pasiva, ius variandi, feriado acumulado. Antes de la primera búsqueda, escribe
para ti tres cosas: **la institución**, **el artículo que la regula** y **la circunstancia concreta** del caso. Luego
busca por las tres vías: `buscar` con el nombre de la institución, `buscar_por_ancla` con el artículo y la pregunta en
`consulta`, y `buscar` con la circunstancia.

Puntos de entrada frecuentes del Código del Trabajo (verificados contra el texto vigente que trae `ver_articulo`):

| Si el caso trata de… | Institución | Artículo |
|---|---|---|
| cambiar funciones, lugar, turno u horario sin acuerdo | ius variandi; modificación del contrato | 12; 5 y 11 |
| tiempo de espera, de traslado, de vestirse o de estar a disposición | jornada (activa y pasiva) | 21 |
| horas, distribución, rebaja a 40 horas | jornada ordinaria | 22 y 28 |
| horas extra | jornada extraordinaria | 30 y 32 |
| marcar, registrar asistencia | control de asistencia | 33 |
| domingos, festivos, día libre, descanso compensatorio | descanso semanal | 35 y 38 |
| qué es remuneración; comisiones, bonos | remuneración | 41 y 42 |
| pago de domingos con sueldo variable | semana corrida | 45 |
| gratificación | gratificación legal | 47 y 50 |
| descuentos en la liquidación | descuentos obligatorios y voluntarios | 58 |
| igualdad de sueldos | igualdad remuneracional | 62 bis |
| vacaciones, días, acumulación, fraccionamiento | feriado legal y progresivo | 67, 68 y 70 |
| permisos por muerte o nacimiento | permisos legales | 66 |
| teletrabajo: pacto, horario, costos, cuidadores | trabajo a distancia | 152 quáter G, J, L y O bis |
| reglamento interno, sanciones, multas | reglamento interno | 153 y 154 |
| renuncia, mutuo acuerdo, vencimiento | causales objetivas | 159 |
| despido disciplinario, abandono, ausencias | causales de caducidad | 160 |
| necesidades de la empresa | despido por causa económica | 161 |
| carta de despido, cotizaciones al día | formalidades del despido | 162 |
| indemnización por años | indemnización | 163 |
| finiquito, reserva de derechos | finiquito | 177 |
| fuero | desafuero | 174 |
| contratista, empresa principal | subcontratación | 183-A a 183-E |
| seguridad, condiciones del lugar de trabajo | deber de protección | 184 y 184 bis |
| embarazo, pre y postnatal, fuero maternal | protección a la maternidad | 195, 197 bis y 201 |
| hijo enfermo | permiso por enfermedad del hijo | 199 |
| sala cuna, alimentación | sala cuna; derecho a alimentar | 203 y 206 |
| acoso, violencia, Ley Karin | prevención e investigación | 211-A a 211-C |
| presiones contra el sindicato | prácticas antisindicales | 289 |
| extensión de beneficios del contrato colectivo | instrumento colectivo | 322 |

No es una lista cerrada: es el primer paso para salir del vocabulario del caso al de la norma.

## 3 · Quédate con la situación y busca en dos pasadas

Usa `buscar` con **las palabras de quien pregunta**. La DT titula y resume en lenguaje administrativo,
pero el índice pesa el resumen y los descriptores, que suelen ser más cercanos a la consulta que el
cuerpo.

Haz **dos búsquedas** y compáralas:

- **Sin `desde`**, para ver la línea de doctrina completa.
- **Con `desde` reciente** (los últimos dos o tres años), para encontrar lo que la actualiza. La
  doctrina laboral cambia con las reformas, y el pronunciamiento que más se parece a la pregunta suele
  ser el más antiguo, no el que rige.

**Si la consulta trae dos dudas** —un plazo y un procedimiento, el fondo y la prueba— resuélvelas por
separado. Contestar una y callar la otra deja media consulta sin responder.

**El vocabulario importa más de lo que parece.** En las pruebas, la pasada con lenguaje corriente («mi jefe no
me deja trabajar desde la casa») trajo embarazo y sala cuna, y los pronunciamientos que respondían solo
aparecieron al escribir el nombre de la ley («Ley 21.645»), el descriptor («conciliación de trabajo y
familia») y los términos de la norma. Si la primera pasada no trae lo que esperas, **repite con el
vocabulario legal**, no con más palabras corrientes. Una consulta larga y desordenada puntúa peor que una
corta y precisa.

**Mira `anclas_que_concentran`.** Son los artículos que más se repiten entre los resultados. Si uno calza con la
pregunta, síguelo con `buscar_por_ancla`: es la forma de pasar de «documentos que se parecen» a «la doctrina sobre
la norma que rige el caso». Para la rebaja a 42 horas propone el art. 22 del Código y el art. 24 de la Ley 21.755,
que son los que la regulan. No está medido todavía: es una sugerencia, no una respuesta.

**Lee lo que el servicio te dice sobre la calidad de la búsqueda:**

- `busqueda_pobre: true` —o la advertencia «BÚSQUEDA POBRE»— significa que **ni el mejor resultado coincide
  bien**. No presentes esos resultados como respuesta: reformula, y si sigue igual, di que el corpus
  probablemente no trata el punto.
- `coincidencia_debil: true` en un resultado significa que puntúa muy por debajo del mejor. No lo cites sin
  abrirlo y comprobar que trata tu punto.
- `resumen_recortado: true` significa que el resumen de la búsqueda está cortado: ábrelo con `ver_documento`
  antes de citar lo que dice.

**Si no aparece un pronunciamiento del caso exacto, busca el criterio general de la institución.** Muchas consultas son
un caso particular de una regla que la DT ya fijó en general: un descuento por un seguro que nadie autorizó es un caso
del artículo 58; las horas de espera de un actor son un caso de la jornada pasiva del artículo 21. Busca el
pronunciamiento que fija esa regla (con `buscar_por_ancla` y el artículo, o con el nombre de la institución), léela
con `ver_articulo`, y preséntala como lo que es: «no hay un pronunciamiento sobre este caso exacto; la regla general
de la DT es…». Eso es mejor respuesta que un dictamen parecido sobre otro supuesto.

**Si no aparece nada**, eso no es una respuesta: el corpus no es el archivo completo de la DT. Reformula con otros términos
(la norma, el nombre de la ley, el descriptor habitual) antes de concluir que no hay respaldo.

## 4 · No confíes en el orden: comprueba que RESUELVE

La prosa administrativa genérica se parece a cualquier pregunta. Por cada candidato, antes de citarlo,
pregúntate **¿qué decide este pronunciamiento?** Si no puedes decirlo en una frase, no es tu documento
por bien rankeado que venga.

**Antes de entregar, ordena por lo que decide, no por cómo llegó.** Abre con `ver_documento` los dos o tres candidatos
más prometedores y comprueba qué resuelve cada uno. Luego ordena:

1. **Primero, el que decide el supuesto exacto de la pregunta**: la misma institución y la misma circunstancia.
2. Después, el que **fija el criterio general** del que el caso es una aplicación.
3. Después, los que lo **confirman, precisan o actualizan** (mira `vigencia.ultima_senal`). Si dos deciden lo mismo,
   va primero el más reciente que no esté superado.
4. Nunca primero un documento que solo **trata el tema**, ni una declinación de competencia, salvo que la pregunta
   sea justamente a quién le corresponde.

Medido sobre preguntas nuevas: cuando el primer resultado no respondía, en cinco de cada ocho casos lo que respondía
estaba segundo o tercero. Ordenar bien vale tanto como encontrar.

Y mira `texto_origen`:

- **`html`**: tienes el cuerpo. Puedes citar el pasaje literal, con su cita y su URL.
- **`ocr`**: el cuerpo era un PDF escaneado y se leyó por OCR (la mayoría de lo publicado desde 2020). Puedes citarlo,
  pero es una lectura automática: **los números, las fechas y los ordinales son lo que más falla**. Antes de citar un
  pasaje literal o un número, ábrelo en el PDF (`fuente_url`). Si `calidad_ocr.nivel` es `baja`, no cites su pasaje:
  usa el resumen del portal. Dilo así: «según el texto del dictamen, leído del PDF escaneado».
- **`solo-resumen`**: el PDF no se pudo bajar o leer; quedan pocos. Lo único que tienes es el **resumen del
  portal**. Cítalo como tal —«según el resumen del portal de la DT»—, **nunca como si fuera el texto
  del pronunciamiento**, y no afirmes nada que el resumen no diga.
- **`solo-ficha`**: hoy no queda ninguno. La página del documento no se abrió: tienes su título, su
  fecha y su resumen (idéntico al de la página), pero **no** sus descriptores, sus fuentes legales, sus
  concordancias ni su cuerpo. Se cita igual que un `solo-resumen`, y además no sabes qué normas aplica:
  no lo afirmes. Vale mucho para ver una **línea de doctrina** —varios pronunciamientos de distintos años
  que dicen lo mismo—, y poco para el detalle de un caso.

## 5 · La vigencia: aquí se gana o se pierde la respuesta

La DT no declara qué sigue vigente. Un dictamen puede haber sido **reconsiderado** por otro posterior y
**el superado no lo dice**. Este saber te da señales, no veredictos. **Empieza por `vigencia.ultima_senal`**: lo
último que la DT dijo de ese documento en el corpus, de tres tipos:

- **`supera`**: un pronunciamiento posterior lo reconsideró o lo dejó sin efecto. Manda el posterior.
- **`confirma`**: un pronunciamiento posterior **negó reconsiderarlo** o lo **declaró vigente**. Es la mejor
  evidencia de que el criterio seguía en pie: cítala con su fecha («confirmado por el ORD 2591/22, de 2020, que negó
  reconsiderarlo»). Dice que la DT lo sostuvo EN ESA FECHA, no después.
- **`precisa`**: uno posterior lo complementó o aclaró. Lee los dos: el criterio es la suma.

Las listas completas están en `confirmaciones`, `precisiones` y `senales_de_superacion`.

- En cada resultado, `vigencia.senales_de_superacion` lista los pronunciamientos del corpus que dicen
  reconsiderarlo, con la frase literal. **Si hay alguna, abre ese pronunciamiento primero**: manda el
  posterior, y hay que decir que el anterior fue reconsiderado.
- `vigencia.reconsidera` dice a quién reconsidera el que estás leyendo.
- **Que no haya señal no prueba que siga vigente.** La regla es estricta y sin revisar: lee el resumen, el
  encabezado de la DT («RDIC.: Reconsidérase…») y la conclusión, no el resto del cuerpo, y solo cruza
  destinos que están en el corpus y que se identifican sin ambigüedad (número, consecutivo y año, o la
  fecha completa). Dilo: «no encontré señal de que haya sido reconsiderado en el corpus».
- Si dos pronunciamientos dicen cosas distintas y **ninguno declara reconsiderar al otro**, no decidas
  tú cuál rige. Preséntalos los dos, con sus fechas, y di que la tensión no está resuelta.
- Si la pregunta es por un hecho **pasado**, el criterio de su época puede ser el correcto aunque hoy
  esté superado. Dilo también.

*Ejemplo verificable del corpus (30-09-2026):* el ORD 253/21 (16-04-2026) reconsidera «en lo
pertinente» el dictamen 235/8 (2024) sobre cómo distribuir la rebaja de jornada. Quien cite la fórmula
del 235/8 como vigente se equivoca.

## 6 · La ley: los códigos y las leyes que más aplican los dictámenes, en su versión vigente

Cuando la respuesta dependa de lo que dice la ley, léela con `ver_articulo`. Trae el **Código del Trabajo**
(«22», «161», «211-B bis», «152 quáter O bis»), el **Código Civil** («1545», «1792-1»), la **Constitución** («19») y
las leyes que lista `listar_cobertura`: entre ellas la **16.744** (accidentes del trabajo), la **19.378** (atención
primaria de salud municipal), la **18.883** (funcionarios municipales), la **19.296** (asociaciones de funcionarios), la
**21.109** (asistentes de la educación), la **19.880** (procedimiento administrativo) y las reformas recientes: **21.561**
(40 horas), **21.755** (su art. 24 fija la fórmula de la rebaja), **21.645** (conciliación) y **21.643** («Ley Karin»).
Pasa `norma` («Ley 19.378», «Código Civil», «Constitución») y `transitorio` si lo es. Los transitorios de las leyes se
nombran en palabras («tercero»), pero se pueden pedir en cifras («3»).

Cada artículo viene con cuántos dictámenes del corpus lo citan; para recorrerlos, con su vigencia y por páginas,
usa `buscar_por_ancla`. `buscar_por_ancla` también llega a normas cuyo texto NO está aquí (el Estatuto Docente, el
DFL 2 de 1967, el DL 3.166): trae lo que la DT pronunció al aplicarlas, aunque no puedas leer el artículo. Y cuando dos dictámenes aplican la misma norma de forma distinta, leer
el artículo ayuda a exponer la tensión, **pero no la resuelve tú**: preséntala.

Dos límites que se dicen:

- **Es la versión vigente**, con su `fecha_version`. Si la pregunta es por un hecho pasado y el artículo
  cambió después, el texto de entonces no está aquí.
- **Las demás normas no están**: el Estatuto Docente (su texto refundido, el DFL 1 de 1996), el DFL 2 de 1967, la
  19.728, la 20.123 y otras.
  `ver_articulo` responde con la lista de las que sí hay. Si la respuesta depende de ellas, **no las completes con conocimiento
  general**: di qué pronunció la DT sobre esa norma y remite a Ley Chile para el texto.

## 7 · Repetición no es corroboración

Varios resultados pueden ser el mismo criterio reiterado, o reconsideraciones que se citan entre sí.
Cinco pronunciamientos que dicen lo mismo no lo hacen más sólido. Cita el que fija la doctrina, y
menciona que se reitera si importa.

## 8 · Cuando el pronunciamiento no resuelve, dilo

**Mira `declina_competencia` en cada resultado.** Marca los pronunciamientos en que la DT dice que no le corresponde
pronunciarse: `total` o `parcial`, el `motivo` (`materia_judicial`, `otro_organismo`, `consulta_generica`, `otro`) y a
qué organismo remite, con la frase. Una declinación no es criterio de fondo: si es lo que encontraste, la respuesta es
«la DT declina, y remite a…», con la cita. Si `buscar` trae `frontera.senal: true`, varios de los primeros resultados
son declinaciones: es probable que la pregunta la resuelva otro organismo, y la evidencia está en `frontera.evidencia`.

**Que no haya señal NO prueba que la DT resuelva el punto.** Medido sobre 18 preguntas de frontera escritas por
terceros, la señal se disparó en 3: las declinaciones existían, pero quedaban lejos de los primeros resultados. Por eso
`buscar` trae siempre **`antes_de_concluir_que_no_esta`**: la lista de los organismos a los que la propia DT remite
cuando declina —los tribunales, la Contraloría, la Superintendencia de Pensiones, la SUSESO y otros— con las materias de
cada uno. Léela **antes de decir «no encontré»** y antes de responder con dictámenes que no tocan el punto. Es una lista,
no un juicio sobre la consulta: si la pregunta cae en una de esas materias, dilo y nombra al organismo; si no cae, la
lista no dice nada. Nombra al organismo en 23 de las 24 preguntas de frontera de la evaluación; la que falta es de
Migraciones, al que la DT no remite en el corpus.

Este saber **no trae sentencias**. Si la pregunta es sobre lo que resolvió o resolvería un tribunal, dilo así: que no
aparezca un fallo no dice nada sobre si existe.

**Las preguntas litigiosas tienen dos mitades.** «¿Sirve el despido o puedo demandar?», «¿de quién es la culpa del
accidente?», «¿es válido que me hagan renunciar a demandar para pagarme más?»: si el despido fue justificado, quién
responde por un accidente o si una renuncia a acciones vale, lo decide un tribunal. Pero la DT sí fijó lo que rodea esas
preguntas: qué debe decir la carta de despido y qué pasa con las cotizaciones (art. 162), cómo se firma y ratifica un
finiquito y qué es la reserva de derechos (art. 177), qué debe hacer el empleador para proteger la vida y la salud de
quien trabaja (art. 184). Responde esa mitad con sus pronunciamientos, y di con claridad que la otra la resuelve un
tribunal.

Parte del corpus son pronunciamientos que **declinan competencia**, responden **por remisión** o se
limitan a un caso particular con hechos que no son los de quien pregunta. Son legítimos y no contienen
criterio general. Descríbelos como lo que son. **No completes el vacío con conocimiento general de
derecho laboral**: ahí este saber deja de ser verificable.

También hay **materias que la DT no resuelve** —lo que deciden los tribunales, o los organismos de
seguridad social y pensiones—. Si la consulta cae ahí, dilo en vez de improvisar.

**Si la pregunta es de libertad sindical** —huelga, fuero, dirigentes, cuota sindical, negociación colectiva—, mira
`condenas_relacionadas` en la respuesta de `buscar`, o usa `buscar_condenas`: es la nómina que la DT publica de condenas
FIRMES por prácticas antisindicales (art. 294 bis), con los hechos, el tribunal y la multa. Sirve para decir «esta
conducta ya terminó en condena, y con multas de tanto», junto al criterio de la DT. No trae la sentencia: no le atribuyas
un razonamiento, y si el registro dice `dudoso`, compruébalo en su `fuente_url`.

## 9 · Responde con cita, condición, vigencia y límite

Una respuesta terminada tiene cinco partes:

1. **Qué pronunció la DT**, en una frase y en el registro de quien preguntó.
2. **Bajo qué condición**: casi ningún pronunciamiento es incondicional, y la condición es lo que lo
   hace utilizable.
3. **La cita y la URL**, con el pasaje literal si `texto_origen` es `html`, para que se pueda abrir y
   verificar.
4. **Su vigencia**: si hay señal de reconsideración, cuál; si no la hay, que no se encontró y que eso
   no prueba que rija.
5. **Qué queda fuera**: lo que el pronunciamiento no aborda, la ley que no está en el corpus, lo
   posterior a la última cosecha, y que el corpus no es el archivo completo de la DT.

## Cuándo abstenerse

- No aparece ningún pronunciamiento que resuelva la situación.
- Aparecen pronunciamientos que la rozan, pero ninguno decide el punto.
- El punto depende de hechos que quien pregunta no dio.
- La consulta pide un cálculo o una liquidación: esto entrega criterios, no calcula.
- Es una materia de los tribunales o de otro organismo.

**Decir «no tengo respaldo para esto» es una respuesta correcta.** Una respuesta plausible sin
pronunciamiento detrás es, en este dominio, un pasivo profesional para quien la reciba.

## Si preguntan por un pronunciamiento concreto, no por un caso

Usa `ver_documento` con la cita («253/21», con el año si hace falta, porque el consecutivo se reinicia
cada año) o con el id (`dt:129189`).
