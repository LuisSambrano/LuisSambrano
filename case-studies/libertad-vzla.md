# Libertad VZLA

> **Rol**: lo empecé y lidero el desarrollo
> **Tipo**: mi proyecto principal, hoy una organización con equipo
> **Stack**: React, TypeScript, Supabase, Edge Functions

## Qué es

Libertad VZLA es una plataforma de periodismo independiente para Venezuela. Recolecta, verifica y preserva reportes ciudadanos en un contexto donde la información independiente suele estar bloqueada. La idea era pasar de un sitio estático a una redacción que funcione de verdad: una herramienta para que el equipo editorial junte, revise y publique noticias, con una lectura rápida y limpia.

## Cómo funciona

Corre sobre Supabase, con acceso por roles para el equipo (admin, editor, periodista), así cada persona toca solo lo que le corresponde. Las noticias entran por un proceso que agrupa historias parecidas de distintas fuentes y marca duplicados, para que el equipo dedique menos tiempo al ruido.

Algunas piezas técnicas:

- Backend en Supabase con Row Level Security para los distintos roles.
- Un proceso de ingesta que detecta y junta historias parecidas usando búsqueda vectorial.
- Un flujo editorial con permisos detallados, armado según cómo trabaja una redacción real.
- Un frontend con Tailwind y Framer Motion, hecho para sentirse rápido y tipo app en la web.

## Stack

- **Frontend**: React, TypeScript, Vite, Tailwind, Framer Motion.
- **Backend**: Supabase (PostgreSQL), Edge Functions (Deno).
- **IA**: para agrupar y etiquetar las noticias que entran (búsqueda semántica).

---

Repositorio privado. Con gusto muestro el código o la arquitectura si hace falta.
