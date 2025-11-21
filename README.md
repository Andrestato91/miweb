# FullOps CSS Integration

Este proyecto utiliza la paleta de colores **FullOps** para mantener una identidad visual consistente.

## ✅ Cómo integrar el CSS corregido
1. Descarga el archivo `styles_corrected.css`.
2. Colócalo en la carpeta principal del proyecto (junto a `index.html`).
3. En tu `index.html`, asegúrate de incluirlo:

```html
<link rel="stylesheet" href="styles_corrected.css">
```

4. Limpia la caché del navegador (Ctrl + Shift + R) para ver los cambios.

---

## 🎨 Paleta FullOps
- **Harbor Sky**: `#0A2B30`
- **Dockside**: `#2B2B28`
- **Pearl**: `#E2E222`
- **Sandstone Dark**: `#0A2B34`
- **Sandstone Light**: `#D1A574`
- **Azure Accent**: `#00A6FF`

Estas variables están definidas en `:root` para uso global:

```css
:root {
  --harbor-sky: #0A2B30;
  --dockside: #2B2B28;
  --pearl: #E2E222;
  --sandstone-dark: #0A2B34;
  --sandstone-light: #D1A574;
  --azure-accent: #00A6FF;
}
```

---

## ✅ Buenas prácticas
- Usa **variables CSS** en lugar de valores hexadecimales directos:

```css
background-color: var(--azure-accent);
color: var(--dockside);
```

- Mantén el fondo principal neutro (blanco o sandstone claro).
- Usa el gradiente azul para secciones destacadas (hero).
- Botones: contraste alto (ej. fondo blanco + texto azul).

---

## 📂 Estructura recomendada
```
project/
├── index.html
├── styles_corrected.css
└── README.md
```

---

## 🚀 Publicación en GitHub Pages
1. Haz commit y push de los cambios.
2. Activa GitHub Pages en la rama principal.
3. Accede a la URL pública y verifica los estilos.

¡Listo! Tu sitio ahora tendrá la identidad visual FullOps.
