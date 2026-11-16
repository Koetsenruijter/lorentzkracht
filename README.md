# Lorentzkracht oefenen

Een oefenapp voor de lorentzkracht. Leerlingen bepalen de richting van de ontbrekende grootheid met de rechterhandregel **Ik Ben Lorentz**:

- **Duim** = stroomrichting *I*
- **Wijsvinger** = magneetveld *B*
- **Middelvinger** = lorentzkracht *F*

De app is één HTML-bestand. Er is geen installatie, geen account en geen server nodig. Hij werkt in de browser, ook op een telefoon.

## Openen

Open `index.html` in een browser. Via GitHub Pages is de app ook online te bereiken.

## Hoe werkt het

Bij elke opdracht ontbreekt precies één grootheid: de lorentzkracht **F**, het magneetveld **B** of de stroom **I** (of snelheid **v** bij deeltjes). Kies de richting met de knoppen:

- de acht pijlen voor de richtingen in het vlak van het papier
- **⊙** voor uit het papier en **⊗** voor in het papier

Na het antwoord zie je direct of het goed is. Bij een fout antwoord staat er een stapsgewijze uitleg met de rechterhandregel. Met **Volgende opdracht** ga je verder, en met **Overslaan** (de knop is licht) sla je een opdracht over zonder dat die meetelt.

## Kleuren

| Kleur | Betekenis |
|---|---|
| Groen | stroom *I* of snelheid *v* |
| Blauw | magneetveld *B* |
| Rood | lorentzkracht *F* |

## Extra opties

Klik op **Extra opties** om de volgende vinkjes aan te zetten:

- **Geladen deeltjes: protonen en elektronen.** Naast draden komen protonen (+) en elektronen (−) voor, met een groene snelheidspijl *v*. Bij een elektron staat de stroom tegengesteld aan de snelheid.
- **Niet-loodrechte situaties (verdieping).** *I* (of *v*) en *B* staan onder een hoek van 30° tot 150°. De lorentzkracht staat dan nog steeds loodrecht op beide, dus in of uit het papier. De uitleg laat zien dat de kracht kleiner is, met F = B·I·ℓ·sin θ.
- **Cirkelbanen en middelpuntzoekende kracht (6V).** Een proton of elektron beweegt in een cirkelbaan in een magneetveld dat loodrecht op het papier staat. De lorentzkracht is dan de middelpuntzoekende kracht. Er geldt B·q·v = m·v²/r.

## Uitleg

Met de knop **Uitleg** opent een venster met:

- waarom er een lorentzkracht ontstaat
- een voorbeeld met een stroomdraad
- de rechterhandregel in vijf stappen, met plaatje
- tips, zoals welke vinger je afleest en hoe je met ⊙ en ⊗ omgaat

## Score

De score (goed van totaal, en de reeks goede antwoorden op rij) wordt alleen op dit apparaat bijgehouden. Met **Opnieuw beginnen** zet je hem op nul.

## Bestanden

- `index.html`: de volledige app (HTML, CSS en JavaScript in één bestand)
- `README.md`: dit bestand
