# Reglas de esta biblioteca de práctica

Esta carpeta contiene ejemplos ficticios del curso de Git para personas no técnicas.
Responde en español sencillo. Resuelve los pasos con tus herramientas: el alumno
no tiene que escribir comandos, elegir identificadores ni nombrar ramas.

## Documentos
- Conserva sin modificaciones las notas originales de `notas/`. Puedes añadir notas nuevas.
- Guarda la limpieza, las etiquetas y los enlaces en `biblioteca/`.
- Conserva la fecha de origen y la fuente de cada nota. La fecha del commit es otra fecha.
- Distingue lo escrito en las fuentes de tus interpretaciones. No inventes decisiones.
- Modifica `propuesta-taller.md` cuando el usuario pida actualizar la propuesta.

## Preparar la biblioteca
Cuando el usuario pida preparar esta biblioteca, comprueba primero la carpeta y Git.
Si no existe repositorio, inicialízalo aquí con `main` como rama principal.
Si esta carpeta está dentro de otro repositorio, explica el caso antes de tocarlo.
Si falta identidad para el commit, usa solo en este repositorio la identidad ficticia
`Alumno del taller <demo@example.invalid>`. No cambies la configuración global.
Cuenta y guarda los originales, la propuesta, estas reglas y las skills en un commit
`entrada: preparar biblioteca con N notas`, sustituyendo N por la cantidad real
(en este ejemplo son 10). Ponle la etiqueta `inicio-biblioteca`.
Si el punto inicial ya existe, compruébalo y no dupliques commits ni etiquetas.
No organices las notas durante esta preparación.

## Ramas y commits
- Antes de editar, comprueba la rama y los cambios pendientes. No mezcles trabajo ajeno.
- Prepara cada propuesta en una rama desde `main`: `<accion>/<tema>-<numero>`.
- Usa números de dos cifras y el siguiente disponible; nunca sobrescribas una rama.
- Ejemplos: `organizar/notas-01` y `actualizar/taller-01`.
- Guarda un commit por tarea terminada y comprobada, sin pedir otra confirmación.
- Mensaje: `<tipo>: <cambio concreto>`. Tipos: entrada, organizar, actualizar, recuperar.
- Cuenta notas y cambios antes de describirlos. No crees commits vacíos.
- Incluye solo los archivos de la tarea. Conserva las ramas y el historial.

## Aceptar una propuesta
Cuando el usuario diga que aprueba la propuesta actual, esa frase autoriza la integración.
Comprueba que esté guardada y sin cambios pendientes; incorpórala a `main` con
avance rápido (`merge --ff-only`) y quédate en `main`. Conserva la rama de trabajo.
Si las ramas han divergido, explica qué impide el avance antes de continuar.
La aprobación no necesita otro commit si el contenido ya está guardado.

## Recetas
- Organizar notas o incorporar una nota y actualizar documentos: lee y usa
  `.agents/skills/organizar-notas/SKILL.md`.
- Volver al punto previo o retomar una propuesta: lee y usa
  `.agents/skills/recuperar-version/SKILL.md`.
- Preguntar por notas, versiones o evolución: lee y usa
  `.agents/skills/consultar-memoria/SKILL.md`.
- Si el usuario solo pide ver o explicar una regla o una skill, muéstrala sin ejecutarla.

## Al terminar
Resume qué cambió, la rama actual y si el resultado está pendiente de aprobación.
Muestra los documentos o diferencias solicitados en el chat para facilitar su revisión.
Una consulta no cambia archivos ni crea commits. No publiques ni conectes servicios.
