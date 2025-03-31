# P2 Clasificación

Este reporte aborda un análisis de datos proporcionados por Kaggle en el contexto de la competencia "Spaceship Titanic" (https://www.kaggle.com/competitions/spaceship-titanic). A lo largo de este proyecto, desarrollaré y evaluaré varios modelos de clasificación utilizando diferentes enfoques de machine learning. Las variables disponibles en la base de datos incluyen:

* PassengerId: Identificador único de cada pasajero.

* HomePlanet: Planeta de origen del pasajero.

* CryoSleep: Indica si el pasajero estaba en criosueño durante el viaje (sí/no).

* Cabin: Número de cabina asignado al pasajero.

* Destination: Destino final del pasajero.

* Age: Edad del pasajero.

* VIP: Indica si el pasajero es una persona VIP (sí/no).

* RoomService: Gasto del pasajero en el servicio de habitación durante el viaje.

* FoodCourt: Gasto del pasajero en el área de comida.

* ShoppingMall: Gasto del pasajero en el centro comercial.

* Spa: Gasto del pasajero en el spa.

* VRDeck: Gasto del pasajero en el área de VR (realidad virtual).

* Name: Nombre del pasajero.

* Transported: Variable objetivo que indica si el pasajero fue transportado exitosamente (1) o no (0).

Se implementarán modelos de regresión logística multinomial, Análisis Discriminante Lineal (LDA), árboles de decisión, y métodos de ensemble, evaluando la calidad de cada uno mediante validación cruzada. Finalmente, se seleccionará el mejor modelo y se utilizará para predecir las clases de los datos de prueba, evaluando su desempeño a través de la métrica de exactitud (accuracy).

Este proyecto incluye los siguientes documentos:

[Reporte en formato ipynb](P2%20584678.ipynb)

[Reporte en formato html](P2%20584678.html)

[Base de datos (train)](train.csv)

[Base de datos (test)](test.csv)
