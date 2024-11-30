# Analisis_IRA_Neumonia
El proyecto se centra en el análisis y predicción de datos relacionados con infecciones respiratorias agudas (IRAs) y neumonías, basándose en un extenso dataset con información por departamentos, provincias, distritos, y años. A continuación, se detalla el alcance y enfoque del proyecto:

Análisis Exploratorio de Datos
Descripción del Dataset:

Contiene información detallada sobre IRAs y neumonías, hospitalizaciones y defunciones en diferentes grupos etarios, desde menores de 5 años hasta mayores de 60.
Los datos están organizados por departamentos, provincias, distritos, años y semanas.
Resumen de métricas clave:

Número total de casos de IRAs no neumonías.
Número de episodios de neumonías, hospitalizaciones y defunciones en diferentes grupos etarios.
Visualizaciones:

Gráficos de línea:
Evolución anual de los casos de IRAs no neumonías.
Comparativa de hospitalizaciones y defunciones por neumonías en menores de 5 años y mayores de 60 años.
Histogramas:
Total de hospitalizaciones por neumonías agrupadas por departamentos.
Modelos Predictivos
Regresión Lineal:

Predice hospitalizaciones en menores de 5 años a partir de variables como casos de IRAs no neumonías, episodios de neumonías y tiempo (año, semana).
Se evalúa el modelo utilizando métricas como el error cuadrático medio (MSE) y el coeficiente de determinación (R²).
Modelo LSTM (Long Short-Term Memory):

Utiliza redes neuronales recurrentes para predecir hospitalizaciones por neumonías en menores de 5 años.
Incluye técnicas de preprocesamiento, como la estandarización de datos y manejo de valores atípicos.
El modelo se entrena y evalúa con métricas específicas, mostrando predicciones visuales comparadas con los datos observados.
Hallazgos y Evaluaciones
Se calcula el número total de casos, hospitalizaciones y defunciones por neumonías, destacando su distribución temporal y geográfica.
Se exploran los departamentos con mayor número de hospitalizaciones, lo que podría orientar políticas de salud pública.
Los modelos predictivos permiten observar patrones y tendencias, ofreciendo herramientas para la toma de decisiones basada en datos.
