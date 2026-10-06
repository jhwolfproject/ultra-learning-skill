---
name: ultra-learning
description: Crea un plan de ultraaprendizaje de 3 meses para dominar cualquier tema desde cero, combinando principios de Ultralearning, Atomic Habits y Make It Stick. Usar cuando el usuario quiera aprender algo rápido y a fondo, dominar una habilidad en un plazo corto, o pida un plan de estudio con método, aunque no diga literalmente "ultra learning".
---

# Ultra Learning

Esta skill arma un plan de aprendizaje intensivo de 3 meses. Tiene tres etapas: primero el marco de principios, luego las preguntas, y al final el plan.

## Etapa 1: Principios de referencia

Usa estos puntos como base del plan. Son resúmenes propios, no citas de los libros.

### 1. Antes de empezar (preparación)
- **Metalearning** (*Ultralearning*): investigar cómo se aprende la habilidad y definir una meta medible.
- **Make it obvious** (*Atomic Habits*): dejar la señal de práctica a la vista.
- **Plan your schedule and environment** (*Atomic Habits*): decidir cuándo y dónde practicar, y preparar el material.

### 2. Durante el proceso
- **Make it easy** (*Atomic Habits*): empezar con el paso más pequeño posible.
- **Make it attractive** (*Atomic Habits*): que la práctica te dé ganas de empezar.
- **Focus** (*Ultralearning*): practicar en bloques largos y sin distracciones.
- **Directness** (*Ultralearning*): practicar la habilidad en su forma real.
- **Drill** (*Ultralearning*): atacar la parte más difícil o débil.
- **Retrieval practice** (*Make It Stick* / *Ultralearning*): recordar de memoria en vez de releer.
- **Interleaving** (*Make It Stick*): mezclar temas o tipos de problema.
- **Elaboration** (*Make It Stick*): explicar con tus palabras y relacionar con lo que ya sabes.
- **Feedback** (*Ultralearning*): recibir correcciones rápidas y frecuentes.
- **Make it satisfying** (*Atomic Habits*): cerrar cada sesión con una recompensa inmediata.

### 3. At the end (consolidación y cierre)
- **Spaced practice** (*Make It Stick*): repasar con intervalos cada vez más largos.
- **Retention** (*Ultralearning*): diseñar un sistema de repasos a largo plazo.
- **Intuition** (*Ultralearning*): llegar a responder sin pensar cada paso, gracias a la práctica abundante y variada.
- **Experimentation** (*Ultralearning*): evaluar qué funcionó y ajustar el método.
- **Identity** (*Atomic Habits*): reforzar "soy alguien que hace esto", para que el hábito se sostenga sin depender de la motivación.

## Etapa 2: Preguntas de diagnóstico

Cuando el usuario diga qué quiere aprender (por ejemplo, programación), **haz estas preguntas antes de armar nada**. Hazlas en tandas de 3 o 4 para no abrumar, y espera las respuestas.

1. **Tema concreto:** ¿qué parte del tema? (por ejemplo, Python para datos, JavaScript para web, programación en general)
2. **Nivel actual:** ¿cero, básico o intermedio? ¿Qué ya sabes hacer?
3. **Meta medible a 3 meses:** ¿qué debe ser capaz de hacer al final? (por ejemplo, desplegar una app, automatizar una tarea real, pasar una entrevista)
4. **Proyecto final:** ¿hay un proyecto concreto que quieras construir?
5. **Horas disponibles:** ¿cuántas horas por día y cuántos días por semana?
6. **Horario preferido:** ¿mañana, tarde o noche? ¿Cuándo tienes más energía?
7. **Compromisos fijos:** ¿trabajo, entrenamiento u otros horarios que no se pueden mover?
8. **Recursos disponibles:** ¿tienes computador, internet y cuánto presupuesto para cursos o herramientas?
9. **Idioma de los materiales:** ¿español, inglés u otro?
10. **Estilo de aprendizaje:** ¿prefieres videos, lectura, práctica directa o un mix?
11. **Apoyo:** ¿tienes mentor, comunidad o alguien que revise tu trabajo?
12. **Retroalimentación:** ¿cómo sabrás si lo estás haciendo bien? (tests, revisión de código, retos)
13. **Historial de abandono:** ¿en qué suele fallarte el aprendizaje? ¿Qué señal te avisa que vas a dejarlo?
14. **Criterio de salida:** ¿qué fecha de revisión y qué resultado concreto decidirían si sigues o cambias de método?

## Etapa 3: Plan de 3 meses

Con las respuestas, arma el plan así:
- **Semana 1:** medir el punto de partida y definir la meta medible.
- **Meses 1 a 3:** sesiones en bloques, siguiendo los puntos de la etapa 1 en el orden de fases (antes, durante, al final). Cada sesión empieza con el paso más fácil y termina con una recompensa.
- **Repasos:** programados con intervalos crecientes, y una prueba de recuperación cada semana.
- **Revisión:** en la fecha de revisión, compara contra el criterio de salida, no contra cómo se siente el usuario ese día.

Ajusta horas y carga según lo que dijo el usuario. Si su tiempo es limitado, prioriza práctica directa sobre teoría.

## Etapa 4: Exportar el plan a PDF

Cuando el usuario pida el plan en PDF, o al terminar la etapa 3:

1. Crea un archivo HTML de una sola hoja A4 horizontal, con el plan en sprints semanales (una tarjeta por semana), las fechas de inicio y fin, y las evaluaciones mensuales marcadas.
2. Exporta el HTML con Chrome sin ventana, desde la terminal:

```bash
"<ruta a chrome>" --headless=new --disable-gpu --no-pdf-header-footer --print-to-pdf="plan.pdf" "file:///<ruta absoluta>/plan.html"
```

3. Verifica que el PDF tenga una sola página. Si tiene más, reduce el tamaño de letra o los márgenes del HTML.

En Windows, la ruta típica de Chrome es `C:\Program Files\Google\Chrome\Application\chrome.exe`.
