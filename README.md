# Análisis de Pingüinos 🐧

Este proyecto contiene la configuración inicial y el entorno de desarrollo para el análisis de un conjunto de datos sobre pingüinos.

## Estructura del Proyecto

```text
analisis_pinguinos/
├── .venv/
├── .gitignore
├── requirements.txt
├── analisis.py
└── README.md
```

## Requisitos Previos

- Python 3.8 o superior instalado en el sistema.

## Configuración e Instalación del Entorno

Sigue estos pasos para replicar el entorno de trabajo:

### 1. Crear el entorno virtual
```bash
python -m venv .venv
```

### 2. Activar el entorno virtual

- **Windows (PowerShell / CMD):**
  ```bash
  .venv\Scripts\activate
  ```
- **Linux / macOS / Git Bash:**
  ```bash
  source .venv/bin/activate
  ```

### 3. Instalar dependencias
Con el entorno virtual activado, instala las librerías listadas en `requirements.txt`:

```bash
pip install -r requirements.txt
```