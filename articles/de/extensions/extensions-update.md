<!-- Filename: Help4.x:Extensions:_Update / Display title: Erweiterungen: Aktualisieren -->

## Beschreibung

Über diese Seite können installierte Erweiterungen aktualisiert werden,
die einen Aktualisierungsserver bereitstellen. Die Live-Aktualisierung
der Erweiterung erfolgt, ohne dass die aktualisierten
Erweiterungsdateien manuell hochgeladen und installiert werden müssen.
Sie werden stattdessen über Standard-HTTP-Verbindungen vom externen
Aktualisierungsserver bezogen.

## Wie darauf zugreifen

- Im Administrator-Menü
  **System → Aktualisierungen → Erweiterungen** wählen. Dann, um
  ein Update durchzuführen ...
  - das Kontrollkästchen eines oder mehrerer Einträge markieren, die
    aktualisiert werden sollen.
  - Die Schaltfläche **Aktualisieren** in der Symbolleiste anklicken.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/d/d7/Help-4x-extensions-extension-manager-update-en.png"
decoding="async" data-file-width="800" data-file-height="363"
width="800" height="363"
alt="extensions extension manager update" />

## Spalten-Überschriften

<img
src="https://docs.joomla.org/images/thumb/1/1d/Help-4x-Extensions-Manage-Update-columns-en.png/680px-Help-4x-Extensions-Manage-Update-columns-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/1/1d/Help-4x-Extensions-Manage-Update-columns-en.png 1.5x"
data-file-width="871" data-file-height="29" width="680" height="23"
alt="Extensions Manage Update columns" />

- **Checkbox**. Dieses Kästchen markieren, um einen oder mehrere
  Einträge auszuwählen. Um alle Einträge auszuwählen, das Kästchen im
  Spaltenkopf markieren. Nachdem ein oder mehrere Kästchen markiert
  sind, auf eine Schaltfläche in der Werkzeugleiste klicken, um eine
  Aktion für den ausgewählten Eintrag oder die ausgewählten Einträge
  durchzuführen. Viele Aktionen, wie z.B. Veröffentlichen und
  Verstecken, können mit mehreren Einträgen arbeiten. Andere, wie z.B.
  Bearbeiten, funktionieren gleichzeitig jeweils nur mit einem Eintrag.
  Wenn mehrere Einträge markiert sind und Sie auf „Bearbeiten“ drücken,
  wird der erste der markierten Einträge zur Bearbeitung geöffnet.
- **Name**. Der Name der Erweiterung.
- **Location.** Specifies if this is a site or administrator extension.
- **Type.** The extension type. Examples of extension types are module,
  plug-in, template, component, language or package.
- **Installed.** The version number of the currently installed
  extension.
- **Available.** The version number of the available update.
- **Changelog.** The changelog.
- **Folder.** If the extension is a plug-in, the subdirectory of your
  Joomla! installation's /plugins directory where the extension is
  located. By default Joomla! has the following subdirectories in the
  plugins directory which each represent the different types of plug-ins
  that are defined: authentication, content, editors, editors-xtd,
  extension, search, system, user.
- **Install Type.** The type of installation that will be performed by
  the update. Usually this will be type ***Update*** which will perform
  an in-place update of the extension.

## List Filters

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Filter Options**. Click to display the additional filters.
- **Clear**. Click to clear the Filter field and restore the list to its
  unfiltered state.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- **Number to Display**. Shows the number of items in a list. Select
  from the dropdown list to change the number displayed.The default for
  a site is '20' but this may be changed in the Global Configuration.

#### Filter Options

- **-Select Location-.** Select Site, Administrator or API from the
  drop-down list of available locations.
- **-Select Type-.** Select the extension type from the drop-down list
  box of available types.
- **-Select Folder-.** Select a plug-in folder from the drop-down list
  box of available folders. There is a separate folder for each type of
  plug-in defined in your Joomla installation.

**Page Controls**. When the number of items is more than one page, you
will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Page numbers**. Click to go to the desired page.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Update.** Perform update of selected options. This will fetch an
  update file from the update server and may take several seconds.
  Please be patient!
- **Find Updates.** Query update servers for the latest versions of
  installed extensions. Again, this may take a while.
- **Clear Cache.** Clear the available extension update information
  displayed in the listing.
- **Options.** Opens the Options window where settings such as default
  parameters can be edited.
- **Help**. Opens this help screen.

## Quick Tips

- Only extensions which support the Joomla! update system will be listed
  in this screen. If you use extensions which do not support the new
  update system or you are not sure, consult the extension developer's
  website.
- It is critical to keep your extensions up-to-date. Failure to do so
  may expose a vulnerability in your Joomla! installation which can be
  exploited by hackers.
- It is recommended to backup your Joomla! installation files and
  database before attempting to update extensions or the Joomla!
  installation itself. This will ensure that you can restore your
  Joomla! installation to its previous state if the update fails or
  causes unexpected results.
