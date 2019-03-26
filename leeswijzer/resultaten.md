# Resultaten

In het [adviesrapport](../adviesrapport.md) word gedemonstreerd a.d.h.v. visualities en werkende [prototypes](../prototypes/) hoe de huidige interface verbeterd kan worden. Elke verbetering heeft een onderbouwing, documentatie, prijs indicatie en voorspelling van de impact die het gaat maken. 

## **Oriëntatiefase** 

Gedurende de oriëntatiefase is er kwalitatief onderzoek gedaan naar het bedrijf en gezocht naar een goede probleemstelling.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Onderzoeksvraag</th>
      <th style="text-align:left">Methode</th>
      <th style="text-align:left">Resultaat</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Wat is Fatboy?</td>
      <td style="text-align:left">
        <p>(Veld onderzoek)</p>
        <p>Semigestructureerd interview met e-commerce medewerker</p>
      </td>
      <td style="text-align:left">Verkopen via de webshop is heel belangrijk omdat daar de meeste marge
        op gepakt wordt. De situatie met huidige backend is niet optimaal.</td>
    </tr>
    <tr>
      <td style="text-align:left">Hoe ziet de backend van Fatboy&apos;s webshop eruit?</td>
      <td style="text-align:left">
        <p>(Veld onderzoek)</p>
        <p>Semigestructureerd interview met e-commerce medewerkers</p>
      </td>
      <td style="text-align:left">informatieflow chart</td>
    </tr>
    <tr>
      <td style="text-align:left">Wat is er mogelijk vanuit de backend?</td>
      <td style="text-align:left">
        <p>(Veld onderzoek)</p>
        <p>Alle pagina&#x2019;s en invoervelden in de testomgeving uitproberen</p>
      </td>
      <td style="text-align:left">Wat is er mogelijk vanuit de backend.pdf</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>Hoe veel werk is het om een product te lanceren via de huidige backend?</p>
      </td>
      <td style="text-align:left">
        <p>(Lab onderzoek)</p>
        <p>Kliktest</p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>Het kost minimaal 359 kliks om een hoofdproduct met gekoppelde producten
          in twee verschillende talen te lanceren. (Normaal gesproken worden er 8
          vertalingen. Voor een nauwkeurigere inschatting verwijs ik naar <a href="https://jonathanferede.gitbook.io/afstudeerportfolio/~/edit/drafts/-LaVeAGwj0bkl1kM-hiN/leeswijzer">bewijs_van_dubbel_werk.pdf</a>)
          (kliktest.pdf)(screencapture.mp4)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>Hoe werkt de e-commerce afdeling met de backend?</p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>(Veldonderzoek)</p>
        <p>Semi-gestructureerd interview met ecommercemedewerker (ecom bestaat uit
          twee medewerkers)</p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>Hoe een product gelanceerd word. Welke velden wel/niet ingevuld worden.
          Waar vertalingen vandaan komen. Wat vaak mis gaat en veel tijd kost. (Interview_ecommerce.pdf)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>Hoe werkt de salesafdeling met de backend?</p>
      </td>
      <td style="text-align:left">
        <p>(Veldonderzoek)</p>
        <p>Semi-gestructureerd interview met salesmanager</p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>Sales maakt heel weinig gebruik van backend. Functies die ze nodig hebben
          werken naar verwachting. Hebben geen behoefte aan verandering of extra
          features. (interview_sales.pdf)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Hoe is de relatie tussen Fatboy en Kabisa</td>
      <td style="text-align:left">Semi-gestructureerd interview met e-commerce, CEO Fatboy en Kabisa medewerker</td>
      <td
      style="text-align:left">Huidige situatie is zo erg nog niet.</td>
    </tr>
  </tbody>
</table>## Ontwerpfase 

Gedurende de ontwerpfase zijn er veel ideeën geschetst en uitgeprobeerd. Visuele, tastbare en interactieve ideeën spreken veel beter tot de verbeelding en zorgen voor waardevollere feedback. Deze uitwerkingen zijn in een vroeg stadium gemaakt. Dit omdat ik in voorgaande projecten vaak te lang in de conceptfase bleef hangen en daardoor in een laat stadium erachter kwam dat bepaalde ideeën in de praktijk niet gingen werken. 

IDEE: Verwijzen naar /prototypes en alleen onderzoeksmethode benoemen. 

### [1. Sortable form ](../prototypes/1.-sortable-form.md)

De volgorde van ingevoerde invoervelden veranderen door drag ’n drop. Ik bedacht dat dit wel van pas zou kunnen komen bij het verbeteren van vertaaltabellen.

### [2. Livesearch](../prototypes/2.-livesearch.md)

Livesearch voor lange lijsten miste ik heel erg in de huidige backend. Ik wilde weten wat ervoor nodig was om het zelf te bouwen.

Aanpak: Online zoeken naar bestaande voorbeelden. Deze voorbeelden downloaden, proberen te begrijpen en vervolgens zelf na te bouwen/ aan te passen naar mijn eisen.

Resultaat: 

Terwijl ik het aan het bouwen was bedacht ik dat het handig zou kunnen zijn om een lijst van SKU-nummers in een zoekveld in te voeren. Rick heeft namelijk een keer een lijst met SKU’s binnen gekregen waar iets aan veranderd moest worden. En in het huidige systeem moet elke SKU individueel opgezocht worden. Het normale livesearch en 'bulk-livesearch' is beide gelukt. Het wordt ingewikkelder als er meerdere lijsten met livesearch op de pagina staan. Maar zeker niet onmogelijk.

