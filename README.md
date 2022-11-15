# tfm_gee

Esta app te permite visualizar varias colecciones de imagenes (imageCollection), disponibles en Earth Engine Data Catalog. Permite seleccionar el ImageCollection, sus bandas, elegir el estadistico para reducir esta coleccion, o seleccionar una imagen de la coleccion dentro del rango temporal seleccionado. Tambien permite escoger una paleta con su rango de visualización para representar los resultados.

Instucciones:

"From date, To date": Seleccion del periodo que representa el imageCollection.

"Band": Permite seleccionar la banda o bandas del imageCollection que se quiere visualizar. Debe introducirse el valor separado por comas y sin comillas (B1, B2, B3...).

"ImageColl": Seleccion del imageCollection que se quiere representar, se debe escribir como figura en el ejemplo (MODIS/006/MOD11A1).

"Image": Muestra las diferentes imagenes que contiene el imageCollection dentro del periodo de estudio, si se selecciona alguna de las opciones, la aplicacion cargara esa imagen en concreto y no la reduccion correspondiente del imageCollection.

"Reduce": Seleccion del estadistico que se desea aplicar para la representacion del imageCollection. En caso de que se haya seleccionado alguna opcion en "Image", este estadistico no se aplicara.

"Palette": Define la paleta que se quiere utilizar para la representacion de los resultados en el mapa. Se debe escribir separado por comas y cada unos de los codigos entre comillas simples ('040274', '040281', '0502a3', '0502b8', '0502ce', '0502e6'...)

"VisRange": Define los valores maximos y minimos que utilizara la "Palette" para representar los resultados. Se permiten numeros negativos y flotantes.

"Layer Name": Indica el nombre con que se va a cargar la capa.
