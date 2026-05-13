# 📊 Manual Maestro Power BI - Punto de Restauración v1.0

Este proyecto contiene la infraestructura y los entregables de la conversión de la página web del diplomado de Power BI a un formato de manual profesional en Microsoft Word.

## 📁 Estado del Proyecto
- **Ubicación:** `C:\Users\User\Desktop\PAGINA DIPLOMADO POWER BI`
- **Estado:** 100% Finalizado y Estabilizado.
- **Fecha:** lunes, 11 de mayo de 2026.

## 📄 Entregables Principales
1. **Manual Maestro Power BI.docx:** Documento de Word de alta fidelidad con todo el temario, medidas DAX, tablas de datos y diseño editorial.
2. **index.html:** Fuente original con el contenido del diplomado.
3. **ventas_tecnologia_500_registros.csv:** Dataset de práctica utilizado en el manual.

## 🛠️ Tecnologías y Herramientas
- **Python 3.13:** Utilizado para la automatización de la generación del documento.
- **python-docx:** Librería para la manipulación y creación de archivos `.docx`.
- **PowerShell:** Para la gestión de archivos y entorno.

## 🔄 Cómo Recuperar o Regenerar
Si el archivo `.docx` se pierde o necesita modificaciones:
1. El contenido reside en el archivo `index.html`.
2. Se utilizó un script de Python dinámico que lee el HTML y aplica estilos de `Segoe UI`, `Consolas` para DAX, y tablas formateadas.
3. Para mantener la integridad, no abrir el archivo de Word mientras se está procesando (Error 13 de Permiso).

## 🚀 Puntos de Control (Git)
Para recuperar este estado exacto, utilice el repositorio Git local:
- `git status`: Para ver el estado actual.
- `git log`: Para ver el historial de cambios y el tag `v1.0-ESTABLE`.

---
**Desarrollado por:** Gemini CLI Agent
**Para:** Ing. Juancito Peña
