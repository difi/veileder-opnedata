Oversikt filformat
------------------

**JSON:** JSON er en enkel tekstbasert standard for datautveksling. Den er opprinnelig avledet fra JavaScript for å representere enkle datastrukturer. Standarden er imidlertid uavhengig av JavaScript eller andre programmeringsspråk.

**XML:** XML er et mye brukt format for datautveksling. Formatet er et vanlig tekstformat, leselig for mennesker, der merker, eller tagger, gir informasjon om hva innholdet er.

**RDF:** RDF er er en gruppe av W3C-spesifikasjoner som beskriver en modell for å representere metadata, data om data. RDF-data kan blant annet kodes i XML og JSON. RDF kan entydig identifisere objekter og begreper ved hjelp av samlinger med beskrivelser av klasser og egenskaper. Dette gir store muligheter for utveksling av informasjon på tvers av systemer og teknologier. RDF er derfor egnet til å kommunisere og samordne data som kan lagres i ulike systemer, for eksempel i relasjonsdatabaser.

**Regneark:** Microsoft Excel er ofte brukt til å lagre data. Denne dataen kan ofte bli brukt direkte dersom beskrivelsene av hva de ulike kolonnene betyr/viser til. Men, i enkelte tilfeller kan regnearket inneholde makroer og former som er tungvint å jobbe med. Det er derfor anbefalt å legge slike regnestykker utenom regnearket, siden det da er lettere å lese for brukeren.

**Comma Separated Files (CSV):** CSV-filer kan være nyttige format siden de er kompakte og derfor passende til å overføre store datasett med same struktur. Men, formatet er så spartansk at det ofte er svært vanskelig å finne ut hvilke kolonner som er viktige. Derfor er det svært viktig i CSV-filer at beskrivelsen av de ulike feltene er nøyaktige.

**Tekstdokument:** Ordinære dokument i format som Word, ODF, OOXML eller PDF kan være godt nok til å vise enkelte typer data, for eksempel forholdsvis statiske epostlister eller lignende. Det kan være en billig løsning å fremstille dataen I, siden det er ofte dette formatet det blir opprettet i. Formatene holder ikke strukturen fast, hvilket betyr at det ofte er vanskelig å hente ut data automatisk. Dersom du benytter en av disse formatene, bør du bruke maler slik at det i det minste blir mulig å trekke ut informasjon fra dokumentene.

Bruk av typografiformatering kan også støtte videre bruk av data, da det blir lettere for maskiner å skille overskrifter fra innholdet osv. Det er generelt ikke anbefalt å fremvise data i Word-format, dersom dataen finnes i et annet format.

**Tekstfiler:** Dokument med ren tekst (.txt) er veldig lette for datamaskiner å lese. De ekskluderer derimot vanligvis strukturerte metadata fra dokumentet, som betyr at utviklere må lage en algoritme som kan tolke/lese hvert dokument.

Det kan oppstå enkelte problem ved utveksling av rene tekstfiler mellom operativsystem. MS Windows, Mac OS X og andre Unix-varianter har sine egne metoder å fortelle datamaskinen at de har kommet til slutten av en linje.

**Scannet bilde:** Dette er mest sannsynlig det minst passende formatet for det meste av data, men både TIFF og JPEG-2000 kan i det minste markere hva som er i bildet. Det kan være relevant å vise data som bilder dersom det opprinnelig ikke var elektronisk, som gamle kirkearkiv og andre arkivmateriale. Et bilde er uansett bedre enn ingenting.

**Proprietære format:** Enkelte dedikerte system har sine egne dataformat som de kan lagre eller eksportere data i. Det kan ofte være nok å vise data I slike format, spesielt dersom man forventer at videre bruk skal være I lignende system som de kom fra. Det bør alltid være indikert hvor du kan finne informasjon om disse proprietære formatene, for eksempel ved å legge ved en link til leverandørens nettside. Det er anbefalt å vise data i ikkeproprietære format, der det er mulig.

**HTML:** HTML er et markeringsspråk for formatering av nettsider med hypertekst og annen informasjon som kan vises i en nettleser. HTML benyttes til å strukturere informasjon,  angi noe tekst som overskrifter, avsnitt, lister og så videre – og kan, i en viss grad, brukes til å beskrive utseende og semantikk i et dokument.

**Åpne filformat:** Formatet som dataen er publisert kan enten være åpne eller lukkede. Et åpent format er et der spesifiseringen for programvaren er tilgjengelige for alle, kostnadsfritt, slik at alle kan bruke disse spesifikasjonene I sine egne programvarer uten begrensninger for gjenbruk eller bruk påført av immaterielle rettigheter.

Dersom et proprietært filformat er lukket, er det enten fordi spesifikasjonene ikke er tilgjengelige eller gjenbruken er begrenset.

I tråd med åpen forvaltning burde informasjon tilgjengeliggjøres i et åpent filformat som er maskinlesbart.
