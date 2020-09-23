# Cibercrimen_predicciones_Espana_2020
NEOLAND


Septiembre 2020

Cibercrimen en España, análisis predictivo año 2020


 
 



Presentado por
Jessye Pedraja Rodríguez 


 
Antecedentes 
El desarrollo de las tecnologías de las comunicaciones y su expansión hacia los hogares ha permitido la proliferación de la ciberdelincuencia. Ante esta realidad es bueno conocer las estadísticas sobre este fenómeno para estar prevenidos.
Según el estudio realizado por el Colegio Profesional de la Criminología de la Comunidad de Madrid, sobre la ciberseguridad y la confianza se determinó que en los hogares españoles con datos se aprecia lo siguiente respecto a los perfiles en redes sociales:
•	5,5% abierto a todo el mundo
•	11,3% compartido a amigos de sus amigos
•	49,3% visible solo a sus contactos
•	11% visible solo a algunos amigos

Estos son otros datos aportados por el estudio:
•	Los españoles superan en 6 puntos la media de uso de las redes sociales que la media de los europeos (73% frente a 67%)
•	Mayor precocidad en el uso de las nuevas tecnologías y acceso a las redes.
o	95 % de niños entre 10 y 15 años 
o	98% de jóvenes entre 15 y 26 años
•	En los adultos mayores entre 65 y 74 años solo un 43% hace uso de las nuevas tecnologías
•	Más hombres que mujeres, con solo una diferencia de dos puntos porcentuales, acceden a las redes
•	La compra electrónica se ha triplicado en la última década
•	Más del 83% de los hogares tienen acceso a internet

Descripción del proyecto
En este proyecto se busca crear una herramienta con la cual predecir la ciber criminalidad para el año 2020 y hacer un análisis estadístico de los datos según rango de edad, sexo, comunidad autónoma y grupo penal.

En la actualidad se han realizado muchos estudios sobre el comportamiento delictivo y sus diferentes causas. Con este trabajo se persigue mostrar la evolución con los años de la ciberdelincuencia, la composición y distribución geográfica, así como una valoración del estado actual de la efectivad de las autoridades frente a este flagelo.



Tecnologías aplicadas 
Python, pandas, regresiones logísticas tales como Regresión lineal, Regresión de árboles de decisión, Regresión Polinomial, preprocesamiento de datos.


