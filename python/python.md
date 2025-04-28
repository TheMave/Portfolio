# Python en AI Portfolio

## AI en python gegeven als vakken

Tijdens mijn werk op de hogeschool heb ik verschillende **python based vakken** gegeven, zoals:

- **Inleiding Applied AI** (KNN, KMeans, BOW, CNN, NN doorrekenen)

- **Algoritmen en Datastructuren** (Trees, Lists, Pathfinding, MonteCarlo Tree Search)
  Voor dit vak heb ik een test-framework [(zie evt. deze downloadable zip)](gomoku_easy_test_environment_v1.66.zip) geschreven welke studenten kunnen gebruiken om hu eigen AI voor een gomoku (5 op een rij spel) te kunnen testen (tegen elkaar en mijn eigen, web-based variant). Het is deels gebaseerd op PyGame.

- **Computer Vision**

- **Meten Regelen en besturen** 

Al deze vakken raakten in meer of mindere mate ook aan AI.

Verder heb ik diverse studenten begeleid op een project ter ontwikkeling van **nasaliteits quantificering middels AI** voor het Wilhelmina Kinderziekenhuis.

## Geautomatiseerd leerdoelenkaart inkleursysteem

Voor de hogeschool heb ik met python een [**geautomatiseerd leerdoelenkaart inkleursysteem**](https://github.com/HU-TI-DEV/semesteroverzichten) ontwikkeld. Zo'n leerdoelenkaart ziet er nog on-ingekleurd [op deze manier](https://github.com/HU-TI-DEV/TI-S3/blob/main/leerdoelen/interactieve-leerdoelen-kaart/LeerdoelenKaart_S3.svg) uit.

- Periodiek scraped een python script van alle studenten de beoordelingen van de diverse opdrachten van canvas (dat is een cloud systeem voor onderwijs), en weegt die mee in de inkleuring van de leerdoelenkaart.
- Elke student (en docent) kan daarmee in een oogwenk zien hoe de betreffende student ervoor staat.

## Eigen gomoku AI

Om de studenten te prikkelen om een goede gomoku AI te schrijven, heb ik zelf een AI voor het spel geschreven [(speel er hier zelf tegen)](https://www.pikido.com/gomoku_react/). Het produceert in enkele tientallen milliseconden een goede zet, en is tot nog toe niet verslagen door een AI van een student.

## AI en python thuis

Als eigen "nuttige" AI toepassing heb ik geschreven:

- Een **muiscontroller** die de cursor bestuurt **middels camerabeelden**.
  Dat werkt via de volgende stappen:
  - Kalibratie: Op grid posities verschijnt een stip op het scherm waar je naar moet kijken.
  - Dat herhalen met andere kleding, haar in de war, bril op of af, etc.
  - CNN trainen met deze testset.
  - Getrainde CNN muis laten aansturen.

Dat werkte aan de ene kant goed. Aan de andere kant werkten grafische kaart en cpu's van de processor voortdurend rond de 90%. Dus enorm beslag op systeem resources en ventilatorherrie. Vandaar dat ik het niet meer gebruik.

## Flask

- Vanilla Flask applicaties

- Flask applicaties op basis van blueprints

Het flask gebeuren hoort ook bij Web/Cloud portfolio. Meer erover is [hier](../web/web.md) te vinden.