Links: Prototypes/livesearch/

### [3. Selection methods ](../prototypes/3.-selection-methods.md)

Ik wilde weten in hoeverre het mogelijk was om de selectiemethodes zoals in Windows Verkenner en Finder na te maken in een html-pagina. Iedereen is bekend met het tekenen van selectiekaders, Shift + click, ctrl/cmd + click, ctrl/cmd + A, ctrl/cmd + D etc. voor het \(de\)selecteren van items in een lijst. De manier hoe gebruikers met de webversie van Google Drive kunnen werken komt hier al heel dicht in de buurt.

Aanpak: Ik heb eerst online gezocht naar werkende voorbeelden van selectiemethodes in webapps. Vervolgens heb ik er een paar gedownload, aangepast en geprobeerd om te combineren.

Resultaat: Ik ontdekte dat de manier van interactie zoals in Windows Verkenner en Finder tot op zekere hoogte prima te vertalen is naar een webapp. Het wordt ingewikkelder wanneer er meerdere lijsten in één pagina staan. Dit is mij nog niet gelukt, maar ik weet zeker dat het mogelijk is.

Links:

### \*\*\*\*[**4. Sortable and selectable**]() ****

Ik was benieuwd of het sorteren en selecteren te combineren was zonder dat er rare bugs ontstaan.

### **5. Sortable and selectable and actions** 

Ik heb actie-knoppen toegevoegd zodat je iets kunt doen met wat je geselecteerd hebt.

### \*\*\*\*[**6. Paste csv**](../prototypes/6.-paste-csv.md)\*\*\*\*

Omdat ik ontdekte dat er vaak vertalingen vanuit excel gekopieerd worden naar de backend wilde ik uitzoeken of hier een makkelijkere manier voor was. Dus ik bouwde een feature waardoor je stukken van een tabel uit Excel kopiëren naar meerdere invoervelden op HTML pagina.

### \*\*\*\*[**7. Bulkbewerken**](../prototypes/7.-bulkbewerken.md)\*\*\*\*

De functie die de ecommerce het meeste tijd gaat besparen is de mogelijkheid om meerdere producten, hoofdproducten, pagina’s, pagina-elementen etc. tegelijkertijd te bewerken. En ik was benieuwd in hoeverre dit te realiseren was voor op een webpagina. Het idee kwam van de interface die iTunes gebruikte voor het bewerken van meerdere nummers in een playlist. 

Methode:

Ik wilde een dynamisch systeem bouwen. Een systeem dat werkt met verschillende lijsten van objecten en dus eenvoudig op meerdere plekken implementeerbaar is. Dus ik maakte een script die een json-file uitleest en deze als een lijst toont. In deze lijst werden alle objecten \(verticaal\) met hun eigenschappen\(horizontaal\) getoond. Ik heb voor dit voorbeeld echte SKU’s met de bijbehorende productnamen gebruikt. Alle list-items heb ik selecteerbaar gemaakt met de technieken uit het prototype selectionmethods. Wanneer er op bewerken geklikt word, verschijnt er een venster met de invoervelden die bij de geselecteerde objecten horen. Wanneer de invoervelden bewerkt zijn en er op opslaan geklikt word moeten de geselecteerde objecten uit de jsonfile geüpdatet. Daarna moet de lijst opnieuw geladen omdat het anders lijkt alsof er niets gebeurd is.

Resultaten:

Ik leerde dat er rekening gehouden moet worden met eigenschappen van objecten die onveranderd moeten blijven. Ik bedacht me dat er veel scenario’s kunnen zijn waar voor meerdere objecten een eigenschap op BIJNA dezelfde manier ingevuld kan worden. Bijvoorbeeld een zin met één variabel woord erin. Ik leerde dat het belangrijk is om een vorm van bevestigingsfeedback te ontvangen wanneer de geselecteerde items bewerkt zijn.

Links:

Bestaande bulkbewerk interfaces.pdf iTunes bulk bewerk UI werkplaatsonderzoek.pdf Toepasbaarheid bulkbewerk techniek.pdf Prototypes/bulkbewerken/ Variabelen\_invoeren.pdf

### **8. Producten\_koppelen** 

Meerdere producten tegelijk aan hetzelfde hoofdproduct koppelen

Links:

UI\_schets.jpg

### 9. Bulk bewerken met variabelen

> Is het mogelijk om een eigenschap van meerdere objecten te veranderen en daarbij variabelen te gebruiken die per object kunnen verschillen in een HTML pagina?

 Methode: proberen 

Resultaat

### **10. Presets** 

Presets gebruiken om meerdere invoervelden in te vullen

### **11. Fieldset\_idee** 

Een dynamische manier om presets per fieldset aan te maken, opslaan en updaten. Met een hele simpele implementatie.

### **12. Bulkbewerken met presets** 

met presets Presets gebruiken bij het bewerken van meerdere items. \(nog niet gelukt\)

## Lab fase

Na terugkomdag veel labonderzoek gedaan om problemen te analyseren en oplossingen te onderbouwen. 1. Bewijs van dubbel werk

3.4.1.4 Verificatie fase Toetsen en testen

3.4.2 Resultaten en toegevoegde waarde

## 



