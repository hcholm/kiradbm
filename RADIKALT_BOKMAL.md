# Radikalt bokmål for LLM-er

Denne veilederen er laga for språkmodeller som skal skrive normert bokmål med radikale ordformer. Målet er ikke å presse fram en bestemt smak eller tone, men å gjøre det lettere å velge former som ligger nær talemål og som er tillatt i bokmålsnormen.

Radikalt bokmål er ikke et eget skriftspråk ved sida av bokmål. Det er bokmål. Det som skiller det fra mer konservativt bokmål, er først og fremst hvilke valgmuligheter en bruker. En radikal bokmålstekst kan derfor godt være normert og formell, samtidig som den bruker former som *ei bok*, *boka*, *kasta*, *skreiv*, *sjøl* og *fram*.

Det viktigste for en LLM er dette:

- Skriv normert bokmål, ikke nynorsk og ikke dialektstavning.
- Bruk radikale former der bokmålet åpner for det.
- Vær konsekvent nok til at teksten får tydelige og gjenkjennelige formvalg.
- Bevar brukerens egne ønsker hvis brukeren ber om ei bestemt blanding av former.
- Når du er usikker på ei form, sjekk den i ei oppdatert normkilde som Bokmålsordboka.

## Kort innføring

Radikalt bokmål er bokmål som tar i bruk talemålsnære og ofte nynorsknære former som er godkjent i den offisielle bokmålsnormen. Mange av de mest synlige trekka er:

- hunkjønn med *ei* og *-a*: *ei jente*, *jenta*
- a-endinger i verb: *kasta*, *åpna*, *henta*
- a-endinger i partisipper: *lukka*, *stressa*
- diftonger: *stein*, *bein*, *heime*, *røyk*
- sterke verb i preteritumsformer: *skreiv*, *greip*, *krøyp*, *frøys*
- talemålsnære enkeltformer: *sjøl*, *mjølk*, *fram*, *gammal*, *vatn*

En tekst trenger ikke bruke alle disse trekka samtidig for å kunne kalles radikalt bokmål. Mange skriver for eksempel *boka* og *kasta*, men ikke *veit*. Andre bruker *fram* og *sjøl*, men holder seg til *vet*. Veilederen her er derfor laga som et kart over muligheter, ikke som ei tvangsliste.

Radikalt bokmål er ikke en stil. Det er et sett med formvalg. En tekst med radikale former kan være like formell, nøktern og saklig som en tekst med konservative former. Denne veilederen handler om hvilke normerte bokmålsformer en velger, ikke om tone, register eller sjanger. Når en LLM skriver *boka* i stedet for *boken*, skal ikke resten av teksten bli mer uformell av den grunn.

## Arbeidsprinsipper for LLM-er

### 1. Hold deg innafor bokmålsnormen

Radikalt bokmål er normert bokmål. Former som *ikkje*, *me*, *dykk*, *kjem*, *mykje*, *utan*, *saman* og *eitt* hører hjemme i nynorsk, ikke i bokmål. Dialektformer som *hu*, *itte*, *ække*, *bærre* og *ska* er heller ikke normert bokmål.

### 2. Velg mønster, ikke bare enkeltord

Hvis du velger *ei* og *jenta*, passer det ofte dårlig å skifte til *boken* og *solen* i neste avsnitt uten grunn. Hvis du velger *kasta*, bør du ikke gli over til *kastet* tilfeldig. Radikalt bokmål blir tydeligst når valga danner mønster.

### 3. Ikke bland radikalt bokmål med nynorsk

Mange LLM-er prøver å bli radikale ved å gli over i nynorsk. Det gir feil resultat. *jenta*, *boka*, *kasta*, *skreiv* og *sjøl* er radikalt bokmål. *jenta*, *boka*, *kasta*, *skreiv* og *sjølv* er ei blanding av bokmål og nynorsk. Hold deg til bokmålsformene.

### 4. Bevar brukerens preferanser

Brukeren kan ønske ei bestemt blanding, for eksempel:

- *ei* og *-a*, men ikke diftonger
- *fram* og *sjøl*, men *vet* i stedet for *veit*
- radikale former i løpende tekst, men konservative former i sitater eller navn

En god modell overstyrer ikke dette. Den følger det.

### 5. Vær forsiktig med overgeneralisering

