# SnipX - Snippets de Componentes HTML y CSS

Una extensión de **Visual Studio Code** que proporciona snippets listos para usar de componentes HTML y animaciones CSS avanzadas. Ahorra tiempo generando código de calidad con un simple prefijo.

## 🎯 Características

### Snippets HTML

- **Navbar Responsiva** - Barra de navegación con menú móvil integrado
- **Formularios Estilizados** - Inputs, textareas y botones con estilos modernos
- **Tarjetas de Contenido** - Cards responsive con soporte para imágenes y contenido dinámico
- **Grillas de Galería** - Layouts optimizados para galerías de imágenes
- **Modales Accesibles** - Diálogos modal con overlay y cierre interactivo

### Snippets CSS

- **Botón con Efecto Líquido** (prefix: `btn-li`) - Animación suave al hover con gradientes
- **Máquina de Escribir** (prefix: `typewriter`) - Efecto de escritura progresiva con cursor parpadeante
- **Botón Neón** (prefix: `btn-neon`) - Efecto neon multicolor con pulso infinito
- **Botón de Carga** (prefix: `btn-loa`) - Spinner animado con transformación circular
- **Tarjeta Flip 3D** (prefix: `card-3d`) - Volteo 3D con contenido frontal y trasero
- **Tarjeta Tilt 3D** (prefix: `3d-animation`) - Rotación 3D basada en la posición del cursor
- **Iconos Magnéticos** (prefix: `icons`) - Efecto magnético con atracción hacia el cursor

## 📋 Requisitos

- **VS Code 1.107.0** o superior
- Navegador moderno que soporte CSS Grid, Flexbox y transforms 3D

No se requieren dependencias externas. SnipX funciona completamente como una extensión nativa de VS Code.

## 🔧 Instalación

1. Abre VS Code
2. Ve a la sección de **Extensiones** (`Ctrl+Shift+X` o `Cmd+Shift+X`)
3. Busca "SnipX"
4. Haz clic en **Instalar**

O instálalo desde la línea de comandos:

```bash
code --install-extension johan.SnipX
```

## ⚙️ Configuración de la Extensión

Actualmente, SnipX no requiere configuración adicional. Los snippets se activan automáticamente para archivos `.html` y `.css`.

### Próximas mejoras de configuración (roadmap):

- `snippx.enableHTMLSnippets`: Activar/desactivar snippets de HTML
- `snippx.enableCSSSnippets`: Activar/desactivar snippets de CSS
- `snippx.cssFramework`: Seleccionar entre Tailwind, Bootstrap o CSS puro
- `snippx.theme`: Tema de colores predefinido (dark, light, neon, minimal)

## 🚀 Uso

### Activar un snippet

1. Abre un archivo `.html` o `.css`
2. Escribe el prefix del snippet que deseas (ej: `btn-li`)
3. Presiona `Tab` o `Enter` para insertar el código

**Ejemplo:**

```
Escribe: btn-neon
Resultado: Se inserta el código CSS del botón neón completo
```

### Personalización

Todos los snippets están diseñados para ser editados fácilmente. Después de insertarlos, puedes:

- Cambiar colores y gradientes
- Ajustar duraciones de animaciones
- Modificar tamaños y espacios
- Adaptar clases CSS a tu proyecto

## 🎨 Ejemplos de Uso

### Botón Neón

```css
/* Después de insertar 'btn-neon' */
button {
  /* Cambiar colores según tu diseño */
  background: #111; /* tu color base */
  box-shadow: 0 0 10px #ff0080; /* tu color neón */
}
```

### Tarjeta Flip 3D

```html
<!-- El snippet incluye la estructura HTML y CSS lista para usar -->
<div class="card-flip-container">
  <div class="card-flip">
    <div class="card-front"><!-- Tu contenido --></div>
    <div class="card-back"><!-- Tu contenido --></div>
  </div>
</div>
```

## 📦 Archivos Incluidos

- `snippets/snippets.code-snippets` - Snippets de HTML
- `snippets/css-snippets.code-snippets` - Snippets de CSS
- `package.json` - Configuración de la extensión
- `README.md` - Este archivo

## 🐛 Problemas Conocidos

- Los efectos 3D pueden tener un rendimiento limitado en navegadores antiguos (IE11 y anteriores)
- Algunos snippets incluyen código JavaScript comentado para funcionalidades adicionales que requieren su integración manual

## 💡 Sugerencias y Mejoras

¿Tienes ideas para nuevos snippets? [Abre un issue](https://github.com/Johan409IA/SnipX/issues) con tus sugerencias.

## 📝 Notas de Versión

### 0.0.1 (Versión Inicial)

- Lanzamiento inicial de SnipX
- 7 snippets CSS con efectos visuales avanzados
- Soporte para HTML y CSS
- Estructura de proyecto lista para publicación

### Próximas versiones

- [ ] Añadir más snippets de componentes HTML
- [ ] Integración con frameworks CSS populares
- [ ] Snippets para formularios avanzados
- [ ] Temas personalizables
- [ ] Librería de iconos SVG

## 📄 Licencia

MIT License - Eres libre de usar, modificar y distribuir esta extensión.

## 🙋 Soporte

Para reportar bugs o solicitar características, visita:

- [GitHub Issues](https://github.com/Johan409IA/SnipX/issues)
- [Email](johan2a409@gmail.com)

---

**¡Disfruta creando con SnipX!** 🚀
