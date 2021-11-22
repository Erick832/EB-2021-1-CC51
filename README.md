# EB-2021-1-CC51
# Objetivo
Crear conocimiento a partir de los datos, al desarrollar un Análisis Exploratorio de Datos (EDA) y resolver un problema básico de Modelización de Datos, en el marco de la ejecución de un proyecto de analítica.

# Alumnos participantes
•	Erick Wilson Aronés Garcilazo
•	David Martin Yanallaco Temoche

# Breve descripción del conjunto de datos 
El conjunto de datos motivo de análisis se denomina “Tendencias de las estadísticas de videos de YouTube” (Trending YouTube Video Statistics). Este conjunto de datos, en su versión original se obtiene desde el sitio web Kaggle, de la cuenta de Mitchell J. Este usuario se desempeña como desarrollador de software en Backbeat Technologies y es proveniente del Reyno Unido.

Este conjunto de datos es un registro diario de los videos de YouTube de mayor tendencia, cuyo contenido incluye la recopilación de datos de varios meses sobre las tendencias diarias de videos de YouTube en los siguientes países México, India, Alemania, Gran Bretaña, EE. UU, Canadá. Para este trabajo, el conjunto de datos a trabajar será del país de Canadá y cuenta con 20 variables y 40881 registros.

# Conclusiones.

## 1.	¿Qué categorías de videos son las de mayor tendencia?

Analizando los datos de la gráfica con la frecuencia de videos por categoría y la tabla con los datos de la categoría con su frecuencia, concluimos que la categoría de “Entertainment” es la de mayor tendencia con un resultado bastante superior a las demás categorías, le siguen las categorías de “News and Politcs”, “People and Blogs” y “Comedy”.
 
## 2.	¿Qué categorías de videos son los que más gustan? ¿Y las que menos gustan?

Visualizando la gráfica de barras agrupadas de likes y dislikes por categorías. Concluimos que, las principales categorías que más gustan son las de “Music”, “Entertainment”, “Comedy” y “People and Blog” ya que estos géneros poseen una gran cantidad de seguidores y popularidad en YouTube. En las categorías que menos likes poseen están “Show”, ”Travel and Event” y ”Movies”. Estas categorías, actualmente son las mas afectadas por las restricciones de derecho de autor, la cual algunos canales terminan disminuyendo la calidad de los videos o generar interrupciones en medio estos, para evitar la eliminación del video. Además, existen varias plataformas de streming que hoy en día poseen mucha popularidad y son mejor que visualizar estas categorías en YouTube. 


## 3. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”?

Después de analizar el gráfico de dispersión de cada categoría, concluimos que las categorías que poseen una mejor proporción de likes y dislikes son las siguientes “Movies”,”Shows”,”Autos and Vehicles” y “Travel and Event”, categorías que no son muy populares y no poseen muchas vistas, y por ello la diferencia de likes y dislikes no es muy marcada.

## 4.¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” / “Comentarios”?

Analizando los gráficos de dispersión, afirmamos que las categorías que poseen una mejor proporción de vistas y cantidad de comentarios son “Shows” y ”Travel and Event”. Del mismo modo, los mismos factores de la pregunta anterior, afecta en la diferencia de las vistas comentarios.
 
## 5. ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?

El volumen de los videos en tendencia ha variado levemente en los últimos meses registrados, pero aún se sigue manteniendo en sus valores. Lo que indica que las personas, aun utilizan este medio con la misma frecuencia de antes y sigue siendo importante para las empresas analizar el comportamiento de las personas en este medio para obtener grandes oportunidades de marketing. 

## 6. ¿Qué Canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?

