# Doctorado en Ciencia de Datos

Repositorio de clases del doctorado en ciencia de datos: fundamentos estadísticos, métodos computacionales, series de tiempo, ingeniería de features, APIs y aplicaciones de IA.

## Estructura

```
Doctorado/
├── metodos computacionales estadistica/
│   └── Clase 1/
├── requirements.txt              # Stack base: Jupyter, DS, ML, stats, DL
├── requirements-etl.txt          # ETL y pipelines de datos
├── requirements-timeseries.txt   # Series de tiempo y forecasting
├── requirements-fastapi.txt      # APIs con FastAPI
└── requirements-ai.txt           # LLMs, RAG, vector stores, NLP
```

## Setup

```bash
# 1. Crear entorno virtual
python -m venv .venv
source .venv/bin/activate

# 2. Instalar dependencias base (Jupyter + Data Science)
pip install -r requirements.txt

# 3. Módulos adicionales según la clase
pip install -r requirements-etl.txt
pip install -r requirements-timeseries.txt
pip install -r requirements-fastapi.txt
pip install -r requirements-ai.txt
```

## Temas del doctorado

| Módulo | Enfoque | Requirements |
|--------|---------|--------------|
| Métodos computacionales y estadística | NumPy, SciPy, statsmodels, optimización | `requirements.txt` |
| ETL y pipelines | Ingesta, transformación, calidad de datos | `requirements-etl.txt` |
| Series de tiempo | Prophet, sktime, statsforecast, boosting | `requirements-timeseries.txt` |
| APIs y servicios | FastAPI, SQLAlchemy, auth, async | `requirements-fastapi.txt` |
| IA generativa y LLMs | OpenAI, LangChain, RAG, embeddings | `requirements-ai.txt` |

## Convenciones

- Un notebook o script por clase dentro de su carpeta temática.
- No versionar datos crudos ni artefactos de modelos (ver `.gitignore`).
- Documentar decisiones metodológicas en el notebook o en `README` de la clase.
- Usar los `requirements-*.txt` específicos por módulo para aislar entornos.

## Autor

Sebastián Ulloa — Doctorado en Ciencia de Datos
