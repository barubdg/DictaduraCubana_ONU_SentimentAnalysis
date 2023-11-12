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

#### 1. Origen del Dataset:
   - El dataset utilizado en este proyecto, denominado "Data-Eleccion-ONU-Cuba", fue adquirido a través de la aplicación de técnicas de web scraping utilizando la herramienta Octoparse 8. La fuente primaria de los datos es la red social Twitter.

###### 1.1 Selección de la Plataforma:
   - Twitter fue elegido como la plataforma principal para la recolección de datos debido a su relevancia en la difusión de información y opiniones.

###### 1.2. Configuración de Octoparse 8:
   - Se utilizó Octoparse 8, una herramienta especializada en web scraping, para automatizar el proceso de extracción de datos. Esta herramienta permitió definir patrones de extracción específicos para capturar información relevante de los tweets.

###### 1.3. Definición de Criterios de Búsqueda:
   - Se establecieron criterios de búsqueda específicos, como hashtags, palabras clave, o perfiles relevantes, para focalizar la obtención de datos en el tema de interés: Elección de Cuba en la ONU.

###### 1.4. Extracción de Datos:
   - Octoparse 8 fue configurado para navegar por la plataforma Twitter, recopilando tweets del tema definido en los criterios de búsqueda. Se extrajeron datos como el contenido del tweet, la fecha de publicación, y otros metadatos relevantes.

###### 1.5. Proceso Ético y Legal:
   - Es importante destacar que el proceso de web scraping se llevó a cabo de manera ética y legal, respetando los términos de servicio de Twitter y las leyes de privacidad aplicables.

#### 2. Descripción de las Columnas:
   - Titulo = nombre de usuario
   - Imagen = imagen_nombreusuario
   - css1dbjc4n_URL = url del usuario
   - css901oao = nick de usuario
   - css4rbku5_URL = enlace del reposteo de usuario
   - css4rbku5 = Fecha de respuesta
   - css901oao1 = comentario de usuario
   - css4rbku5_URL2 = Enlace Cantidad de visualización
   - css901oao3 = cantidad de reposteo
   - css4rbku54 = Cantidad de visualización (vistas)

#### 3. Calidad de los Datos:
   - La combinación de estos procesos aseguró que el dataset resultante estuviera libre de problemas significativos, como valores nulos, duplicados o inconsistencias, proporcionando una base sólida para el análisis subsiguiente de sentimiento.
###### 3.1 Verificación, Corrección y Eliminación de Columnas:
   - Se llevó a cabo una revisión detallada de las columnas presentes en el dataset. Aquellas que no aportaban información relevante para el análisis de sentimiento fueron eliminadas, simplificando así la estructura del dataset.

###### 3.2 Eliminación de Valores Nulos Existente:
   - Se identificaron y eliminaron valores nulos en las columnas pertinentes. Este paso fue crucial para garantizar la integridad y coherencia de los datos utilizados en el análisis.

###### 3.3 Valores Duplicados:
   - Se implementó un proceso para identificar y eliminar valores duplicados en el dataset. Esto contribuyó a evitar sesgos en el análisis y garantizar la representatividad de las muestras.

###### 3.4 Rellenar Valores Nulos Existente por Fila-Columna:
   - Cuando fue necesario, se aplicaron técnicas de imputación para rellenar valores nulos de manera estratégica, evitando la pérdida de información valiosa.

###### 3.5 Conversión de Cantidad - Visualización en Mil a Números Enteros:
   - Se llevó a cabo la conversión adecuada de las cantidades expresadas en visualizaciones en mil a números enteros, facilitando así la interpretación y comparación de los datos.

#### 4. Desafíos Encontrados:
   - Durante el proceso de construcción del dataset y el análisis de sentimiento, se enfrentaron varios desafíos que requirieron atención y resolución. Aquí se destacan los principales:

###### 4.1 Limpieza y Tokenización:

   - **Desafío:** La fase de preprocesamiento, específicamente la limpieza y tokenización del texto, presentó dificultades debido a la presencia de caracteres especiales, emojis o formatos no estándar en los tweets.

   - **Solución:** Se implementaron técnicas avanzadas de limpieza de texto y tokenización para abordar estos desafíos. Se utilizaron expresiones regulares y bibliotecas especializadas para manejar eficazmente la diversidad de formatos presentes en los datos.

###### 4.2 Correlación entre Nick_Usuario:

   - **Desafío:** La identificación y análisis de la correlación entre los nicks de usuario en los tweets presentó desafíos debido a la variabilidad en la forma en que los usuarios expresan sus opiniones y la posible presencia de cuentas falsas o bots.

   - **Solución:** Se llevó a cabo un análisis detallado de la variabilidad y autenticidad de los nicks de usuario. Se aplicaron técnicas de detección de anomalías para identificar posibles cuentas no auténticas, y se ajustó el enfoque de análisis de sentimiento para considerar estas variabilidades.

###### 4.3 Submuestreo (Undersampling):

   - **Desafío:** En el proceso de modelado, la gestión del desequilibrio de clases en el conjunto de datos fue un desafío, ya que la cantidad de tweets positivos y negativos podía variar significativamente.

   - **Solución:** Se optó por aplicar técnicas de submuestreo (undersampling) para equilibrar las clases y mejorar la capacidad predictiva de los modelos. Se evaluó y visualizó el impacto de esta técnica en la representación general del conjunto de datos.

#### 5. Tamaño del Dataset:
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
