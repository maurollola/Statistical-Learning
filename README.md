# Statistical learning (Breast cancer notebook)

Este repositorio contiene el cuaderno `Statistical learning.ipynb`, que muestra un repaso práctico de técnicas de aprendizaje estadístico usando scikit-learn aplicadas al conjunto de datos "Breast Cancer Wisconsin (Diagnostic)".

Contenido del cuaderno
- Instalación rápida de dependencias (scikit-learn, xlrd).
- Ejemplos con datasets incorporados (Iris) y explicación básica de regresión logística.
- Ejercicio final: carga de los ficheros `Files/TRAIN_breast_cancer_kaggle.xls` y `Files/TEST_breast_cancer_kaggle.xls` para entrenar y evaluar modelos.
- Modelos implementados: Logistic Regression, Random Forest, SVM (kernel RBF) y MLP (dos capas ocultas de 100 neuronas).
- Uso de validación cruzada (k-fold) y búsqueda de parámetros para SVM.

Cómo usar
1. Abrir `Statistical learning.ipynb` en Jupyter / JupyterLab / VS Code (Jupyter extension).
2. Asegurarse de tener Python y las dependencias instaladas. Ejemplo de instalación:

```zsh
pip install --user --upgrade scikit-learn xlrd
```
