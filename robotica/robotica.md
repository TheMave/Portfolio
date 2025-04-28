# Robotica Portfolio

## Meten, Regelen en Besturen

Het vak Meten, Regelen en Besturen dat ik doceerde aan de hogeschool had raakvlakken met Robotica. Studenten moesten er regelsystemen bouwen, bestaande uit sensoren (zoals camera's), actuatoren en control units (typisch microcontroller, raspberry pi of combinatie). Via een **PID regeling** werd dan een en ander geregeld. Veel studenten kozen voor het regelen van de hoogte van een bal in een **ventilatorbuis** of van het regelen van de positie van een **gebalanceerde bal op een plank**, welke beweegt naar de positie waar je op het scherm klikt. Alvorens deze regelsystemen aan de studenten te suggeren, heb ik ze uiteraard ook zelf gebouwd. Van laatstgenoemde zelfs twee flitsend werkende versies. Helaas heb ik die systemen ook weer afgebroken en kan er geen video-opnames van vinden. <i>Mental note voor mezelf- maak voortaan overal video's van met eventueel toekomstig portfolio materiaal in gedachten :-)</i>.

## Pokemonkaart sorterende Robotarm / Digital Twin

Voordat ik docent aan de hogeschool werd, heb ik als hobby projectje een [Pokemonkaart sorterende robotarm](https://www.youtube.com/watch?v=0Oi4DWKNfh4&t=5s) gemaakt. 
Features:

- **Eigen ontwerp** van een 7 assige robotarm, gemaakt van goedkope MG996 servos en zelf-ontworpen en 3d geprinte koppelstukken.
- Via **computervision** wordt de individuele pokemonkaart en zijn positie herkend (**Vuforia**).
- Via **zelfgeschreven inverse kinematics** (die had ik al geschreven voor mijn eerdere Unity3D game "Paffen Vreten en Zuipen") de robotarm de kaart vanaf een willekeurige naburige plek laten overpakken.
- Daarbij gebruik makend van een [**Digital Twin** van diezelfde robotarm](https://youtube.com/shorts/0eRmFyaWNlw) binnen Unity3D.
- De servo's werden draadloos bestuurd **via bluetooth** (gewoon, voor de leukigheid)

Enfin, de uitdaging was dus een vrij cheapo, niet al te stijve robotarm via software toch nog aardig bestuurbaar te maken. Dat was aardig gelukt. Verder met een zoon die pokemon fan is, succes verzekerd!
