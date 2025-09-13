# Claude Agents para Principiantes 🚀

Un sistema guiado y simplificado para crear tu primer agente de Claude - ¡sin experiencia técnica requerida!

## Qué Es Esto

Este repositorio contiene un **sistema guiado de 4 pasos** que te lleva de la idea al agente funcional en aproximadamente 30 minutos. Perfecto para:
- 🎯 Usuarios no técnicos que quieren construir agentes
- 💡 Desarrolladores que encuentran complejo el onboarding de Claude Code
- 🚀 Cualquiera que quiera lanzar su primer agente rápidamente

## El Viaje Guiado de 4 Pasos

### 🔵 Paso 1: Guía de Ideas de Agente
**Te ayuda a descubrir y refinar el concepto de tu agente**
- Convierte ideas vagas en conceptos claros y construibles
- Hace las preguntas correctas para definir alcance y características
- No se necesita conocimiento técnico

### 🟢 Paso 2: Constructor de Agente
**Construye tu agente basado en tu idea refinada**
- Maneja toda la complejidad técnica automáticamente
- Crea prompts de agente de grado profesional
- Explica lo que está haciendo mientras construye

### 🟠 Paso 3: Instalador de Agente
**Instala automáticamente tu agente en Claude Code**
- No necesita línea de comandos ni gestión de archivos
- Elige la mejor ubicación de instalación
- Verifica que todo funcione correctamente

### 🟣 Paso 4: Probador de Agente
**Te guía a través de pruebas y optimización de tu agente**
- Escenarios de prueba estructurados
- Identifica y corrige problemas
- Asegura que tu agente funcione perfectamente

## Inicio Rápido (5 minutos)

1. **Instala los agentes guiados**:
   ```bash
   mkdir -p ~/.claude/agents
   cp guided-agents/*.md ~/.claude/agents/
   ```

2. **Inicia con Claude Code** y di:
   "Quiero usar el agent-idea-guide para crear mi primer agente"

3. **Sigue el proceso guiado** - cada agente te pasa al siguiente

4. **¡Disfruta tu nuevo agente!** 🎉

Para agentes de código (Cursor, Aider, Copilot, etc.), consulta `AGENTS.md` para una guía mínima y legible por máquina.

## Qué Construirás

Primeros agentes populares incluyen:
- **Pulidor de Emails** - Hace los emails más profesionales
- **Resumidor de Reuniones** - Extrae puntos clave y elementos de acción
- **Revisor de Código** - Proporciona retroalimentación constructiva
- **Generador de Ideas de Contenido** - Genera ideas creativas
- **Divisor de Tareas** - Divide proyectos en pasos manejables

## Por Qué Funciona Este Enfoque

### Método Tradicional (Difícil)
- ❌ Leer documentación técnica
- ❌ Entender estructuras de archivos
- ❌ Escribir prompts complejos
- ❌ Manejar instalación manualmente

### Nuestro Método Guiado (Fácil)
- ✅ Guía conversacional
- ✅ Manejo técnico automático
- ✅ Proceso paso a paso
- ✅ Pruebas integradas

## Agentes Disponibles

### Sistema Guiado (Recomendado para Principiantes)
- **agent-idea-guide**: Descubre y refina el concepto de tu agente
- **agent-builder**: Construye tu agente desde la idea refinada
- **agent-installer**: Instala automáticamente tu agente
- **agent-tester**: Prueba y optimiza tu agente

### Agentes Tradicionales (Para Usuarios Avanzados)
- **code-refactorer**: Asistencia para refactorización de código
- **content-writer**: Asistencia para redacción de contenido
- **frontend-designer**: Asistencia en diseño frontend
- **prd-writer**: Redacción de documentos de requerimientos de producto
- **project-task-planner**: Planificación de proyectos y desglose de tareas
- **security-auditor**: Asistencia en auditoría de seguridad
- **vibe-coding-coach**: Guía y mentoría en programación

## Comenzar

👉 **[Lee la Guía Completa de Inicio](GETTING_STARTED.md)** (en inglés)

¿Listo para construir tu primer agente? ¡El sistema guiado lo hace fácil! 🚀

## Compatibilidad con AGENTS.md

Este repositorio incluye un `AGENTS.md` en la raíz y otro anidado en `guided-agents/AGENTS.md`. También funciona con todos los proveedores que soportan el estándar AGENTS.md. Ejemplos populares:

- Cursor
- Aider
- Agente de código de GitHub Copilot
- Zed
- Google Gemini CLI
- RooCode
- Factory
- Amp
- Ona
- Phoenix
- VS Code (reglas de proyecto para IA)
- Warp
- Semgrep
- Devin

Los agentes leen el `AGENTS.md` más cercano en el árbol de directorios (gana el más próximo). Más info: https://agents.md/
