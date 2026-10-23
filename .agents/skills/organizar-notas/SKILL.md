---
name: organizar-notas
description: Organiza las notas de esta biblioteca por temas, con limpieza, etiquetas y enlaces; también incorpora notas nuevas y actualiza la propuesta cuando el usuario lo pide.
---

# Organizar las notas de la biblioteca

Aplica las reglas de `AGENTS.md`. Esta receta prepara una propuesta guardada;
la aprobación e incorporación a `main` corresponden a una petición posterior.

1. Comprueba que existe el estado inicial guardado y que no hay cambios pendientes.
   Si hay trabajo ajeno o ambiguo, identifícalo sin guardarlo ni descartarlo.
   Si esta misma tarea quedó a medias y puedes identificar tus propios cambios,
   continúala en su rama; no la dupliques. Para una tarea nueva parte de `main`
   y crea la siguiente rama `organizar/notas-NN`.
   Si también se pide actualizar la propuesta con una nota nueva, usa
   `actualizar/taller-NN`. No abandones sin guardar una propuesta previa.
2. Lee todas las notas y la propuesta actual. Si recibiste una nota nueva,
   guárdala completa en `notas/nota-NN.md`, con el siguiente número disponible.
   Usa solo la fecha y la fuente proporcionadas; si faltan, indica que no constan.
3. Crea o actualiza una versión limpia de cada original en
   `biblioteca/notas/nota-NN.md`: título, fecha de origen, fuente, etiquetas,
   contenido limpio, enlace al original y enlaces relativos a notas relacionadas.
   Mantén un archivo por original, incluso si dos dicen algo parecido.
   No borres incertidumbres, matices ni diferencias entre las fuentes.
4. Crea o actualiza `biblioteca/INDICE.md` con grupos temáticos y enlaces a todas
   las notas limpias. Crea o actualiza `biblioteca/RESUMEN.md` con una síntesis
   apoyada en enlaces a las notas. Separa antecedentes de decisiones posteriores.
5. Si el usuario pidió actualizar la propuesta, modifica `propuesta-taller.md`
   únicamente según la nueva decisión. Conserva el resto, incluida la fecha
   del taller, salvo que la fuente indique otro cambio. Refleja la decisión
   también en el resumen, conservando los antecedentes y sus fuentes.
6. Comprueba que los originales previos siguen idénticos, cada original tiene
   su versión limpia, no hay enlaces locales rotos y los cambios de la propuesta
   coinciden con la fuente. No conviertas una interpretación en un dato confirmado.
7. Revisa las diferencias y guarda solo la tarea en un commit. Para la primera
   organización usa `organizar: clasificar las 10 notas del taller`; para el ajuste
   del ejemplo, `actualizar: ajustar el taller a 60 minutos y 8 personas en línea`.
   En otras tareas escribe una descripción fiel al cambio real.
8. Entrega una vista breve del índice o del cambio solicitado, indica qué conservaste
   y que la propuesta está guardada en su rama, pendiente de aprobación.

Si el usuario solo pide explicar esta skill, explica el procedimiento sin crear
carpetas, cambiar de rama ni ejecutar la organización.
