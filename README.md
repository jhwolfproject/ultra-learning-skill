# Ultra Learning Skill

Skill para Claude Code que arma un plan de aprendizaje intensivo de 3 meses. Combina principios de *Ultralearning*, *Atomic Habits* y *Make It Stick*, y exporta el plan como PDF de una hoja.

## Qué hace

1. **Principios de referencia:** organiza los puntos de los tres libros en tres fases: antes, durante y al final del proceso.
2. **Entrevista:** hace 14 preguntas en tandas para conocer tu tema, nivel, horario, recursos y criterios de evaluación.
3. **Plan de 3 meses:** arma sprints semanales con una meta medible por semana y evaluaciones al final de cada mes.
4. **PDF:** exporta el plan a una hoja imprimible.

## Instalación

Copia la carpeta a tu carpeta de skills de Claude Code:

```bash
mkdir -p ~/.claude/skills/ultra-learning
cp SKILL.md ~/.claude/skills/ultra-learning/
```

Reinicia Claude Code para que la detecte.

## Uso

Escribe algo como "quiero aprender X en 3 meses" o usa `/ultra-learning` seguido del tema.

## Licencia

MIT
