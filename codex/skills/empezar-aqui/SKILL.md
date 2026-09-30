---
name: empezar-aqui
description: Orienta a quien acaba de instalar Normativa Laboral y no sabe qué pedirle — «¿qué puedes hacer?», «¿qué sabes de derecho laboral?», «¿por dónde empiezo?», «ayuda». Presenta qué resuelve este saber, con la cobertura consultada en vivo, y dice desde el principio lo que NO cubre, lo que no está verificado y que es de uso interno.
---

# Empezar aquí

Este saber responde sobre **cómo la Dirección del Trabajo (DT) ha resuelto cuestiones laborales en
Chile**. No lee la ley y la interpreta: lee lo que la DT efectivamente **pronunció** en dictámenes y
ordinarios, con su cita y su rastro.

La diferencia importa. Ante «¿cómo debe una empresa bajar la jornada a 42 horas si no hay acuerdo?»,
la respuesta útil no es el texto de la ley: es el pronunciamiento donde la DT fijó la fórmula, su
fecha, y si otro posterior lo reconsideró.

## Esto es de uso interno

El corpus sale de dt.gob.cl y **la DT no publica una licencia de reutilización**. Por eso este saber
está declarado de uso interno: solo staging, sin asientos de terceros, y no debe promoverse a
producción. Si alguien ajeno al equipo pregunta, no le entregues textos completos.

## Al activarse esta puerta

1. Llama a `listar_cobertura` para saber **qué hay disponible ahora**: años, cuántos
   pronunciamientos tienen cuerpo y cuántos solo resumen, y hasta qué fecha llega. No presentes la
   cobertura de memoria: consúltala, porque el corpus se recosecha.
2. Presenta lo que el saber responde, en el idioma de quien pregunta:
   - **«Me pasó esto en mi empresa, ¿qué ha dicho la DT?»** — `buscar`, con las palabras de quien
     pregunta. Es la puerta principal.
   - **«¿Y qué dice el dictamen 253/21?»** — `ver_documento`, por cita o por id.
   - **«¿Hay algo más reciente sobre esto?»** — `buscar` con `desde`, porque la doctrina cambia.
3. Para resolver un caso concreto de punta a punta, sigue la puerta `resolver-un-caso`.

## La frontera, dicha desde el principio

- **Esto no es asesoría laboral.** Entrega pronunciamientos de la DT con su fuente para que un
  profesional decida. No reemplaza a un abogado laboralista.
- **Un pronunciamiento de la DT no es la ley ni un fallo.** Es la interpretación administrativa del
  Servicio. **Aquí no hay sentencias de tribunales**, y hay materias que solo resuelven ellos.
- **De la ley, está el Código del Trabajo y algunas leyes laborales** (21.561, 21.755, 21.645 y 21.643
  «Ley Karin»; la lista exacta la da `listar_cobertura`). `ver_articulo` entrega cada artículo en la versión vigente que publica
  la BCN, con los dictámenes que lo citan. **No está su historia** (el texto que regía antes) **ni las
  demás leyes** (16.744, 19.728 y otras): si la respuesta depende de ellas, dilo y remite a Ley Chile.
- **La vigencia no está declarada.** La DT no la publica de forma estructurada. Un dictamen puede
  haber sido reconsiderado por otro posterior, y **eso no figura en el documento superado**. Este
  saber marca *señales* de reconsideración con una regla estricta, sin revisar: una señal es un
  aviso, y su ausencia no prueba que la doctrina siga vigente.
- **El corpus es una muestra.** No es el archivo de la DT. «No aparece» no significa «no existe», y
  puede haber un pronunciamiento posterior a la última cosecha.
- **La mayoría del corpus son fichas, no documentos leídos.** Cada resultado dice su `texto_origen`:
  - `html`: se leyó el cuerpo, y se puede citar un pasaje literal.
  - `solo-resumen`: se abrió la página, pero el cuerpo es un PDF que no se leyó.
  - `solo-ficha`: solo se tiene la ficha del listado de la DT (título, fecha y resumen). Es la gran mayoría.

  En los dos últimos casos lo único citable es el **resumen del portal**, y hay que decirlo.
- **Sin cálculos.** Este saber dice qué pronunció la DT; no liquida finiquitos ni horas extras.

## Reglas que no se negocian

- Toda afirmación sobre lo que pronunció la DT va **con su cita y su URL**, para que quien la reciba
  pueda abrirla y verificarla.
- Lo que llegue como `no_derivable` **no se estima** ni se completa con conocimiento general.
- **Ante la falta de respaldo, se dice que no hay respaldo.** Abstenerse es una respuesta válida, y
  aquí es la correcta más veces de lo que parece.
