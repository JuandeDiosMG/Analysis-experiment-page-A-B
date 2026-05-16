# Analysis-experiment-page-A-B
Landing Page A/B Test Analysis – Sprint 9
Este repositorio contiene el análisis de un experimento A/B realizado en una página de inicio (landing page) de una plataforma de comercio electrónico. El objetivo es evaluar qué versión (A o B) genera mejores resultados en términos de conversión y gasto promedio, así como explorar la relación de estos con la fuente de tráfico y el tipo de usuario.

El dataset landing_experiment.csv incluye 40,000 registros de usuarios expuestos a las dos versiones de la página, con información sobre región, dispositivo, fuente de tráfico, tipo de usuario, conversión y gasto.

📂 Contenido del repositorio
notebooks/S9_Version_Student_Proyecto_Landing_Experiment.ipynb
→ Notebook principal con carga, exploración, pruebas estadísticas (t-test, chi-cuadrado, prueba z para proporciones) y visualizaciones.

▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:

[https://colab.research.google.com/assets/colab-badge.svg](https://colab.research.google.com/drive/1S-rh_dXEqtW0LQvHKQ0gd1NyiivfHTXS?usp=sharing)

O:

Abre el archivo .ipynb en GitHub

Haz clic en Open in Colab

📘 Cómo reproducir el análisis
Abre notebooks/S9_Version_Student_Proyecto_Landing_Experiment.ipynb en Colab o Jupyter

Ejecuta las celdas en orden

El notebook carga automáticamente el dataset desde la ruta /datasets/ (asegúrate de que el archivo esté disponible en el entorno de ejecución)

🧠 Objetivo del análisis
Explorar y validar los datos del experimento A/B

Comparar el gasto promedio por usuario entre la página A y B (prueba t de Student)

Comparar la tasa de conversión entre ambas versiones (prueba z para proporciones)

Analizar la asociación entre fuente de tráfico y conversión (chi-cuadrado)

Analizar la asociación entre tipo de usuario y conversión (chi-cuadrado)

Visualizar resultados y generar insights ejecutivos para la toma de decisiones

📊 Resumen de hallazgos
La página B presenta una tasa de conversión significativamente más alta (≈16.0%) que la página A (≈12.6%), con una diferencia de ~3.4 puntos porcentuales.

El gasto promedio de los usuarios que convirtieron también es mayor en la página B (≈68.7 vs ≈61.1), diferencia estadísticamente significativa.

La fuente de tráfico Orgánico es la que aporta mayor volumen de usuarios, pero las tasas de conversión son similares entre fuentes (~14-15%).

No se encontró asociación estadísticamente significativa entre el tipo de usuario (nuevo vs recurrente) y la conversión.

Recomendación: Implementar la página B a nivel general, reforzar campañas en fuentes de tráfico con mejor tasa de conversión (Email y Ads) y monitorear el comportamiento a largo plazo.

🔗 Enlace al repositorio público
[https://github.com/tuusuario/landing-ab-test](https://github.com/JuandeDiosMG/Analysis-experiment-page-A-B)
