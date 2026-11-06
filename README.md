# Kafé Commit — Grupp 3

## Roller

- Scrum Master: Göran (även utvecklare)
- Utvecklare: William
- Utvecklare: Johan
- Utvecklare: Alecia

## Tavla

[Trello](https://trello.com/invite/b/6ae87b0524f7967c1546d347/ATTI84ec69d36cddb1aaf033a2dbfa394e4507457628/📌scrum-agile-work-exam-kanban-dev-board)

## Sprintmål

När sprinten är klar ska hemsidan gör det enkelt för besökare att planera sitt besök genom att presentera caféets adress, menyutbud, kontaktuppgifter och tillgänglighet på ett tydligt sätt.

## Daily standups

### 03/11/2026 - Tisdag

- **Johan**: Har klonat repot från github, skrivit user stories på kanban tavlan. / Idag är planen att göra funktion 3, skapa separat branch. / Inte stött på några problem.
- **Göran**: Har skapat kanban tavlan, skrivit user stories på tavlan/ Idag är planen att klona ned repot, skapa separat branch och göra färdigt första user story/funktion./ Inga hinder.
- **Alecia**: Skapade repot, bjöd in allihopa som collaborators, skrivit sina user stories/ Idag är planen arbeta med två av sina user stories, göra pull request osv./Inga hinder.
- **William**: Har klonat ned repot, skrivit funktionerna på tavlan/ ska börja arbeta med sin första user story/ Gått bra har inte stött på några problem.

### 04/11/2026 - Onsdag

- **Johan**: Har gjort min första US och granskat Williams första US./ Och idag ska jag gör funktion 4 och funktion 5./ inga hinder
- **Göran**: Har gjort färdigt sin första US och granskat Alecias första US/ Idag ska han göra sin andra US/ Haft hinder med att godkänna en annan US då det blev merge conflict, problemet blivit åtgärdat.
- **Alecia**: Gjorde funktion 12 och funktion 13, har granskat Johans US/ Ska göra funktion 14 och 15./ Hade problem med en PR, men löste det.
- **William**: Slutförde US6 gjorde pull request, mergade in den i Main
  Granskade Görans user story/ Ska idag göra US7-8/ Inga hinder.

### 05/11/2026 - Torsdag

- **Johan**: Gjort färdigt sina sista US, funktion 4 och 5 samt tagit bort gamla branches/Ska idag jobba med teorifrågor och reflektioner/ hade lite hinder med att ta bort branches men löste det tillslut.
- **Göran**: Gjorde färdigt sista 2 User stories (US-10, US-11)/ Granskade Alecias US-14 och US-15/ Ska idag jobba med teorifrågor och reflektioner.
  Inga hinder.
- **Alecia**: Igår slutförde man US 14-15, granskade US4-5/ Ska idag jobba med teorifrågor och personliga reflektioner/ Inga hinder.
- **William**: Gjorde klart US-7 och US-8, granskade Görans funktioner i US-10 och US-11/ ska idag göra teorifrågor och reflektioner/ stötte inte på några hinder.

## Retrospektiv

**_- Start:_** Att man går genom och diskutera hela arbetsflödet tillsammans innan start så att alla är på samma plan vad gäller insruktioner och förståelse. Kan hända att man missat något sen tidigare eller inte vet något, då kan man ta hjälp av varandra.

**_- Stop:_** En del som sinkade oss var ett tidigt misstag pga oklarheter kring fel som kan ske i arbetsflödet, det vi tror är (man har råkat merga in main till sin branch) vilket skapat dubbla koder. vilket senare ledde till att det blev merge konflikt.

**_- Continue:_** God samarbete och kommunikation, vi var väldigt flexibla och anpassade våra dailies efter varandras schema.

**_- Konkret förbättring:_** Är att ha korta dagliga avstämningar utöver dailies för att upptäcka problem tidigare.
En konkret förbättring är att vi bestämde i tisdags att den som granskar ska också merga samt flytta kort till klart, det gjorde att arbetsflödet blev mer strukturerad.

## Teorifrågor

### 1. Vad är agil utveckling, och vad i ert arbetssätt den här veckan var agilt?

Agil utveckling innebär att man jobbar flexibelt stegvis i korta steg och anpassar sig efter hand, även om man planerar allting så stöter man oftast på hinder som gör att man måste ändra prioritering och anpassa sig.
Vi har levererat färdigtestade och fungerande kod per dag, det som är stor fördel med Agilt utveckling är att man testar och levererar fungerande kod i korta steg istället för att leverera och testa först i slutet av projektet.
Vi har delat upp User Stories i olika dagar och följt planering, haft daily standups, slutför vårat sprint, diskuterat utmaningar mot slutet, hållit retrospektiv och förbättrar vårt arbetssätt.

### 2. Vilka Scrum-roller och moment använde ni (till exempel Scrum Master, daily, sprint och retrospektiv)? Beskriv hur de fungerade i er grupp.

Vi har haft Scrum master och utvecklare, haft daily-standups och retrospketiv mot slutet.
Vi tycker att det har fungerat bra, vi har haft dagliga möten som vi gått genom enligt insruktioner, vi har hållit tiden för daily standups.
Genom våra dagliga standups och Kanban-tavlan kunde vi hela tiden stämma av läget och hjälpa varandra längs vägen genom god kommunikation och samarbete.

### 3. Beskriv hur en user story gick från Att göra till Klart hos er, med branch, Pull Request, review och merge.

Man börjar med att flytta sin kort till från att göra till pågår och börjar arbeta med sin User story. Därefter skapar man en ny branch i Git, gör sina kodändringar och testar att allt fungerar.
När koden är klar gör man commit och pushar upp koden. Efter det skapar man en pull request och flyttar kortet till granskning.
När en gruppmedlem har granskat den, godkänt och mergat koden till main branchen så flyttar samma medlem kortet till klart.

### 4. Vad är en merge-konflikt, när uppstår den och hur löser man den på GitHub? Ge ett exempel med en funktion i index.html. Om ni fick en konflikt under veckan, beskriv den.

En merge konflikt uppstår när två personer (eller branscher) ändrar på samma rader i koden och försöker merga:

```javascript
/*Görans branch på main:*/
function funktion03() {
	return "Adress: Gitgatan 1";
}

/*Williams branch inkommande ändring: */
function funktion03() {
	return "Adress: Errorgatan 57";
}
```

Vi fick en merge konflikt för att branchen försökte skriva över main.
På main var 3 funktioner redan färdigkodade och uppdaterade, medan branchen utgick från en äldre version där (samma) 3 funktioner fortfarande var tomma.

## Personlig reflektion

### Johan

Den här veckan har jag lärt mig hur man arbetar i team med Git och GitHub och med Scrum-tavla, jag har fått en bättre förståelse för branches, commits och pull requests. Till nästa gång tar jag med mig att kommunicera med varandra i gruppen för att minska stress och misstag.

### Göran

Jag har lärt mig hur viktigt kommunkation är, att vara överens på samtliga punkter och synka med varandra då detta har hjälpts oss mycket. har lärt mig hur branches, pull requests/reviews och merge-konflikt funkar och vilka steg man ska följa.
Jag kommer ta med mig tyngden av god kommunkation samt spridning utav våra kunskaper med varandra då det gynnar oss allihopa.

### Alecia

Jag har lärt mig att samarbete och god, frekvent kommunikation är avgörande, och att ett stöttande team där alla blir hörda leder till bättre kod och högre effektivitet. Jag har också insett värdet av att diskutera problem – även små sådana – med sina teammedlemmar. Framöver kommer jag att ta god tid på mig att undersöka saker mer grundligt när något inte verkar stämma, istället för att stressa fram ett visst resultat.

### William

Den här veckan har jag lärt mig hur smidigt det är att jobba i team med Git när alla delar upp arbetet i egna feature-branches och kör Pull Requests. Det var väldigt lärorikt att både skapa egna PRs och göra reviews på kod innan mergning. Till nästa gång tar jag med mig att fortsätta ha en nära och tydlig kommunikation i gruppen.
