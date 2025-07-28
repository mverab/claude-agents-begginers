# Agentes Personalizados para Claude Code

Este repositorio contiene agentes personalizados para Claude Code.

## Instalación

### Para uso específico de un proyecto
Copia los agentes al directorio `.claude/agents/` de tu proyecto:
```bash
mkdir -p .claude/agents
cp agents/*.md .claude/agents/
```

### Para uso global (todos los proyectos)
Copia los agentes al directorio Claude de tu usuario:
```bash
mkdir -p ~/.claude/agents
cp agents/*.md ~/.claude/agents/
```

## Agentes Disponibles

- **code-refactorer**: Asistencia para refactorización de código
- **content-writer**: Asistencia para redacción de contenido
- **frontend-designer**: Asistencia en diseño frontend
- **prd-writer**: Redacción de documentos de requerimientos de producto
- **project-task-planner**: Planificación de proyectos y desglose de tareas
- **security-auditor**: Asistencia en auditoría de seguridad
- **vibe-coding-coach**: Guía y mentoría en programación

## Uso

Una vez instalados, Claude Code detectará y usará automáticamente estos agentes cuando sean apropiados para tus tareas.
