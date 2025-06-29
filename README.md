# Clasificación de Tumores Cerebrales usando Redes Neuronales Convolucionales

Un proyecto de aprendizaje profundo que implementa una Red Neuronal Convolucional (CNN) para clasificar tipos de tumores cerebrales a partir de imágenes de resonancia magnética usando PyTorch.

## Informe del proyecto

Si eres miembro de la Universidad Metropolitana, puedes consultar el [informe del proyecto en Google Docs](https://docs.google.com/document/d/1qo02udINvQoQUkBSMpvlBpCs8ts2WGyhhSxEeaugeD4/edit?usp=sharing).

## Kaggle del proyecto

Puedes encontrar y utilizar el [Notebook del proyecto en Kaggle](https://www.kaggle.com/code/paulaalonso123/brain-tumor-classification).

## Dataset

El proyecto utiliza el dataset de [MRI de tumores cerebrales de Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/DAHDOR/cnn.git
cd cnn
```

2. Instala las dependencias usando uv (recomendado):
```bash
uv sync
```

O usando pip:
```bash
pip install -r requirements.txt
```

## Uso

### Ejecutar el Notebook

La implementación principal está contenida en `main.ipynb`. Puedes ejecutarlo usando:

1. **Jupyter Notebook**:
```bash
jupyter notebook main.ipynb
```

2. **JupyterLab**:
```bash
jupyter lab main.ipynb
```

3. **VS Code**: Abre el archivo del notebook directamente en VS Code con la extensión de Python instalada.

4. **Kaggle**: También puedes ejecutar el proyecto directamente en Kaggle:
   - Visita: [Brain Tumor Classification - Kaggle Notebook](https://www.kaggle.com/code/paulaalonso123/brain-tumor-classification)
   - Haz clic en "Copy and Edit" para crear tu propia copia
   - El dataset ya está disponible en Kaggle, por lo que no necesitas descargarlo

## Aviso Médico

Este proyecto es solo para fines educativos y de investigación. El modelo no debe ser usado para diagnóstico médico real sin validación y aprobación adecuadas de profesionales médicos. Siempre consulta a proveedores de atención médica calificados para decisiones médicas.
