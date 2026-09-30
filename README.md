# English Tutor Agent 🇬🇧

Este repositorio es mi **espacio personal para aprender inglés** con la ayuda de un tutor (GitHub Copilot u otro asistente de IA) configurado con instrucciones propias.

La idea es simple: practico, el tutor me corrige, y guardo todo en Markdown para poder **ver mi progreso con el tiempo** (cada commit es un paso más).

## Cómo usarlo

1. **Hacer ejercicios** — Empieza por [`exercises/starter-exercise.md`](exercises/starter-exercise.md). Escribe tus respuestas directamente en el archivo (o crea uno nuevo en `exercises/`).
2. **Pedir correcciones al tutor** — Pídele que revise tu ejercicio siguiendo [`AGENT_INSTRUCTIONS.md`](AGENT_INSTRUCTIONS.md).
3. **Registrar lo aprendido**:
   - Palabras y expresiones nuevas → [`progress/vocabulary.md`](progress/vocabulary.md)
   - Errores que se repiten → [`progress/mistakes.md`](progress/mistakes.md)
4. **Revisión semanal** — Una vez por semana completa una entrada en [`progress/weekly-log.md`](progress/weekly-log.md): qué hiciste, qué aprendiste, qué te cuesta y qué harás la semana siguiente.

> 💡 Consejo: poco y seguido es mejor que mucho de golpe. 15–20 minutos al día funcionan muy bien.

## Estructura del repositorio

```text
.
├── README.md                  # Este archivo
├── AGENT_INSTRUCTIONS.md      # Personalidad y reglas del tutor
├── exercises/
│   └── starter-exercise.md    # Ejercicio inicial para estimar tu nivel
└── progress/
    ├── weekly-log.md          # Registro semanal de progreso
    ├── vocabulary.md          # Vocabulario nuevo y fechas de repaso
    └── mistakes.md            # Errores frecuentes y sus correcciones
```

## Ejemplos de prompts para el tutor

Puedes escribirle en inglés o en español:

- *"Follow AGENT_INSTRUCTIONS.md and correct my answers in exercises/starter-exercise.md."*
- *"Based on my starter exercise, what is my approximate CEFR level?"*
- *"Give me 3 short exercises about the present perfect, at my level."*
- *"Quiz me on the words in progress/vocabulary.md that I need to review."*
- *"Look at progress/mistakes.md and give me a short exercise to practise my most common mistakes."*
- *"Let's have a 10-minute conversation about my job. Correct me at the end."*
- *"Explícame en español la diferencia entre 'since' y 'for'."*
- *"Help me write this week's entry in progress/weekly-log.md based on what we did today."*

## Cómo ver tu progresión

- Revisa el historial de commits y los pull requests para ver tus ejercicios corregidos.
- Compara las entradas de `progress/weekly-log.md` de distintas semanas.
- Marca como dominadas (`✅ mastered`) las palabras y errores que ya no te cuestan.
