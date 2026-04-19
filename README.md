
# 💰 FinTrack Pro – Gestión Financiera Personal

Aplicación web progresiva (PWA) diseñada para el control y seguimiento de finanzas personales. Permite registrar ingresos y gastos, visualizar estadísticas, establecer presupuestos por categorías y gestionar metas de ahorro, con todos los datos almacenados localmente en el dispositivo.

![Versión](https://img.shields.io/badge/versión-2.0-blue)
![Estado](https://img.shields.io/badge/estado-activo-brightgreen)

## ✨ Características

- **Dashboard principal** con balance total, ingresos y gastos
- Registro rápido de transacciones con categorías personalizables
- **Gráficos interactivos** de tendencias y distribución por categoría
- Gestión de **presupuestos mensuales** por categoría
- **Metas de ahorro** con seguimiento de progreso
- Sistema de **backup y restauración** de datos
- Exportación de datos a **CSV** (compatible con Excel/Google Sheets)
- **Tema oscuro/claro** adaptable al sistema
- **PIN de seguridad** para proteger la aplicación
- Soporte multi-moneda (USD, EUR, MXN, PEN, GBP)
- Diseño responsivo optimizado para dispositivos móviles

## 🚀 Tecnologías utilizadas

- HTML5 / CSS3 (variables CSS para temas claro/oscuro)
- JavaScript vanilla (ES6+)
- Almacenamiento local en el dispositivo
- Diseño mobile-first (max-width: 480px)

## 📱 Uso de la aplicación

### Registro de transacciones
1. Selecciona el tipo **Ingreso** o **Gasto** desde el panel de acciones rápidas
2. Completa el formulario con el monto, descripción y categoría
3. Confirma para registrar la operación

### Copias de seguridad
- **Exportar backup completo**: Guarda todos los datos en un archivo JSON
- **Exportar CSV**: Genera un archivo compatible con Excel y Google Sheets
- **Importar datos**: Restaura desde un archivo JSON previo

### Presupuestos
- Define presupuestos mensuales por categoría
- Visualiza el progreso mediante barras de gasto
- Recibe alertas visuales al superar los límites

### Personalización
- Cambia entre tema claro/oscuro automático o manual
- Configura un PIN de seguridad
- Selecciona la moneda principal de tus finanzas

## 💾 Almacenamiento de datos

Todos los datos se guardan **exclusivamente en el dispositivo del usuario**. No se envían a servidores externos, garantizando la privacidad y control total sobre la información financiera.

Las exportaciones permiten:
- Transferir datos entre dispositivos
- Crear copias de seguridad periódicas
- Analizar datos en herramientas externas

## 📋 Categorías disponibles

La aplicación incluye categorías predefinidas tanto para gastos como para ingresos, organizadas con colores distintivos para facilitar su identificación visual en gráficos y listados.

## 🔒 Seguridad

- **PIN de acceso**: Protege la aplicación con un código numérico
- **Datos locales**: Sin almacenamiento en la nube ni servidores externos
- **Backups cifrables**: El usuario controla sus archivos de respaldo

## 🛠️ Instalación y uso local

```bash
# Clonar el repositorio
git clone https://github.com/aurenox-global/inventario.git

# Navegar al directorio
cd inventario

# Abrir en el navegador (cualquier servidor web estático)
# Por ejemplo, con Python:
python -m http.server 8000
```

O simplemente accede a la versión desplegada:
👉 [https://aurenox-global.github.io/inventario/](https://aurenox-global.github.io/inventario/)

## 📱 Compatibilidad

- ✅ Navegadores modernos (Chrome, Safari, Firefox, Edge)
- ✅ Dispositivos iOS y Android
- ✅ Funciona offline después de la primera carga
- ✅ Diseño táctil optimizado

## 🔄 Actualizaciones

**Versión actual: 2.0**
- Interfaz rediseñada con diseño nativo iOS
- Nuevos gráficos de tendencia y mapa de calor
- Sistema mejorado de presupuestos
- Exportación a CSV
- Tema oscuro completo

## 📄 Licencia

Este proyecto es de uso interno de Aurenox Global. Todos los derechos reservados.

---

Desarrollado con ❤️ por [Aurenox Global](https://github.com/aurenox-global)
