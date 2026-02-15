# TITAN - E-Bike Premium Landing Page

Landing page moderna y elegante para TITAN E-Bike con diseño oscuro premium (negro y rojo).

## 🚀 Características

- ✨ Diseño oscuro elegante (negro y rojo vibrante)
- 🎨 Estilo minimalista y profesional
- 📱 100% Responsive (mobile-first)
- 🌊 Navbar con efecto blur al scroll
- 🎯 Hero section a pantalla completa
- 🖼️ Galería con imágenes reales de TITAN
- ⚙️ Especificaciones técnicas completas
- 💬 Botón flotante de WhatsApp directo
- ✨ Animaciones suaves con Intersection Observer
- 🎭 Efectos parallax y hover
- ⚡ Optimizado para rendimiento

## 📁 Estructura del Proyecto

```
titan-ebike/
│
├── index.html          # Estructura HTML principal
├── style.css           # Estilos CSS personalizados
├── script.js           # JavaScript para interactividad
├── titan1.JPG          # Imagen 1 de TITAN
├── titan2.JPG          # Imagen 2 de TITAN
├── titan3.JPG          # Imagen 3 de TITAN
├── titan4.JPG          # Imagen 4 de TITAN
└── README.md           # Este archivo
```

## 🌐 Demo en Vivo

Una vez desplegado en GitHub Pages, tu sitio estará disponible en:
```
https://miguel-mm729.github.io/e-titan/
```

## 🛠️ Despliegue en GitHub Pages

### IMPORTANTE: Sube TODOS los archivos incluyendo las imágenes

1. **Ve a tu repositorio en GitHub** (e-titan)
   - Accede a https://github.com/miguel-mm729/e-titan

2. **Sube los archivos nuevos**
   - Haz clic en "Add file" > "Upload files"
   - Arrastra TODOS estos archivos:
     * index.html (reemplazar el existente)
     * style.css (nuevo)
     * script.js (nuevo)
     * titan1.JPG (imagen 1)
     * titan2.JPG (imagen 2)
     * titan3.JPG (imagen 3)
     * titan4.JPG (imagen 4)
   
3. **Commit de los cambios**
   - Escribe un mensaje: "Actualización completa TITAN con imágenes"
   - Click en "Commit changes"

4. **Verifica GitHub Pages**
   - Ve a Settings > Pages
   - Asegúrate que esté activado desde la rama `main`
   - Espera 1-2 minutos y visita: https://miguel-mm729.github.io/e-titan/

### ⚠️ Notas importantes

- **Las imágenes DEBEN estar en la raíz del repositorio** (mismo nivel que index.html)
- Los nombres de archivos son case-sensitive: `titan1.JPG` (no titan1.jpg)
- Si no ves las imágenes, verifica que se hayan subido correctamente

## 🎨 Personalización

### Cambiar el número de WhatsApp
Busca en `index.html` todas las apariciones de:
```html
https://wa.me/34697222354
```
Y reemplázalo con tu número (formato internacional sin +):
```html
https://wa.me/34TU_NUMERO
```

### Colores
Modifica las variables CSS en `style.css`:
```css
:root {
    --black: #0a0a0a;
    --red: #ff0a16;
    --red-dark: #cc0000;
}
```

### Especificaciones Técnicas
Edita los valores en la sección `#specs` del `index.html`:
- Autonomía: actualmente 30 km
- Velocidad máxima: actualmente 25 km/h (cumple normativa)

### Imágenes
Para cambiar las imágenes:
1. Sube tus nuevas imágenes al repositorio
2. En `index.html`, busca `titan1.JPG`, `titan2.JPG`, etc.
3. Reemplaza con los nombres de tus nuevos archivos

## 🔧 Tecnologías Utilizadas

- HTML5 semántico
- CSS3 moderno (Grid, Flexbox, Custom Properties)
- JavaScript Vanilla (ES6+)
- Google Fonts (Orbitron, Bebas Neue, DM Sans)
- Intersection Observer API
- Sin frameworks pesados (100% nativo)

## 📱 Compatibilidad

- ✅ Chrome (últimas 2 versiones)
- ✅ Firefox (últimas 2 versiones)
- ✅ Safari (últimas 2 versiones)
- ✅ Edge (últimas 2 versiones)
- ✅ Dispositivos móviles (iOS y Android)

## ⚡ Optimizaciones

- Lazy loading de imágenes
- Animaciones con CSS cuando es posible
- Intersection Observer para scroll animations
- Debouncing en eventos de scroll
- Mobile-first approach
- Código minificable

## 📄 Licencia

Este proyecto es de uso libre. Puedes modificarlo y adaptarlo a tus necesidades.

## 🤝 Contribuciones

Si encuentras algún bug o tienes sugerencias:
1. Abre un Issue
2. Crea un Pull Request
3. Comparte tu feedback

## 💡 Tips Adicionales

### Para mejorar el SEO:
- Añade `meta` tags en el `<head>`
- Incluye un `sitemap.xml`
- Añade un `robots.txt`
- Optimiza las imágenes (usa WebP)
- Añade textos `alt` descriptivos

### Para mejor rendimiento:
- Comprime las imágenes (TinyPNG, Squoosh)
- Minifica CSS y JS antes del despliegue
- Usa CDN para fuentes
- Implementa caché del navegador

### Para Analytics:
Añade Google Analytics en el `<head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TU-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TU-ID');
</script>
```

---

Hecho con ⚡ por [Tu Nombre]