Ikke alle substantiv og ikke alle verb følger de samme radikale mønstra. Det går ikke an å sette *-a* på alt og kalle det radikalt bokmål. Når du er usikker, slå opp forma.

## Regler og prinsipper med eksempler

### Diftonger i vanlige ord

Diftongene *ei*, *au* og *øy* er typiske i radikalt bokmål.

Eksempler med *ei*: *aleine*, *bein*, *beist*, *bleik*, *brei*, *feit*, *grein*, *heil*, *heile*, *heit*, *heim*, *heime*, *heit*, *leike*, *leite*, *meine*, *reim*, *rein*, *reip*, *reir*, *sein*, *skei*, *skeiv*, *steik*, *stein*, *veik*

Eksempler med *au*: *aure*, *aust*, *blaut*, *dau(d)*, *gauk*, *graut*, *klauv*, *laus*, *lauv*

Eksempler med *øy*: *bløyte*, *kløyve*, *løyse*, *røyk*, *støype*
 
I en radikal bokmålstekst kan det være naturlig å skrive f.eks. *sein* og *aleine*, men det er ikke nødvendig å bruke alle diftongmulighetene samtidig.

Setningseksempler:

- *Han blei aleine igjen i det gamle huset.*
- *Det lå stein og bein utover den breie stien.*
- *Hun kom seinere heim og la fra seg den feite boka.*

### Substantiv hunkjønn

Et av de tydeligste trekka i radikalt bokmål er at hunkjønn brukes aktivt, både med artikkelen *ei* og med *-a* i bestemt form entall.

Bøyningsmønster:

- *ei jente*, *jenta*
- *ei bok*, *boka*
- *ei sol*, *sola*
- *ei dør*, *døra*
- *ei oppgave*, *oppgava*

Dette mønsteret gjelder også mange ord på *-ing*, *-ning* og *-het*.

For en LLM er hovedregelen enkel: hvis du først bruker radikalt hunkjønn, bruk det gjennom teksten der det passer.

Flere eksempelpar: *en bok - boka*, *en dør - døra*, *en gate - gata*, *en hytte - hytta*, *en stue - stua*, *en kake - kaka*, *en natt - natta*, *en bygd - bygda*

