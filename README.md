## Redes de unicel





### Unicel en la vida diaria

¿Sabías que el vaso de unicel donde tomaste tu bebida en aquella fiesta puede tardar hasta 1000 años en degradarse?

Probablemente pensarás que solo fue un vaso, pero el tema se torna más preocupante al saber que tan solo en México se desechan alrededor de 100 mil toneladas de unicel al año. 
Y es que el unicel, conocido científicamente como poliestireno expandido (EPS), es un material plástico derivado del petróleo, compuesto por un 95% de aire y 5% de materia prima, por lo que  tiende a ocupar cantidades masivas de espacio con un bajo peso neto.
Cuando el unicel es desechado, cuenta con diferentes destinos que van desde ser incinerados a grandes temperaturas emitiendo gases altamente dañinos, o bien, fragmentarse en microplásticos que pueden terminar en el océano, representando un enorme peligro para la vida marina. Además, su principal material es el estireno, un compuesto químico que ha sido catalogado como cancerígeno de acuerdo a la Agencia de Sustancias Tóxicas y el Registro de Enfermedades de Estados Unidos de América (ATSDR).


   <img src="Vaso.jpeg" width=500>

Ante esto, diferentes países han tomado cartas en el asunto a través de acciones como prohibir el uso de unicel o en la creación de plantas de separación y reciclaje. Sin embargo, separar enormes cantidades de unicel con los métodos convencionales puede representar una alternativa poco eficaz en términos económicos, generando cierto desinterés en la creación de plantas de reciclaje, tal es el caso de México, que cuenta únicamente con una planta para el reciclaje del unicel, la cual se encuentra en el centro del país y es propiedad de la compañía de plásticos Dart.

Por lo tanto, se llevó a cabo el desarrollo de una base de datos de un modelo de deep learning para el reconocimiento de unicel en desechos, con la finalidad de aportar una solución eficaz a los métodos que actualmente se aplican en las plantas de reciclaje y asi poder aportar una medida encaminada a lograr el objetivo 12: Producción y consumo sostenible, de la Agenda 2030 para el Desarrollo Sostenible de la ONU.


### Metodología

Para la detección automática de polímeros como el unicel, se utilizó el sistema YOLO (por sus siglas en inglés You Only Look Once), el cual es un algoritmo con base en redes neuronales y convolucionales capaz de detectar distintos objetos en tiempo real. 
Primero, se tomaron aproximadamente 200 fotos de desechos donde se visualizarán objetos de unicel en distintas posiciones, formas y ángulos. Posteriormente, utilizando el lenguaje de programación Python, se procedió a etiquetar cada una de las imágenes con el programa labelImg para asi poder llevar a cabo el entrenamiento del modelo de deep learning con duración aproximada de 5 horas para reconocer este tipo de material con la mayor precisión posible.
Finalmente, se utilizó otro grupo reducido de imagenes de desechos para comprobar la eficiencia del modelo.

<img src="Diagrama.jpeg" width=700>


### Resultados



<img src="DSC01094.png" width=400> <img src="IMG_0750.png" width=400>

### Conclusiones

Al comprobar la eficiencia del modelo, se observó que el modelo no identificó correctamente los desechos objetivo. Estos resultados se vieron afectados por limitaciones de tiempo, la poca cantidad de datos (imágenes) e incluso condiciones climatológicas que impidieron que el modelo se entrenara correctamente. A pesar de esto, el modelo es bueno y puede entrenarse mucho mejor aumentando significativamente el número de imágenes (>10000) y si se entrena por un periodo de tiempo más prolongado. Además, podría ser un proyecto escalable ya que puede aplicarse para el reconocimiento de cualquier otro tipo de desecho.


### Video
 1. Para insertar un video de YouTube, en la página de YouTube del video selecciona compartir y selecciona el código de html.
 <iframe width="560" height="315" src="https://www.youtube.com/embed/PLj1-CMNERM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 2. Insertar el link de tu video en YouTube, [nuestro video](https://youtu.be/rmXvlBPq24Q).
 4. Puedes subir el archivo de tu video directamente a Github [instrucciones aquí](https://stackoverflow.com/questions/4279611/how-to-embed-a-video-into-github-readme-md)
 
### Por equipo 2.1:

* Delicia Cortés
* Andrea Tamayo
* Krystel Rodríguez
* David Ramírez

Club 2. "Learning Machine de Polimeros"

<img src="Logo_CdeCMx.png" width=300>
