# ThinkInAzul Water Quality Visualization Web 🌊

Welcome to the ThinkInAzul Water Quality Visualization platform. This web application enables you to explore, visualize, and download water quality data collected from two key locations in the Mar Menor region: Estacio and Marchamalo.

## About the Project 🏛️

This project is part of the ThinkInAzul initiative ([thinkinazul.es](https://thinkinazul.es/)), funded by:

- 🏢 **Ministerio de Ciencia e Innovación**
- 🧬 **Fundación Séneca**
- 🎓 **UCAM Universidad Católica de Murcia**

The project brings together several research groups:

- 📡 [Telecomunicaciones, IoT, SmartCity, Sonido y Acústica](https://investigacion.ucam.edu/grupos/grupo/telecomunicaciones-iot-smartcity-sonido-acustica)
- 🏃‍♂️ [UKEIM (Unidad de Kinesiología y Ergonomía en Investigación y Medicina)](https://investigacion.ucam.edu/grupos/grupo/ukeim)
- 🌱 [Tecnologías Aplicadas a la Salud Ambiental](https://investigacion.ucam.edu/grupos/grupo/tecnologias-aplicadas-a-la-salud-ambiental)

## Dataset Overview 📊

The dataset (`Parametros_Aguas.csv`) contains water quality measurements taken periodically at two locations:

- 📍 **Estacio** ![Estacio](Estacio.png)
- 📍 **Marchamalo** ![Marchamalo](Marchamalo.png)

### Time Period 🗓️

Measurements span from **March 2023 to April 2024**, providing a comprehensive view of seasonal and environmental changes.

### Parameters Measured 🧪

Each row in the CSV file represents a measurement at a specific date and place. The main parameters include:

- 📅 **Date**: Measurement date
- 📌 **Place**: Location of measurement (Estacio or Marchamalo)
- 🧪 **pH General**: Acidity/alkalinity of water
- ⚡ **CE compensada (mS/mL)**: Compensated electrical conductivity
- 🫧 **O2 (mg/L)**: Dissolved oxygen
- 🧂 **Salinidad (ppt)**: Salinity
- 🌫️ **Turbidez (mg/L)**: Turbidity
- 🌡️ **Temperatura (C)**: Water temperature
- 🧬 **Ca, Cb, Cc, Al, As, Be, Bi, B, Cd, Co, Cr, Cu, Fe, K, La, Li, Mg, Mn, Mo, Na, Ni, Pb, P, Rb, Sb, Se, Si, S, Sr, Ti, Tl, V, Zn, F-, Cl-, NO2-, Br-, NO3-, PO43-, SO42-**: Various chemical and mineral concentrations (see CSV header for full list)

Values are separated by semicolons (`;`) and use commas (`,`) as decimal points.

## How to Use the Web Application 🖥️

1. **Explore the Timeline** 🗓️: Select a date range to view measurements over time.
2. **Choose Locations** 📍: Select one or both places to compare water quality data.
3. **Select Parameters** 🧪: Pick which water quality parameter to visualize in the interactive charts.
4. **View Interactive Charts** 📈: Line and histogram charts update based on your selections.
5. **Download Data** ⬇️: Click the download link below the charts to get the raw CSV data for your own analysis.

## Acknowledgements 🙏

This platform is made possible thanks to the support of ThinkInAzul, Ministerio de Ciencia e Innovación, Fundación Séneca, UCAM, and the dedicated research groups listed above.

For more information, visit [thinkinazul.es](https://thinkinazul.es/).
