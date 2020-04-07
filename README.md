# FAIR tutorials
In deze repository zullen verschillende tutorials geplaatst worden die raakvlakken hebben met FAIR data. Het gaat niet zozeer over het uitleggen van wat FAIR is. Het beoogd een starpunt te geven voor de vraag welke technische stappen je moet zetten om data volgens FAIR principes te kunnen publiceren.

De tutorials geven in deze eerste versies zeker geen perfect of totaal overzicht. Ik denk dat de losse onderwerpen ook relevant zijn voordat alles compleet is, daarom heb ik ervoor gekozen deze tutorials te publiceren. Het is mijn eerste serieuze poging tutorials te maken en ook in het gebruik van Github ben ik onervaren. Tips, opmerkingen, etc. zijn dan ook van harte welkom.

De [eerste tutorial](./Ontologie%20voor%20datasets.md) gaat over hoe je verschillende bronnen van data, die over hetzelfe onderwerp gaan, kunt koppelen zonder de data zelf te hoeven converteren. In de tutorial wordt voor dat doel een ontolgie gebouwd om te laten zien hoe een ontologie in combinatie met Linked Data meerwaarde kan bieden in het koppelen van meerdere bronnen. Een korte introductie over Linked Data vindt je [hier](https://github.com/mnieuwland/LinkedData).

De tutorial gaat uit van enige basiskennis over [Protégé](https://protege.stanford.edu/) en ontologieën. Deze tutorial is gebaseerd op versie 5.5.0 van deze vrij beschikbare tool. Zeker niet perfect, maar wel de beste en meest ondersteunde (op bijv. www.stackoverflow.com). De ontologie die gemaakt wordt is [hier](./BMI%20ontologie.owl) beschikbaar.

De [tweede tutorial](./data2triples.md) beschrijft de stappen om tabulaire data in de vorm van een CSV bestand om te zetten naar Linked Data. Hiervoor maken we gebruik Karma. Alle voorbeeld data en de bestanden die we aanmaken tijdens het uitvoeren van de tutorial zijn te vinden in de map [bestanden/data2triples](./bestanden/data2triples/)

De [derde tutorial](./triples2store.md) gebruikt de data die gecreëerd is in de tweede tutorial om een triple store te vullen met deze data en de bijbehorende ontologie, zodat we de data kunnen visualiseren en queries uit kunnen voeren met behulp van SPARQL.

Deze drie tutorials vormen een (technische) basis voor FAIR data, maar maken data nog niet FAIR. Voor meer details over FAIR is het [GO FAIR Initiative](https://www.go-fair.org/go-fair-initiative/) een goed startpunt. Veel succes met de tutorials.

Marc Nieuwland.
