# Fietsen-in-Friesland
Applied the data science basics

Als het om fietsen gaat, heeft Friesland één van de meest afwisselende landschappen van de Nederlandse provincies. Mooie landschappen als de Friese Wouden, de Friese meren, het Waddengebied en de vele terpen die er in de provincie te vinden zijn. Naast dit prachtige natuur, kom je langs historische dorpen en de oude 11 steden. Dit allemaal afgewisseld door enorme open vlaktes, waar het voor mijn gevoel altijd waait. Niet voor niets de "dutch mountains" genoemd.
Elke keer als ik weer op de fiets stap, eerst bekijken wat de windrichting is, om zo lekker tegen de wind in te beginnen aan je ronde. Voor mijn gevoel waaide het 's middags altijd harder dan 's morgens. Ik heb meer dan eens gedacht toen ik weer met een ronde van 100km bezig was: "Wat zou nu de beste tijd zijn om te vertrekken, om het meeste profijt van de wind te hebben?".

Dit leek mij een mooie eerste opdracht om uit te werken.

Stelling: " 's Middags waait het meestal harder dan 's morgens ".

Daarbij wil ik vragen beantwoorden zoals:

- wat is de gemiddelde windkracht over een jaar gezien?
- wat is de gemiddelde windkracht over een week gezien?
- wat is de gemiddelde windkracht over een dag gezien?
- Wat is de meest voorkomende windrichting en de windkracht per windrichting?

Wanneer deze gegevens bekend zijn, kunnen we berekenen wat de meest efficiëntste tijd is om een ronde van 100km te fietsen, uitgaande van 25km per uur.

Uitgangspunten:
- Morgen: 0600 - 1200
- Middag: 1200 - 1800
- Avond: 1800 - 2200
- Nacht: 2200 - 0600

Deze dataset gebruikt KNMI data, gemeten in Leeuwarden!
Data is van 1-1-2000 tot 1-1-2021 en wordt vanuit een dataset in Dataiku geladen.
Dataset download link: http://projects.knmi.nl/klimatologie/uurgegevens/selectie.cgi

Als eerste gaan we de data laden en bekijken.
Note: In Jupyter Notebooks gebruiken we display() in plaats van print(), omdat dat een mooiere weergave geeft.

Er zijn diverse mogelijkheden om dergelijk vragen uit te werken. Ik heb diverse methoden gebruikt en toegepast. Aangezien ik 'lerende' ben, heb ik zoveel mogelijk verschillende methodes gebruikt. Doel is namelijk voor mijzelf, om zoveel mogelijk toegepaste kennis op te kunnen doen. Voor mij is dat natuurlijk prachtig om te kunnen combineren met mijn andere hobby, namelijk het fietsen.