Eksempler på hunkjønnsord: *avisa*, *blokka*, *boka*, *brua*, *bygda*, *bygninga*, *bølga*, *børsa*, *bøtta*, *dama*, *dokka*, *drifta*, *dua*, *døra*, *elva*, *enga*, *evna*, *fella*, *flata*, *flua*, *fløyta*, *forandringa*, *forklaringa*, *forma*, *fortellinga*, *frakta*, *furua*, *gata*, *gava*, *greina*, *grensa*, *gropa*, *gruppa*, *gryta*, *grøfta*, *gåsa*, *handa*, *heia*, *helga*, *helsa*, *historia*, *hytta*, *hånda*, *høna*, *jakka*, *jakta*, *jenta*, *jorda*, *kaka*, *kassa*, *kilda*, *kirka*, *kista*, *kjerna*, *klokka*, *kona*, *krisa*, *kråka*, *kua*, *kvinna*, *lampa*, *linja*, *lista*, *lomma*, *lua*, *lukta*, *lønna*, *makta*, *marka*, *mugga*, *musa*, *mølla*, *natta*, *nota*, *nåla*, *oppgava*, *pakka*, *panna*, *plata*, *pumpa*, *rekka*, *renna*, *renta*, *rolla*, *rota*, *røra*, *saka*, *senga*, *setninga*, *sida*, *skjea*/*skeia*, *skia* (entall og flertall), *skrifta*, *skåla*, *sletta*, *smørja*, *snella*, *sola*, *stranda*, *strømpa*, *stua*, *søstra*, *tanna*, *tavla*, *tegninga*, *tida*, *trappa*, *uka*, *utviklinga*, *verda*, *veska*, *visa*, *volla*, *vogga*, *vurderinga*, *åra*

Hunkjønnsord på *-ing* og *-ning*: *beretninga*, *etableringa*, *finansieringa*, *forklaringa*, *fortellinga*, *hoppinga*, *kastinga*, *legninga*, *løsninga*, *meldinga*, *overbevisninga*, *regjeringa*, *setninga*, *skildringa*, *tegninga*, *treninga*, *utbygginga*, *utviklinga*, *vurderinga*, *åpninga*

Hunkjønnsord på *-het*: *avhengigheta*, *friheta*, *kjærligheta*, *leiligheta*, *myndigheta*, *offentligheta*, *sikkerheta*, *virksomheta*

Setningseksempler:

- *Jenta la boka på hylla og lukka døra.*
- *Sola kom fram over bygda tidlig om morgenen.*
- *Hun satte kaka på bordet i stua.*

### Intetkjønn med ubestemt form flertall uten ending

Mange intetkjønnsord har valgfri ending *-er* eller tom ending i ubestemt form flertall:

*departement*, *eksempel*, *parti*, *problem*, *kontor*

Setningseksempler:

- *Flere departement har ansvar for dette området.*
- *Det var mange eksempel på problem med den gamle løsninga.*


### Intetkjønn med bestemt form flertall på *-a*

Mange intetkjønnsord kan ha *-a* i bestemt flertall:

*abonnementa*, *anlegga*, *banda*, *barna*, *behova*, *bilda*, *blada*, *blikka*, *borda*, *breva*, *brudda*, *buda*, *dyra*, *eksempla*, *fata*, *felta*, *fjella*, *flya*, *folka*, *forholda*, *forslaga*, *forsøka*, *frøa*, *grunnlaga*, *hulla*, *husa*, *innlegga*, *kapitla*, *karta*, *knea*, *krava*, *kursa*, *laga*, *landa*, *ledda*, *løpa*, *låra*, *midla*, *møta*, *måla*, *navna*, *orda*, *problema*, *punkta*, *resultata*, *romma*, *råda*, *selskapa*, *sentra*, *skia*, *skipa*, *slaga*, *spanna*, *spilla*, *spørsmåla*, *språka*, *stega*, *stoffa*, *svara*, *taka*, *talla*, *teatra*, *tilfella*, *tilbuda*, *tiltaka*, *tinga*, *tipsa*, *trekka*, *trinna*, *utlegga*, *utvalga*, *valga*, *verka*, *verktøya*, *vilkåra*, *vindua*, *våpna*, *øya*, *øyeblikka*, *åra*

Setningseksempler:

- *Spørsmåla kom tett, men svara var uklare.*
- *Bilda og karta lå utover bordet.*
- *Romma i huset var små, men vindua var store.*

### Andre substantiv bestemt form flertall på *-a* som er tillatt i bokmål

Tillatte former: *hønsa*, *skoa*, *tinga*

### Substantiv bestemt form flertall på *-a* som ikke er tillatt i bokmål

Ikke tillatte former: *~~gjessa~~*, *~~musa~~* (bestemt form flertall av *mus*), *~~penga~~*

### Noen substantiv som bare er hankjønn

Disse er hunkjønn i noen talemål, men bare hankjønn i bokmål:

*scenen*

*dialekten*, *oversikten*

### Svake verb på *-a* i fortid

Mange svake verb kan ha *-a* i preteritum og perfektum partisipp. Dette er kanskje det mest synlige verbtrekket i radikalt bokmål.

Bøyingsmønster:

- *å kaste - kaster - kasta - har kasta*
- *å åpne - åpner - åpna - har åpna*

Eksempler: *dytta*, *droppa*, *handla*, *henta*, *hevda*, *hoppa*, *jobba*, *kasta*, *klaga*, *laga*, *løfta*, *malta*, *mista*, *ordna*, *pakka*, *prata*, *regna*, *rydda*, *sletta*, *slappa*, *slutta*, *snakka*, *starta*, *trena*, *tvitra*, *venta*, *virka*, *åpna*, *ydmyka*

Setningseksempler:

- *Hun snakka med læreren og ordna avtalen med en gang.*
- *Det virka lovende først, men stemninga smelta bort.*
- *Vi rydda rommet og pakka sakene før vi dro.*

Noen verb kan ha både *-a* og *-de* som preteritum: *laga*/*lagde*

### Partisipper på *-a*

Det samme mønsteret dukker opp i partisipper og adjektiviske partisipper:

- *lukka dører*
- *stressa elever*
- *forelska folk*
- *egna tiltak*
- *beskytta område*
- *velutvikla språk*

Dette gir ofte teksten et tydelig radikalt preg uten at syntaksen trenger å endres.

Flere setningseksempler:

- *De gikk inn gjennom den lukka porten.*
- *En stressa lærer rakk så vidt møtet.*
- *Et godt egna tiltak kan gi raske resultater.*
- *Hun var forelska, men prøvde å virke rolig.*

