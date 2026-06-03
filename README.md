# CliniMind Analytics

## Análisis de citas, demanda psicológica y continuidad terapéutica en una clínica de salud mental

CliniMind Analytics es un proyecto de análisis de datos aplicado a una clínica psicológica ficticia. El objetivo es combinar conocimientos de **psicología**, **secretariado médico** y **data analytics** para estudiar la gestión de citas, la demanda psicológica y la continuidad terapéutica de los pacientes.

El proyecto parte de un dataset sintético creado con Python, por lo que no contiene datos reales ni información sensible de pacientes.

---

## Objetivo del proyecto

El objetivo principal es responder a la siguiente pregunta:

> ¿Cómo puede una clínica psicológica mejorar la gestión de sus citas, reducir ausencias y comprender mejor la demanda asistencial mediante análisis de datos?

Para ello, se analizan variables relacionadas con:

- asistencia, cancelaciones y no asistencias,
- envío de recordatorios,
- canales de reserva,
- modalidad online o presencial,
- motivos de consulta,
- nivel de urgencia,
- días de espera,
- satisfacción,
- continuidad terapéutica,
- perfil de pacientes por edad y ocupación.

---

## Dataset

El dataset fue creado de forma sintética con Python para simular la actividad de una clínica psicológica durante dos años.

Características principales:

- **1.600 citas**
- **400 pacientes ficticios generados**
- **392 pacientes únicos presentes en las citas**
- **Periodo analizado:** enero de 2024 a diciembre de 2025
- **Sin datos reales de pacientes**
- **Sin valores nulos ni registros duplicados**

Variables principales:

- `id_cita`
- `id_paciente`
- `edad`
- `genero`
- `ocupacion`
- `motivo_consulta`
- `nivel_urgencia`
- `fecha_solicitud`
- `fecha_cita`
- `dias_espera`
- `dia_semana`
- `franja_horaria`
- `modalidad`
- `canal_reserva`
- `recordatorio_enviado`
- `estado_cita`
- `num_sesion`
- `continuidad`
- `satisfaccion`

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git
- GitHub

---

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