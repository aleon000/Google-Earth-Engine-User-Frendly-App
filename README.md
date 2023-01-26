# Google Earth Engine User Frendly App

Esta app permite visualizar varios datasets disponibles en Earth Engine Data Catalog. Permite seleccionar el set de datos, sus bandas y su repreetación en el mapa de Google Earth Engine. También permite descargar los estadísticos de la variable perteneciente al area de estudio.

Descripcción:

"From date, To date": Selección del período de estudio.

"Band": Permite seleccionar la banda o bandas del dataset que se quiere visualizar. Debe introducirse el valor separado por comas y sin comillas (B1, B2, B3...).

"ImageColl": Selección del dataset que se quiere representar, se debe escribir como figura en el ejemplo (MODIS/006/MOD11A1).

"Image": Muestra las diferentes imagenes que contiene la colección de imagenes seleccionada dentro del período de estudio, si se selecciona alguna de las opciones, la aplicación cargara esa imagen en concreto y no la reduccion correspondiente del imageCollection.

"Reduce": Seleccion del estadístico que se desea aplicar para la representacion de la colección de imagenes. En caso de que se haya seleccionado alguna opción en "Image", este estadistico no se aplicara.

"Palette": Define la paleta que se quiere utilizar para la representación de los resultados en el mapa. Se debe escribir separado por comas y cada unos de los códigos entre comillas simples ('040274', '040281', '0502a3', '0502b8', '0502ce', '0502e6'...)

"VisRange": Define los valores máximos y minimos que utilizara la "Palette" para representar los resultados. Permiten números negativos y flotantes.

"Layer Name": Indica el nombre con que se va a cargar la capa.
