# SKILLS_DESIGN.md - Diseño de Habilidades para Miguel

## Skill 1: nota-en-drive
- **¿Qué hace esta skill?** Guarda una nota, idea o resumen directamente en Google Drive como un documento de texto editable.
- **¿Qué input necesita?** El texto de la nota provisto por el usuario. Utiliza las convenciones de TOOLS.md y AGENTS.md para estructurar el nombre y la ubicación del archivo.
- **¿Cómo es un buen output?** Un documento en Google Drive con el prefijo "AIE-", la fecha actual en su título, almacenado en la carpeta "Agente", devolviendo el enlace directo al usuario.

## Skill 2: resumen-telegram
- **¿Qué hace esta skill?** Envía un resumen estructurado con mis tareas pendientes y prioridades del día directamente a mi móvil a través del canal conectado de Telegram.
- **¿Qué input necesita?** Ninguno manual de forma obligatoria. El agente lee el contexto del día de forma automática desde las directivas internas de USER.md y MEMORY.md.
- **¿Cómo es un buen output?** Un mensaje instantáneo en Telegram enviado por Miguel 🧭 que contiene los puntos clave del día formateados con claridad y emojis.
