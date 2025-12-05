# APS Preliquidación

Sistema de Rendiciones de Colegios Privados Subsidiados - Dirección de Educación Privada Mendoza

## Características

- Autenticación con Supabase
- Registro de usuarios (Colegios y Auditores)
- Recuperación de contraseña
- Carga de archivos Excel con validación
- Panel de auditoría con filtros
- Generación de plantillas Excel

## Tecnologías

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Supabase (Auth, Database, Storage)
- ExcelJS

## Variables de Entorno

Copia `.env.example` a `.env.local` y configura las variables:

```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Desarrollo

```bash
npm install
npm run dev
```

## Despliegue

El proyecto está preparado para desplegarse en Vercel.
