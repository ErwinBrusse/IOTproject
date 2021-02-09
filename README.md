IOT-project, bewegingen detecteren middels een HC-SR501 motion sensor.

Dit project meet bewegingen aan de hand van een HC-SR501 motion sensor. De data die de motion sensor ontvangt, zal doorgestuurd worden richting de raspberry pi, waar vervolgens een LED-lampje mee wordt aangestuurd.
De HC-SR501 sensor detecteert bewegingen door infraroodstraling. Mensen en dieren wordt gedetecteert door de lichaamswarmte.
De specificaties van de sensor zijn:

Specificaties:

Input Spanning: DC 4.5-20V
Ruststroom: <50uA
Level output: High 3.3 V /Low 0V
Vertragingstijd is instelbaar
Gevoeligheid is instelbaar van circa 3 meter tot 7 meter*
Afmetingen: 32mm*24mm
Hoek van Sensor: <100 °
Werktemperatuur: -15°C-+70°C
Lens grootte: 23mm(diameter)

Inspiratie:

Ik ben dit keuzevak gestart, omdat ik in de toekomst met Python wil werken binnen Power BI. Dit leek mij een uitgekozen moment om een goede start te maken.
Tijdens de introductie werd verteld dat de opdracht bestond uit het bouwen van een prototype wat data ontvangt, doorstuurt en acties uitvoert.
Ik ben niet zo technisch aangelegd, waardoor ik heb gekozen het project zo simpel mogelijk te houden. Complexere projecten had ik achteraf niet uit kunnen voeren.
Ik had al snel het idee om een bewegingssensor te maken, omdat ik na wat onderzoek een ander leuk idee tegenkwam.
Ik zag dat Coolblue een serie heeft op YouTube waarin ze allerlei dingen ontwerpen, zo ook een eigen Smart Mirror. Dit leek mij enorm gaaf om te maken, maar te hoog gegrepen.
Uiteindelijk is het mijn doel om een Smart Mirror te maken die apps weergeeft op basis van de persoon die ervoor staat.
Een motion sensor is een goede start om te experimenteren met de mogelijkheden.

Benodigde hardware:

- Raspberry PI
- HC-SR501 motion sensor
- Jumper cables
- LED-lampje 5v
- Breadboard (optioneel)

Uitvoering project:
In de eerste weken van het keuzevak heb ik mij geörienteerd naar de mogelijke project, waaruit ik voor een bewegingssensor heb gekozen.
In week 3 en 4 ben ik begonnen met een kleine zelfstudie van Lindy. Deze zelfstudie bevatte veel filmpjes met uitleg over functies, loops en dergelijke.
Vervolgens ben ik gestart met het aanleggen van het circuit. Dit leidde al snel tot problemen, omdat ik niet de juiste jumper cables had. Deze moesten besteld worden.
Nadat ik alle onderdelen tot mijn beschikking had, ben ik begonnen aan het aanleggen van het circuit.
Dit ging redelijk goed en ik begon met het definiëren van de GPIO-pins.
In week 8 heb ik de verkeerde pins aangesloten en heb ik de raspberry pi weg moeten doen wegens een defect. De SD-kaart kon niet meer uitgelezen worden.
Na de levering van een nieuwe pi heb ik mij gericht tot het configureren van de motion sensor.
De sensor deed wat hij moest doen, maar het lampje bleef niet aan staan, omdat de sensor tijdens een delay GPIO.LOW doorgeeft.
Na lang zoeken heb ik de delay in de sensor aan kunnen passen. Op dit moment moesten de timeframes (sleeps) in de code aangepast worden, zodat ze hierbij aansloten.
Na de aanpassingen deed de sensor wat hij moest doen en was het prototype af.

Foto's:
![IMG-20210203-WA0004](https://user-images.githubusercontent.com/74979378/107403850-e8d1bc80-6b05-11eb-8274-db07a3961483.jpeg)
