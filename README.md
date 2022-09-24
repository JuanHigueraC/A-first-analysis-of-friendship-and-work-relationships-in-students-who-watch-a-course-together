# A First Analysis of Friendship and Work Relationships in Students who Take a Course Together

This project was realized by 

**Diego A Heredia F**

**Juan C Higuera C**

And was presented for the course **Introduction To Sociophysics** of the National University of Colombia.

We study the structure of friendship and work relationships in a group of students, this project intended to be an introduction to the construction of complex networks and the use of tools from network science.

## Description 

En este trabajo se estudian las relaciones de amistad y colaboración académica, en el sentido de ser ayudado y haber ayudado, sobre un grupo de 24 estudiantes encuestados que ven conjuntamente una materia. Este grupo no corresponde con el total de estudiantes en el curso, y se centra principalmente en una componente principal de nodos altamente interconectados que representan a un conjunto de amigos. Se estudia la relación de esta componente con los nodos aledaños. A partir de la transitividad y densidad del grupo se evidencia que la relación de amistad implica un vinculo más fuerte entre los actores que los une y clusteriza, comparado con las relaciones de ayuda académica. De la componente principal de amigos se encontraron dos subgrupos, uno relacionado con la intermediación de la componente principal con el resto de nodos y otro relacionado con la cohesión interna del grupo. 

## Methods

Para caracterizar las relaciones de amistad y de trabajo, a los estudiantes se les realizaron las siguientes preguntas,

- De la lista de estudiantes, seleccione a quienes a lo largo de la carrera de física le han ayudado a estudiar o en actividades académicas.
- De la lista de estudiantes, seleccione a quienes a lo largo de la carrera de física usted les ha ayudado a estudiar o en actividades académicas. 
- De la lista de estudiantes, seleccione a sus amigos.

Despues de la extraccion de los datos se construyeron con UCINET software las redes dirigidas y binarias que caracterizaban estas relaciones. Se utilizaron medidas de redes tanto locales como globales para caracterizar su topologia e identificar a los nodos mas importantes en terminos de como ayudan a comunicar y mantener unida a la red. Las medidas utilizadas se presentan a continuación,

- Degree Centrality
- Graph Density
- Betweenness Centrality
- Clustering Coefficient
- Transitivity
- Reciprocity
- Hubbs/Authorities
- Cutpoints

## Results

A continuacion se muestran las redes encontradas para la relacion de amistad, y la relacion de trabajo donde se distinguen dos tipos: usted ha ayudado a quien y quienes lo han ayudado a usted en actividades academicas a lo largo de la carrera

![image](https://github.com/DiegoHerediaF/A-first-analysis-of-friendship-and-work-relationships-in-students-who-take-a-course-together/blob/16b61f32307bacd5285634acc33994d97f9eaba3/you_consider_them_friends.PNG)

**Figure 1.** Red de amistad, donde se observa la componente principal como el subgrupo de nodos altamente interconectado.

![image](https://github.com/DiegoHerediaF/A-first-analysis-of-friendship-and-work-relationships-in-students-who-take-a-course-together/blob/16b61f32307bacd5285634acc33994d97f9eaba3/they_helped_you.PNG)

**Figure 2.** Red dirigida donde los links indican quienes lo han ayudado a usted en actividades academicas a lo largo de la carrera.

![image](https://github.com/DiegoHerediaF/A-first-analysis-of-friendship-and-work-relationships-in-students-who-take-a-course-together/blob/16b61f32307bacd5285634acc33994d97f9eaba3/you_helped%20them.PNG)

**Figure 3.** Red dirigida donde los links indican a quienes usted ha ayudado en actividades academicas a lo largo de la carrera.

## Conclusions

La relación de amistad demuestra ser la relación más clusterizada, transitiva y menos densa de las tres estudiadas, lo que concuerda para una relación como la amistad, caracterizada por la fortaleza de sus vínculos en comparación con las relaciones de ayuda académica entre estudiantes. Por otra parte, la reciprocidad de las relaciones con respecto a la componente principal, altamente interconectada, indica que los criterios de los actores sobre lo que ser amigo de alguien significa no difieren significativamente, salvo en casos específicos como los nodos 11 y 21. Las mediciones de centralidad en la relación de amistad nos permiten determinar a los nodos 7 y 9 como los más importantes de la red, en el sentido de que propician la interacción de la componente principal con los nodos de la periferia, y además son nodos fundamentales en mantener unido y clusterizado a este grupo, junto con el nodo 2.

Las relaciones de ayuda o colaboración académica demuestran componer una red más extendida y robusta, donde los nodos que pertenecen a la periferia se relacionan entre sí sin recurrir a la componente principal. Esto se evidencia en las medidas de transitividad y densidad para estas relaciones, siendo menores a los valores obtenidos para la amistad, lo que también indica una menor cohesión entre los nodos, indicando que las relaciones académicas son vínculos más débiles y de más alcance que las relaciones de amistad. Los nodos con mayor centralidad son aquellos de la componente principal, pues es mas probable y frecuente que los amigos se ayuden entre si.
