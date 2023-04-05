# lzo-maths
Math practice site

## Description
This repo contains a website for practice math for SPP caporal concours.
The questions is refresh all 3 days.

## How to
How to create your questions ?  From directory "exercices" and edit "questions.json" file. 

The json structure : 

```json
[
  {
      "id": 1,
      "text": "Parmi les différents trajets ci-dessous, lequel est le plus rapide pour le CCR d'atteindre le lieu d'incendie ?",
      "answers": [
          {
              "text": "32 km à 70 km/h"
          },
          {
              "text": "25 km à 80 km/h"
          },
          {
              "text": "36 km à 90 km/h"
          },
          {
              "text": "16 km à 60 km/h"
          }
      ],
      "correctAnswer": "16 km à 60 km/h"
  },
]

```
