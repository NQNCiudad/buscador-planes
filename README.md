# 🔍 Sistema de Consulta de Promociones - La Anónima

Sistema web para consulta rápida de planes de financiación y descuentos activos.

## 📋 Características

- 📊 **Búsqueda por código individual**
- 📋 **Búsqueda masiva por CSV**
- 💾 **Guardado automático** (localStorage)
- 📥 **Exportación a Excel/CSV**
- 🏷️ **Filtros automáticos** (solo vigentes)
- 📱 **Responsive** (funciona en móviles)

## 🚀 Uso

### Opción 1: Usar online (GitHub Pages)

1. Accedé a: `https://[tu-usuario].github.io/buscador-promociones/`
2. Cargá tus archivos Excel
3. ¡Listo para usar!

### Opción 2: Uso local

1. Descargá `index.html`
2. Abrilo en tu navegador
3. Cargá tus archivos Excel

## 📂 Archivos Necesarios

### Archivo 1: Financiación (Excel)
- Hojas con códigos de artículos
- Primera hoja con info de planes (fechas, estados)

### Archivo 2: Descuentos/NT (Excel)
- Columnas: Articulo, Descripcion, Marca, Lote, Mecanica, Estado, Desde, Hasta

### Archivo 3: Lista de Códigos (CSV) - Opcional
```csv
Codigo
3418984
1512195
1164636
```

## 💾 Datos Guardados

El sistema guarda automáticamente:
- ✅ Archivos cargados
- ✅ Estadísticas
- ✅ Fecha de última actualización

**Importante:** Los datos se guardan en **tu navegador**, no en servidores externos.

## 🔄 Actualización Mensual

1. Cargá los nuevos archivos Excel del mes
2. El sistema sobrescribe los datos anteriores
3. Automáticamente filtra planes vencidos

## 🛠️ Desarrollo

**Desarrollado por:** Jonathan Cheves  
**Empresa:** La Anónima S.A.  
**Cargo:** Analista de Gestión y Datos Jr.

### Stack Tecnológico
- HTML5 + CSS3 + JavaScript (Vanilla)
- SheetJS (xlsx.js) para procesamiento de Excel
- localStorage para persistencia de datos
- Sin dependencias de backend

## 📊 Estadísticas del Sistema

- **12,958** códigos únicos procesados
- **65** planes de financiación
- **40,335** códigos con descuentos
- **100%** automático

## 📝 Licencia

© 2026 Jonathan Cheves - La Anónima S.A.  
Uso interno exclusivo.

---

**Versión:** 1.0  
**Última actualización:** Febrero 2026
