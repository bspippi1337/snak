# Metode og definisjoner

## Datagrunnlag

Analysen bygger på to opptak med samlet varighet 83 minutter og 40,5 sekunder.

Primæranalysen av Pippi og Zlatko omfatter:

- Record-1 fra 19:15, etter den opplyste avgangen til Chris
- hele Record-3

Denne rammen varer 3 865,526 sekunder.

## Transkripsjon

Norsk råtranskripsjon ble produsert med NB-Whisper Small Q5. Transkripsjonen ble delt i korte blokker og lagret fortløpende. Lav modellkonfidens ble bevart som usikkerhet, ikke språkvasket bort.

## Talerfordeling

Talerfordelingen ble modellert med taleaktivitet, talersegmentering og stemmeinnbygginger. Identitetsankrene var:

- Chris forlater møtet først
- bare Pippi og Zlatko er igjen etterpå
- Zlatko er personen knyttet til notatbrenningen

Koblingen mellom Pippi- og Zlatko-klyngene på tvers av opptakene var stabil i 2 000 av 2 000 bootstrap-trekk innen modellen.

## Operasjonelle definisjoner

### Taletid

Summen av tidsintervaller der en taler er modellert som aktiv. Samtidig tale kan inngå for begge talere. Derfor er tilskrevet taletid ikke identisk med opptakets klokketid.

### Konkurrerende overlapp

En ny taler starter mens den andre fortsatt har en pågående ytring, og overlappingen overstiger minimumsterskelen. Korte bekreftelser og minimale responser klassifiseres separat som backchannel når kriteriene tilsier det.

### Vellykket gulvovertakelse

En taler starter under den andres pågående ytring, den første taleren avslutter kort tid etterpå, og den nye taleren fortsetter utover en fast minimumsvarighet.

### Avbruddsrate

Antall klassifiserte avbrudd eller gulvovertakelser per ti minutter av talerens egen taletid.

## Sensitivitetsanalyse

Hendelsene ble beregnet på nytt med 36 kombinasjoner av terskler for minimumsoverlapp, tid til avståelse av gulvet og minimumsfortsettelse. Rangeringen av hvem som oftest avbrøt var stabil på tvers av kombinasjonene.

## Etterprøvbarhet

De publiserte CSV-filene inneholder tidskoder, klassifikasjoner, varigheter og terskler. Definisjonene er publisert her slik at tallene kan vurderes mot samme kriterier.
