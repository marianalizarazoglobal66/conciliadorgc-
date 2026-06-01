# ReconciliadorGC — Global81 SPA

Herramienta de conciliación contable que cruza los movimientos del estado de cuenta
de tarjetas de crédito corporativas contra los documentos del sistema Manager.

Aplicación **100% estática**: un único `index.html` autocontenido (React + SheetJS vía CDN).
No requiere build ni servidor.

## Despliegue en Vercel

Este repositorio se despliega como sitio estático sin configuración:
Vercel sirve `index.html` directamente. No hay paso de build.

- **Framework Preset:** Other
- **Build Command:** *(vacío)*
- **Output Directory:** *(raíz / vacío)*

Cada `git push` a la rama `main` publica automáticamente la nueva versión.
