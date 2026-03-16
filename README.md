# Radikalt bokmål for språkmodeller

Dette repoet er en praktisk språkstandard for å få språkmodeller til å skrive **konsekvent radikalt bokmål** uten å gli over i nynorsk, dialekt eller blandingsspråk.

Det er laga for typiske bruksområder som:

* KI-chatter
* systeminstrukser
* KI-agenter
* omskriving og redigering
* tekniske prosjekter der norsk språkføring må være stabil

## Start her

For de fleste er [RADIKALT_BOKMAL.md](RADIKALT_BOKMAL.md) et greit sted å starte.

Hvis du vil ha en **mer «maksimerende» variant**, kan du bruke [RADIKALT_BOKMAL_MAKS.md](RADIKALT_BOKMAL_MAKS.md) i tillegg. Den er ikke ei erstatning for hovedveilederen, men et tillegg som overstyrer enkelte valg når du bevisst vil presse normen lenger i radikal retning.

Kort anbefaling:

* bruk `RADIKALT_BOKMAL.md` som standard
* bruk `RADIKALT_BOKMAL_MAKS.md` hvis du eksplisitt vil ha flere radikale former
* bruk `INSTRUKSJONER.md` når du trenger ferdig tekst du kan lime rett inn
* bruk `TESTSETT.md` og `examples/` når du vil kontrollere at modellen faktisk følger normen

## Hvilken fil gjør hva?

* [RADIKALT_BOKMAL.md](RADIKALT_BOKMAL.md) – hovedveilederen
* [RADIKALT_BOKMAL_MAKS.md](RADIKALT_BOKMAL_MAKS.md) – tillegg for mer maksimerende bruk
* [INSTRUKSJONER.md](INSTRUKSJONER.md) – ferdige instruksjonsmaler for chat, systeminstruks og omskriving
* [TESTSETT.md](TESTSETT.md) – enkle tester og sjekklister
* [examples/](examples/) – gode og dårlige eksempler, samt omskrivingspar

## Laste ned fra GitHub

Hvis du bare trenger éi eller to filer:

1. Åpne fila på GitHub.
2. Last ned fila direkte, eller kopier innholdet fra GitHub-sida.
3. Start som regel med `RADIKALT_BOKMAL.md`.
4. Legg til `RADIKALT_BOKMAL_MAKS.md` bare hvis du vil ha en mer maksimerende variant.

Hvis du vil ha hele repoet:

1. Last ned repoet som ZIP fra GitHub, eller klon det med Git.
2. Åpne mappa lokalt.
3. Bruk `README.md` som inngang, `RADIKALT_BOKMAL.md` som hovedkilde og `INSTRUKSJONER.md` som ferdig tekst for videre bruk.

## For ikke-tekniske brukere

Hvis du bruker en vanlig KI-chat:

1. Last ned `RADIKALT_BOKMAL.md`, eller åpne fila på GitHub og kopier innholdet.
2. Start med en kort instruks fra [INSTRUKSJONER.md](INSTRUKSJONER.md).
3. Hvis KI-chatten støtter filvedlegg eller referansefiler, last opp `RADIKALT_BOKMAL.md` der.
4. Hvis KI-chatten ikke støtter filopplasting, lim inn relevant tekst direkte i første melding eller i feltet for faste instruksjoner.
5. Hvis du vil ha en tydeligere og mer radikal variant enn standarden, last også opp eller lim inn [RADIKALT_BOKMAL_MAKS.md](RADIKALT_BOKMAL_MAKS.md) og si at den skal brukes som tillegg.
6. Bruk [TESTSETT.md](TESTSETT.md) hvis du vil sjekke om svaret faktisk følger normen.

Typiske steder å lime inn eller laste opp:

* i første melding i en KI-chat
* i et felt for egendefinerte instruksjoner
* i et oppsett for en fast assistent eller chatbot
* som vedlegg eller referansefil hvis plattformen støtter det

Praktisk tommelfingerregel:

* bare `RADIKALT_BOKMAL.md` hvis du vil ha en trygg og stabil standard
* `RADIKALT_BOKMAL.md` + `RADIKALT_BOKMAL_MAKS.md` hvis du vil ha en mer maksimerende variant

## For tekniske brukere

Hvis du setter opp en KI-agent, en systeminstruks eller en fast arbeidsflyt:

1. Last ned hele repoet som ZIP eller klon det, så du har filene lokalt.
2. Bruk [RADIKALT_BOKMAL.md](RADIKALT_BOKMAL.md) som primær kilde for språkreglene.
3. Bruk tekst fra [INSTRUKSJONER.md](INSTRUKSJONER.md) som utgangspunkt for systeminstruks, agentinstruks eller omskrivingsinstruks.
4. Hvis plattformen støtter kunnskapsfiler, referansefiler eller vedlegg til agenten, last opp `RADIKALT_BOKMAL.md` der.
5. Hvis du vil støtte både standard og maksimerende modus, la `RADIKALT_BOKMAL.md` være grunnlag og gjør `RADIKALT_BOKMAL_MAKS.md` til et eksplisitt tilvalg.
6. Verifiser oppsettet med eksempler fra [TESTSETT.md](TESTSETT.md) og [eksempler/](eksempler/).

Typiske steder å bruke materialet:

* i systeminstruksen til agenten
* i instruksjonsfeltet for en assistent
* som kunnskapsfil eller referansefil i agentoppsettet
* i et internt `docs/`-område eller instruksjonsbibliotek i eget prosjekt

Det viktigste tekniske prinsippet er dette:

> Behandle `RADIKALT_BOKMAL.md` som hovedregelsett. Bruk `RADIKALT_BOKMAL_MAKS.md` bare som et bevisst tillegg.

## Når bør du bruke maksvarianten?

Bruk [RADIKALT_BOKMAL_MAKS.md](RADIKALT_BOKMAL_MAKS.md) hvis du:

* allerede er fornøyd med hovedveilederen, men vil ha flere radikale former
* tåler at normen blir smalere og mindre konservativ
* vil teste en mer maksimerende stil i kontrollerte oppsett

Ikke bruk maksvarianten aleine, den er et tillegg til hovedveilederen, ikke ei erstatning.

## Grunnidé

Radikalt bokmål betyr her:

* bokmål, ikke nynorsk
* standardisert skriftspråk, ikke dialekt
* konsekvent bruk av utvalgte radikale bokmålsformer

Den viktigste regelen er denne:

> Radikalt bokmål skal behandles som et kontrollert skriftspråk, ikke som mer muntlig norsk.
