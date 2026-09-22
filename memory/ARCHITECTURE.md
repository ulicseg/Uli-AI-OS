# Arquitectura Viva del Proyecto

> **Propósito:** Documentar las decisiones arquitectónicas clave, la estructura de la base de datos y la interconexión de servicios. La IA debe leer esto antes de proponer cambios estructurales grandes.

## 1. Stack Tecnológico General
- **Frontend:** [Ej: React / Next.js / Angular]
- **Backend:** [Ej: Node.js / Express / Cloud Functions]
- **Base de Datos:** [Ej: Firebase Firestore / Postgres]
- **Infraestructura:** [Ej: Docker / Firebase Hosting]

## 2. Decisiones Arquitectónicas (ADRs)
(Registro de por qué se tomó una decisión importante)

- **ADR-001 [Fecha]:** Por qué elegimos Firebase en lugar de X.
  - *Contexto:* ...
  - *Decisión:* ...

## 3. Esquema de Datos Principal (Ej: Firestore Collections)

### `users` (Colección)
- `uid` (String, Auth ID)
- `email` (String)
- `createdAt` (Timestamp)

### `...` (Colección)

## 4. Servicios y Contenedores (Docker)
(Lista de contenedores activos en local, ej: `firebase-emulator`, `postgres-db`, `redis-cache`)

---
*(Instrucción para la IA: Mantener este documento actualizado cada vez que se agregue una colección a la BD, un servicio nuevo, o se haga un cambio estructural importante)*
