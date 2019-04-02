# Leeswijzer

## De opdracht

Design challenge:

Maak POC cliënt-side oplossingen voor in de backend van Fatboy’s webshop die het aantal handelingen die nodig zijn, om de taken die de e-commerceafdeling moet doen, te verminderen. 

## Aanpak, uitvoering en resultaten

### 1. Werkwijze

Gedurende dit project is er gebruik gemaakt van de scrum-methode. Het project verlangde een methode die de mogelijkheid bood om tussendoor bij te kunnen sturen. Vanaf januari is er telkens in sprints van twee weken gewerkt. Elke sprint eindigde met een sprint-demo. Hier werden de resultaten van de sprint en de plannen voor de volgende sprint gepresenteerd aan de bedrijfsbegeleider.

### 2. Stakeholders

| Bedrijf | Naam | Functie |
| :--- | :--- | :--- |
| Fatboy | Rick Berenschot | Bedrijfsbegeleider, Customer Interaction E-commerce |
|  | Tom de Vos | E-commerce director |
| Fontys FHICT | Erik Heijligers | Stagebegeleider |
| Kabisa | Bart Vollebregt | Developmentpartij |

### 3. Planning en onderzoeksmethoden



  
&lt;!--  
 /\* Font Definitions \*/  
  /\* Style Definitions \*/  
 p.MsoNormal, li.MsoNormal, div.MsoNormal  
	{mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-parent:"";  
	margin:0cm;  
	margin-bottom:.0001pt;  
	mso-pagination:widow-orphan;  
	font-size:12.0pt;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:Calibri;  
	mso-fareast-theme-font:minor-latin;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-ansi-language:NL;}  
h1  
	{mso-style-priority:9;  
	mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-link:"Heading 1 Char";  
	mso-style-next:Normal;  
	margin-top:12.0pt;  
	margin-right:0cm;  
	margin-bottom:0cm;  
	margin-left:0cm;  
	margin-bottom:.0001pt;  
	mso-pagination:widow-orphan lines-together;  
	page-break-after:avoid;  
	mso-outline-level:1;  
	font-size:16.0pt;  
	font-family:"Calibri Light",sans-serif;  
	mso-ascii-font-family:"Calibri Light";  
	mso-ascii-theme-font:major-latin;  
	mso-fareast-font-family:"Times New Roman";  
	mso-fareast-theme-font:major-fareast;  
	mso-hansi-font-family:"Calibri Light";  
	mso-hansi-theme-font:major-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:major-bidi;  
	color:\#2F5496;  
	mso-themecolor:accent1;  
	mso-themeshade:191;  
	mso-font-kerning:0pt;  
	mso-ansi-language:NL;  
	font-weight:normal;}  
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph  
	{mso-style-priority:34;  
	mso-style-unhide:no;  
	mso-style-qformat:yes;  
	margin-top:0cm;  
	margin-right:0cm;  
	margin-bottom:0cm;  
	margin-left:36.0pt;  
	margin-bottom:.0001pt;  
	mso-add-space:auto;  
	mso-pagination:widow-orphan;  
	font-size:12.0pt;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:"Times New Roman";  
	mso-fareast-theme-font:minor-fareast;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-ansi-language:NL;}  
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst  
	{mso-style-priority:34;  
	mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-type:export-only;  
	margin-top:0cm;  
	margin-right:0cm;  
	margin-bottom:0cm;  
	margin-left:36.0pt;  
	margin-bottom:.0001pt;  
	mso-add-space:auto;  
	mso-pagination:widow-orphan;  
	font-size:12.0pt;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:"Times New Roman";  
	mso-fareast-theme-font:minor-fareast;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-ansi-language:NL;}  
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle  
	{mso-style-priority:34;  
	mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-type:export-only;  
	margin-top:0cm;  
	margin-right:0cm;  
	margin-bottom:0cm;  
	margin-left:36.0pt;  
	margin-bottom:.0001pt;  
	mso-add-space:auto;  
	mso-pagination:widow-orphan;  
	font-size:12.0pt;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:"Times New Roman";  
	mso-fareast-theme-font:minor-fareast;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-ansi-language:NL;}  
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast  
	{mso-style-priority:34;  
	mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-type:export-only;  
	margin-top:0cm;  
	margin-right:0cm;  
	margin-bottom:0cm;  
	margin-left:36.0pt;  
	margin-bottom:.0001pt;  
	mso-add-space:auto;  
	mso-pagination:widow-orphan;  
	font-size:12.0pt;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:"Times New Roman";  
	mso-fareast-theme-font:minor-fareast;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-ansi-language:NL;}  
