# Plantilla web — estilo retro terminal

Plantilla reutilizable para crear páginas con el mismo lenguaje visual del proyecto PIA: fondo oscuro, cuadrícula discreta, tipografía monoespaciada y detalles inspirados en interfaces de videojuegos clásicos.

## Archivos

- `index.html`: página de demostración con ejemplos de los componentes.
- `styles.css`: colores, distribución, componentes, animaciones y ajustes para celular.

## Cómo verla

Abre `index.html` en tu navegador. No necesita instalar programas, dependencias ni iniciar un servidor.

## Cómo reutilizarla

1. Copia `styles.css` a tu proyecto.
2. Enlázalo desde el HTML:

   ```html
   <link rel="stylesheet" href="styles.css">
   ```

3. Reutiliza las clases que necesites: `button`, `panel`, `tag`, `info-card`, `demo-form` y otras.
4. Cambia los textos y elimina las secciones de demostración que no vayas a utilizar.

## Colores del diseño

Los colores están definidos al inicio de `styles.css`, dentro de `:root`:

| Variable | Color | Uso |
| --- | --- | --- |
| `--color-bg` | `#0d1117` | Fondo general |
| `--color-panel` | `#161b22` | Paneles y tarjetas |
| `--color-text` | `#d7dee6` | Texto principal |
| `--color-muted` | `#929eaa` | Texto secundario |
| `--color-border` | `#303943` | Bordes |
| `--color-primary` | `#58a6ff` | Azul de acento |
| `--color-secondary` | `#63d471` | Verde de acento |
| `--color-yellow` | `#f0c674` | Detalles dorados |

## Qué incluye

- Fondo oscuro con cuadrícula pequeña y movimiento discreto.
- Tipografía monoespaciada.
- Botones rectos con efectos sencillos al pasar el cursor.
- Paneles, tarjetas, etiquetas y barra de progreso.
- Campos de formulario.
- Portada decorativa construida con CSS.
- Diseño adaptable a celular.
- Respeto a la preferencia del sistema para reducir movimiento.

## Tecnologías

Solo utiliza HTML y CSS. No necesita Angular, React, PHP, JavaScript, bases de datos ni dependencias externas.
