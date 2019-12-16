# FAIR tutorials
In deze repository zullen verschillende tutorials geplaatst worden die raakvlakken hebben met FAIR data.

De [eerste tutorial](./Ontologie%20voor%20datasets.md) gaat over hoe je verschillende bronnen van data, die over hetzelfe onderwerp gaan, kunt koppelen zonder de data zelf te hoeven converteren. In de tutorial wordt voor dat doel een ontolgie gebouwd om te laten zien hoe een ontologie in combinatie met Linked Data meerwaarde kan bieden in het koppelen van meerdere bronnen.

De tutorial gaat uit van enige basiskennis over [Protégé](https://protege.stanford.edu/) en ontologieën. Deze tutorial is gebaseerd op versie 5.5.0 van deze vrij beschikbare tool. Zeker niet perfect, maar wel de beste en meest ondersteunde (op bijv. www.stackoverflow.com). De ontologie die gemaakt wordt is [hier](./BMI%20ontologie.owl) beschikbaar.

De [tweede tutorial](./data2triples.md) beschrijft de stappen om tabulaire data in de vorm van een CSV bestand om te zetten naar Linked Data. Hiervoor maken we gebruik Karma. Alle voorbeeld data en de bestanden die we aanmaken tijdens het uitvoeren van de tutorial zijn te vinden in de map [bestanden/data2triples](./bestanden/data2triples/)

De derde tutorial gebruikt de data die gecreëerd is in de tweede tutorial om een triple store te vullen met deze data en de bijbehorende ontologie, zodat we de data kunnen visualiseren en queries uit kunnen voeren met behulp van SPARQL.
