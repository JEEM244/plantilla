# PixelStation — Plantilla CSS retro

Plantilla inicial para crear páginas web con una estética inspirada en videojuegos arcade y gráficos de 8 bits.

## Archivos

- `index.html`: página de demostración con ejemplos de los componentes.
- `styles.css`: estilos, colores, distribución, componentes, animaciones y ajustes para celular.

## Cómo verla

Descarga o clona el repositorio y abre `index.html` en el navegador. No necesita instalar programas, dependencias ni iniciar un servidor.

## Cómo reutilizar el diseño

1. Copia `styles.css` a tu proyecto.
2. Enlázalo desde el HTML dentro de `<head>`:

   ```html
   <link rel="stylesheet" href="styles.css">
   ```

3. Usa las clases de los componentes que necesites: `button`, `panel`, `tag`, `info-card`, `demo-form` y otras.
4. Cambia los textos y elimina las secciones de demostración que no necesites.

## Personalizar los colores

Al principio de `styles.css` está el bloque `:root`. Ahí puedes cambiar los colores principales sin buscar cada regla:

- `--color-bg`: fondo general.
- `--color-panel`: fondo de tarjetas y paneles.
- `--color-primary`: acento principal.
- `--color-secondary`: acento secundario.
- `--color-pink` y `--color-yellow`: colores adicionales.

## Qué incluye

- Fondo oscuro con cuadrícula.
- Colores neón y bordes marcados.
- Botones con sombra tipo píxel.
- Paneles, tarjetas, etiquetas y barra de progreso.
- Campos de formulario.
- Portada con una ilustración arcade hecha con CSS.
- Animaciones pequeñas y opción para respetar la preferencia de movimiento reducido.
- Diseño adaptable a pantallas pequeñas.

La plantilla utiliza HTML y CSS normales. No depende de Angular, React, PHP, JavaScript ni bases de datos.
