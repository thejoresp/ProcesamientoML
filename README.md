# Trabajo final Procesamiento de Aprendizaje Automático
En base al dataset proporcionado que contiene la siguiente información:
Información completa sobre 2,392 estudiantes de secundaria, que detalla sus datos demográficos, hábitos de estudio, participación de los padres, actividades extracurriculares y rendimiento académico. La variable objetivo, “GradeClass”, clasifica las calificaciones de los estudiantes en categorías distintas, proporcionando un conjunto de datos sólido para la investigación educativa, la modelización predictiva y el análisis estadístico.
## Tabla de contenidos
1. Student Information
 • Student ID
 • Demographic Details
 • Study Habits
2. Parental Involvement
3. Extracurricular Activities
4. Academic Performance
5. Target Variable: Grade Class
## Student Information
### Student ID
• StudentID: Un identificador único asignado a cada estudiante (del 1001 al 3392).
### Demographic Details
• Age
• Gender: Género de los estudiantes, donde 0 representa Masculino y 1 representa Femenino.
• Ethnicity: 
 • 0: Caucasian
 • 1: African American
 • 2: Asian
 • 3: Other
• ParentalEducation: nivel de educación de los padres:
 • 0: None
 • 1: High School
 • 2: Some College
 • 3: Bachelor's
 • 4: Higher
### Study Habits
 • StudyTimeWeekly: Tiempo de estudio semanal en horas, que varía de 0 a 20..
 • Absences: Número de ausencias durante el año escolar, que varía de 0 a 30.
 • Tutoring: Estado de tutoría, donde 0 indica No y 1 indica Sí.
### Parental Involvement
 • ParentalSupport:
 • 0: None 
 • 1: Low
 • 2: Moderate
 • 3: High
 • 4: Very High
### Extracurricular Activities
 • Extracurricular: Participación en actividades extracurriculares, donde 0 indica No y 1 indica Sí.
 • Sports: Participación en deportes, donde 0 indica No y 1 indica Sí.
 • Music: Participación en actividades musicales, donde 0 indica No y 1 indica Sí.
 • Volunteering: Participación en voluntariado, donde 0 indica No y 1 indica Sí.
### Academic Performance
 • GPA: Promedio de calificaciones en una escala de 2.0 a 4.0, influenciado por hábitos de estudio, participación de los padres y actividades extracurriculares.
### Target Variable: Grade Class
GradeClass: Clasificación de las calificaciones de los estudiantes basada en el GPA:
 • 0: 'A' (GPA >= 3.5)
 • 1: 'B' (3.0 <= GPA < 3.5)
 • 2: 'C' (2.5 <= GPA < 3.0)
 • 3: 'D' (2.0 <= GPA < 2.5)
 • 4: 'F' (GPA < 2.0)
## Objetivo del trabajo:
Entrenar un modelo de aprendizaje automático Naive Bayes utilizando las variables de este dataset capaz de predecir el grado al cual hipotéticamente un alumno debería pertenecer.
Para ello deberán seguir los siguientes pasos:
### 1. Codificación de variables categóricas y escala de variables numéricas:
Convertir las variables categóricas en variables numéricas utilizando técnicas como codificación one-hot o etiquetado ordinal.Escalar las variables numéricas para asegurar que todas estén en la misma escala, utilizando técnicas como la estandarización (por ejemplo, escala Z).
### 2. División del conjunto de datos:
Separar el conjunto de datos en predictores (X) y variable objetivo (y).
### 3. División del conjunto de datos en conjuntos de entrenamiento y prueba:
Dividir X e y en conjuntos de entrenamiento y prueba. Por ejemplo, utilizar una proporción como 80% para entrenamiento y 20% para prueba.
### 4. Definición del modelo inicial:
Definir el algoritmo de Naive Bayes.
### 5. Ajuste del modelo al conjunto de entrenamiento:
Entrenar el modelo seleccionado utilizando el conjunto de entrenamiento.
### 6. Predicción en el conjunto de prueba:
Utilizar el modelo entrenado para hacer predicciones sobre el conjunto de prueba.
### 7. Evaluación del modelo:
Evaluar el rendimiento del modelo ajustado utilizando métricas apropiadas como precisión, recall, F1-score, matriz de confusión, etc.