span.Heading1Char  
	{mso-style-name:"Heading 1 Char";  
	mso-style-priority:9;  
	mso-style-unhide:no;  
	mso-style-locked:yes;  
	mso-style-link:"Heading 1";  
	mso-ansi-font-size:16.0pt;  
	mso-bidi-font-size:16.0pt;  
	font-family:"Calibri Light",sans-serif;  
	mso-ascii-font-family:"Calibri Light";  
	mso-ascii-theme-font:major-latin;  
	mso-fareast-font-family:"Times New Roman";  
	mso-fareast-theme-font:major-fareast;  
	mso-hansi-font-family:"Calibri Light";  
	mso-hansi-theme-font:major-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:major-bidi;  
	color:\#2F5496;  
	mso-themecolor:accent1;  
	mso-themeshade:191;  
	mso-ansi-language:NL;}  
.MsoChpDefault  
	{mso-style-type:export-only;  
	mso-default-props:yes;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:Calibri;  
	mso-fareast-theme-font:minor-latin;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;}  
@page WordSection1  
	{size:595.0pt 842.0pt;  
	margin:2.8pt 72.0pt 72.0pt 72.0pt;  
	mso-header-margin:35.4pt;  
	mso-footer-margin:35.4pt;  
	mso-paper-source:0;}  
div.WordSection1  
	{page:WordSection1;}  
 /\* List Definitions \*/  
 @list l0  
	{mso-list-id:2016613005;  
	mso-list-type:hybrid;  
	mso-list-template-ids:1371729284 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}  
@list l0:level1  
	{mso-level-number-format:bullet;  
	mso-level-text:;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:Symbol;}  
@list l0:level2  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:"Courier New";}  
@list l0:level3  
	{mso-level-number-format:bullet;  
	mso-level-text:;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:Wingdings;}  
@list l0:level4  
	{mso-level-number-format:bullet;  
	mso-level-text:;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:Symbol;}  
@list l0:level5  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:"Courier New";}  
@list l0:level6  
	{mso-level-number-format:bullet;  
	mso-level-text:;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:Wingdings;}  
@list l0:level7  
	{mso-level-number-format:bullet;  
	mso-level-text:;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:Symbol;}  
@list l0:level8  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:"Courier New";}  
@list l0:level9  
	{mso-level-number-format:bullet;  
	mso-level-text:;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	font-family:Wingdings;}  
ol  
	{margin-bottom:0cm;}  
ul  
	{margin-bottom:0cm;}  
--&gt;  


