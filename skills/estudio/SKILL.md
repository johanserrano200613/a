---
name: estudio
description: Flujo de estudio guiado para parciales, quices y laboratorios. Se activa cuando el usuario escribe /estudio.
activation: /estudio
---

# /estudio

Objetivo: convertir materiales del usuario en un sistema de estudio completo, visual, activo y orientado al tipo real de evaluación.

## 1. Al activarse

Primero revisar lo que YA se sabe en la conversación y NO volver a preguntar datos ya dados.

Preguntar solo lo que falte para completar este perfil:

- Asignatura y tema.
- Fecha y hora del parcial.
- Tipo de evaluación: teórica, práctica, teórico-práctica, oral, laboratorio, problemas, opción múltiple, desarrollo, etc.
- Duración aproximada del examen si se conoce.
- Cuánto tiempo real tiene para estudiar: hoy, mañana y total.
- Materiales oficiales: PDFs, fotos, diapositivas, apuntes, talleres, guías, rúbricas.
- Qué temas entran y cuáles NO entran.
- Nivel actual del estudiante de 0 a 10.
- Meta: aprobar, nota objetivo o dominar el tema.
- Cómo pregunta el profesor: pedir parciales anteriores, preguntas reales, ejemplos o correcciones si existen.
- Si el profesor valora palabras exactas, cálculos, procedimientos, interpretación, dibujos, tablas o casos.
- Si se permite ampliar con conocimiento externo o si debe usarse SOLO el material del profesor.
- Preferencia de estudio: escribir, mnemotecnias, preguntas, ejercicios, dibujos, explicación oral, etc.
- Si quiere PDF final y si debe publicarse en GitHub.

Para laboratorio preguntar además:
- Qué prácticas realizaron.
- Reactivos, materiales y equipos usados.
- Procedimientos que pueden pedir que ejecute.
- Observaciones/resultados esperados.
- Cálculos o conversiones del laboratorio.
- Errores experimentales comunes.
- Si habrá estaciones prácticas, identificación de muestras/equipos o interpretación de resultados.

## 2. Regla de fuentes

El material enviado por el usuario es la base principal.

No reemplazar ni corregir silenciosamente lo que diga la guía del profesor.

Cuando se agregue una explicación, analogía, ejemplo o dato que no esté literalmente en la fuente, marcarlo como:
- EXPLICACIÓN SENCILLA / ANALOGÍA, o
- AMPLIACIÓN / DATO CURIOSO.

Si el usuario pide investigar o verificar, distinguir claramente:
- SEGÚN LA GUÍA
- AMPLIACIÓN / FUENTE EXTERNA

## 3. Estructura obligatoria del estudio

Cada concepto importante debe tener, cuando aplique:

1. CONCEPTO NORMAL
   Definición correcta con vocabulario de la asignatura.

2. EN 5 AÑOS
   Explicación extremadamente sencilla, sin perder la idea central.

3. IMAGÍNALO
   Analogía visual o escena mental para recordarlo.

4. PALABRAS CLAVE
   Términos exactos y puntuales que podrían aparecer en completar, relacionar o definir.

5. POR QUÉ IMPORTA
   Relación con la práctica, problema o pregunta de parcial.

6. DATO CURIOSO
   Solo cuando aporte memoria o comprensión. Marcarlo como ampliación si no viene de la guía.

7. MNEMOTECNIA
   Si el tema contiene listas, rutas, clasificaciones, pasos, enzimas, reactivos o nombres.

8. PREGUNTA TIPO PROFESOR
   Basada en el estilo real observado del docente, no en preguntas genéricas.

9. ERROR / TRAMPA
   Confusiones frecuentes, resultados anormales y cómo detectarlos.

10. RECUPERACIÓN ACTIVA
   Mini reto, espacio para responder o pregunta sin respuesta visible inmediata.

## 4. Si el parcial es práctico o de laboratorio

Añadir obligatoriamente:

- Estaciones prácticas simuladas.
- Equipo/muestra/reactivo -> identificación -> función.
- Procedimiento paso a paso.
- Qué debe observar.
- Qué significa cada resultado.
- Controles positivos y negativos si aplica.
- Errores de técnica y cómo cambian el resultado.
- Preguntas de “qué salió mal y por qué”.
- Seguridad y manejo correcto del equipo cuando aplique.
- Cálculos con unidades y conversiones.
- Simulacro teórico-práctico cronometrado.
- Respuestas y criterio de autoevaluación.

## 5. Plan de estudio

Construir un plan REALISTA según el tiempo disponible.

Priorizar:
- Alta probabilidad de pregunta.
- Temas que conectan varios conceptos.
- Procedimientos y cálculos.
- Errores que el estudiante ya comete.
- Palabras exactas del profesor.

Usar ciclos:
- aprender
- cerrar material
- recuperar de memoria
- corregir
- repetir errores

No gastar el mismo tiempo en todo.

## 6. Estilo del PDF

El PDF NO debe parecer un resumen plano.

Debe ser visual y escaneable:
- portada limpia;
- bloques de colores;
- tablas;
- conceptos separados;
- tarjetas “CONCEPTO / EN 5 AÑOS / IMAGÍNALO”;
- palabras clave resaltadas;
- preguntas intercaladas;
- mnemotecnias;
- mini retos con espacios;
- datos curiosos;
- secciones prácticas;
- errores/trampas;
- simulacro;
- respuestas;
- última hoja “ESTO SÍ O SÍ”.

Evitar:
- paredes de texto;
- páginas casi vacías;
- tablas cortadas;
- texto apretado;
- caracteres dañados.

Antes de entregar:
1. generar PDF;
2. renderizar todas las páginas;
3. revisar visualmente cada página;
4. corregir cortes, solapamientos o páginas mal distribuidas.

## 7. Entrega de PDFs

Preferencia permanente del usuario para este flujo:

Cuando pida un PDF de estudio:
- generar el PDF final;
- verificar visualmente;
- subir el archivo PDF REAL a GitHub;
- NO sustituirlo por README, Markdown ni enlace sandbox como entrega principal;
- usar preferentemente el repositorio johanserrano200613/a;
- crear una rama descriptiva tipo pdf-<tema>-<año>;
- guardar bajo documentos/<nombre>.pdf;
- verificar que el archivo GitHub empiece como PDF válido;
- entregar el enlace GitHub que abre el .pdf.

Si GitHub falla de verdad, decirlo explícitamente y no fingir que el README es el PDF.

## 8. Cierre

Terminar con:
- qué priorizar;
- qué puede ignorar si queda poco tiempo;
- simulacro o siguiente acción;
- PDF en GitHub si fue solicitado.
