# Taller 1 - BEDA

## Configuración del proyecto

**Requisitos:** Python 3.8 o superior

### Instalación 

**Windows:**
1. Crear el entorno virtual:
   ```powershell
   python -m venv .venv
   # Otras opciones si python no funciona:
   # py -m venv .venv
   # py -3 -m venv .venv
   # python3 -m venv .venv
   ```
2. Activar el entorno virtual:
   ```powershell
   .venv\Scripts\activate
   ```
3. Instalar dependencias:
   ```powershell
   pip install -r requirements.txt
   ```

**macOS / Linux:**
1. Crear el entorno virtual:
   ```bash
   python3 -m venv .venv
   # Otras opciones según tu instalación:
   # python -m venv .venv
   # python3.8 -m venv .venv
   # python3.9 -m venv .venv
   # python3.10 -m venv .venv
   # python3.11 -m venv .venv
   # python3.12 -m venv .venv
   ```
2. Activar el entorno virtual:
   ```bash
   source .venv/bin/activate
   ```
3. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```

**Para desactivar el entorno virtual** (cualquier sistema):
```bash
deactivate
```

## Evaluación

### Desarrollo local
Desarrolla tu solución en `notebooks/ejercicio1.ipynb`.

### Evaluación
Los tests se ejecutan automáticamente cuando haces push a GitHub:

1. Desarrolla tu solución en `notebooks/ejercicio1.ipynb`
2. Haz push de tus cambios a GitHub
3. Revisa los resultados en la pestaña "Actions" de tu repositorio


pytest tests/test_1.py