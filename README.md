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

3. Ejecutar las celdas del notebook en orden. Asegúrate de que la carpeta `Files/` con los ficheros Excel esté en la misma ruta que el notebook.

Notas
- El notebook está en español (comentarios y explicaciones). Si quieres subir el proyecto a GitHub, sigue las instrucciones proporcionadas en el README o en la sección "Comandos sugeridos" de este archivo.

Comandos sugeridos para inicializar repo local (ver más abajo para push a GitHub):

```zsh
# desde la carpeta del proyecto
git init
git add Statistical\ learning.ipynb README.md .gitignore
git commit -m "Add notebook and README"
```