Los canales que son tendencias más frecuentemente son SET India, MSNNBC, FBE, The Young Turks y REACT. La mayoría de estos canales poseen una gran cantidad de vistas y forman parte de la categoría “Enterteinment” que es la categoría de mayor tendencia y vistas, la otra parte de los canales forman parte de la categoría “News y Politics” la cual suele ser bastante popular cuando ocurren hechos importantes y de gran relevancia. En los canales de menos frecuencia, existen varios y poseen una baja cantidad de likes, dislikes, vistas y comentarios entre ellas están Marcus Johns, Marc Fitt Fr, Marie Claire, etc.

## 7. ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?

Analizando el mapa de los Estados por Vistas y su tabla. Visualizamos que los estados que presentan la mayor cantidad de vistas son Nova Scotia, British Columbia, Alberta y Northwest Territories.

Seguidamente, en el siguiente mapa, vemos que los Estados que presentan mayor cantidad de likes son los mismos Estados anteriores, pero variando el orden de la siguiente forma British Columbia, Northwest Territories, Alberta y Nova Scotia.
Finalmente, en el mapa de Estados por dislikes, visualizamos a los Estados de Alberta, Nova Scotia, Prince Edward Island y Nortwest Territories.

Los Estados en los resultados en su mayoría coinciden entre ellos, lo cual indica la relación que existe entre estas variables y que la cantidad de likes y dislikes totales tienen una relación en la cantidad de vistas del Estado a que pertenecen.

## 8.	¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta”?

Utilizando el modelo de regresión lineal podemos predecir ciertos resultados esperados. 
En el caso del valor de las vistas como resultado esperado utilizamos los datos de entrada likes y dislikes. Según los resultados, un aumento de una unidad en los likes está relacionado con un incremento de 19 vistas aproximadamente. De la misma manera, un aumento de una unidad en los dislikes está relacionado con un incremento de 36 vistas aproximadamente. 

En el caso del número de las likes como resultado esperado utilizamos los datos de entrada dislikes, vistas y cantidad de comentarios. Con ello podemos predecir que el aumento de una unidad en los comentarios está relacionado con un incremento de aproximadamente 4 likes, así como el aumento de 44 unidades en vistas esta relacionado al incremento de un like aproximadamente. De la misma manera, el aumento de una unidad en la cantidad de dislikes esta relacionada con la disminución de 2 likes aproximadamente.
En el caso del número de las dislikes como resultado esperado utilizamos los datos de entrada likes, vistas y cantidad de comentarios. Con los resultados de los coeficientes, podemos predecir que el aumento de una unidad en los comentarios está relacionado con un incremento de aproximadamente 0.75 dislikes, así como el aumento de una unidad en vistas está relacionado con el incremento de un 0.003 dislikes aproximadamente. De la misma manera, el aumento de una unidad en la cantidad de likes está relacionada con la disminución de 0.1 likes aproximadamente.

Finalmente, concluimos que es posible predecir una aproximación en las variables esperadas utilizando algunas variables de entrada, en algunos casos como el de los likes una disminución en la variable dislikes afecta en el incremento de likes, y sucede lo mismo en el caso de los dislikes, donde la disminución de likes incrementa la cantidad de dislikes. Ambas variables se ven incrementas por las vistas y la cantidad de comentarios, lo cual tiene sentido ya que en los mismos Estados donde estaban la mayor cantidad de vistas, eran los mismos estados en donde se presentaba la mayor cantidad de likes y dislikes. 

## 9.¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?
Para esta pregunta utilizamos la columna de comentarios deshabilitados, ya que muchos canales tienden a deshabilitar los comentarios cuando muchos de ellos son negativos. Según nuestro gráfico, el 1,42% de los videos tienen desactivados los comentarios. Lo cual indica, que lo videos en tendencia poseen una mínima cantidad de comentarios negativos y son más los comentarios positivos.

# Licencia
Apache License 2.0

Una licencia permisiva cuyas principales condiciones requieren la preservación de derechos de autor y avisos de licencia. Los contribuyentes proporcionan una concesión expresa de derechos de patente. Los trabajos con licencia, las modificaciones y los trabajos más grandes pueden distribuirse bajo diferentes términos y sin código fuente.
