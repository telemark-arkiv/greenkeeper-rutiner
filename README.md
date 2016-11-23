# greenkeeper-rutiner
Beskrivelse av alle rutiner omkring greenkeeper

## Før du starter

Pass på at du har på plass nødvendig programvare og har bruker på aktuelle nettsteder.

- [programvare](programvare.md)
- [kontoer](kontoer.md)

## Arbeidsflyt

1 - Gå til [assigned pull requests](https://github.com/pulls/assigned) på GitHub

2 - Velg hvilken du skal sjekke

3 - Scroll nedover siden og trykk "Show all checks"

4 - Sjekk at "greenkeeper/verify" er grønn

5 - Trykk "Merge pull request"

6 - Trykk "Confirm merge"

7 - Gå til repoets forside og trykk "Clone or download"

8 - Velg clone with ssh og kopier linken

9 - Gå til egnet sted og skriv inn ```git clone <link til repoet>```

10 - Gå inn i mappen kjør ```npm install```

11 - Kjør ```npm test```

12 - Hvis alt er ok kjør ```code package.json```

13 - Oppdater version med minor + 1

14 - Lagre

15 - Kjør ```git commit -am "Updates version"```

16 - Kjør ```npm test```

17 - Hvis alt ok kjør ```git push```

18 - Slett mappen

19 - Repeat