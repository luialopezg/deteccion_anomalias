# Detección de Anomalías en Datos

Este proyecto es parte de la actividad grupal del Máster Universitario en Inteligencia Artificial. Su propósito es explorar y aplicar técnicas de detección de anomalías en un conjunto de datos eléctricos recopilados mediante dispositivos IoT.

## Objetivos

- Aplicar técnicas de detección de anomalías en datos univariados y multivariados.
- Implementar métodos como:
  - Media móvil (Moving Average)
  - Z-Score
  - Isolation Forest
  - Local Outlier Factor (LOF)
- Investigar y aplicar una técnica adicional de detección de anomalías con un caso de uso concreto.
- Analizar los resultados y comparar la eficacia de las técnicas aplicadas.

## Descripción del Dataset

El conjunto de datos contiene mediciones de parámetros eléctricos obtenidas mediante dispositivos IoT desde el 25 de junio de 2019 hasta el 14 de abril de 2020, con una actualización cada 15 minutos. Incluye un total de 19,352 registros y los siguientes parámetros:

- **Voltaje de Corriente:**
  - VL1: Fase Línea 1
  - VL2: Fase Línea 2
  - VL3: Fase Línea 3
  - IL1: Línea actual 1
  - IL2: Línea actual 2
  - IL3: Línea actual 3
  - VL12: Línea de tensión 1-2
  - VL23: Línea de tensión 2-3
  - VL31: Línea de tensión 3-1
  - INUT: Corriente neutra

## Estructura del Proyecto

```plaintext
deteccion_anomalias/
├── data/                   # Datos crudos y procesados
│   ├── raw/                # Datos sin procesar
│   └── processed/          # Datos transformados
├── notebooks/              # Jupyter Notebooks para análisis exploratorio
├── scripts/                # Scripts Python reutilizables
├── models/                 # Modelos entrenados y checkpoints
├── reports/                # Reportes generados
│   └── figures/            # Visualizaciones
├── tests/                  # Pruebas unitarias
├── .gitignore              # Archivos y carpetas a ignorar
├── requirements.txt        # Dependencias del proyecto
└── setup.py                # Configuración del paquete (opcional)

Requisitos del Entorno

    Python: 3.8+
    Dependencias: Se encuentran en requirements.txt. Incluyen:
        numpy
        pandas
        matplotlib
        seaborn
        scikit-learn
        jupyter

Ejecución

    Clona el repositorio:

git clone https://github.com/tu_usuario/deteccion_anomalias.git
cd deteccion_anomalias

Crea y activa un entorno virtual:

python3 -m venv env_anomalias
source env_anomalias/bin/activate

Instala las dependencias:

pip install -r requirements.txt

Abre el notebook principal:

    jupyter notebook notebooks/

Investigación Adicional

Además de las técnicas implementadas, se busca investigar y aplicar una técnica moderna de detección de anomalías, seleccionando un caso de uso concreto y evaluando sus resultados.

Autoría: Este proyecto fue desarrollado como parte del Máster Universitario en Inteligencia Artificial.
Contacto: luialopezg@dominio.com


Este archivo proporciona un marco sólido y profesional para documentar el proyecto. ¿Quieres agregar o ajustar algo? &#8203;:contentReference[oaicite:0]{index=0}&#8203;
