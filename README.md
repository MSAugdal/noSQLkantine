# noSQL oppgave 2IT

## Oppgavetekst
Tenk deg at kantina på skolen din trenger en nettside for å gi informasjon om maten de selger. Mange skolekantiner serverer en eller flere varmretter som varierer fra dag til dag, i tillegg til faste matvarer som bagetter, boller, drikke og sjokolade. Du skal lage en nettside som viser ukens meny samt ei liste over varer og prisene på varene. Ta gjerne utgangspunkt i utvalget på din egen skolekantine.

Ukens meny og øvrige varer, med priser, skal hentes fra en Cloud Firestore-database og vises fram på siden. Det skal også være mulig for ansatte i kantina å endre ukemenyen via nettsiden, uten å måtte gå inn i databasen eller redigere kode.

### Tips
- Lag to samlinger (collections), en med ukemenyen og en med øvrige varer med priser.
- Lag to atskilte nettsider: en som viser fram menyen og priser, og en nettside for å redigere ukemenyen. For eksempel kan det være fem tekstbokser for å skrive inn ukemenyen og en knapp som legger informasjonen inn i databasen.
- Siden for å redigere menyen ville typisk kreve innlogging, men du kan skjule den ved å ikke lenke til den fra hovedsida, slik at man må vite URL-en for å komme til den. Dette er imidlertid veldig usikkert, så denne metoden er bare for enkel testing. Hvis en slik løsning publiseres på nett, kan uvedkommende få tilgang til databasen din og mulighet til å sabotere nettsiden din eller gjøre noe verre. Om nettsiden faktisk skal være i bruk, må du lage en ordentlig innlogging. Dette kan gjøres via Google-siden "Firebase Authentication".

## Hva skal jeg lære ved å gjøre denne oppgaven?
- Hva en noSQL database er
- Lage/designe/strukturere en dokumentbasert database
- CRUD (Create, Read, Update, Delete)
