# Hypertension Classification with MLP

Este proyecto implementa un modelo de clasificación basado en un Perceptrón Multicapa (MLP) para predecir hipertensión a partir de un conjunto de datos previamente preprocesado y balanceado.

## Objetivo del proyecto

Construir y evaluar un modelo de Machine Learning capaz de clasificar correctamente casos de hipertensión mediante técnicas de preprocesamiento y un clasificador neuronal MLP.

## Dataset

El programa utiliza el archivo:

train_test_split(X, y, test_size=0.40, random_state=45)


### 4. Escalado de características
Se aplica `StandardScaler` para normalizar los valores numéricos.

### 5. Entrenamiento del modelo MLP
El modelo está configurado como:

hidden_layer_sizes=(15, 15)
max_iter=2000


Dos capas ocultas de 15 neuronas cada una.

### 6. Predicción y evaluación

Se calculan métricas:
- Matriz de confusión
- Informe de clasificación con precision, recall y f1-score

## Requisitos

Instalar dependencias necesarias:

pip install pandas scikit-learn


## Ejecución

Ejecutar el script principal:
python3 main.py


Aparecerá por consola:
- Predicciones del modelo
- Matriz de confusión
- Informe de clasificación completo

## Archivos incluidos

- `main.py` — código principal del modelo
- `hipertension_preprocesado_final_balanceado.csv` — dataset utilizado
- `README.md` — documentación del proyecto

## Autoría

- Pablo de la Iglesia Otero
