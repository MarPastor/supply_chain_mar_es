# Supply Chain Analytics - Análisis de Cadena de Suministro y de Logística

Este proyecto nos sumerge en el Supply Chain Analytics utilizando Microsoft Power BI, herramienta usada para Business Intelligence Analytics. Se analizará el corazón operativo de cualquier empresa: la cadena de suministro. Desde la logística y las compras estratégicas hasta la gestión optimizada del inventario y la relación con proveedores, este proyecto refleja habilidades para evaluar y mejorar cada eslabón de la cadena.

En este proyectos se transforman datos brutos en informes dinámicos y visualizaciones impactantes, revelando insights cruciales para la toma de decisiones estratégicas y la mejora de la eficiencia operativa, en el contexto de una empresa de productos electrónicos multinacional y sus proveedores.

---

## 🔎 Fase 1:  Conexión con los datos

En esta fase, la base de datos se conecta al modelo de Power BI. Se realiza una EDA mediante Power Query para unificar los datos y garantizar que no contengan columnas vacías ni filas que no proporcionen información relevante.

---

## 🧮 Fase 2: Cálculo de medidas

Creación medidas que ayudan a calcular el 'Monto de las Ordenes de Compra', 'Cantidad Comprometida y Recibida', 'InFull', 'OnTime', 'OTIF', 'Desviación InFull y Desviación OnTime', 'Montos Comprometidos', 'Lead Time' y 'Cantidad de ODC Anuladas'. Con estas medidas se podrán aplicar filtros y visualizar los KPI necesarios para el análisis en el performance y cumplimiento en la cadena de suplemento y logística por cada proveedor. Para ellos se emplea DAX y lenguaje M.

---

## 📈 Fase 3: Selección de visualizaciones que cuentan la historia

Se trabaja en la construcción de la narrativa, la selección de los gráficos y KPI's, tanto como en la selección de las visualizaciones en Power BI. 

---

## 🔧 Fase 4: Construcción del Dashboard y formato de la presentación

Esta fase final se centra en refinar el formato general de la presentación para unificar visualizaciones, formatos, paleta de colores y hacerla más atractiva, iterativa y fácil de entender. Se crean los dashboard 'Resumen de Gestión de Compras', que ofrecen una visión general del rendimiento de cada proveedor; y los dashboard 'Resumen de Proveedor' y 'Resumen de Producto' que filtran y detallan la información. Se aplican filtros por proveedor y rango de fechas para analizar diferentes situaciones.

---

## 👩‍💻 Tecnologías utilizadas

![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

---

## 📁 Estructura del Repositorio

```
supply_chain_mar_es/
│
├── README.md                                           // Documentación del proyecto
│
├── .gitignore                                          // Archivo de exclusión para Git
│
├── Informe Gestion Compras y Supply - Pastor.pbix      // Dashboard en Power BI             
│
├── documents/                              
│   └── supplyChainProject_PDF.ipynb                    // Dashboard exportados en PDF
│ 
├── images/                                             // Imágenes utilizadas en el dashboard y presentación
│   ├── 1.supply_back.png
│   ├── 2.supply_back.png
│   ├── 3.supply_back.png
│   ├── Dashboard_1.png 
│   ├── Informe_gestion_compras_filtro.png
│   ├── Resumen_producto_filtro.png                  
│   └── Resumen_proveedores_filtro.png                
│
└── resources/                             
    ├── Compras.xlsx                                     // Dataset de estudio
    ├── query+compras+adventureworks.sql                 // SQL con querys para exportación de datos de compras
    ├── query+productos.sql                              // SQL con querys para exportación de datos de productos
    └── query+proveedores.sql                            // SQL con querys para exportación de datos de proveedores
```
---

## 📝 Instructions for use

This project requires Python 3.8 or higher and Power BI desktop.

1. Clone the repository:

- git clone https://github.com/MarPastor/housing_analysis_mar.git
- cd .\notebook

2. Run the code to clean the CSV file

3. Open the Power BI file  ['Dashboard']('Dashboard.pbix') to interact with the visualizations.

---

## ✅ Project status

✅ Completed

---

## 📷 Some dashboard visualizations

- Dashboard_01 1:

![inicio](https://github.com/MarPastor/housing_analysis_mar/blob/main/images/Inicio.PNG)

- Visualizations (education vs income):
  
![educacion_ingresos](https://github.com/MarPastor/housing_analysis_mar/blob/main/images/educacion_ingresos.PNG)

- Graphic_01:
  
![graphic_01](https://github.com/MarPastor/housing_analysis_mar/blob/main/images/graphic_01.png)

- Graphic_02:
  
![graphic_02](https://github.com/MarPastor/housing_analysis_mar/blob/main/images/graphic_02.png)

- Graphic_03:
  
![graphic_03](https://github.com/MarPastor/housing_analysis_mar/blob/main/images/graphic_03.png)

- Graphic_04:
  
![graphic_04](https://github.com/MarPastor/housing_analysis_mar/blob/main/images/graphic_04.png)

- Graphic_05:
  
![graphic_05](https://github.com/MarPastor/housing_analysis_mar/blob/main/images/graphic_05.png)

---

## ✍️ Authors

- [Alejandra Martin - Development team](https://github.com/al3msvll)
- [Esther Domínguez - Develeopment team](https://github.com/EstherDE135)
- [Iris Barredo del Sol - Scrum Master y Development team](https://github.com/irisbdelsol)
- [Julia Becaria Coquet - Development team](https://github.com/juliabeco)
- [Mar Pastor - Development team](https://github.com/MarPastor)

---