# TFM
Trabajo Final de Máster: Modelos estadísticos para el análisis integrativo de experimentos multi-ómicos

##RESUMEN
Los avances recientes en las tecnologas de secuenciacion nos han brindado una
oportunidad sin precedentes para entender mejor el papel de la genomica, epigenetica
y transcriptomica en la regulacion de la expresion genica. Un analisis integrativo de
experimentos en los que se han medido varias de estas omicas proporciona una descripcion mas
clara y completa de los procesos biologicos, fenotipos o enfermedades estudiados. Sin embargo,
muchas de las estrategias de integracion de datos descritas en la literatura consisten en
analizar por separado cada tipo de datos omicos y comparar \integrativamente" los resultados,
ya que todava se carece de herramientas estadsticas para la integracion de datos que puedan
ser utilizadas por investigadores que no son expertos en estadstica.
El desarrollo de una herramienta estadstica para la integracion de datos multi-omicos
plantea no pocos desafos. Primero, la gran cantidad de variables omicas (miles de genes)
en comparacion con los peque~nos tama~nos de muestra en este tipo de experimentos (por
lo general, no mas de decenas de muestras biologicas). En segundo lugar, el nivel inherente
de ruido en las tecnologas omicas. Y tercero, el dise~no de una herramienta que sirva para
una amplia gama de escenarios biologicos o dise~nos experimentales y ayude a interpretar los
resultados y a responder a las preguntas biologicas.
En este trabajo, hemos explorado diversas estrategias estadsticas para superar estas
limitaciones en el contexto de los modelos lineales generalizados de forma que se puedan
obtener modelos utiles que expliquen la regulacion de la expresion genica. Para facilitar la
aplicacion de dichas estrategias a usuarios no estadsticos, hemos generado una librera en el
lenguaje estadstico R y una aplicacion web mediante Shiny que se ha puesto a disposicion de
cualquier investigador a traves del repositorio publico Bitbucket: https://bitbucket.org/
ConesaLab/more/.
Palabras clave: integracion de datos multi{omicos, regulacion de la
expresion genica, modelos lineales generalizados, bioinformatica, paquete
en R, Shiny.