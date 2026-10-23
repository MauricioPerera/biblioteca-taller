---
name: consultar-memoria
description: Responde preguntas sobre fechas de las notas y evolución de la propuesta usando las fuentes y el historial de Git, sin modificar la biblioteca.
---

# Consultar la memoria de la biblioteca

Consulta únicamente: no cambies archivos, ramas, etiquetas ni commits.

1. Decide si la pregunta trata de la fecha de origen de las notas o de cambios
   guardados en Git. Son cronologías distintas. Un commit de hoy puede incorporar
   una nota de marzo. Nunca atribuyas a marzo un commit creado hoy.
2. Para preguntas como «qué investigábamos en marzo», busca `Fecha de origen`
   dentro de las notas originales. Agrupa los hallazgos y enlaza las fuentes.
   Aclara que esas fechas proceden del ejemplo, no de la antigüedad del repositorio.
3. Para explicar la evolución de la propuesta, consulta el historial de
   `propuesta-taller.md` en `main` y lee su contenido anterior y sus diferencias
   con `git log`, `git show` o `git diff`. Los títulos de los commits ayudan
   a localizar cambios, pero no sustituyen la lectura de los documentos.
4. Usa `main` para describir la evolución aceptada. Si consultas otras ramas,
   identifícalas como propuestas y distingue si fueron incorporadas. El alcance
   por defecto es esta biblioteca: no atribuyas recuerdos a chats no guardados.
5. Da una respuesta breve, en lenguaje sencillo, con documentos, identificadores
   reales de commits relevantes y fragmentos suficientes para comprobarla.
   Explica el motivo solo si una nota o el usuario lo documentó; en otro caso,
   indica que el historial muestra el cambio pero no permite saber por qué.

En la demostración, el ajuste posterior mantiene el 15 de noviembre de 2026.
Comprueba los datos en los archivos: no uses esta frase como sustituto de la evidencia.
