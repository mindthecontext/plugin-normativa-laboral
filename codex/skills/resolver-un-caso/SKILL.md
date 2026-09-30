---
name: resolver-un-caso
description: Resuelve un caso laboral concreto con lo que pronunció la Dirección del Trabajo — «¿cómo debe una empresa bajar la jornada a 42 horas sin acuerdo?», «¿qué ha dicho la DT sobre el teletrabajo?», «¿se puede pactar horas extraordinarias así?». Va de la situación en palabras de quien la vive hasta el pronunciamiento que la resuelve, con cita, vigencia y límites declarados. Úsala siempre que la respuesta deba apoyarse en lo que la DT pronunció y no en conocimiento general de derecho laboral.
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

## 1 · Quédate con la situación y busca en dos pasadas

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

**Si no aparece nada**, eso no es una respuesta: el corpus es una muestra. Reformula con otros términos
(la norma, el nombre de la ley, el descriptor habitual) antes de concluir que no hay respaldo.

## 2 · No confíes en el orden: comprueba que RESUELVE

La prosa administrativa genérica se parece a cualquier pregunta. Por cada candidato, antes de citarlo,
pregúntate **¿qué decide este pronunciamiento?** Si no puedes decirlo en una frase, no es tu documento
por bien rankeado que venga.

Abre los que importan con `ver_documento`. Y mira `texto_origen`:

- **`html`**: tienes el cuerpo. Puedes citar el pasaje literal, con su cita y su URL.
- **`solo-resumen`**: el cuerpo es un PDF que no se leyó. Lo único que tienes es el **resumen del
  portal**. Cítalo como tal —«según el resumen del portal de la DT»—, **nunca como si fuera el texto
  del pronunciamiento**, y no afirmes nada que el resumen no diga.

## 3 · La vigencia: aquí se gana o se pierde la respuesta

La DT no declara qué sigue vigente. Un dictamen puede haber sido **reconsiderado** por otro posterior y
**el superado no lo dice**. Este saber te da señales, no veredictos:

- En cada resultado, `vigencia.senales_de_superacion` lista los pronunciamientos del corpus que dicen
  reconsiderarlo, con la frase literal. **Si hay alguna, abre ese pronunciamiento primero**: manda el
  posterior, y hay que decir que el anterior fue reconsiderado.
- `vigencia.reconsidera` dice a quién reconsidera el que estás leyendo.
- **Que no haya señal no prueba que siga vigente.** La regla es estricta y sin revisar, y solo cruza
  destinos que están en el corpus (la mayoría de las reconsideraciones apuntan a documentos que no
  cosechamos). Dilo: «no encontré señal de que haya sido reconsiderado en el corpus».
- Si dos pronunciamientos dicen cosas distintas y **ninguno declara reconsiderar al otro**, no decidas
  tú cuál rige. Preséntalos los dos, con sus fechas, y di que la tensión no está resuelta.
- Si la pregunta es por un hecho **pasado**, el criterio de su época puede ser el correcto aunque hoy
  esté superado. Dilo también.

*Ejemplo verificable del corpus (30-09-2026):* el ORD 253/21 (16-04-2026) reconsidera «en lo
pertinente» el dictamen 235/8 (2024) sobre cómo distribuir la rebaja de jornada. Quien cite la fórmula
del 235/8 como vigente se equivoca.

## 4 · El texto de la ley no está aquí

El corpus tiene lo que pronunció la DT, no los artículos que aplica. Si la respuesta depende de lo que
dice la ley (plazos, montos, gradualidad de una reforma), **no lo completes con conocimiento
general**: di qué pronunció la DT sobre esa norma y remite a la fuente oficial para el texto.

## 5 · Repetición no es corroboración

Varios resultados pueden ser el mismo criterio reiterado, o reconsideraciones que se citan entre sí.
Cinco pronunciamientos que dicen lo mismo no lo hacen más sólido. Cita el que fija la doctrina, y
menciona que se reitera si importa.

## 6 · Cuando el pronunciamiento no resuelve, dilo

Parte del corpus son pronunciamientos que **declinan competencia**, responden **por remisión** o se
limitan a un caso particular con hechos que no son los de quien pregunta. Son legítimos y no contienen
criterio general. Descríbelos como lo que son. **No completes el vacío con conocimiento general de
derecho laboral**: ahí este saber deja de ser verificable.

También hay **materias que la DT no resuelve** —lo que deciden los tribunales, o los organismos de
seguridad social y pensiones—. Si la consulta cae ahí, dilo en vez de improvisar.

## 7 · Responde con cita, condición, vigencia y límite

Una respuesta terminada tiene cinco partes:

1. **Qué pronunció la DT**, en una frase y en el registro de quien preguntó.
2. **Bajo qué condición**: casi ningún pronunciamiento es incondicional, y la condición es lo que lo
   hace utilizable.
3. **La cita y la URL**, con el pasaje literal si `texto_origen` es `html`, para que se pueda abrir y
   verificar.
4. **Su vigencia**: si hay señal de reconsideración, cuál; si no la hay, que no se encontró y que eso
   no prueba que rija.
5. **Qué queda fuera**: lo que el pronunciamiento no aborda, la ley que no está en el corpus, lo
   posterior a la última cosecha, y que es una muestra.

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
