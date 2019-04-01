# Resultaten

In het [adviesrapport](../adviesrapport/) wordt gedemonstreerd aan de hand van visualisaties en werkende [prototypes](../prototypes/) hoe de huidige interface verbeterd kan worden. Elke verbetering heeft een onderbouwing, documentatie, prijsindicatie en voorspelling van de impact die het gaat hebben. 

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
        <p>Semi-gestructureerd interview met e-commerce medewerker</p>
      </td>
      <td style="text-align:left">Verkopen via de webshop is heel belangrijk omdat daar de meeste marge
        op gepakt wordt. De situatie met huidige backend is niet optimaal.</td>
    </tr>
    <tr>
      <td style="text-align:left">Hoe ziet de backend van Fatboy&apos;s webshop eruit?</td>
      <td style="text-align:left">
        <p>(Veld onderzoek)</p>
        <p>Semi-gestructureerd interview met e-commerce medewerkers</p>
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
        <p>Het kost 1719 kliks om een gemiddeld product te lanceren. zie <a href="https://jonathanferede.gitbook.io/afstudeerportfolio/~/edit/drafts/-LaVeAGwj0bkl1kM-hiN/leeswijzer">bewijs_van_dubbel_werk.pdf</a> 
        </p>
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
        <p>Semi-gestructureerd interview met e-commerce medewerker (e-com. bestaat
          uit twee medewerkers)</p>
      </td>
      <td style="text-align:left">
        <p></p>
        <p>De e-commerce afdeling maakt veel gebruik van de backend. Ze zijn verantwoordelijk
          voor het invoeren van alle content en vertalingen die op de webshop komen.
          De interface van de backend remt hen erg af. (Interview_e-commerce.pdf)</p>
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
        <p>De sales afdeling maakt minder gebruik van de backend. Functies die ze
          nodig hebben, werken naar verwachting. Ze hebben geen behoefte aan verandering
          of extra features. <em><b>interview_sales.pdf</b></em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Hoe is de relatie tussen Fatboy en Kabisa?</td>
      <td style="text-align:left">Semi-gestructureerd interview met e-commerce, CEO Fatboy en Kabisa medewerker</td>
      <td
      style="text-align:left">Het feit dat veel zaken rondom de backend altijd via Kabisa lopen, in
        plaats van dat alles in eigen beheer is, is juist gunstig. zie<em><b> Relatie_Fatboy_en_Kabisa.pdf</b></em>
        </td>
    </tr>
  </tbody>
</table>## Ontwerpfase 

Gedurende de ontwerpfase zijn er veel ideeën geschetst en uitgeprobeerd. Visuele, tastbare en interactieve ideeën spreken veel beter tot de verbeelding en zorgen voor waardevollere feedback. Deze uitwerkingen zijn in een vroeg stadium gemaakt. Dit omdat ik in voorgaande projecten vaak te lang in de conceptfase bleef hangen en daardoor in een laat stadium erachter kwam dat bepaalde ideeën in de praktijk niet gingen werken. 

IDEE: Verwijzen naar /prototypes en alleen onderzoeksmethode benoemen. 

### [1. Sortable form ](../prototypes/1.-sortable-form.md)

De volgorde van ingevoerde invoervelden veranderen door drag ’n drop. Ik bedacht dat dit wel van pas zou kunnen komen bij het verbeteren van vertaaltabellen.

### [2. Livesearch](../prototypes/2.-livesearch.md)

In de huidige situatie zijn er veel pagina's met lange lijsten waar geen Livesearch zoekfunctie bij zit. Ik wilde wat er voor nodig was om zo'n functie te bouwen en wat voor effect het op andere functies zou kunnen hebben.

Aanpak: Online zoeken naar bestaande voorbeelden. Deze voorbeelden downloaden, proberen te begrijpen en vervolgens zelf na te bouwen/ aan te passen naar mijn eisen.

Resultaat: 

Terwijl ik het aan het bouwen was bedacht ik dat het handig zou kunnen zijn om een lijst van SKU-nummers in een zoekveld in te voeren. Rick heeft namelijk een keer een lijst met SKU’s binnen gekregen waar iets aan veranderd moest worden. En in het huidige systeem moet elke SKU individueel opgezocht worden. Het normale livesearch en 'bulk-livesearch' is beide gelukt. Het wordt ingewikkelder als er meerdere lijsten met livesearch op de pagina staan. Maar zeker niet onmogelijk.

Links: Prototypes/livesearch/

### [3. Selection methods ](../prototypes/3.-selection-methods.md)



### **5. Sortable and selectable and actions** 

Ik heb actie-knoppen toegevoegd zodat je iets kunt doen met wat je geselecteerd hebt.

### \*\*\*\*[**6. Paste csv**](../adviesrapport/6.-paste-csv.md)\*\*\*\*

Omdat ik ontdekte dat er vaak vertalingen vanuit excel gekopieerd worden naar de backend wilde ik uitzoeken of hier een makkelijkere manier voor was. Dus ik bouwde een feature waardoor je stukken van een tabel uit Excel kopiëren naar meerdere invoervelden op HTML pagina.

### \*\*\*\*[**7. Bulkbewerken**](../adviesrapport/7.-bulkbewerken.md)\*\*\*\*

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



