# Plantilla de Skill (Capacidad)

> **Propósito:** Este archivo es un modelo para crear nuevas capacidades para tu AI OS. Cuando la IA detecte una tarea repetitiva (ej: limpiar BD de desarrollo, hacer un despliegue), puede crear un archivo nuevo basado en este formato.

## Nombre de la Skill: [Nombre]
## Descripción Breve: [Qué hace esta automatización]

---

### Cuándo usarla (Triggers)
(Condiciones bajo las cuales la IA debería sugerir o ejecutar esta skill)
- Cuando el usuario pide hacer X.
- Cuando falla el despliegue con el error Y.

### Prerrequisitos
(Qué herramientas deben estar instaladas, ej: Firebase CLI, Docker)
- [ ] Herramienta 1
- [ ] Permisos especiales

### Flujo de Ejecución (Pasos)
1. Ejecutar el comando `...`
2. Leer la salida y verificar `...`
3. Si ocurre un error X, aplicar mitigación Y.

### Scripts Asociados (Opcional)
(Si la skill requiere un script de Node o Python complejo, referenciar la ruta relativa acá, ej: `scripts/mi-script.js`)
