# En enkel hemsida till ett fiktivt lokalt rockband som heter "The Velvet Storm"

## Sidor som ska finnas

- Hem (index)
- Turné-sida som innehåller ett turné schema i from av en tabell
- Bokningssida som inkluderar forms

## Initial idé och sketch:

### Hem (index)

![alt text](mockup/startsida-mockup.png)

### Turné-sida

![alt text](mockup/tour-mockup.png)

### Kontakt sida

![alt text](mockup/contact-mockup.png)

## "Dagbok" och planering

### Torsdag:

TODO:

- [ ] Setup HTML structure for home page (index.html)
  - [x] Header
    - [x] HTML
      - [x] Navbar with logo and menu links
    - [ ] CSS
      - [ ] Styling
      - [ ] Layout Flex/Grid?
  - [ ] Main
    - [ ] HTML
      - [x] Images
      - [ ] Content
    - [ ] CSS
      - [ ] Styling
      - [ ] Layout Flex/Grid?
  - [ ] Footer
    - [x] HTML
      - [x] Navbar
      - [x] Logo
      - [ ] Contact
      - [ ] Copyright
    - [ ] CSS
      - [x] Styling
      - [ ] Layout Flex/Grid?

### Reflektion slutet av dagen:

Lyckades få ner den grundläggande html-strukturen för hemsidan. Behöver fortfarande en hel del fix att göra.
Jag lyckades åtminstone få header-layouten att fungera med flex och jag tror att jag äntligen förstår flex, typ.

Jag vill få header:n och footer:n gjorda innan jag fortsätter med resten av innehållet och de andra två sidorna eftersom dom används på alla tre sidor. Efter det kommer jag att fokusera på festivalsektionen och recensions-delen av hemsidan eftersom de är ganska enkla och jag tror att jag skulle kunna återanvända mycket av stylingen därifrån på de andra sektionerna på de andra sidorna.

Anteckning till mig själv:
Avsluta en uppgift/tanke innan du går över till att fixa eller implementera en ny idé.

## Fredag:

TODO:

- [x] Setup HTML structure for home page (index.html)
- [x] Add booking-button in header
  - [ ] CSS
    - [x] Styling
    - [x] Layout Flex/Grid?
  - [ ] Main
    - [ ] HTML
      - [ ] Content
    - [ ] CSS
      - [ ] Styling
      - [ ] Layout Flex/Grid?
  - [ ] Footer
    - [ ] HTML
      - [ ] Content
        - [ ] Add booking button
        - [ ] Contact
        - [ ] Social Media Links
        - [ ] Copyright
    - [ ] CSS
      - [ ] Layout Flex/Grid?

### Reflektion slutet av dagen:

Har problem med att placera logotypen till vänster i header:n. När jag använder mig av en lista för menyalternativen fungerar det inte som jag vill.

Gillar typ hur navbaren/headern ser ut nu. Behöver bara några små förändringar.
Ska fokusera på att få footern nu.

## Söndag/Måndag:

TODO:

- [x] Setup HTML structure for home page (index.html)
- [x] Add booking-button in header
  - [x] CSS
    - [x] Styling
    - [x] Layout Flex/Grid?
  - [x] Main
    - [x] HTML
      - [x] Content
    - [x] CSS
      - [x] Styling
      - [x] Layout Flex/Grid?
  - [x] Footer
    - [x] HTML
      - [x] Content
        - [x] Add booking button
        - [x] Contact
        - [x] Social Media Links
        - [x] Copyright
    - [x] CSS
      - [x] Layout Flex/Grid?

### Reflektion slutet av dagen:

Lyckades få till en snygg sidfot med flex. Har lite problem med att få saker i mitten men jag återkommer till det senare.

Nu har alla sidor sin grundstruktur och styling. Nästa steg är att implementera bättre CSS för responsivitet. Jag trodde först att jag bara behöver flexbox för detta men jag kanske försöker byta ut allt till grids för att ha mer kontroll över layouten för olika enheter.

Jag kommer förmodligen bara att börja implementera rutnät på kontaktsidan för kontaktformuläret och sedan försöka implementera det på resten av webbsidorna.

## Tisdag:

Planer för dagen:

Fortsätta på gårdagens arbete med kontaktformuläret. Jag vill använda grids för kontaktformulärets layout. Om det går som planerat kommer jag att vilja implementera grids för resten av sidornas layout eftersom det känns som att det blir lättare att kontrollera när man testar för mindre skärmar och olika media queries.