##  Planning

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left">Wk.</th>
      <th style="text-align:left"></th>
      <th style="text-align:left">Sprint</th>
      <th style="text-align:left">Bijzonderheden</th>
      <th style="text-align:left">Fase</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">nov</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">1</td>
      <td style="text-align:left">12 nov - 16 nov</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Orientatiefase</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">2</td>
      <td style="text-align:left">19 nov - 23 nov</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">3</td>
      <td style="text-align:left">26 nov - 30 nov</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">dec</td>
      <td style="text-align:left">4</td>
      <td style="text-align:left">3 dec - 7 dec</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">1e bedrijfsbezoek?</td>
      <td style="text-align:left">Planfase</td>
    </tr>
    <tr>
      <td style="text-align:left">5</td>
      <td style="text-align:left">10 dec - 14 dec</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
        <p>Onderzoek naar gebruikers is klaar</p>
        <p>P.I.D. (Project Initiatie Document) goed gekeurd</p>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">6</td>
      <td style="text-align:left">17 dec - 21 dec</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Plan van aanpak (welke verbeteringen hebben prioriteit?)</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">7</td>
      <td style="text-align:left">24 dec - 28 dec</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Kerstvakantie</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">jan</td>
      <td style="text-align:left">8</td>
      <td style="text-align:left">31 dec - 4 jan</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Kerstvakantie</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">9</td>
      <td style="text-align:left">7 jan - 11 jan</td>
      <td style="text-align:left">
        <p>1</p>
        <p>Bulk</p>
      </td>
      <td style="text-align:left">
        <p>Onderzoek naar hoe het invoeren en bewerken van tekst-invoervelden beter
          kan</p>
        <p>Meerdere invoervelden tegelijkertijd</p>
        <p>Kopi&#xEB;ren vanuit Excel</p>
        <p>Mogelijkheid om invoerveld op te spitsen in meerdere variabelen (naam-sequence)</p>
      </td>
      <td style="text-align:left">Ontwerp &amp; Realisatie fase</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">10</td>
      <td style="text-align:left">14 jan - 18 jan</td>
      <td style="text-align:left">Sprint demo 1</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">11</td>
      <td style="text-align:left">21 jan - 25 jan</td>
      <td style="text-align:left">2 presets</td>
      <td style="text-align:left">Student zal voor &#xE9;&#xE9;n dag terug naar school gaan voor een tussentijdse
        presentatie (week 10).</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">12</td>
      <td style="text-align:left">28 jan - 1 feb</td>
      <td style="text-align:left">Sprint demo 2</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">feb</td>
      <td style="text-align:left">13</td>
      <td style="text-align:left">4 feb - 8 feb</td>
      <td style="text-align:left">3</td>
      <td style="text-align:left">--</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">14</td>
      <td style="text-align:left">11 feb - 15 feb</td>
      <td style="text-align:left">Onderbouwing voor bedachte oplossingen</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">15</td>
      <td style="text-align:left">18 feb - 22 feb</td>
      <td style="text-align:left">4</td>
      <td style="text-align:left">Onderzoek naar betere manier om media te selecteren</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">16</td>
      <td style="text-align:left">25 feb - 1 maa</td>
      <td style="text-align:left">Sprint demo 4</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">maa</td>
      <td style="text-align:left">17</td>
      <td style="text-align:left">4 maa - 8 maa</td>
      <td style="text-align:left">5</td>
      <td style="text-align:left">
        <p>Onderzoek naar verbetering workflow en navigatie + nieuwe inzichten en
          idee&#xEB;n.</p>
        <p>Uitwerken van POC&#x2019;s en adviesrapport</p>
      </td>
      <td style="text-align:left">Afronden onderzoek en eindproduct</td>
    </tr>
    <tr>
      <td style="text-align:left">18</td>
      <td style="text-align:left">11 maa - 15 maa</td>
      <td style="text-align:left">Sprint demo 5</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">19</td>
      <td style="text-align:left">18 maa - 22 maa</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">2e bedrijfsbezoek + presentatie van eindproduct</td>
      <td style="text-align:left">Afronden eindproduct</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">20</td>
      <td style="text-align:left">25 maa - 29 maa</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">apr</td>
      <td style="text-align:left">21</td>
      <td style="text-align:left">1 apr - 5 apr</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Oplevering eindproduct</td>
      <td style="text-align:left">Afstudeerfase</td>
    </tr>
    <tr>
      <td style="text-align:left">22</td>
      <td style="text-align:left">8 apr - 14 apr</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">23</td>
      <td style="text-align:left">17 apr - 19 apr</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">&#xB7; Portfolio/ thesis inleveren</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">x</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">&#xB7; Afstudeerzitting</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

