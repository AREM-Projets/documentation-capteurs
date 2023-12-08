# Capteurs Time Of Flight (TOF)

Les capteurs TOF (Time Of Flight) sont des capteurs qui fonctionnement de manière très similaire à des capteurs ultrasons, mais utilisent des ondes électromagnétiques (un laser) au lieu des ondes sonores.

Il va donc émettre de la lumière (un faisceau laser), puis la détecter et calculer le temps de trajet du faisceau.

## Avantages

- temps de mesure bien plus faible qu'un capteur ultrasons (30ms au lieu de 70ms, voir datasheets)
- permet de détecter des objets assez petits
- interface I2C

## Inconvénients

- plus complexes qu'un capteur ultrasons en terme de fonctionnement
- plus chers que des capteurs ultrasons (mais faits par ST donc pas un problème si sponsor)
