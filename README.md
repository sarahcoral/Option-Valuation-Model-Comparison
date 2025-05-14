# Taller Binomial – Métodos Numéricos en Finanzas 2025-I

**Autores:**  
Sarah Daniella Coral Zúñiga  
Daniel Aragón Urrego  

## Descripción

Este notebook desarrolla e implementa diversos modelos de valoración de opciones financieras europeas utilizando métodos numéricos. Los modelos evaluados son:

- Modelo Binomial de Cox-Ross-Rubinstein (CRR)
- Modelo Binomial de Jarrow-Rudd
- Modelo Trinomial
- Modelo de Black-Scholes

También se realiza una calibración empírica utilizando precios históricos del ETF SPY obtenidos desde Yahoo Finance para estimar parámetros como la volatilidad y la tasa libre de riesgo. Finalmente, se analiza la convergencia de los modelos binomiales hacia la solución de Black-Scholes al aumentar el número de pasos \( N \).

---

## Requisitos

- Python 3.7+
- `yfinance 0.2.58`
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `time`

Puedes instalar los requisitos ejecutando:

```bash
pip install yfinance==0.2.58 pandas numpy matplotlib scipy time
```

Puedes visualizar el Notebook abriendo el archivo desde Google Colab o JupyterLab

---

## Estructura del Notebook

1. **Instalación y carga de librerías**  
   Incluye la instalación de paquetes necesarios y configuración inicial.

2. **Definición de funciones auxiliares**  
   Funciones para visualización de árboles binomiales y otros cálculos.

3. **Implementación de modelos de valoración**  
   Se implementan cuatro modelos principales para valorar opciones financieras.

4. **Ejemplos de uso**  
   Se ejecutan ejemplos con parámetros predefinidos para comparar resultados.

5. **Calibración a datos reales**  
   Descarga de datos históricos de SPY, estimación de volatilidad y tasa de interés.

6. **Análisis de convergencia**  
   Se evalúa la estabilidad de los modelos binomiales frente a la fórmula de Black-Scholes con distintos valores de \( N \).

---

## Ejecución

Para correr el notebook, asegúrate de:

1. Ejecutar todas las celdas secuencialmente.
2. Tener conexión a Internet para la descarga de datos desde Yahoo Finance.
3. Correr el ejemplo final que compara la convergencia de los modelos.

---

## Créditos

Este notebook fue desarrollado como parte del curso *Métodos Numéricos en Finanzas* (2025-I), y está destinado a fines académicos.
