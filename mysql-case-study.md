# MySQL

## Innhold

1. [Introduksjon](#introduksjon)
2. [Historie](#historie)
3. [Hvordan det Funker](#hvordan-det-funker)
4. [Styrker](#styrker)
5. [Svakheter](#svakheter)
6. [MySQL Vs PostgreSQL](#mysql-vs-postgresql)
7. [Oppsummering](#oppsummering)
8. [Referanser](#referanser)

## Introduksjon

MySQL er et gratis og åpen kildekode relasjonelt databasehåndteringssystem, eller den noe kortere varianten RDBMS. Det bruker SQL for å opprette, oppdatere og administrere relasjonelle databaser.

Det er veldig utbredt innen webutvikling, da i kombinasjon med programmeringsspråk som PHP og Python for å lage dynamiske nettsider og webapplikasjoner. Det brukes også i mange andre sammenhenger, der kanskje mest blant firma som håndterer store mengder data.

Med MySQL kan du opprette og administrere ulike databaser, inkludert tabeller, kolonner og relasjonene mellom disse. Du kan også gjøre veldig komplekse spørringer for å hente og filtrere dataene dine. MySQL er per i dag en av de mest utbredte RDBMS-ene og fortsetter stadig å utvikle seg og forbedre sin funksjonalitet.

## Historie

MySQL ble først utviklet av svenske MySQL AB i 1994, som et enkelt og raskt alternativ til datidens databasehåndteringssystemer. Etter hvert som MySQL økte i popularitet, ble det stadig utviklet til å inkludere mer avanserte funksjoner. I 2008 ble MySQL kjøpt opp av amerikanske Sun Microsystems, som selv ble kjøpt opp av tech-gigant Oracle i 2010. Siden da har MySQL vært driftet av Oracle som stadig fortsetter å utvikle og oppdatere det fremdeles populære systemet.

## Hvordan Det Funker

For å forstå hvordan MySQL funker, er det greit å vite forskjellen på relasjonelle og ikke-relasjonelle databaser, eller SQL og No-SQL som det også kalles. En SQL database lagrer data i forskjellige mindre tabeller, som gjerne skal kommunisere med hverandre ved hjelp av nøkler. Ved bruk av SQL setter man opp statiske tabeller, med forhåndsbestemte kolonner og datatyper. Man kan selvfølgelig legge til flere underveis. I en No-SQL database, slik som MongoDB lagres dataene gjerne i dokumenter i JSON-format. Dette gjør det veldig fleksibelt å lagre nesten hvilken datatype du ønsker, når du slipper å forholde deg til de litt mer strenge reglene til SQL.

Så MySQL er da altså en metode for å kommunisere med en database. MySQL bruker SQL for å utføre forskjellige metoder på data som å legge til, endre og slette data. MySQL har også ulike sikkerhetsfunksjoner for å beskytte dataene som lagres i databasen, som brukerautentisering, tilgangskontroll og kryptering.

## Styrker

MySQL er veldig skalerbart, og kan håndtere store datamengder og høye trafikkmengder. Dette gjør det til et populært valg for applikasjoner som krever mye databehandling og ressurser. Det er også raskt og effektivt, og kan håndtere mange samtidige forespørsler. MySQL er pålitelig og stabilt, og har et godt rykte for å håndtere store datamengder uten å miste data. Det har et enkelt grensesnitt og brukervennlige verktøy, og er enkelt å lære for både erfarne og uerfarne brukere.

MySQL er et åpent kildekode-prosjekt, noe som betyr at det er gratis å bruke, og at brukerne kan tilpasse koden etter behov. Dette gir også en stor brukerbase og et aktivt fellesskap som stadig forbedrer og utvider MySQL. Samlet sett er MySQL en kraftig og pålitelig database som er enkelt å bruke, og som kan skaleres og optimaliseres for å møte de fleste behov.

En av de største fordelene ved bruk av SQL databaser er når man skal spørre etter data. Siden man vet at all data følger de samme reglene, er det veldig enkelt å vite at dataene du får tilbake matcher det du spurte om.

## Svakheter

Selv om MySQL har mange styrker, har det også noen svakheter. En av de største utfordringene kommer dersom det er mye trafikk inn til databasen. Her vil det oppstå problemer med skalering, og et No-SQL alternativ ville heller lønt seg. Dersom det er større datamengder kan MySQL få problemer med spørringsytelsen. Dette skyldes ofte manglende indeksering, dårlige eller komplekse spørringer.

Mens MySQL støtter de fleste grunnleggende funksjonaliteter, mangler det noen av de mer avanserte funksjonene som finnes i andre databasesystemer. For eksempel kan det være begrensninger i støtten for geografiske data, eller komplekse spørringer som krever mer avansert funksjonalitet.

Det kan også kreve mye vedlikehold for å optimalisere ytelse og sikkerhet, spesielt når det brukes i store og komplekse miljøer. Dette kan øke kostnadene for organisasjoner som bruker MySQL som sin primære database.

Som med alle databaser, er det alltid en risiko for sikkerhetsbrudd eller dataangrep med MySQL. Selv om MySQL har flere sikkerhetsfunksjoner, er det alltid viktig å sørge for at databasen er riktig konfigurert og sikret.

## MySQL Vs PostgreSQL

En av de største konkurrentene til MySQL er PostgreSQL, som også er en åpen kildekode-relasjonsdatabase. Mens MySQL er lisensiert under GPL, er PostgreSQL lisensiert under BSD-lisensen, noe som betyr at PostgreSQL gir større fleksibilitet for kommersiell bruk.

Begge er veldig raske og kan håndtere store datamengder. Men MySQL er generelt sett raskere enn PostgreSQL når det gjelder enkle spørringer. PostgreSQL er kjent for ha bedre funksjonalitet når det kommer til støtte for avanserte funksjoner som geografiske data, hierarkisk lagring og mer komplekse spørringer.

Et eksempel der det vil lønne seg å velge PostgreSQL framfor MySQL er dersom du trenger å håndtere data som inneholder geografisk informasjon, som f.eks. GPS-koordinater. Her vil PostgreSQL være et bedre valg enn MySQL på grunn av dens støtte for geografiske data og funksjoner. PostgreSQL lar deg lagre geografisk data som punkter, linjer og polygoner og har innebygde funksjoner for geografiske beregninger, som f.eks. å finne avstanden mellom to punkter på en overflate. Mens MySQL kan håndtere geografisk informasjon, er det begrenset funksjonalitet og støtte for dette sammenlignet med PostgreSQL.

## Oppsummering

Med mange sterke sider, men også noen svakheter er MySQL altså et kraftig verktøy, som brukes av mange av de største bedrifter og organisasjoner. Til å være en relativt gammel teknologi, er det fremdeles veldig populært og i stadig utvikling. Alt i alt er MySQL et veldig godt alternativ til mange bruksområder.

Espen Holm Pedersen (PederZzen)

## Referanser

- https://no.wikipedia.org/wiki/MySQL
- https://dev.mysql.com/doc/
- https://www.integrate.io/blog/the-sql-vs-nosql-difference/
- https://www.hostinger.com/tutorials/what-is-mysql
- https://www.careerride.com/MySQL-disadvantages.aspx
