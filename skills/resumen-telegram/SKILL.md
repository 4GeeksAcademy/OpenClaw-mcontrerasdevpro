---
name: resumen-telegram
description: Envía un resumen estructurado del día o alertas prioritarias al canal de Telegram del usuario.
---

# Skill: Resumen en Telegram

## Cuándo usar
Cuando te pida un resumen de mi día, cuando se active un recordatorio importante o al iniciar mi jornada de AI Engineering.

## Prerrequisitos
- El servidor MCP de Zapier con la integración de Telegram activa.
- Cargar correctamente los datos de USER.md y MEMORY.md para dar un contexto personalizado.

## Procedimiento
1. Extrae los puntos clave sobre mis proyectos actuales y las lecciones aprendidas anotadas en mi memoria a largo plazo.
2. Dale un formato amigable utilizando viñetas claras y el emoji identificador del agente (🧭).
3. Envía el mensaje estructurado utilizando la herramienta de integración de Telegram.
4. Confirma en el log local de la sesión que el envío fue exitoso.

## Salida esperada
Un mensaje directo recibido en el móvil del usuario que resume las prioridades actuales en menos de 5 líneas, respetando el estilo definido en SOUL.md.

## Casos especiales
- Si no hay información relevante nueva en el sistema de memoria, genera un mensaje breve de buenos deseos enfocado en las tareas pendientes de 4Geeks Academy.