Eksempler: *beskytta*, *egna*, *forelska*, *forankra*, *forenkla*, *fornya*, *forsterka*, *gira*, *lukka*, *løfta*, *malta*, *rusa*, *stenga*, *stressa*, *trøtta*, *utvida*, *velutvikla*, *åpna*, *avsløra*, *belasta*

### Sterke verb med diftong i preteritum

Mange sterke verb kan ha preteritumsformer med diftong.

Eksempler: *beit*, *blei*, *dreiv*, *glei*, *gnei*, *grein*, *greip*, *heiv*, *kneip*, *lei*, *rei*, *reiv*, *seig*, *skeit*, *sklei*, *skreik*, *skreiv*, *sleit*, *smøyg*, *sneik*, *steig*, *svei*, *sveik*, *veik*, *vrei*, *brøyt*, *fløyt*, *frøys*, *føyk*, *gøyv*, *krøyp*, *nøys*, *nøyt*, *røyk*, *skøyt*, *skøyv*, *strøyk*, *tøyt*

Presensforma *veit* hører også hjemme her.

Merk at perfektum partisipp (supinum) ikke kan ende på *-e* eller *-i* i bokmål. Det heter *bitt*, *drevet*, *knepet* osv., ikke *biti*, *drivi*, *knipi* e.l.

Setningseksempler:

- *Hun skreiv brevet seint på kvelden.*
- *Han greip sekken og reiv opp døra.*
- *Katten krøyp under bordet da det smalt.*
- *Vannet frøys i røra før noen rakk å reagere.*
- *De brøyt opp kista og skøyt fart ned bakken.*

### Andre vanlige radikale ordformer

Radikalt bokmål består ikke bare av endelser. Mange enkeltord og ordgrupper har radikale varianter som ofte gjør stor forskjell i tonen. Noen radikale former som er tillatt i bokmål:

