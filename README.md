# Autor

Baruch Benjamin Dámazo Gálvez

Estudiante en ingeniería de Software (UTP)

# Descripción de la problemática

<img src="https://github.com/barubdg/DictaduraCubana_ONU_SentimentAnalysis/blob/main/img-post-twitter.png?raw=true" alt="Post Twitter: Cuba en el Consejo de Derechos Humanos">
Nota. Publicado por UHN Plus, 10 de octubre de 2023, escándalo de cuba por elección del Consejo de Derechos Humanos de la ONU. https://twitter.com/UHN_Plus/status/1711776517242470818

----

**La elección de Cuba como miembro del Consejo de Derechos Humanos de la ONU es un problema por las siguientes razones:**

_**Es un insulto a las víctimas de la represión cubana que su gobierno sea elegido para defender los derechos humanos.**_ Cuba tiene un historial de violaciones de los derechos humanos, incluyendo la represión de la libertad de expresión, la asociación y la reunión pacífica. En la actualidad, el país tiene más de 1.000 presos políticos, muchos de los cuales han sido condenados por ejercer sus derechos fundamentales. Elegir a Cuba como miembro del Consejo de Derechos Humanos es una burla a las víctimas de estas violaciones.

_**La elección de Cuba es un retroceso para la credibilidad de las Naciones Unidas.**_ La ONU se ha comprometido a promover y proteger los derechos humanos en todo el mundo. La elección de Cuba, un país con un historial de abusos de derechos humanos, es un claro ejemplo de la falta de credibilidad de la organización.

_**Es importante que la comunidad internacional exprese su rechazo a esta decisión.**_ La elección de Cuba es un mensaje equivocado a los países que violan los derechos humanos. Les dice que pueden seguir cometiendo abusos sin consecuencias. Es importante que la comunidad internacional exprese su rechazo a esta decisión y haga un llamamiento a Cuba para que libere a todos los presos políticos y respete los derechos humanos de su pueblo.

# Objetivos Generales del Proyecto

#### 1. Exploración y Definición del Problema:
   - Analizar el contexto del tweet y comprender la relevancia del problema planteado.
   - Definir claramente el objetivo general del proyecto de análisis de sentimiento.

#### 2. Construcción y Preparación del Dataset:
   - Importar las librerías necesarias y cargar el dataset de manera eficiente.
   - Realizar una exploración inicial del dataset para comprender su estructura y contenido.

#### 3. Data Wrangling y Transformación:
   - Realizar un proceso de data wrangling para garantizar la calidad y consistencia de los datos.
   - Transformar el dataset para facilitar el análisis de sentimiento, incluida la limpieza, manejo de valores nulos y duplicados.

#### 4. Análisis Exploratorio de Datos (EDA):
   - Realizar un análisis exploratorio detallado, visualizando la frecuencia de palabras y patrones en los datos.
   - Identificar las palabras más utilizadas por los usuarios y explorar la presencia de stop words.

#### 5. Extracción de Características:
   - Aplicar técnicas de extracción de características, como TF-IDF, para preparar los datos para el análisis de sentimiento.

#### 6. Análisis de Sentimiento:
   - Descargar y aplicar un léxico (en este caso, "Latin 1") para evaluar el sentimiento de los tweets.
   - Categorizar los tweets en positivos, negativos y neutros, asignando puntuaciones correspondientes.
   - Analizar las palabras más utilizadas en cada categoría y por cada usuario.

#### 7. Modelado y Evaluación:
   - Transformar las puntuaciones de sentimiento a una escala binaria (0 para negativo, 1 para positivo).
   - Dividir los datos en conjuntos de entrenamiento y prueba.
   - Implementar y ajustar modelos de aprendizaje automático, como Linear SVM y Random Forest.
   - Evaluar el rendimiento de los modelos mediante métricas relevantes y visualizar resultados con matrices de confusión.

