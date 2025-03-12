# **Análisis de PIB Global y Modelos de Redes Neuronales**

## Autores
-[**Helen Melissa Margfoy Contreras**](https://www.linkedin.com/in/helenmargfoy/)
Estudiante de Economía y Gobierno y asuntos Públicos Universidad de Los Andes
-
[**Cristian Oviedo**](https://www.linkedin.com/in/cristian-oviedo-78362524b/)
Estudiante de economía Universidad de Los Andes
[**Tomás Acevedo Echeverría**](https://www.linkedin.com/in/tom%C3%A1s-acevedo-echeverr%C3%ADa-913a35212?trk=contact-info)
Estudiante de economía Universidad de Los Andes
[**Andres Felipe Ballén Caceres**](http://www.linkedin.com/in/andr%C3%A9s-ball%C3%A9n)
Estudiante de economía Universidad de Los Andes

## 📚 Descripción

Este proyecto aplica redes neuronales para analizar el conjunto de datos "World GDP Dataset" del World Bank Group, que contiene información sobre el Producto Interno Bruto (PIB) de países desde 1960 hasta 2022. Se transformará un problema de regresión en clasificación para construir y evaluar diferentes modelos de redes neuronales, comparando su rendimiento.

## 🎯 Planteamiento del Problema

El objetivo es predecir la clasificación de PIB de los países como "Bajo", "Medio" o "Alto" según el valor de su PIB. El proyecto involucra el procesamiento de datos, la construcción de modelos de redes neuronales y la evaluación de su rendimiento.

## 📂 Contenido del Repositorio

- **notebooks/**: Carpeta con los cuadernos de Jupyter para análisis y construcción de modelos.
- **gdp_data.csv**: Datos del PIB de los países.
- **country_codes.csv**: Clasificación de países por región y grupo de ingreso.
- **models/**: Carpeta con los modelos exportados.

## 🤖 Algoritmos Implementados

1. **Red Neuronal Tradicional (Scikit-Learn)**: Construcción de una red neuronal con una capa oculta, optimización de hiperparámetros y regularización.
2. **Red Neuronal Profunda (TensorFlow)**: Construcción de una red neuronal profunda con dos capas ocultas y optimización de hiperparámetros.
3. **Red Neuronal con Mala Función de Pérdida (TensorFlow)**: Análisis de los efectos de usar una función de pérdida incorrecta y un aprendizaje inadecuado.
4. **Exportación de Modelos**: Exportación de los modelos entrenados para reutilización.

## 🔍 Variables de la base de datos

1. **year**: Año del dato del PIB (tipo de dato: entero).
2. **country**: Nombre del país (tipo de dato: texto).
3. **gdp**: Valor del Producto Interno Bruto (PIB) de cada país por año (tipo de dato: flotante).
4. **region**: Región geográfica del país (tipo de dato: texto).
5. **income_group**: Clasificación por grupo de ingreso del país (tipo de dato: texto).

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

