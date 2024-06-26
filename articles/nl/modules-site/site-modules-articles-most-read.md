<!-- Filename: Help4.x:Site_Modules:_Articles_-_Most_Read / Display title: Site modules: Meest gelezen artikelen -->

## Beschrijving

Het **Artikelen - Meest gelezen** moduletype toont een lijst met de
momenteel gepubliceerde artikelen die het meest bekeken zijn.

## Hoe toegang te krijgen

- Selecteer **Systeem → Beheren → Website modules** vanuit het
  beheermenu. Dan...
  - Om een nieuwe module aan te maken: selecteer de **Nieuw** knop uit
    de werkbalk. Dan...
    - Selecteer het gewenste moduletype.
  - Om een bestaande module te bewerken:
    - Zoek de module in de lijst met geïnstalleerde modules en selecteer
      de titel-link in de **Titel** kolom.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/8/8a/Help-4x-modules-site-module-manager-module-most-read-content-nl.png/800px-Help-4x-modules-site-module-manager-module-most-read-content-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/8/8a/Help-4x-modules-site-module-manager-module-most-read-content-nl.png 1.5x"
data-file-width="1115" data-file-height="847" width="800" height="608"
alt="modules site module manager module most read content" />

## Formulier velden

- **Titel.** De titel van de module. Dit is ook de titel die wordt
  weergegeven in de module afhankelijk van de *Toon Titel* formulierveld

### Module tabblad

#### Linker venster

- **Categorie:** Selecteer artikelen uit een bepaalde categorie of een
  reeks Categorieën. Als er niets wordt geselecteerd dan worden
  standaard alle categorieën getoond.
- **Weer te geven artikelen:** Het aantal weer te geven artikelen
  (standaard is 5).
