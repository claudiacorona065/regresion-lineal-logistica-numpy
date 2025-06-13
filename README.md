# regresion-lineal-logistica-numpy

# Implementación desde cero de regresión lineal y logística con Numpy

Este proyecto consiste en desarrollar **modelos de regresión y clasificación** utilizando únicamente `NumPy`, sin usar librerías de machine learning como scikit-learn. El objetivo es comprender en profundidad cómo funcionan algoritmos como la **regresión lineal** y la **regresión logística**, implementando manualmente todos los pasos: desde el cálculo de gradientes hasta la actualización de parámetros.



## Dataset

El dataset utilizado contiene datos sintéticos con las siguientes variables:

- `Altura` (en centímetros)
- `Peso` (en kilogramos)
- `Género`
- `Tamaño de pie`

---

## Parte 1: Regresión Lineal

### Objetivo

Predecir la altura (en cm) a partir del resto de variables.

### Modelos implementados

1. Regresión lineal por **solución analítica** (mínimos cuadrados)
2. Regresión lineal por **batch gradient descent**

### Métricas usadas

- **SSR** (Suma de residuos al cuadrado)
- **R² Score**

Se realiza además una comparación de parámetros entre ambos modelos para validar su equivalencia.

---

## Parte 2: Clasificación con Regresión Logística

### Objetivo

Predecir si una persona mide más de **1.75 metros** (1 si sí, 0 si no).

### Modelos implementados

1. Regresión logística por **batch gradient descent**
2. Regresión logística por **stochastic gradient descent**

### Métricas usadas

- **Porcentaje de aciertos**
- **Cross Entropy Loss**

También se comparan los parámetros obtenidos entre ambos métodos para asegurar su coherencia.

---



