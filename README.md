# Grupperepository for gruppe 9A
### Gruppemedlemmer

| Fullt Navn 		        | URL til GITHUB konto 	          |
| --------------------- | ----------------------------------- |
| Kjell Roar Lindberg   | https://github.com/kjellern98       |
| Jacob Rusch Svendsen  | https://github.com/jacobrsv         |
| Anna Maria Dang       | https://github.com/4nn4md           |
| Johanne Haakenstad    | https://github.com/Johannekh        |
| Sebastian Nesheim     | https://github.com/sebastiannesheim | 
| Simen Abild Olsen     | https://github.com/Venterommet      |
| Oliver Aaron Berg Johnston | https://github.com/Schniipi    |

### Møtereferat (oppsummering av de 3 møtene):

**I det første møtet (01.09.22)**, var flere gruppemedlemmer syke. Derfor begynte vi ikke med “Pull Request” til README.md fil. I stedet for, fikk alle gruppemedlemmer beskjed om å laste ned Git, lage GitHub konto og sin egen individuelle repository. I tillegg, var alle bedt om å undersøke og lære om både Git og GitHub. 

**I det andre møtet (05.09.22)**, lagde gruppeleder gruppe repositoryen og gruppen inviterte sammen alle gruppemedlemmer inn til repositoryen. Noen gruppemedlemmer var syke der og. Resten av gruppen fikk hjelp av et gruppemedlem som viste og forklarte hvordan man utfører et “Pull Request” i terminal. Vi fikk en utfordring når vi skulle få autorisert endringer til “gruppe repository” hvis vi brukte en Mac. 
 
**I det tredje møtet (08.09.22)**, fikk vi lagt inn det siste medlemmet i gruppen inn i repositoryen. En annen utfordring vi har hatt gjennom hele oppgaven, var vanskeligheten ved å forstå hvordan de forskjellige kommandoene fungerer og hvordan man bruker dem. Til slutt resonnerte vi oss frem til en konklusjon over hvordan vi følte at prosjektet gikk.

Gruppens selvevaluering av forståelse av Git og GitHub: _2,5_


# Flaggoppgaven
**Klikk her for å vise flaggoppgaven: https://4nn4md.github.io/GRUPPE-REPOSITORY/**
##Beskrivelse av prosess og strukturering (oppgave 5a)
I denne oppgaven valgte vi å bruke “Github projects” funksjonen for å gjøre det lettere å fordele oppgaver mellom alle gruppemedlemmene. Ved å bruke “Github projects” ble det enklere å se hvilke deloppgaver vi hadde igjen å gjøre slik at vi kunne fullføre prosjektet vårt over Flaggoppgaven. 

Vi valgte å strukturere vårt “Github project” som et “bord”, fordi det gjorde det mer oversiktlig å se hva vi måtte gjøre, hva vi holder på med og hva som er fullført. Med disse kategoriene kunne vi dermed lage deloppgaver av hovedoppgaven som ble gitt i Flaggoppgaven. Dermed delte vi hovedoppgaven inn i flere deloppgaver, og deloppgavene i enda flere deloppgaver. Dette oppsettet relaterer seg veldig til Kanban metoden, men vi brukte altså Scrumban metoden i hovedpunktet. Vi lente Scrumban metoden vår mer mot Kanban enn Scrum. Vi hadde gruppemøter som vi brukte som Scrum møter, men alt som ble gjort på Git var ved å bruke Kanban metoden. Gruppemedlemmene valgte selv hvilke oppgaver de ville gjøre i prosjektet. Videre brukte vi FORK metoden, siden da kan alle gruppemedlemmer jobbe i sin egen repository og så lage en “pull request” etterpå (NB: vi er ikke så flinke med “pull requests” enda). Dette fungerte bra for oss, siden vi kunne jobbe med oppgaven individuelt men fortsatt i gruppe utenfor gruppemøtene. I tillegg, ga Scrum møtene oversikt ettersom vi kunne gå gjennom hva vi hadde igjen å gjøre, og hva vi hadde fått til så langt. Samtidig ga også møtene tid til spørsmål og veiledning mellom gruppemedlemmer.

## Refleksjon rundt implementeringen
### 1. Flagg med bruk av p-element
Vi valgte å lage det italienske flagget med p-elementet. Det ga en utfordring i og med de tre farger er vertikale i stedet for horisontale i f.eks. det tyske flagget og derfor var bruk a p-elementet alene ikke nok. Derfor har vi brukt en tabell i formen av *"table"* tagget, og på den måten gjort det mulig å ha p-elementer ved siden av hverandre horisontalt. 
P-elementet er ment til tekst, og har derfor padding, margin, border osv. innebygget. Dette gjør det til en utfordring å anvende p-elementet til å lage grafikk, og det er nødvendig å eksplisitt fortelle nettleseren dette skal være slått fra.
### 2. Flagg med bruk av CSS
Med sine horisontale oppdelinger var det tyske flagget var mye lettere å konstruere.
### 3. Canvas flagg
Canvas-tagget gjør bruk av Javascript til å 'tegne' grafikken. Dette fungerer helt annerledes enn de to overstående metoder. Her ser vi forskjellen på markup-språk og scripting-språk.
Vi tok utgangspunkt i w3schools eksempel med en bue, og tilpassede det derfra.
Det står skrevet kommentarer in-line i koden som beskriver tegningen steg for steg.


## Kilder:
* (1) flagcolorcodes. "Germany flag color codes." Hentet fra: https://www.flagcolorcodes.com/germany (Lastet ned: 04.10.2022)
* (2) flagcolorcodes. "Italy flag color codes." Hentet fra: https://www.flagcolorcodes.com/italy (Lastet ned: 04.10.2022)
* (3) flagcolorcodes. "Japan flag color codes." Hentet fra:https://www.flagcolorcodes.com/japan (Lastet ned: 04.10.2022)
* (4) Wikipedia. "Flag of Germany." Hentet fra: https://en.wikipedia.org/wiki/Flag_of_Germany (Lastet ned: 04.10.2022)
* (5) Wikipedia. "Flag of Italy." Hentet fra: https://commons.wikimedia.org/wiki/File:Flag_of_Italy_(1946%E2%80%932003).png (Lastet ned: 04.10.2022)
* (6) Wikipedia. "Flag of Japan." Hentet fra: https://en.wikipedia.org/wiki/Flag_of_Japan (Lastet ned: 04.10.2022)
* (7) W3schools. "HTML canvas arc() Method" Hentet fra: https://www.w3schools.com/tags/canvas_arc.asp
* (8) MDN Web Docs. "CanvasRenderingContext2D" Hentet fra: https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D#basic_example
