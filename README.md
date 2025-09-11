# 🛳️ Análisis de Datos del Titanic

Este proyecto tiene como objetivo explorar, limpiar y visualizar el famoso dataset del Titanic.  
El dataset contiene información sobre los pasajeros: clase, edad, sexo, puerto de embarque, tarifa y si sobrevivieron o no.  

El análisis busca responder preguntas como:  
- ¿Qué porcentaje de pasajeros sobrevivió?  
- ¿Influyó la clase del pasajero en la supervivencia?  
- ¿Las mujeres tuvieron mayor probabilidad de sobrevivir que los hombres?  
- ¿Cómo se distribuyen las edades dentro de las clases?  

---

## 📂 Estructura del proyecto

- **Exploración inicial** → revisión de la estructura del dataset, valores faltantes y estadísticas básicas.  
- **Visualización exploratoria** → gráficos descriptivos para analizar la distribución de variables.  
- **Limpieza de datos** → tratamiento de valores nulos e imputación de la edad.  
- **Próximos pasos** → preparación para aplicar modelos predictivos.  

---

## 📊 Visualizaciones realizadas

- Distribución de pasajeros por clase.  
- Distribución por sexo.  
- Supervivencia general.  
- Supervivencia según sexo.  
- Supervivencia según clase.  
- Histograma de edades.  
- Boxplot de edades por clase.  

---

## 🧹 Limpieza de datos

Acciones aplicadas:  
1. Eliminación de la columna `Cabin` (demasiados valores nulos).  
2. Eliminación de filas con valores nulos en `Embarked`.  
3. Imputación de valores nulos en `Age` con la **mediana**.  

---

## 🚀 Próximos pasos

- Analizar correlaciones entre variables numéricas.  
- Estudiar relación entre `Fare`, clase y supervivencia.  
- Crear nuevas variables (ej: rangos de edad).  
- Aplicar modelos de Machine Learning para predecir la supervivencia.  

---

## ⚙️ Tecnologías utilizadas

- Python 🐍  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 📌 Cómo ejecutar el proyecto

1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/AllEndsours/titanic-analysis.git
   cd titanic-analysis
