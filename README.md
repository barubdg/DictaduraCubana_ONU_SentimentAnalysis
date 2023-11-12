# Autor

Baruch Benjamin Dámazo Gálvez

Estudiante en ingenieria de Software (UTP)

# Descripción de la problemática

<img src="https://github.com/barubdg/DictaduraCubana_ONU_SentimentAnalysis/blob/main/img-post-twitter.png?raw=true" alt="Post Twitter: Cuba en el Consejo de Derechos Humanos">
Nota. Publicado por UHN Plus, 10 de octubre de 2023, escandalo de cuba por elección del Consejo de Derechos Humanos de la ONU. https://twitter.com/UHN_Plus/status/1711776517242470818
--------

**La elección de Cuba como miembro del Consejo de Derechos Humanos de la ONU es un problema por las siguientes razones:**

_**Es un insulto a las víctimas de la represión cubana que su gobierno sea elegido para defender los derechos humanos.**_ Cuba tiene un historial de violaciones de los derechos humanos, incluyendo la represión de la libertad de expresión, la asociación y la reunión pacífica. En la actualidad, el país tiene más de 1.000 presos políticos, muchos de los cuales han sido condenados por ejercer sus derechos fundamentales. Elegir a Cuba como miembro del Consejo de Derechos Humanos es una burla a las víctimas de estas violaciones.

_**La elección de Cuba es un retroceso para la credibilidad de las Naciones Unidas.**_ La ONU se ha comprometido a promover y proteger los derechos humanos en todo el mundo. La elección de Cuba, un país con un historial de abusos de derechos humanos es un claro ejemplo de la falta de credibilidad de la organización.

_**Es importante que la comunidad internacional exprese su rechazo a esta decisión.**_ La elección de Cuba es un mensaje equivocado a los países que violan los derechos humanos. Les dice que pueden seguir cometiendo abusos sin consecuencias. Es importante que la comunidad internacional exprese su rechazo a esta decisión y haga un llamamiento a Cuba para que libere a todos los presos políticos y respete los derechos humanos de su pueblo.

# Objetivos Generales del Proyecto:

1. **Exploración y Definición del Problema:**
   - Analizar el contexto del tweet y comprender la relevancia del problema planteado.
   - Definir claramente el objetivo general del proyecto de análisis de sentimiento.

2. **Construcción y Preparación del Dataset:**
   - Importar las librerías necesarias y cargar el dataset de manera eficiente.
   - Realizar una exploración inicial del dataset para comprender su estructura y contenido.

3. **Data Wrangling y Transformación:**
   - Realizar un proceso de data wrangling para garantizar la calidad y consistencia de los datos.
   - Transformar el dataset para facilitar el análisis de sentimiento, incluida la limpieza, manejo de valores nulos y duplicados.

4. **Análisis Exploratorio de Datos (EDA):**
   - Realizar un análisis exploratorio detallado, visualizando la frecuencia de palabras y patrones en los datos.
   - Identificar las palabras más utilizadas por los usuarios y explorar la presencia de stop words.

5. **Extracción de Características:**
   - Aplicar técnicas de extracción de características, como TF-IDF, para preparar los datos para el análisis de sentimiento.

6. **Análisis de Sentimiento:**
   - Descargar y aplicar un léxico (en este caso, "Latin 1") para evaluar el sentimiento de los tweets.
   - Categorizar los tweets en positivos, negativos y neutros, asignando puntuaciones correspondientes.
   - Analizar las palabras más utilizadas en cada categoría y por cada usuario.

7. **Modelado y Evaluación:**
   - Transformar las puntuaciones de sentimiento a una escala binaria (0 para negativo, 1 para positivo).
   - Dividir los datos en conjuntos de entrenamiento y prueba.
   - Implementar y ajustar modelos de aprendizaje automático, como Linear SVM y Random Forest.
   - Evaluar el rendimiento de los modelos mediante métricas relevantes y visualizar resultados con matrices de confusión.

8. **Conclusiones y Recomendaciones:**
   - Sintetizar los hallazgos del análisis de sentimiento.
   - Reflexionar sobre las limitaciones del enfoque y las posibles áreas de mejora.
   - Proporcionar recomendaciones para futuras investigaciones o aplicaciones del análisis de sentimiento en contextos similares.
