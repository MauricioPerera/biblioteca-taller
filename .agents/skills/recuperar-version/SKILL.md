---
name: recuperar-version
description: Vuelve al estado principal conservando una organización pendiente, retoma esa propuesta guardada o recupera un documento de una versión anterior sin borrar el historial.
---

# Recuperar o retomar una versión

Usa `AGENTS.md`. Identifica el objetivo con las ramas y el historial; no pidas
al alumno identificadores que puedes averiguar tú.

- Comprueba primero el estado de trabajo. Si existen cambios sin guardar,
  explica cuáles son y resuelve su destino con el usuario antes de cambiar de rama.
  No los descartes ni los mezcles con una tarea diferente.
- Si pide volver a la biblioteca anterior a una organización todavía no aprobada,
  confirma que esa organización tiene commit y cambia a `main`. Conserva su rama.
  En esta demostración `main` contiene el punto previo: los diez originales y
  la propuesta inicial; `biblioteca/` deja de aparecer al cambiar de rama.
  Confirma ese resultado sin crear un commit vacío.
- Si pide retomar la organización guardada, localiza la rama `organizar/notas-NN`
  que contiene esa propuesta y vuelve a ella. Si varias propuestas encajan y el
  historial no resuelve cuál quiere, pregunta cuál. Retomar no implica aprobar;
  una aprobación explícita del usuario sí se tramita según `AGENTS.md`.
- Si pide recuperar un documento ya aprobado, consulta versiones anteriores sin
  mover `main` hacia atrás. Crea una rama `recuperar/<tema>-NN` desde `main`,
  recupera solo el documento solicitado, revisa diferencias y registra el cambio
  con `recuperar: <explicación>`. Queda pendiente de aprobación como las otras tareas.
  Distingue la recuperación de ese documento de recuperar toda la biblioteca.

No uses `reset --hard`, `clean`, eliminación de ramas ni reescritura del historial.
Termina indicando qué versión se ve ahora, qué carpetas de contenido están
presentes y dónde sigue la propuesta conservada. Muéstralo en el chat.
