## 📊 Adult Income Prediction

**Autor:** Aaron Elizondo Vargas  
**Proyecto de Ciencia de Datos - Predicción de Ingresos Adultos**

### 📌 Objetivo del Proyecto
Desarrollar un modelo de aprendizaje automático capaz de **predecir el nivel de ingresos** de personas adultas, clasificando si su ingreso es **menor o igual a 50k** o **mayor a 50k**.

---

### 🧰 Herramientas de Software

Este proyecto fue desarrollado en Python utilizando las siguientes bibliotecas:

- `pandas` (como `pd`)
- `numpy`
- `seaborn` (como `sns`)
- `matplotlib.pyplot` (como `plt`)
- `os`
- `math`

---

### 📂 Conjunto de Datos

El dataset contiene **32,561 registros** con **14 variables**:

- `age`: Edad (continua)
- `workclass`: Tipo de empleo (Privado, Gobierno, Autoempleo, etc.)
- `fnlwgt`: Peso final (continua)
- `education`: Nivel educativo (desde preescolar hasta doctorado)
- `education-num`: Años de educación (continua)
- `marital-status`: Estado civil
- `occupation`: Ocupación
- `relationship`: Rol familiar
- `race`: Raza
- `sex`: Género
- `capital-gain`: Ganancia de capital
- `capital-loss`: Pérdida de capital
- `hours-per-week`: Horas trabajadas por semana
- `native-country`: País de origen

La variable objetivo es **`income`**, que toma los valores:
- `<=50K`
- `>50K`

---

### 🤖 Modelos de Machine Learning Implementados

Se exploraron los siguientes modelos de clasificación:

- `LogisticRegression`
- `DecisionTreeClassifier`
- `SVC` (Support Vector Classifier)
- `KNeighborsClassifier`
- `RandomForestClassifier`

🔍 **Modelos destacados**:
- `KNeighborsClassifier`: Precisión de hasta **90%**
- `RandomForestClassifier`: Precisión de hasta **91%**

---

### Conclusión

El modelo de Random Forest mostró el mejor rendimiento general en términos de precisión. Este proyecto demuestra la aplicabilidad del análisis exploratorio de datos, limpieza, visualización y modelado predictivo en problemas del mundo real utilizando herramientas de ciencia de datos.