Jag vill också göra koden renare. Jag har börjat organisera style.css för bättre läsbarhet, och det känns som att jag skulle kunna göra både HTML och CSS renare med färre klasser.

### Uppdatering

Lyckades skriva ett kontaktformulär genom att använda grids för layout.
Jag har märkt att när jag ändrar skärmstorlek är flexboxarna jag satt upp trasig för alla delar av sidan så jag kommer att skapa en branch och försöka göra all flex till grid och samtidigt städa upp både HTML och CSS vilket är en hemsk röra just nu.

Önska mig lycka till!

### Reflektion slutet av dagen:

....

## Fredag, inlämningsdag 17:16:

### Well...

Avsaknaden av inlägg här i journalen kanske talar för sig...
Jag satte igång med att implementera grids på de andra sidorna. Det gick till en början bra och jag kände att "det här går nog vägen".

Någon gång där på tisdag natt hade jag trasslat in mig ordentligt i en salig blandning av grids och flex och gav upp då jag knappt visste vad som hörde till vad.

Som tur var hade jag ju gjort allt det här i en separat branch! På onsdagen kunde jag gå tillbaka till min main-branch och fortsätta där jag saker och ting ändå såg och funkade hyfsat. Jag skapade ett nytt "experiment"-projekt där jag försökte återskapa min layout och mina olika delar av sidan med grids fast enbart med div:ar i olika färger och text. Något jag faktiskt fick att funka som jag ville!
När jag väl gick tillbaka till det riktiga projektet och försökte implementera samma metoder där så började grejer spöka på riktigt.

Resten av onsdags-kvällen/natten gick åt att felsöka försöka förstå varför det inte ville fungera utan några större framgångar.

Torsdagen bestod av ungefär samma sak fast med allt mer stigande kortisol-värden. Tack och lov kunde jag få lite input från kursledaren mot slutet av dagen vilket fick det att lossna för mig!

Idag fredag har jag lugn och metodiskt gått genom varje del av sidan och verkligen testat och gjort färdigt saker innan jag går vidare till nästa.

Det jag kommit fram till såhär vid dagens slut är att jag måste bli bättre på att börja enkelt först och främst.

Att i början bygga upp sidan med div:ar eller "primitiva" objekt och testa varje del noggrant innan jag går på nästa. Detta gjorde jag visserligen när jag började projektet dock så blev jag lite för varm i kläderna för mitt eget bästa och bakade in mig själv i en satans massa div:ar och klasser.
Jag försökte implementera grids när jag inte helt hade förstått mig på det. Samt att jag försökte baka in för mycket i en och samma "sektion" för att jag tänkte att allt i den skulle kunna kontrolleras samtidigt och automatiskt (något som säkert går men inte med den lilla kunskap jag besitter).

När jag satt idag delade jag upp saker och ting i lite mindre delar som hör till varandra vilket gjorde det lättare att välja ut och manipulera.

Något jag skulle vilja göra bättre men som jag inte riktigt känner att jag har hundra koll på är att skapa mer "generiska" css-klasser som fungerar på många sidor. Jag förstår det till viss del men ibland känns det som att jag inte riktigt når fram. Det känns som att css-filen blir så otroligt lång och rörig. Det måste jag bli bättre på!

Något annat jag måste bli bättre på är att göra bättre commits. Dels att skriva bättre meddelanden men också att göra commits som är bra, alltså inte commit:a grejer som är ofärdigt.
Jag tror anledningen till att det blir "hipp-som-happ"-commits är för att jag hoppar och jobbar på flera saker samtidigt, efter ett tag minns man inte vad man ändrat och då är det svårt att redogöra för det i ett commit.

Sammanfattningsvis kan jag väl säga att sidan ser ju inte helt ut som jag tänkt mig och den fungerar inte helt som jag vill. Dock är jag nöjd med den för att vara min "första" hemsida. Till nästa gång ska jag till en början inte lägga så mycket fokus på utseende utan på funktion för att sen börja styla samt att kanske inte försöka göra saker för avancerade utifrån min egna kunskap.
Jag har dock lärt mig väldigt mycket av det här projektet och jag har faktiskt haft väldigt roligt, sådär så att jag inte velat sluta (alltså när jag inte varit helt förtvivlad över att något inte fungerat).

Verkligen ett kul och lärorikt projekt!!

Tack för mig, leverpastej!
