# Dashboard Pronóstico de Demanda Corrugados - Molino PROAN - Power BI
Este repositorio tiene como objetivo documentar el tablero de pronóstico de demanda de corrugados - molino PROAN, con la estructura de conexiones, tablas, columnas calculadas y medidas utilizadas para la creación del modelo visual. 
---
## Objetivo
El tablero de pronóstico de moldeados tiene como objetivo determinar la proyección de demanda acorde a la definición de un método que permita establecer la demanda futura para los siguientes 12 meses en conjunto con el explosionado de materiales acorde a la alternativa de fabricación que se requiera. Esto llegando hasta las necesidades de bobinas a producir por parte de molino y a solicitar de importación por parte de compras. 
---
## Tecnologías Utilizadas
- **Power BI Desktop y Power BI App.com** ([modo de conexión: Import])
- **[Fuente de datos: SharePoint / SQL Server / SAP]**
- **DAX** (*[tipo de cálculos: medidas de forecast, métricas de calidad, etc.]*)
- **GitHub** (para control de versiones y documentación técnica)
---
## Estructura del Repositorio
```plaintext
[Nombre_Repositorio]/
├── pbix/ ├── README.md ├── docs/
│ ├── Medidas.md │ ├── Columnas_Calculadas.md │ ├── Tablas_Calculadas.md │ └── video_tutorial.md ├── img/
│ ├── preview_dashboard.png │ └── modelo_datos.png → Archivos PBIX del tablero
→ Descripción general del repositorio
→ Medidas DAX documentadas
→ Columnas calculadas documentadas
→ Tablas calculadas documentadas