#### 8. Conclusiones y Recomendaciones
   - Sintetizar los hallazgos del análisis de sentimiento.
   - Reflexionar sobre las limitaciones del enfoque y las posibles áreas de mejora.
   - Proporcionar recomendaciones para futuras investigaciones o aplicaciones del análisis de sentimiento en contextos similares.

# Tecnologías Utilizadas

#### 1. Google Colaboratory:

   - Google Colaboratory es una plataforma de computación en la nube gratuita que permite a los usuarios crear y ejecutar código de Python en un entorno web. Es una herramienta muy útil para el análisis de sentimientos, ya que permite a los usuarios acceder a grandes cantidades de datos de texto sin tener que instalar ningún software en su propio ordenador.

#### 2. OctoParse8:

   - OctoParse8 es un web scraper. Es una herramienta muy útil para el análisis de sentimientos, ya que permite a los usuarios extraer datos de Twitter de forma rápida y sencilla.

#### 3. Twitter:

   - Twitter es una red social en la que los usuarios pueden publicar mensajes de texto cortos, conocidos como "tweets". Es una fuente de datos muy rica para el análisis de sentimientos, ya que los usuarios a menudo expresan sus opiniones y emociones en sus tweets.

#### 4. Python:

   - Python es un lenguaje de programación de propósito general que es muy popular para el análisis de datos. Es un lenguaje de alto nivel que es fácil de aprender y usar. Python tiene una amplia gama de bibliotecas y herramientas disponibles para el análisis de sentimientos, lo que lo convierte en una opción muy versátil para este tipo de proyectos.

#### 5. Excel:

   - Excel es una hoja de cálculo popular que se puede utilizar para almacenar y manipular datos. Excel es una buena opción para guardar los resultados de su análisis de sentimientos, ya que le permite crear gráficos y tablas para visualizar sus datos.

#### 6. GitHub:

   - GitHub es un servicio de alojamiento de código fuente que le permite almacenar y compartir su código con otros. GitHub es una buena opción para guardar su proyecto de análisis de sentimientos, ya que le permite colaborar con otros y hacer un seguimiento de los cambios en su código.

# Comentarios sobre el Dataset

#### 1 Origen del Dataset:
   - Indicar la fuente de donde se obtuvo el dataset, ya sea a través de la recolección directa, descarga de repositorios en línea, u otras fuentes.

#### 2 Descripción de las Columnas:
   - Proporcionar una descripción detallada de cada columna en el dataset, incluyendo su nombre, tipo de datos, y significado.
   - Señalar si alguna columna específica fue crucial para el análisis de sentimiento.

#### 3 Calidad de los Datos:
   - Evaluar la calidad general de los datos, destacando si hubo problemas significativos con valores nulos, duplicados, o inconsistencias.

#### 4 Desafíos Encontrados:
   - Identificar y discutir los desafíos encontrados durante el análisis del dataset, como la presencia de datos ruidosos o la necesidad de procesamiento adicional.

#### 5 Tamaño del Dataset:
   - Mencionar la cantidad total de registros en el dataset y si este tamaño fue considerado adecuado para el análisis de sentimiento.

# Datos Utilizados

#### 1 Selección de Datos Relevantes:
   - Explicar la lógica detrás de la selección de las columnas específicas utilizadas para el análisis de sentimiento.

#### 2 Razones para la Elección del Dataset:
   - Justificar la elección del dataset en relación con el problema específico que se está abordando y cómo se alinea con los objetivos del proyecto.

#### 3 Preprocesamiento de Datos:
   - Detallar cualquier preprocesamiento aplicado a los datos antes de realizar el análisis de sentimiento, como limpieza de texto, tokenización, o conversión de formatos.

#### 4 Inclusión de Variables Adicionales:
   - Si se incluyeron variables adicionales o características específicas para mejorar el análisis de sentimiento, proporcionar información sobre estas adiciones y su impacto potencial.

#### 5 Limitaciones de los Datos:
   - Reconocer y discutir las limitaciones inherentes al dataset utilizado, ya sea en términos de representatividad, sesgos, o cualquier otro factor que pueda afectar la validez de los resultados.

# Resultado e Interpretaciones

# Conclusiones
