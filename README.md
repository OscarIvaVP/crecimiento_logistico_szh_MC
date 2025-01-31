# Simulación de Crecimiento Logístico de Cultivos

Este proyecto simula el crecimiento logístico de diferentes cultivos en varias cuencas, considerando la competencia por recursos. Utiliza un modelo de crecimiento logístico para predecir la expansión de los cultivos a lo largo del tiempo.

## Requisitos

Para ejecutar este proyecto, necesitas tener instalado Python 3 y las siguientes librerías:

- `pandas`
- `numpy`
- `matplotlib`
- `openpyxl` (para leer archivos de Excel)

Puedes instalar las dependencias usando el siguiente comando:

```bash
pip install pandas numpy matplotlib openpyxl

# Estructura del Proyecto

El proyecto tiene la siguiente estructura de archivos:

crecimiento_logistico_szh_MC/
├── datos/
│   └── datos_cultivos.xlsx       # Archivo de Excel con los datos de cultivos
├── scripts/
│   └── simulacion_cultivos.py    # Script principal de simulación
└── README.md                     # Este archivo