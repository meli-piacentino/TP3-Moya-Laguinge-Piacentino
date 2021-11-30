# TP3-Moya-Laguinge-Piacentino

En cada uno de los scripts se encuentra:

- **modelo transfer learning con Data Augmentation**: modelo de transfer learning con VGG16 cargado con los pesos de imagenet con data augmentation a partir de capas de preprocesamiento de keras para aumentar la cantidad de datos de entrenamiento

- **modelo transfer learning ImageDataGenerator**: modelo de transfer learning con VGG16 cargado con los pesos de imagenet con data augmentation a partir ImageDataGenerator que devuelve randomly transformed data.

- **modelo transfer learning**: modelo de transfer learning con VGG16 cargado con los pesos de imagenet sin data augmentation.

- **Modelo transfer learning VGG16-final**: modelo de transfer learning con VGG16 (de keras) cargado con los pesos de imagenet con data augmentation.

- **modelo transfer learning -ImageDataGenerator - MobileNET**:  modelo de transfer learning con MobileNET cargado con los pesos de imagenet con data augmentation a partir ImageDataGenerator que devuelve randomly transformed data.

- **Prueba Modelo MobileNET (Libreria)**: modelo secuencial visto en clase con MobileNET cargado con los pesos de imagenet con data augmentation a partir de capas de preprocesamiento de keras para aumentar la cantidad de datos de entrenamiento


- **Prueba Modelo Alexnet**: modelo secuencial visto en clase de Alexnet a mano, poniendo cada una de las capas en una función que se encuentra en el Helper. Además, se utiliza data Aumgentation a partir de capas de preprocesamiento de keras para aumentar la cantidad de datos de entrenamiento
