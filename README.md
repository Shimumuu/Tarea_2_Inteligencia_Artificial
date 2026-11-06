# Tarea_2_Inteligencia_Artificial

Universidad Diego Portales, segundo semestre 2026.

## Contenido del repositorio

```
Tarea_2_Inteligencia_Artificial/
├── Dataset/
│   ├── default of credit card clients.xls
│   └── letter-recognition.data
├── Part1.ipynb          # Pregunta 1: regresión lineal y logística
├── Part2.ipynb          # Pregunta 2: aprendizaje supervisado y semisupervisado
├── Part3.ipynb          # Pregunta 3: reducción de dimensionalidad y clustering
├── requirements.txt
└── README.md
```

## Datasets utilizados

| Pregunta | Dataset | Fuente |
|---|---|---|
| 1 | Default of Credit Card Clients | https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients |
| 2 | Letter Recognition | https://archive.ics.uci.edu/dataset/59/letter+recognition |

Los archivos ya vienen incluidos en la carpeta `Dataset/`, así que no hace falta descargarlos.

## Requisitos

- Python 3.13
- Git
- VS Code con las extensiones de Python y Jupyter (o Jupyter Notebook)

## Cómo preparar el entorno

### 1. Clonar el repositorio

```bash
git clone <URL_DEL_REPO>
cd Tarea_2_Inteligencia_Artificial
```

### 2. Crear el entorno virtual

Windows:

```powershell
py -3.13 -m venv venv_t2
```

Linux o macOS:

```bash
python3.13 -m venv venv_t2
```

### 3. Activar el entorno virtual

Windows (PowerShell):

```powershell
.\venv_t2\Scripts\Activate.ps1
```

Si PowerShell bloquea la activación, ejecutar una vez el siguiente comando y volver a activar:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

Windows (CMD):

```cmd
venv_t2\Scripts\activate.bat
```

Linux o macOS:

```bash
source venv_t2/bin/activate
```

Cuando el entorno está activo, aparece `(venv_t2)` al inicio de la línea de la terminal.

### 4. Instalar las dependencias

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 5. Registrar el kernel de Jupyter

```bash
python -m ipykernel install --user --name venv_t2 --display-name "Python (Tarea 2)"
```

### 6. Abrir los notebooks

Abrir `Part1.ipynb`, `Part2.ipynb` o `Part3.ipynb` en VS Code y seleccionar el kernel **Python (Tarea 2)** en la esquina superior derecha. Ejecutar las celdas en orden de arriba hacia abajo.

Para desactivar el entorno al terminar:

```bash
deactivate
```

## Declaración de uso de IA

<!-- Completar según lo exigido en el enunciado -->