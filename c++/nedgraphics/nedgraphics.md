# Nedgraphics Portfolio

Bij het bedrijf [Nedgraphics.com](https://nedgraphics.com/studio/jacquard-studio/) heb ik negeneneenhalf jaar c++ code geschreven. Ik had de eer om me met de algoritmisch en computationeel complexere code bezig te mogen houden. Dat had allemaal direct of indirect te maken met e-sampling.

De (bedrijfs-)code en modellen kan ik uiteraard niet laten zien, maar met de gerelateerde graphics is denk ik toch een aardig beeld te krijgen van wat ik gemaakt heb:

- Ik heb zowel een algemeen brei-notatiesysteem bedacht en het ontwerp van de **Knitting** software daarvoor. Verder de implementatie van de e-sampling van het breien gemaakt ([Hier is een voorbeeld gesimuleerd breiwerk voor een kabeltrui](./img/Kabeltrui.jpg)).
- Voor het software pakket **Jacquard** schreef ik verschillende stoffensimulaties: [geweven](./img/Tai_Mahal_ft_bk.jpg), al dan niet [met chenille garens](./img/Chenille_front_back.jpg), [roede-velours](./img/WireVelvet.jpg). 
- Onder water kwam het steeds neer op het fysisch uitsimuleren van de krachten die de draadkernen ([voorbeeld](./img/Draadkernen_1.jpg), [nog een voorbeeld](./img/Draadkernen_2.jpg)) op elkaar uitoefenen. 
- Ik ben technical lead geweest bij de implementatie van e-sampling voor getufte tapijten (als onderdeel van het pakket [**Tuft**](https://nedgraphics.com/product/tuft-2/)).
- Ik schreef de recoloring applicatie **TrueColoring**, zodat alle gegenereerde e-samples zonder hersimulatie binnen een split second achteraf gehercoloreerd konden worden [(Hier is eenvoorbeeld van een output)](./img/v6594_shaded_old_colors.pdf).
- Voor het software pakket **Texcelle** schreef ik een efficiente texture synthese simulatie feature. [Hier is het resultaat daarvan te zien](img/2025-04-28-14-13-31-image.png), uitgevoerd met het design van een tapijt. 
- Daarnaast voor hetzelfde pakket wat kleinere dingetjes, zoals een efficiente floodfill en het warpen van rechthoekige naar elliptische designs [(hier, op het plaatje rechtsonder is een voorbeeld daarvan te zien)](https://nedgraphics.com/product/texcelle-design-software/).
- Ten behoeve van performance optimalisatie heb ik een framework geschreven dat ervoor zorgt dat rekentijd parallel gedaan en evenredig verdeeld wordt over de verschillende fysieke cores van de cpu.
