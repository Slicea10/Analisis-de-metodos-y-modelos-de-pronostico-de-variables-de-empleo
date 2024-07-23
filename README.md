# Códigos y datos usados para la elaboración del documento "Analisis de metodos y modelos de pronostico de variables de empleo" (2024). 

Códigos: Carpeta con los códigos elaborados en Python en el entorno de Google Colab.
- comparandoModelos.ipynb: Notebook en donde se aplica backtesting usando diferentes modelos y a diferentes series de tiempo de interés. En este mismo código se obtienen los intervalos de confianza mostrados en la Figura 2 del documento.
- modelosMultivariados.ipynb: Notebook con los diferentes modelos multivariados y de ensamble creados para intentar mejorar las predicciones hechas por los modelos univariados.
- Predicciones.ipynb: Notebook con las predicciones hechas por los modelos seleccionados, contando con datos hasta 2023 y haciendo la predicción para 2024 de manera mensual para los datos de personas registradas en el IMSS.

Datos: Carpeta con las diferentes variables de empleo usadas para medir el desempeño de los modelos. Contiene las variables obtenidas de la ENOE así como la serie de tiempo de personas registradas en el IMSS (de nombre datosMensualesIMSS.csv). 
