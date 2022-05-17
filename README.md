# Modelo de predicción del precio de ordenadores
Competición de tanto solo dos días de duración en la cual se debe realizar un modelo de predicción del precio de diferentes ordenadores a partir de sus características esenciales.
[kaggle: Precio de las laptop](https://www.kaggle.com/c/precio-de-las-laptop)

__Modelo urilizado__: para la competición se ha desarrollado un modelo de Regresión Lineal, y se observa que es un caso de _underfitting_, por lo que es necesario simplificar las variables analizadas por el modelo. Mediante este modelo se consigue un RMSE de 381.

__Próximos pasos__: modelos de regresión que pueda mejorar el rendimiento ante datos nuevos pueden ser Decision Trees, Random Forests, o Neural Networks.

![imagen](src/utils/cuatro_ordenadores.jpg)

Se cuenta con un dataset con más de 900 muestras de entrenamiento, cada una de la cual contiene las siguientes caracteristicas (__features__):
- Company (String): Laptop Manufacturer
- Product (String): Brand and Model
- TypeName (String): Notebook, Ultrabook, Gaming, etc.
- Inches (Float): Screen Size
- ScreenResolution (String): Screen Resolution
- Cpu (String): Central Processing Unit (CPU)
- Ram (String): Laptop RAM
- Memory (String): Hard Disk / SSD Memory
- GPU (String): Graphics Processing Units (GPU)
- OpSys (String): Operating System
- Weight (String): Laptop Weight
- Price_euros (Float): Price (Euro)
