
# 🎨 Nexus Design Studio v3.0

Aplicación web de diseño UI construida en un único archivo HTML (`index.html`). Permite crear y editar capas en un lienzo, ajustar propiedades visuales, generar código y exportar proyectos.

![Versión](https://img.shields.io/badge/versión-3.0-blue)
![Estado](https://img.shields.io/badge/estado-activo-brightgreen)

## ✨ Características

- Editor visual con **canvas** (pan, zoom y selección)
- Gestión de **capas** (crear, seleccionar, duplicar, eliminar, visibilidad y bloqueo)
- Panel **Inspector** para layout, apariencia y efectos
- Herramientas de diseño: rectángulo, elipse y texto
- **Historial** con undo/redo
- Menú contextual (duplicate, delete, bring to front, send to back)
- Panel de código con generación de **CSS** y **React component**
- Copia al portapapeles y descarga de CSS
- Paneles inferiores: **Code, Animation, Assets, Components, AI Chat y Preview**
- Exportación de proyecto a JSON (`nexus-project.json`)
- Onboarding inicial y notificaciones tipo toast

## 🧱 Tecnologías

- HTML5
- CSS3
- JavaScript Vanilla (ES6+)
- Canvas API

## 🚀 Uso local

```bash
git clone https://github.com/aurenox-global/inventario.git
cd inventario
python -m http.server 8000
```

Luego abre: `http://localhost:8000`

## 🕹️ Atajos y controles

- `V`: seleccionar
- `R`: rectángulo
- `O`: elipse
- `T`: texto
- `Delete`: eliminar capa seleccionada
- `Esc`: deseleccionar
- `Ctrl/Cmd + D`: duplicar
- `Ctrl/Cmd + Z`: undo
- `Ctrl/Cmd + Shift + Z`: redo
- Rueda del mouse: zoom
- Espacio + arrastrar (o clic derecho): pan

## 📦 Exportaciones

- **Proyecto completo**: JSON con artboards y capas
- **Código CSS**: copia al portapapeles o descarga (`styles.css`)

## 📄 Estructura del proyecto

- `/home/runner/work/inventario/inventario/index.html`: aplicación completa (UI + lógica)
- `/home/runner/work/inventario/inventario/README.md`: documentación del proyecto

## 📄 Licencia

Este proyecto es de uso interno de Aurenox Global. Todos los derechos reservados.
