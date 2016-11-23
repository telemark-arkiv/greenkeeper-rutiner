# greenkeeper-rutiner
Beskrivelse av alle rutiner omkring greenkeeper

## Før du starter

Pass på at du har på plass nødvendig programvare og har bruker på aktuelle nettsteder.

- [programvare](programvare.md)
- [kontoer](kontoer.md)

## Arbeidsflyt

1 - Gå til [assigned pull requests](https://github.com/pulls/assigned) på GitHub

2 - Velg hvilken PR du skal sjekke. Trykk på den.

3 - Scroll nedover siden og trykk "Show all checks"

4 - Sjekk at "greenkeeper/verify" er grønn

5 - Trykk "Merge pull request" og deretter "Confirm merge"

6 - Gå til repoets forside og trykk "Clone or download"

7 - Velg clone with ssh og kopier linken

8 - Gå til egnet sted og skriv inn ```git clone <link til repoet>```

9 - Gå inn i mappen kjør ```npm install```

10 - Kjør ```npm test```

11 - Hvis alt er ok kjør ```code package.json```

12 - Oppdater version med minor + 1

13 - Lagre

14 - Kjør ```git commit -am "Updates version"```

15 - Kjør ```npm test```

16 - Hvis alt ok kjør ```git push```

17 - Slett mappen

18 - Repeat