- *sjøl*, *sjølve*
- *mjøl*, *mjølk*
- *fjøl*
- *bru*, *bu*, *tru*
- *sjuk*, *sjukehus*, *sjukmelding*
- *djup*, *mjuk*, *sju*, *tjue*, *tjukk*, *tjuv*
- *fram*, *framover*, *framtida*, *fortida*
- *gammal*
- *botn*, *jamn*, *vatn*
- *kval*, *kvass*, *kvile*, *kvine*, *kvit*
- *farge*
- *dogg*, *dokke*, *golv*, *hogg*, *hogge*, *korg*, *mold*, *molte*, *vogge*
- *hol*, *kol*
- *viss*, *verken*
- *skau*
- *åssen*
- *bånn*
- *sia*, som i *for tre år sia*
- *høve*
- *lyge*/*ljuge*, *flyger*, *krage*, *mage*, 
- *høg*, *låg*, *veg*
- *ba*, *ga*, *dro*, *sto* som valgfrie kortformer ved sida av *bad*, *gav*, *drog*, *stod*
- *fins*, *mins*, *ses*, *skjems*, *syns*, *trengs*, *trivs* som kortformer av s-verb
- *bakafor*, *frammafor*, *innafor*, *innafra*, *innabords*, *innalands*, *utafor*, *utaskjærs*
- *atferd*, *atkomst*
- *likne*, *sakne*
- *deltaker*, *mottaker*, *opptaker*

Enkelte adjektiv og pronomen: *lita*, *eiga*, *eige*, *eigne*, *anna*, *mi*, *di*, *si*

Setningseksempler:

- *Jeg gjorde det sjøl og sa det rett ut.*
- *Mjølka sto på golvet ved sida av fjøla.*
- *Han gikk fram og spurte åssen det sto til.*
- *Det var kaldt ute ved vatnet, men utsikta var fin.*
- *Den gamle vegen gikk fram gjennom skauen og ned mot brua.*

### Pronomen, possessiv og talemålsnære uttrykk

Radikalt bokmål handler også om setningsbygning og småord.

#### *han* som objektsform

I bokmål kan *han* brukes både som subjekt og objekt.

Eksempler:

- *han kom tidlig*
- *jeg så han*
- *hun gikk sammen med han*

Dette er ei normert bokmålsløsning som ofte passer godt i radikalt bokmål.

#### Etterstilt possessiv

Etterstilt possessiv er vanlig i talemålsnært bokmål og gir ofte teksten en mindre stiv tone.

Eksempler:

- *huset mitt*
- *kortet ditt*
- *husa våre*
- *oppgava mi*
- *stua di*
- *jorda si*

Foranstilt possessiv brukes for å vektlegge eierskapet:

- *det er mitt hus, ikke ditt*
- *det er ditt kort, ikke mitt*
- *det er våre hus, ikke deres*

#### Flere måter å uttrykke eierskap på

Alle disse mønstra kan brukes i bokmål:

- *bilen til Eva*
- *Evas bil*
- *Eva sin bil*

## Setningseksempler

Her er noen hele setninger som kan brukes som eksempelmodeller:

- *Jenta tok med seg boka og gikk heim før det blei mørkt.*
- *Vi snakka sammen lenge, men ingen fant noen enkel løsning.*
- *Den gamle brua over elva var stengt etter at vannet frøys til.*
- *Læreren skreiv opp spørsmåla på tavla mens elevene venta.*
- *Hun så han med en gang og vinket fra døra.*
- *Barna la klærne sine på golvet og løp ut i hagen.*
- *Det var mange fine bilder, men de beste hang i gangen.*
- *De ordna møta raskt og fikk svara før fristen gikk ut.*
- *Jeg gjorde det sjøl, og resultatet blei bedre enn venta.*
- *Han kom aleine, men gikk heim sammen med resten av laget.*

## Vanlige feil LLM-er gjør

Her er feil som går igjen når modeller prøver å skrive radikalt bokmål:

- De glir over i nynorsk. Typiske tegn er *~~ikkje~~*, *~~eg~~*, *~~me~~*, *~~dei~~*, *~~eitt~~*, *~~mykje~~*, *~~utan~~*, *~~saman~~*, *~~kjem~~*, adjektiv på *~~-leg~~*.
- De blander normert bokmål med dialektstavning. Typiske tegn er *~~itte~~*, *~~hu~~*, *~~ække~~*, *~~bærre~~*, *~~ska~~*.
- De bruker noen radikale former, men lar resten av teksten falle tilbake til mer konservativt bokmål uten mønster. Eksempel: *ei bok*, *jenta*, men *solen*, *boken*, *kastet* litt seinere.
- De overdriver *-a* og setter endinga på ord som ikke har det mønsteret i bokmål.
- De antar at alle diftongformer er tillatt bare fordi de ligner på nynorsk.
- De behandler *skreiv*, *greip* og *krøyp* som om de var nynorskformer, og unngår dem av den grunnen.
- De bruker *ham* konsekvent sjøl når brukeren ber om radikalt bokmål.
- De kopierer ordformer fra brukerens dialekt i stedet for å holde seg til normert bokmål.
- De gjør små blandingsfeil som *sjølv*, *heilt* i ellers bokmålsnær tekst, eller *vet* sammen med tydelige nynorskformer.

Typiske rettinger:

- *eg veit ikkje* skal være *jeg veit ikke*
- *me skreiv brevet i går* skal være *vi skreiv brevet i går*
- *hu kasta boka* skal være *hun kasta boka*
- *sjølv om det var seint* skal være *sjøl om det var seint*
- *me gjekk heim* skal være *vi gikk heim*

## Når du bør sjekke ei normkilde

Sjekk ordet hvis:

- du er usikker på om ei radikal form faktisk er normert bokmål
- du er usikker på bøyninga
- du vil vite om et ord har flere normerte varianter
- du vil kontrollere at teksten holder seg innafor bokmålsnormen

## Kilder

- [Foreninga for radikalt bokmål: Kort innføring i radikalt bokmål](https://bokmal.no/radikale-bokmalsrad/kort-innforing-i-radikalt-bokmal/)
- [Foreninga for radikalt bokmål: Radikale bokmålsråd](https://bokmal.no/radikale-bokmalsrad/)
- [Wikipedia: Radikalt bokmål](https://no.wikipedia.org/wiki/Radikalt_bokm%C3%A5l)
- [Landslaget for språklig samling: Å skrive radikalt bokmål](https://4cc51928-4f6f-4e99-9711-cc9362f45f88.filesusr.com/ugd/e08463_41d704cd5348464ab750f1660e71a315.pdf)
- [Bokmålsordboka](https://ordbokene.no/nob/bm)
- [Nasjonalbiblioteket, Språkbanken: Norsk ordbank - bokmål 2005](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-5/)

