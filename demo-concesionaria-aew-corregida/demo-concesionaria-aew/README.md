# AutoNova — Demo comercial AEW

Sitio demostrativo de concesionaria, desarrollado con Next.js (App Router), React y CSS responsive.

## Iniciar

```bash
npm install
npm run dev
```

## Subir a Vercel

1. Descomprimí el ZIP.
2. Subí la carpeta a un repositorio nuevo en GitHub.
3. En Vercel elegí **Add New > Project** e importá el repositorio.
4. Framework: **Next.js** (detectado automáticamente). Pulsá **Deploy**.

## Personalizar

- `app/page.tsx`: editá el nombre AutoNova, los vehículos del array `cars` y la constante `phone` con el WhatsApp real (formato 549261...).
- `app/globals.css`: colores y estilos.
- `app/layout.tsx`: título y descripción SEO.

**Importante:** La web es una DEMO. Los vehículos, precios, fotos y métricas son ilustrativos. Las imágenes provienen de Unsplash y requieren conexión a internet; algunas pueden no coincidir con el modelo descrito. El botón WhatsApp requiere reemplazar el número ficticio antes de uso comercial.

No incluye backend ni panel de administración; el catálogo de demostración es editable desde código. Se puede implementar un panel real como fase posterior.
