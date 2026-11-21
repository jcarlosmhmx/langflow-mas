# langflow-mas

Sistema multi-agente (MAS) construido con [Langflow](https://github.com/langflow-ai/langflow).

## Estructura

- `src/langflow_mas/` — código Python (componentes personalizados, utilidades)
- `flows/` — flujos exportados de Langflow (`.json`)
- `tests/` — pruebas

## Instalación

Requiere Python 3.10–3.13.

```bash
python3.12 -m venv .venv
source .venv/bin/activate
pip install -e .
langflow run
```