- **Speciale artikelen:** (*Toon*/*Verberg*). Toon/Verberg artikelen
  aangegeven als speciaal.

#### Rechter venster

- **Toon titel.** (Toon/Verberg) Kies of de moduletitel op de website
  getoond of verborgen moet worden. De titel wordt degene in het
  formulierveld hierboven.
- **Positie.** Kies de module
  positie
  waarop u wilt dat de module getoond wordt. Een aangepaste module
  positie mag opgegeven worden om te gebruiken met de load positie
  plugin
  of er kan op de positie knop gedrukt worden om een module positie te
  selecteren uit het template.
- **Status**. De publicatiestatus van het item.
- **Toegang**. Het
  Toegangsniveau
  om het item te bekijken.
- **Module volgorde.** Dit toont een drop-down lijst met iedere module
  op de positie waar de huidige module op staat. Dit is de zowel
  volgorde waarin de modules getoond worden op de website als op de
  Modulebeheer
  pagina.
- **Start publiceren**. Datum en tijd waarop de publicatie moet starten.
  Gebruik dit veld wanneer u voortijdig inhoud wilt toevoegen die
  automatisch op een bepaalde tijd in de toekomst gepubliceerd moet
  worden.
- **Beëindig publiceren**. Datum en tijd om te stoppen met publiceren.
  Gebruik dit veld als u inhoud automatisch de status gedepubliceerd
  wilt geven op een tijdstip in de toekomst (bijvoorbeeld wanneer het
  niet meer van toepassing is).
- **Taal**. Item taal.
- **Notitie**. Dit wordt normaal gesproken door de beheerder gebruikt
  (bijvoorbeeld om informatie te documenteren voor dit item) en is niet
  op de website zichtbaar.

### Menutoewijzing tabblad

<img
src="https://docs.joomla.org/images/c/cc/Help-4x-modules-manager-site-module-menu-assignment-tab-nl.png"
decoding="async" data-file-width="1267" data-file-height="725"
width="1267" height="725"
alt="modules manager site module menu assignment tab" />

- **Moduletoewijzing.** Selecteer **Op alle pagina's**, **Geen
  pagina's**, **Alleen op de geselecteerde pagina's** of **Op alle
  pagina's behalve de geselecteerden** uit de lijst.
- **Menuselectie.** Wanneer de laatste twee opties gekozen worden zal er
  een lijst worden weergegeven met alle menu-items zoals in het
  schermafdruk hierboven is te zien. Dit geeft u de mogelijkheid om de
  menu-links te kiezen waarmee de module geassocieerd moet worden. U
  kunt hier kiezen op welke pagina's de module zichtbaar moet zijn. Zie
  Hoe kunt u een module toewijzen aan specifieke
  pagina's?
  voor meer informatie.

### Geavanceerd tabblad

<img
src="https://docs.joomla.org/images/2/2a/Help-4x-modules-manager-admin-module-site-advanced-options-nl.png"
decoding="async" data-file-width="1003" data-file-height="532"
width="1003" height="532"
alt="modules manager admin module site advanced options" />

- **Weergave.** Als u één of meer alternatieve lay-outs voor een module
  heeft gedefinieerd of in het template of in Joomla! core, dan kunt u
  de layout voor de module hier selecteren.
- **Module class.** Een achtervoegsel dat toegevoegd wordt aan de CSS
  class van de Module. Dit stelt u in staat aangepaste CSS stijlen aan
  te maken die alleen op deze module worden toegepast. U kunt dan het
  "user.css" bestand van uw template aanpassen om de stijl toe te voegen
  aan de nieuwe class. Geef deze parameter op met een voorafgaande
  spatie om een nieuwe CSS class voor deze module aan te maken. Geef de
  parameter zonder voorafgaande spatie om de CSS class naam voor deze
  module aan te passen.
- **Cachen.** Gebruik algemeen/Niet cachen. Of de inhoud van deze module
  al dan niet gecached moet worden. Het instellen van "Gebruik algemeen"
  zal de cache instellingen uit de Algemene instellingen gebruiken.
- **Cachetijd.** Het aantal seconden waarvoor de cache van het item
  lokaal wordt opgeslagen. Deze kan veilig op de standaardwaarde blijven
  staan.
- **Modulestijl.** U kunt deze optie gebruiken om de template-stijl voor
  deze positie te overschrijven.
- **Module-tag.** De HTML tag waar de module in geplaatst wordt. Dit is
  standaard een div tag maar andere HTML5 elementen kunnen ook worden
  gebruikt.
- **Bootstrap grootte.** (waarden 0 tot 12) Dit stelt u in staat de
  breedte van de module in te stellen via het span element uit
  bootstrap.
- **Koptekst-tag.** De HTML tag die gebruikt moet worden voor de header
  of titel van de module. Dit kan een h1, h2, h3, h4, h5, h6 of een p
  tag zijn. Let op dat u een module stijl (chrome) moet gebruiken met
  *html5* of uw eigen stijlen toevoegen in */html/modules.php*.
- **Koptekst class.** Hier kunt u optionele CSS classes toevoegen aan
  het header of titel element.

### Rechten tabblad

<img
src="https://docs.joomla.org/images/4/4f/Help-4x-modules-manager-admin-module-administrator-permissions-nl.png"
decoding="async" data-file-width="977" data-file-height="665"
width="977" height="665"
alt="modules manager admin module administrator permissions" />

Doe, om de rechten te veranderen, het volgende.

- Selecteer de **Groep** door links op de titel te klikken.
- Zoek de gewenste **Actie**. Mogelijke acties zijn:
  - **Verwijderen**. Gebruikers kunnen deze categorie verwijderen.
  - **Bewerken**. Gebruikers kunnen de module bewerken.
  - **Bewerk status**. Gebruikers kunnen de gepubliceerde status en de
    verwante informatie van de module wijzigen.
- Selecteer de gewenste rechten voor de actie die u wilt wijzigen.
  Mogelijke instellingen zijn:
  - '**Overgenomen:'** Overgenomen van gebruikers in deze groep vanuit
    de Algemene instellingen, Artikelen: Opties of Categorie rechten.
  - '**Toegestaan:'** Toegestaan voor gebruikers in deze groep. Let op
    dat wanneer deze actie op één van de hogere niveaus Geweigerd is het
    'Toegestaan' recht hier geen effect heeft. Een instelling geweigerd
    kan niet worden overschreven.
  - '**Geweigerd:'** Geweigerd voor alle gebruikers in deze groep.
- Klik op **Opslaan** in de **werkbalk**. Wanneer het scherm wordt
  vernieuwd, tonen de berekende instellingen de effectieve rechten voor
  deze groep en actie.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Opslaan**. Slaat item op en blijft op het huidige scherm.
- **Opslaan & sluiten**. Slaat item op en sluit het huidige scherm.
- **Opslaan & nieuw**. Slaat item op en houdt het bewerkscherm open,
  klaar voor het aanmaken van een ander item.
- **Opslaan als kopie**. Slaat uw wijzigingen op als een kopie van het
  huidige item. Beïnvloed het huidige item niet. Dit werkbalk icoon
  wordt niet getoond bij het aanmaken van een nieuw item.
- **Sluiten**. Sluit het huidige scherm en keert terug naar het vorige
  scherm zonder wijzigingen die u misschien heeft gedaan op te slaan.
  This toolbar icon is not shown if you are creating a new item.
- **Help**. Opent dit helpscherm.

## Weergave op de website

Een voorbeeld wordt hieronder getoond:

<img
src="https://docs.joomla.org/images/8/83/Help-4x-Extensions-Module-Manager-Most-Read-example-output-nl.png"
decoding="async" data-file-width="186" data-file-height="139"
width="186" height="139"
alt="Extensions Module Manager Most Read example output" />

De moduletype naam voor deze module is "mod_mostread". Het is niet
gerelateerd aan een andere component.
