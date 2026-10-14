# PROYECTOS

Catálogo privado de proyectos con vista pública de solo lectura.

## Stack inicial

- Next.js + TypeScript
- Neon PostgreSQL
- Drizzle ORM
- Zod
- Arquitectura de monolito modular

## Configuración local

1. Instalar dependencias con `npm.cmd install`.
2. Copiar `.env.example` a `.env.local`.
3. Configurar `DATABASE_URL` únicamente en `.env.local`.
4. Iniciar el entorno con `npm.cmd run dev`.

La conexión real de Neon nunca debe subirse a GitHub.

## Módulos previstos

- `src/modules/auth`: autenticación y sesiones.
- `src/modules/projects`: gestión de proyectos.
- `src/modules/sharing`: reglas de visibilidad pública.
- `src/db`: esquema y cliente de Neon.
