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
Baje los datos para el ejercicio de reseñas de aqui: <https://www.dropbox.com/sh/rw3zoaykrsti2mq/AABiRpvMZppNTOzq0N46tYBwa?dl=0> o del folder Datos en este repositorio.

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
## Usuarios
```Json
{
  "user_id": "l6BmjZMeQD3rDxWUbiAiow",
  "name": "Rashmi",
  "review_count": 95,
  "yelping_since": "2013-10-08 23:11:33",
  "useful": 84,
  "funny": 17,
  "cool": 25,
  "elite": "2015,2016,2017",
  "friends": "c78V-rj8NQcQjOI8KP3UEA, alRMgPcngYSCJ5naFRBz5g, ajcnq75Z5xxkvUSmmJ1bCg, BSMAmp2-wMzCkhTfq9ToNg, jka10dk9ygX76hJG0gfPZQ, dut0e4xvme7QSlesOycHQA, l4l5lBnK356zBua7B-UJ6Q, 0HicMOOs-M_gl2eO-zES4Q, _uI57wL2fLyftrcSFpfSGQ, T4_Qd0YWbC3co6WSMw4vxg, iBRoLWPtWmsI1kdbE9ORSA, xjrUcid6Ymq0DoTJELkYyw, GqadWVzJ6At-vgLzK_SKgA, DvB13VJBmSnbFXBVBsKmDA, vRP9nQkYTeNioDjtxZlVhg, gT0A1iN3eeQ8EMAjJhwQtw, 6yCWjFPtp_AD4x93WAwmnw, 1dKzpNnib-JlViKv8_Gt5g, 3Bv4_JxHXq-gVLOxYMQX0Q, ikQyfu1iViYh8T0us7wiFQ, f1GGltNaB7K5DR1jf3dOmg, tgeFUChlh7v8bZFVl2-hjQ, -9-9oyXlqsMG2he5xIWdLQ, Adj9fBPVJad8vSs-mIP7gw, Ce49RY8CKXVsTifxRYFTsw, M1_7TLi8CbdA89nFLlH4iw, wFsNv-hqbW_F5-IRqfBN6g, 0Q1L7zXHocaUZ2gsG2XJeg, cBFgmOCBdhYa0xoFEAzp_g, VrD_AgiFvzqtlR15vir3SQ, cpE-7HK514Sr5vpSen9CEQ, F1UYelhPFB-zIKlt0ygIZg, CQAL1hvsLMCzuJf9AglsXw, 1KnY1wr15WfEWIRLB9IS6g, QWFQ-kXBiLbid-lm5Jr3dQ, nymT8liFugCrM16lTy0ZfQ, qj69bdd885heDvUPCyHd2Q, DySCZZcgbdrlHgEovk5y9w, lZMJIDuvhT9Dy4KyquLXyA, b_9Gn7wS93AoPZPR0dIJqQ, N07g1IaLh0_6sUjtiSRe4w, YdfPX_7DxSnKvvdCJ57iOw, 8GYryZPD22W7WgQ8kvMkEQ, cpQmAgOWatghp14h1pn1dQ, EnchhymLYMqftCRjqvVWmw, -JdfKhFktE7Zs9BMDFcPeQ, uWhC9eof98zPkvsalgaqJw, eyTlNDDaiPatfe6mheIZ0g, VfHq0o73aKsODvfAhwAQtg, kvD5tICngLAaQDujSFWupA, dXacwEhqi9-3_XT6JeH0Og, NfU0zDaTMEQ4-X9dbQWd9A, cTHWBdjSKbctSUIvWsgFxw, 3IEtCbSDF5t7RkZ20T6s9A, HJJXTrp6UybYyPdQ9DA0JA, JaXogQFVjzGRAeBvzamBHg, NUonfKkjS1iVqnNITtgXZg, D5vaJAYp0sOrGfsj9qvsMA, H27Ecbwwu4FGAlLgICourw, S8HrLmMiE4u8FWYWkNEoTw, Io36Y3xWQcIX9rYvPcYfXQ, J5mcqh8KxYpqjaLBNlwcig, -nTB3_08g06fD0GT8AtDBQ, wMpFA46lihK8oFns_5p65A, RZGFJHeomGJCWp3xcL3ejA, ZoQSzzXoSP1RxOD4Amv9Bg, qzM0EB0SkuuGIFv0adjQAQ, HuM6vvuveken-fPZ7d4olA, H3oukHpGpn9n_mJwSDSQyQ, PkmsJsQ8FIZe8eh8c_u96g, wSByVbwME4MzgkJaFyfvNg, YEVqknoDmrHAoUbHX0nPnA, li3vsK1XAPmeJYAUTYflHQ, MKc8yXi0glbPYt0Qb4PECw, fQPH6W9fksi27gkuUPnFaA, amrCMrDsoRetYFg2kwwdFA, 84dVQ6n6r2ezNaTuc7RkKA, yW9QjWY0olv5-uRKv3t_Kw, 5XJDj7c3eoidfQ3jW18Zgw, txSc6a6pIDctvwyBeu7Aqg, HFbbDCyyqP9xPkUlcxeIdg, hTUv5oh2do6Z3OppPuuiJA, gSqonG9J4fNM-fl_fE71AA, pd9mgTFpBTg5F9x-MsczNg, j3VE22V2GcHiH8UZxfFLfw, NYXlMW-T-3V4Jqr4r-i0Wg, btxgAZedxX8IWhMifA7Xkg, -Hp5mPLiRJNFnyeX5Ygzag, P6-DwVg6-t2JuQwIUEk0iQ, OI2TvxYvZrAodBG_RF53Xw, bHxf_VPKmZur1Bier-6A2A, Et_Sb39cVm81_Xe9HDM8ZQ, 5HwGl2UyYbaRq8aD6YC-fA, ZK228WMcCKLo5thcjD7rdw, iTf8wojwfm0NOi7dOiz3Nw, btYRxQYNJjpecflNHtFH0A, Kgo42FzpW_dXFgDKoewbtg, MNk_1Q_dqOY3xxHZKeO8VQ, AlwD504T9k0m5lkg3k5g6Q",
  "fans": 5,
  "average_stars": 4.03,
  "compliment_hot": 2,
  "compliment_more": 0,
  "compliment_profile": 0,
  "compliment_cute": 0,
  "compliment_list": 0,
  "compliment_note": 1,
  "compliment_plain": 1,
  "compliment_cool": 1,
  "compliment_funny": 1,
  "compliment_writer": 2,
  "compliment_photos": 0
}

```
