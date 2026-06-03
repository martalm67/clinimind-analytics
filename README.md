# CliniMind Analytics

## Análisis de citas, demanda psicológica y continuidad terapéutica en una clínica de salud mental

Este proyecto simula el análisis de datos de una clínica psicológica ficticia, combinando conocimientos de psicología, secretariado médico y análisis de datos.

El objetivo principal es analizar la gestión de citas, los motivos de consulta, el efecto de los recordatorios, los tiempos de espera y la continuidad terapéutica de los pacientes.

## Objetivos del proyecto

- Analizar la distribución general de citas y pacientes.
- Estudiar la tasa de asistencia, cancelación, no asistencia y reprogramación.
- Evaluar si el envío de recordatorios se relaciona con una mayor asistencia.
- Identificar los motivos de consulta más frecuentes.
- Analizar los niveles de urgencia según motivo de consulta.
- Explorar la continuidad terapéutica y su relación con los días de espera.

## Dataset

El dataset utilizado es sintético, creado con Python, y no contiene datos reales de pacientes.

Se generaron:

- 1.600 citas
- 400 pacientes ficticios
- Periodo: enero de 2024 a diciembre de 2025
- Variables administrativas y psicológicas

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git y GitHub

## Estructura del proyecto

```text
clinimind-analytics/
│
├── data/
│   ├── citas_clinica_prueba.csv
│   └── citas_clinica_completo.csv
│
├── notebooks/
│   ├── 01_creacion_dataset.ipynb
│   └── 02_analisis_exploratorio.ipynb
│
└── README.md