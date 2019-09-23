# Van MyBand naar SecureBand
### Welke fases ben ik doorlopen?
- Plannen
- Ontwerpen
- Coderen
- Testen
- Opleveren


### Welke onveiligheden zitten er in mijn code?
- De code is niet getest/beveiligd tegen MySQL injection
- Sommige code is rechtstreeks van internet, hier kunnen onveiligheden inzitten.
- Variabelen in PHP zijn niet private, dit betekend dat je ze overal kan aanroepen.
- Code staat openbaar op GitHub dus is gemakkelijk te checken op onveiligheden.
- Database is slecht beveiligd.

### Wat heb ik fout gedaan?
- De website is niet uitgebreid getest.

### User Stories
 User stories

| Nummer | als       | kan ik                                                     | zodat ik  (resultaat)                                   | Veiligheid |
|--------|-----------|------------------------------------------------------------|---------------------------------------------------------|----------------|
| 1      | GEBRUIKER | De hele website doorzoeken                                 | snel info kan vinden                                    | SQL INJECTIE              |
| 2      | GEBRUIKER | Wil ik een overzicht zien van alle posts                   | hij/zei een artikel kan kiezen bij mij aanspreekt.      | SQL INJECTIE             |
| 3      | GEBRUIKER | Wil ik een cookie melding zien                             | zodat ik kan zien dat de site gebruik maakt van cookies | N.v.t              |
| 4      | GEBRUIKER | wil ik kunnen zoeken op blogpost                           | snel bij de posts kom                                   | SQL INJECTIE                |
| 5      | GEBRUIKER | wil ik weten waar het bedrijf zit                          | ik weet waar ik heen moet voor een afspraak             | N.v.t              |
| 6      | GEBRUIKER | wil ik het telefoonnummer weten                            | ik contact kan opnemen.                                 | N.v.t              |
| 7      | GEBRUIKER | wil ik de sociale media volgen                             | ik op de hoogte word gehouden.                          | N.v.t              |
| 8      | GEBRUIKER | wil ik doormiddel van een formulier een mail kunnen sturen | ik contact kan leggen                                   | N.v.t              |
|        |           |                                                            |                                                         |                |
| 1      | BEHEERDER | Wil ik een post kunnen toevoegen                           | ik mijn website up to date hou.                         | Slecht beveiligde PHP / SQL INJECTIE               |
| 2      | BEHEERDER | wil dienst verwijderen                                     | ik diensten die ik niet meer doe kan verwijderen.       | Slecht beveiligde PHP            |
| 3      | BEHEERDER | wil een post kunnen aanpassen                              | ik relevante informatie kan weghalen of bijvoegen.      | Slecht beveiligde PHP / SQL INJECTIE              |
| 4      | BEHEERDER | wil een post kunnen verwijderen                            | ik niet relevante projecten kan weghalen.               | Slecht beveiligde PHP             |
| 5      | BEHEERDER | wil een tags toevoegen                                     | ik mijn werk kan onderscheiden.                         | Slecht beveiligde PHP / SQL INJECTIE             |
| 6      | BEHEERDER | wil ik een post kunnen verwijderen                         | ik een niet relevant project van de site kan halen      | Slecht beveiligde PHP               |
| 7      | BEHEERDER | wil ik een post kunnen toevoegen                           | ik werk op de website kan zetten                        | Slecht beveiligde PHP  / SQL INJECTIE             |
| 8      | BEHEERDER | De database kunnen beheren                                 | Zodat ik de website kan aanpassen                       | Slecht beveiligde PHP              |
