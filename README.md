# A First Analysis of Friendship and Work Relationships in Students who Take a Course Together

This project was realized by 

**Diego A Heredia F**

**Juan C Higuera C**

And was presented for the course **Introduction To Sociophysics** of the National University of Colombia.

Using tools from network science we study the structure of relations of friendship and work.

En este trabajo se estudian las relaciones de amistad y colaboración académica, en el sentido de ser ayudado y haber ayudado, sobre un grupo de 24 estudiantes encuestados que ven conjuntamente una materia. Este grupo no corresponde con el total de estudiantes en el curso, y se centra principalmente en un grupo de nodos altamente interconectados que representan a un grupo de amigos. Se estudia la relación de este grupo con los nodos aledaños y a partir de la transitividad y densidad del grupo se evidencia que la relación de amistad implica un vinculo más fuerte entre los actores que los une y clusteriza más comparados con las relaciones de ayuda académica.  De la componente principal de amigos se encontraron dos subgrupos, uno relacionado con la intermediación de la componente principal con el resto de nodos y otro relacionado con la cohesión al interior del grupo. Se usó la reciprocidad de las relaciones y la correspondencia entre las respuestas de los encuestados como criterio de confiabilidad de las respuestas. 

Como un recuento de lo anterior, las medidas a utilizar se presentan a continuación

- Grado/centralidad de grado
- Densidad de los grafos
- Centralidad de intermediación, betweenness
- Coeficiente de Clusterización
- Transitividad
- Reciprocidad
- Hubbs/Authorities
- Cutpoints

La relación de amistad demuestra ser la relación más clusterizada, transitiva y menos densa de las tres estudiadas, lo que concuerda con lo que se espera para una relación como la amistad, caracterizada por la fortaleza de sus vínculos en comparación con las relaciones de ayuda académica entre estudiantes. Por otra parte, la reciprocidad de las relaciones con respecto a la componente principal, altamente interconectada, indica que los criterios de los actores sobre lo que ser amigo de alguien significa no difieren significativamente, salvo en casos específicos como los nodos 11 y 21. Las mediciones de centralidad en la relación de amistad nos permiten determinar a los nodos 7 y 9 como los más importantes de la red, en el sentido de que propician la interacción de la componente principal con los nodos de la periferia, y además son nodos fundamentales en mantener unido y clusterizado a este grupo, junto con el nodo 2.

Las relaciones de ayuda o colaboración académica demuestran componer una red más extendida y robusta, donde los nodos que pertenecen a la periferia se relacionan entre sí sin recurrir a la componente principal. Esto se evidencia en las medidas de transitividad y densidad para estas relaciones, siendo menores a los valores obtenidos para la amistad, lo que también indica una menor cohesión entre los nodos, indicando que las relaciones académicas son vínculos más débiles y de más alcance que las relaciones de amistad. Se encontró también que pese a lo anterior, en estas relaciones los nodos que mayor centralidad acumulan son aquellos de la componente principal, pues al ser un grupo de amigos en el curso, es probable y más frecuente que se ayuden entre si de lo que nodos de la periferia lo hacen.

Con respecto a las medidas globales, se observa que la correspondencia, planteada en el modelo del sistema, entre las relaciones de Le han Ayudado y Ud ha Ayudado, realmente se tiene y se evidencia en la similitud entre medidas como la densidad, el número de relaciones y la transitividad; aunque no de una manera exacta, dado que la relación Le han Ayudado tiene un mayor número de relaciones, indicando así que los actores en el curso parecen tener más en cuenta a las personas que los han ayudado que a las que ayudan; nuevamente en esto influye la componente principal de amigos, pues es más fácil reconocer y reportar haber ayudado a un amigo que a una persona con la que muy raramente se interactúa.
