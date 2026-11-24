# Diseño de Leva, Análisis Cinemático y Simulación de Movimiento

> **Enfoque:** Mecánica Aplicada / Cinemática de Mecanismos / CAD y Simulación de Movimiento  
> **Contexto:** Proyecto desarrollado en el marco de mi formación en Ingeniería Mecatrónica.  
> **Mi rol:** Modelado CAD y simulación de movimiento del mecanismo de leva y seguidor[cite: 85].

## 📌 Resumen del proyecto
Diseño geométrico, análisis cinemático y simulación de movimiento de perfiles de leva y seguidor (evaluando perfiles de movimiento **3-4-5** y **4-5-6-7**), integrando tablas y datos de diseño, modelos CAD (`.prt`, `.ipt`, `.stp`, `.dwg`) y análisis de simulación de movimiento (`.sim`, `.minf`, `.minp`, `.mres`)[cite: 85].

## 🎯 Objetivos y alcance
- Definir y comparar perfiles de movimiento de leva y seguidor (**3-4-5** y **4-5-6-7**) a partir de los datos y hojas de cálculo del proyecto[cite: 85].
- Construir y estructurar los modelos geométricos de leva, seguidor y base en formatos nativos y neutros de intercambio CAD[cite: 85].
- Simular el comportamiento cinemático y de movimiento del conjunto leva-seguidor[cite: 85].
- **Alcance:** Diseño geométrico, tabulación de perfiles y simulación de movimiento en entorno CAD/CAE[cite: 85].

## 🛠️ Arquitectura / Metodología / Herramientas
- **Herramientas y formatos:** Entornos CAD/CAE (Siemens NX / Autodesk Inventor — archivos `.prt`, `.ipt`, `.stp`, `.dwg`, `.sim`, `.minf`, `.minp`, `.mres`), hojas de cálculo (`.xlsx`) y archivos de datos (`.txt`)[cite: 85].
- **Metodología:**
  1. **Definición de perfiles de movimiento:** Revisión y organización de los datos y tablas correspondientes a los perfiles **3-4-5** y **4-5-6-7**[cite: 85].
  2. **Modelado CAD (labor realizada):** Construcción de la geometría de leva de disco, seguidor y base (`baseleva.prt`, `seguidor.prt`, `Leva de disco*.ipt/.prt`, `leva4567.prt`, `levaseguidor345.prt`)[cite: 85].
  3. **Simulación de movimiento (labor realizada):** Configuración y ejecución de análisis de movimiento (`motion1`) y exportación de geometrías de intercambio (`.stp`, `.dwg`)[cite: 85].

## 📂 Estructura del repositorio
```text
├── docs/            # Informe técnico en PDF
├── data/            # Tablas (.xlsx) y archivos de datos (.txt) de perfiles 3-4-5 y 4-5-6-7
├── cad-simulation/  # Modelos CAD (.prt, .ipt, .stp, .dwg) y archivos de simulación
├── evidence/        # Capturas y vistas gráficas del diseño y la simulación
└── README.md
