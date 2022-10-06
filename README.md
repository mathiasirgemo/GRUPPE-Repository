### Rapport

Vi valgte å ta i bruk GitHub projects for å få en oversikt over hvilke oppgaver som skulle gjøres. Vi delte hver flaggtype inn i 3 oppgaver og omgjorde disse til issues. 
Deretter delte vi ut oppgavene til alle på gruppen, dette var en enkel prossess fordi vi ble enige i gruppen om at alle burde prøve seg ut på de forskjellige typene for å lære.

For å forstå hva oppgavene var har vi tatt i bruk kanbanboard i github projects. Dette er fordi det er lett oversiktlig og enkelt å dele inn. Vi lagde 4 rader.<br>
Rad 1: Læring - Denne raden la vi inn informasjon som er nyttig for å kunne fullføre prosjektet.<br>
Rad 2: Oppgaver - Dette var oppgavene som vi måtte gjøre.<br>
Rad 3: Under arbeid - Når oppgavene ble startet på flyttes de over til under arbeid så gruppen har oversikt over hva som jobbes med.<br>
Rad 4: Ferdig - Her tok hver medlem og flyttet sitt ark som var ferdig slik at gruppen visste hva som var igjen av oppgavene.<br>

Først og fremst delte vi prosjektet inn i en hovedkategori "Prosjekt flagg" etterfulget av underkategoriene "Github metoder" ,"Lag flagg" og "arbeidsoppgaver beskrivelser". Dette var for å lage et tydelig skille mellom de to mest åpenbare prosjektdelene, og for å vite hva vi skal lage arbeidsoppgaver utifra. Deretter brøyt vi ned de to prosjektdelene til 5 arbeidsoppgaver.

Prosjekt flagg:

    - Lag flagg:
        - p - style
        - css - style
        - canvas - style

    - Github metoder:
        - Github projects

    - arbeidsoppgaver beskrivelser:
        - beskrivelse av de ulike prosessene bak prosjektplanlegging

##### p - style

HTML (HyperText Markup Language) er basisen for all internett, og grunnlaget for alt når vi henviser dokumenter til hverandre. Tekst og andre visuelle elementer defineres her med markør "markup" tekster av forskjellige varianter for å gi dem roller og egenskaper. 
Vi brukte HTML for å lage lette "horisontale"-flagg. Tekstblokker ble lagt vertikalt oppå hverandre visuelt med farge koder og størrelse, samt posisjon. De fleste i gruppen fant p-style nokså lett, det ble straks vanskeligere når vi prøvde å lage "vertikale"-flagg. Vi lærte at det lot seg ikke gjøre alene i bare HTML. Fordelen med å bruke bygge direkte inn i p elementet er at du vet akkurat hvilket element på nettsiden du endrer med css. Ulempen er at det ofte blir mye av samme style på forskjellige elementer i koden.(MDN contributors, 2022)
  
##### css - style

Fordelen med CSS i forhold til p-stil og canvas er at man kan lettere style klasser og flere elementer sammen. I CSS kan man ta for seg grupper av elementer og lage de til en klasse og gi hele klassen en betegnelse på hvordan det skal se ut. Med p-stil må man ta hvert element. I tillegg kan CSS style flere HTML elementer enn bare P elementet eller Canvas elementet. En ulempe med CSS er at hvis man bare styler med CSS kan ting crashe litt sammen, hvis ikke stil-elementene spesifiseres nok. Derfor kan det være lurt å også bruke Canvas med CSS, for å lettere skille mellom ting. Flagget til Storbritannia ble laget ved bruk av CSS. Siden den består av flere elementer, ble det brukt class attributet for de ulike objekter. Først ble det laget et 300px høy og 600px bredt hvit bakgrunn for flagget. Deretter ble det definert fire trekanter på hver sin side med nok mellomrom for å beholde de hvite linjer på den ene korset. Det små røde korset ble laget ved å skape fire linjer, og bruke transform elementet til å skjeve dem ut til korrekt vinkel på flagget. Det ble også brukt clip-path for å kutte to linjer slik at den ene enden er vertikal. Til slutt ble det laget to kors, en hvit og en rød med vertikal og horizontal linje, og de ble plassert på midten av flagget for å gjenskape hele britiske flagget. (MDN contributors, 2022)

  
##### canvas-style

*Canvas API gjør som man ha mulighet til å tegne grafikk via JavaScript og HTML når man bruker canvas elementet. Canvas API blir ofte brukt i sammenheng med spill, animasjon og datavisualisering*(MDN contributors, 2022). Det som kan være ulempene med HTML5 Canvas er at ved større modeller så kan det gå utover hastigheten på nettleseren som skal lese koden. En annen ulempe som vi merket er at koden for å lage noe relativt enkelt er mer avansert enn for eksempel å lage samme flagg i html ved bruk av css. Men fordelene ved å bruke canvas er at det er lettere å være kreativ i hvordan en velger å forme en side med å plassere og lage elementer, som for eksempel sirkeler, anmimasjoner og andre geografiske symboler. Norges nasjonalflagg ble laget som lag som bygget på hverandre. Først et rødt rektangel som en base, deretter hvitt horisontalt rektangel, hvitt vertikalt rektangel og det samme bare med blå farge. Justerte deretter størrelse og plassering med å endre x/y aksen, bredde og høyde til riktig dimensjon.(MDN contributors, 2022)

Referanse liste: 

MDN contributors. (13.September 2022) HTML (HyperText Markup Language). Mdn web docs. https://developer.mozilla.org/en-US/docs/Web/HTML

MDN contributors. (2.September 2022). Canvas API. Mdn web docs. https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API 

MDN contributors. (25.September 2022). CSS: Cascading Style Sheets. https://developer.mozilla.org/en-US/docs/Web/CSS
