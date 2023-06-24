# Sistema-de-Reconocimiento-Facial-con-FaceNet
Sistema de Reconocimiento Facial en Python utilizando el modelo MobileNet para hacer la identificación de rostros en imágenes y modelos de tipo FaceNet para poder comparar los rostros. El sistema funciona tanto para hacer el reconocimiento en imágenes almacenadas como con la cámara en vivo.

## Modelos
En el archivo Modelo_FaceNet.ipynb se pueden evidenciar cada una de las capas del modelo Face Net y como se realizo la carga de los pesos del modelo preentranado que se obtuvo del [github](https://github.com/R4j4n/Face-recognition-Using-Facenet-On-Tensorflow-2.X). 

En el archivo Face_Net.ipynb se encuentra el código para realizar el reconocimiento facial a través del calculo de los embeddings utilizando este modelo y su comparación. Además, incluye el procesamiento adecudo de las imágenes previo, y el cálculo del porcentaje de clasificación correcta y de falsos positivos posterior. Código adaptado de [Tutorial: Reconocimiento Facial con Machine Learning en Python](https://www.codificandobits.com/blog/tutorial-reconocimiento-facial-python/).

El archivo VGGFace.ipynb contiene todo lo mencionado para Face Net anteriormente pero realiza el reconocimiento facial a través del cálculo de los embeddings utilizando VGGFace, que se obtuvo del [github](https://github.com/prlz77/vgg-face.pytorch). Esto con el fin de poder comparar el desempeño del primer modelo versus el de VGGFace.

El archivo Api_Rec_Facial_Vivo.ipynb contine el código para realizar el reconocimiento facial en vivo con los rostros de los autores del presente trabajo o para realizar el reconocimiento a traves de imagenes previamente guardadas. Incluye la detección de rostros en video, el cálculo y comparación de los embeddings. El código para la detección por video fue adapatado de [Omes](https://omes-va.com/reconocimiento-facial-python-opencv/) 

Cabe resaltar que para ejecutar nuevamente el código es necesario establecer correctamente los directorios con las imagenes que se desean utilizar y ejecutarlo de forma local en el computador.

La base de datos utilizada fue obtenida de la plataforma [kaggle](https://www.kaggle.com/competitions/11-785-s23-hw2p2-classification/overview).

## Desarrollado por:

- Danna Gabriela Bustacara Rodríguez, dbustacara@unal.edu.co
- Maria Jimena López Munevar, malopezmu@unal.edu.co
- Kevin Andrés Leal Pérez, klealp@unal.edu.co
