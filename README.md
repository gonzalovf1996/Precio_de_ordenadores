# Modelo de predicción del precio de ordenadores
Competición de tanto solo dos días de duración en la cual se debe realizar un modelo de predicción del precio de diferentes ordenadores a partir de sus características esenciales.
[kaggle: Precio de las laptop](https://www.kaggle.com/c/precio-de-las-laptop)

![imagen](src/utils/cuatro_ordenadores.jpg)

Se cuenta con un dataset con más de 900 muestras de entrenamiento, cada una de la cual contiene las siguientes caracteristicas (__features__):
- Company- String -Laptop Manufacturer
- Product -String -Brand and Model
- TypeName -String -Type (Notebook, Ultrabook, Gaming, etc.)
- Inches -Numeric- Screen Size
- ScreenResolution -String- Screen Resolution
- Cpu- String -Central Processing Unit (CPU)
- Ram -String- Laptop RAM
- Memory -String- Hard Disk / SSD Memory
- GPU -String- Graphics Processing Units (GPU)
- OpSys -String- Operating System
- Weight -String- Laptop Weight
- Price_euros -Numeric- Price (Euro)

La métrica utilizada ha sido el RMSE.
