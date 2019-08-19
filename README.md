# Clase-ED
Estructuras de Datos 2019
En este repositorio encontraras información relevante para la clase.

## UML
Para familiarizarse un poco con la herramienta UML para el diseño de sistemas de clases, revisen la información en esta liga <https://www.visual-paradigm.com/guide/uml-unified-modeling-language/uml-class-diagram-tutorial/>

## GIT
Las tareas se asignarán y entreagarán a través de Github.
Para lo que vamos a hacer sólo se necesitan los comandos básicos para copiar repositorios y subir información. No es necesario hacer branches, merges, etc....
Para un primer tutorial vean <https://www.youtube.com/watch?v=SWYqp7iY_Tc>
Pero hay muchos.

## Estilo de Programación en Java

Existen ciertos buenas prácticas para hacer que un programa sea fácil de leer y por lo tanto de entender, modificar y componer. El estilo tiene que ver con como formatear el código, como nombrar variables, métodos etc , como agrupar en directorios los diferentes archivos de un proyecto entre otras cosas.
Leen las partes relevantes del siguiente documento
<https://google.github.io/styleguide/javaguide.html> que es como Google sugiere hacerlo (escogí las sugerencias de Google ya que es una empresa que genera muuuuucho código y asumo entonces sus buenas prácticas están bien probadas)

# Formato Json
Aquí esta la especificación del lenguaje <https://www.json.org/>.
Baje los datos para el ejercicio de reseñas de aqui: <https://www.dropbox.com/sh/rw3zoaykrsti2mq/AABiRpvMZppNTOzq0N46tYBwa?dl=0>
Un par de ejemplos de Json para establecimientos y reseñas
## Establecimentos
```Json
Ejemplo 1

{
  "business_id": "1SWheh84yJXfytovILXOAQ",
  "name": "Arizona Biltmore Golf Club",
  "address": "2818 E Camino Acequia Drive",
  "city": "Phoenix",
  "state": "AZ",
  "postal_code": "85016",
  "latitude": 33.5221425,
  "longitude": -112.0184807,
  "stars": 3,
  "review_count": 5,
  "is_open": 0,
  "attributes": {
    "GoodForKids": "False"
  },
  "categories": "Golf, Active Life",
  "hours": null
}
Ejemplo 2
{
  "business_id": "QXAEGFB4oINsVuTFxEYKFQ",
  "name": "Emerald Chinese Restaurant",
  "address": "30 Eglinton Avenue W",
  "city": "Mississauga",
  "state": "ON",
  "postal_code": "L5R 3E7",
  "latitude": 43.6054989743,
  "longitude": -79.652288909,
  "stars": 2.5,
  "review_count": 128,
  "is_open": 1,
  "attributes": {
    "RestaurantsReservations": "True",
    "GoodForMeal": "{'dessert': False, 'latenight': False, 'lunch': True, 'dinner': True, 'brunch': False, 'breakfast': False}",
    "BusinessParking": "{'garage': False, 'street': False, 'validated': False, 'lot': True, 'valet': False}",
    "Caters": "True",
    "NoiseLevel": "u'loud'",
    "RestaurantsTableService": "True",
    "RestaurantsTakeOut": "True",
    "RestaurantsPriceRange2": "2",
    "OutdoorSeating": "False",
    "BikeParking": "False",
    "Ambience": "{'romantic': False, 'intimate': False, 'classy': False, 'hipster': False, 'divey': False, 'touristy': False, 'trendy': False, 'upscale': False, 'casual': True}",
    "HasTV": "False",
    "WiFi": "u'no'",
    "GoodForKids": "True",
    "Alcohol": "u'full_bar'",
    "RestaurantsAttire": "u'casual'",
    "RestaurantsGoodForGroups": "True",
    "RestaurantsDelivery": "False"
  },
  "categories": "Specialty Food, Restaurants, Dim Sum, Imported Food, Food, Chinese, Ethnic Food, Seafood",
  "hours": {
    "Monday": "9:0-0:0",
    "Tuesday": "9:0-0:0",
    "Wednesday": "9:0-0:0",
    "Thursday": "9:0-0:0",
    "Friday": "9:0-1:0",
    "Saturday": "9:0-1:0",
    "Sunday": "9:0-0:0"
  }
}
```
## Reseñas
```json

Ejemplo 1

{
  "review_id": "Q1sbwvVQXV2734tPgoKj4Q",
  "user_id": "hG7b0MtEbXx5QzbzE6C_VA",
  "business_id": "ujmEBvifdJM6h6RLv4wQIg",
  "stars": 1,
  "useful": 6,
  "funny": 1,
  "cool": 0,
  "text": "Total bill for this horrible service? Over $8Gs. These crooks actually had the nerve to charge us $69 for 3 pills. I checked online the pills can be had for 19 cents EACH! Avoid Hospital ERs at all costs.",
  "date": "2013-05-07 04:34:36"
}
Ejemplo 2
{
  "review_id": "2TzJjDVDEuAW6MR5Vuc1ug",
  "user_id": "n6-Gk65cPZL6Uz8qRm3NYw",
  "business_id": "WTqjgwHlXbSFevF32_DJVw",
  "stars": 5,
  "useful": 3,
  "funny": 0,
  "cool": 0,
  "text": "I have to say that this office really has it together, they are so organized and friendly!  Dr. J. Phillipp is a great dentist, very friendly and professional.  The dental assistants that helped in my procedure were amazing, Jewel and Bailey helped me to feel comfortable!  I don't have dental insurance, but they have this insurance through their office you can purchase for $80 something a year and this gave me 25% off all of my dental work, plus they helped me get signed up for care credit which I knew nothing about before this visit!  I highly recommend this office for the nice synergy the whole office has!",
  "date": "2016-11-09 20:09:03"
}
```