Fuentes de datos
•	Agencia de datos de Europa Press (https://www.epdata.es/)
•	Sitio web de la Iniciativa de datos abiertos del Gobierno de España (https://datos.gob.es/)
•	Instituto Nacional de Estadísticas (https://www.ine.es/)
•	Portal estadístico de criminalidad del Ministerio del Interior (https://estadisticasdecriminalidad.ses.mir.es/publico/portalestadistico/)
•	Sitio web del Colegio Profesional de la Criminología de la Comunidad de Madrid (https://colegiocriminologosmadrid.es/el-estado-de-la-cibercriminalidad-en-espana-datos-y-analisis/)




Alcance del modelo
El alcance del proyecto se resume en dos etapas esenciales, la primera será la parte estadística descriptiva de interés para el trabajo, mientras que en la segunda etapa será destinada a la predicción de las variables seleccionadas con vista al 2020.


Análisis estadístico 
A continuación, se muestran dichos eventos en el periodo comprendido desde al año 2011 al 2019 en España todos estos hechos ya con la causa penal aplicada.


 
La comunidad con más detenciones e investigados corresponde a Andalucía con un 20,7%.



 
 
 
La comunidad con más hechos conocidos corresponde a Cataluña con un 17,5%.



 
 
La comunidad con más hechos esclarecidos corresponde a Andalucía con un 22,6%.



 


 
Las detenciones e investigados presentan un comportamiento ascendente en el tiempo tal y como se muestra en la siguiente gráfica.


 


Las victimizaciones también presentan un comportamiento ascendente en el tiempo tal como se observa en la siguiente gráfica.



 



 
Un comportamiento notable en esta investigación es que a través de los datos se comprobó que la mayor incidencia en detenciones e investigaciones en el periodo 2011-2019 corresponde al sexo masculino, además el mayor delito cometido es fraude informático, tal como se muestra en la siguiente gráfica.




 








 
El rango de edad que presenta mayor incidencia, según las detenciones e investigados corresponde a 26 a 40 años.

 

El delito que con mayor frecuencia se comete es el fraude informático, siendo el de menor incidencia la Interferencia en los datos y en el sistema. En la siguiente gráfica se aprecia con mayor detalle.

 

Distribución geográfica de los cibercrímenes cometidos en España en el periodo 2011-2019 



 



Predicciones para el 2020

Durante esta etapa del trabajo se utilizaron varios métodos de predicción tales como:
•	Regresión lineal
•	Regresión de árboles de decisión
•	Regresión Polinomial
La regresión Polinomial es el método que más se ajusta a las necesidades del proyecto y es la adecuada según los datos escogidos para el mismo. Por lo consiguiente este será al que se hará mención en este resumen final. En los notebook  hay evidencia de la utilización de los métodos antes mencionados.

Regresión Polinomial
Todas las regresiones aplicadas al modelo son de grado 4, de esta manera se logra una mayor efectividad al modelo aplicado.
 
Las Victimizaciones en el año 2019 fueron en total 195446.
Se predice que para el año 2020 serán 259383 victimizaciones, unas 63937 más con respecto al año 2019 lo que representa un incremento del 32%.
En la siguiente gráfica se muestra la evolución ascendente de los datos según su comportamiento.

 

Las Detenciones e investigados en el año 2019 fueron de 8914.
Se predice que para el año 2020 serán 11097 detenciones e investigados, 2183 más con respecto al año 2019 lo que representa un incremento del 24%.
En la siguiente gráfica se muestra la evolución ascendente de los datos según su comportamiento.

 

 
Los Hechos esclarecidos en el año 2019 fueron de 30841.
Se predice que para el año 2020 serán 34538 hechos esclarecidos, unas 3697 más con respecto al año 2019 lo que representa un incremento del 12%.
En la siguiente gráfica se muestra la evolución ascendente de los datos según su comportamiento.


Los Hechos conocidos en el año 2019 fueron de 218302.
Se predice que para el año 2020 serán 282912 hechos conocidos, unas 64610 más con respecto al año 2019 lo que representa un incremento del 30%.
En la siguiente gráfica se muestra la evolución ascendente de los datos según su comportamiento.


Conclusiones 
La ciberdelincuencia, como fenómeno colateral al desarrollo y expansión de las nuevas tecnologías, posee una tendencia ascendente cada año. El incremento de los servicios digitales y la penetración en los hogares estimulan desde edades tempranas la utilización de los medios para acceder a internet, entonces es cuando ante este auge la delincuencia tradicional transmuta y adopta nuevas formas de delinquir constituyendo en ocasiones verdaderas mafias internacionales operando en las redes digitales.
Todos los hechos vinculados a los ciberdelincuentes, tienen como factor común la explotación de las vulnerabilidades de los sistemas informáticos, el desconocimiento, ingenuidad y la confianza de los usuarios. Es menester que se divulguen en mayor medida las diferentes formas en que los sistemas y usuarios pueden ser atracados digitalmente. Es común hoy en día que los cibercriminales empleen la ingeniería social para obtener información que les permita acceder a los sistemas, por eso es muy importante la salvaguarda de la información privada y restringir el acceso público a los perfiles en las redes sociales.
Es preocupante que las estadísticas muestren una baja resolución de los delitos por parte de las autoridades. Esto deja en relieve carencias que han de ser resueltas para garantizar la seguridad de las redes. Los ataques cada más sofisticados han propiciado la creación de compañías privadas dedicadas exclusivamente a la seguridad informática y cubren en parte la demanda de las fuerzas policiales para hacer frente a los delitos informáticos. El estudio de los datos, la constante monitorización del uso de las redes, la identificación de patrones y demás técnicas de predicción son parte del día a día en los centros dedicados a la lucha contra el cibercrimen. La correcta utilización de la tecnología y el estudio minucioso de los datos frenarán el desarrollo de la ciberdelincuencia, y la economía y la sociedad en su conjunto estarán más seguros.


