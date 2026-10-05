# SKILLS_DESIGN.md - Diseño de Habilidades para Miguel

## Convención Global de Herramientas
- De acuerdo con las reglas de AGENTS.md, el agente utilizará de forma prioritaria el sistema de "skill tools" (directorio `skills/`) antes de procesar cualquier flujo genérico.

## Skill 1: nota-en-drive
- **¿Qué hace esta skill?** Guarda una nota, idea o resumen directamente en Google Drive como un documento de texto editable.
- **¿Qué input necesita?** El texto provisto por el usuario. Si está vacío, solicita el contenido. Aplica los prefijos "AIE-", la fecha actual y la carpeta de destino.
- **¿Cómo es un buen output?** Creación exitosa del archivo mediante `google_drive_create_file_from_text` con `convert: verdadero`, devolviendo el enlace directo en el chat.

## Skill 2: resumen-telegram
- **¿Qué hace esta skill?** Envía un resumen estructurado del día o alertas prioritarias al canal de Telegram basándose en USER.md y MEMORY.md.
- **¿Qué input necesita?** Automatizado desde los archivos de contexto a largo plazo.
- **¿Cómo es un buen output?** Un mensaje en Telegram con viñetas limpias usando el emoji identificador (🧭) en menos de 5 líneas.
