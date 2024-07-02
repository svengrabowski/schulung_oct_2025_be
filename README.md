# Angular Grundlagen Recipe Backend


## Installation

`npm i`

## Projekt starten

`npm run start`

## Routen

Basierend auf der db.json werden folgende Routen erzeugt:

```
GET    /recipes
GET    /recipes/:id
POST   /recipes
PUT    /recipes/:id
DELETE /recipes/:id
```

## Beispieldaten

```
{
    "id": "1",
    "name": "Pizza",
    "img": "/recipe_pictures/pizza.jpg",
    "portions": 4,
    "lastEdited": "2024-07-02T08:16:04.477Z",
    "duration": {
        "unit": "Min.",
        "value": 30
    },
    "level_of_difficulty": "Mittel",
    "ingridients": [
        {
            "unit": "g",
            "quantity": 200,
            "name": "Weizenmehl Type 550"
        },
        {
            "unit": "g",
            "quantity": 50,
            "name": "Hartweizengrieß"
        },
        {
            "unit": "Würfel",
            "quantity": 0.25,
            "name": "Hefe"
        },
        {
            "unit": "ml",
            "quantity": 160,
            "name": "Wasser, lauwarm"
        },
        {
            "unit": "TL",
            "quantity": 1,
            "name": "Salz"
        },
        {
           "unit": "EL",
           "quantity": 2,
           "name": "Olivenöl"
        },
        {
           "unit": "",
           "quantity": 4,
           "name": "Romatomaten"
        },
        {
           "unit": "TL",
           "quantity": 1,
           "name": "Oregano, getrocknet"
        },
        {
           "unit": "TL",
           "quantity": 0.25,
           "name": "Salz"
        },
        {
           "unit": "Kugel",
           "quantity": 1,
           "name": "Büffelmozzarella"
        }
   ],
   "preparation": "Zunächst für den Pizzateig Mehl, Grieß und Salz gründlich vermengen. Die Hefe im warmen Wasser auflösen, 5 Minuten ruhen lassen und dann zur Mehlmischung geben. Die Zutaten so lange mit dem Knethaken des Handrührers, in der Küchenmaschine oder von Hand kneten, bis ein elastischer Teig entsteht, das dauert ungefähr 10 Minuten. Falls der Teig zu fest sein sollte einfach noch etwas warmes Wasser zugeben, wenn der Teig zu flüssig ist, etwas Mehl hinzugeben. Erst dann das Olivenöl unterkneten.\n\nDen Teig in Frischhaltefolie wickeln oder unter einem Geschirrtuch mindestens 30 Minuten gehen lassen. Der Teig lässt sich ebenfalls hervorragend im Hefeteig-Programm eines Brotbackautomaten zubereiten.\n\nIn der Zwischenzeit die Roma-Tomaten quer halbieren und über einer feinen Reibe bis auf die Schale abreiben. Das überschüssige Wasser aus den Tomaten durch ein feines Sieb abgießen, so dass nur der Tomatensaft und das Innere der Tomaten übrig bleiben. Diese Tomaten nach Geschmack mit etwas Salz würzen.\n\nEin Backblech ordentlich mit gutem, erhitzbarem Olivenöl bepinseln und den Ofen auf 250°C Ober- und Unterhitze vorheizen. Den Teig nochmals von Hand durchkneten und auf einem bemehlten Brett etwa in Größe des Blechs von der Mitte nach außen ausrollen. Der Teig sollte dabei etwa 3 mm dick ausgerollt werden.\n\nDen ausgerollten Teig auf das Blech geben und nur hauchdünn (das ist wichtig!) mit den Tomaten bestreichen. Mit dem Oregano bestreuen. Die Chorizo in feine Stücke schneiden und auf der Pizza verteilen. Den Mozzarella von Hand in Stücke reißen und über die Pizza streuen.\n\nAuf der zweiten Einschubleiste von unten etwa 10 Minuten backen. Wer einen Pizzastein hat, kann sich das Backen auf dem Blech natürlich sparen und stattdessen zwei Runde Pizzen aus dem Teig formen."
}
```