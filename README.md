# 🤖 Aprendizaje Automático — Q01

Este repositorio contiene el **Cuestionario 01 (Q01)** del curso **Aprendizaje Automático**.  
El objetivo principal es preparar un dataset y entrenar un modelo de **red neuronal multicapa (MLP)** utilizando **PyTorch**.

---

## 📂 Contenido del notebook

- **Estadísticas Descriptivas**  
  Exploración inicial de los datos, revisión de distribuciones y atributos principales.

- **Preparación del Dataset**  
  - Separación en variables independientes (X) y variable objetivo (y).  
  - División en conjuntos de **entrenamiento, validación y prueba**.  
  - Creación de una clase `ManageDataset` para manejar los datos.

- **Implementación de un MLP Regressor**  
  - Definición de una red neuronal multicapa usando PyTorch (`nn.Module`).  
  - Entrenamiento del modelo con backpropagation y descenso del gradiente.  
  - Funciones auxiliares para contar parámetros y controlar épocas.

- **Evaluación del Modelo**  
  Métricas básicas y validación sobre los diferentes conjuntos de datos.

---

## ⚙️ Requisitos

Para ejecutar este notebook necesitas:

- Python 3.8+
- [Jupyter Notebook](https://jupyter.org/) o [JupyterLab](https://jupyter.org/install)
- Librerías:
  - `numpy`
  - `pandas`
  - `torch`
  - `prettytable`

Instala las dependencias con:

```bash
pip install numpy pandas torch prettytable
