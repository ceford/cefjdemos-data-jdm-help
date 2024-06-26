<!-- Filename: Help4.x:Workflows_List / Display title: Workflows-Liste -->

## Beschreibung

Die Publishing-Workflow-Komponente wird benutzt, um bestimmte Stadien
(unveröffentlicht, veröffentlicht, gelöscht und archiviert) durch einen
etwas allgemeineren Ansatz zu ersetzen. Auf diese Weise kann ein
maßgeschneiderter Ablaufplan einfach erzeugt werden, um die eigenen
Beiträge innerhalb einer Komponente zu handhaben.

Weitere Informationen sind auf der Seite
Workflow
zu finden.

## Wie darauf zugreifen

- Enable Workflows in
  **Content → Articles → Options → Integration Tab** from
  the Administrator menu. Then...
  - Select **Content → Workflows** in the Administrator menu.

## Screenshot

<img
src="https://docs.joomla.org/images/c/c8/Help-4x-components-workflows-list-en.png"
decoding="async" data-file-width="800" data-file-height="294"
width="800" height="294"
alt="components workflows list" />

## Column Headings

Click on the column heading to sort the list by that column's value.

- **Checkbox**. Check this box to select one or more items. To select
  all items, check the box in the column heading. After one or more
  boxes are checked, click a toolbar button to take an action on the
  selected item or items. Many toolbar actions, such as Publish and
  Unpublish, can work with multiple items. Others, such as Edit, only
  work on one item at a time. If multiple items are checked and you
  press Edit, the first item will be opened for editing.
- **Ordering.** You can change the order of an item within a list as
  follows:
  - If the list Filter Options include a Position filter select the
    desired Position. This will limit the list to items that are
    assigned to that Position.
  - Select the Ordering icon <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Ordering column header icon" /> in the Table
    heading to make it the active ordering item. The ordering icons in
    each row will change from light grey to dark grey and the pointer
    will change to a drag arrow on hover.
  - Select one of the Ordering icons <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Ordering drag icon" /> and
    drag it up or down to change the position of that row in the list.
    The items will display in the new order within the Position.
- **Status**. The published status of the item.
- **Name:** The (full) name of the user.
- **Default.** If there is more than one workflow. Select to set the
  default.
- **Stages.** The number of stages in the workflow. Select to view the
  stages list.
- **Transition.** The number of transitions. Select to view the
  transitions list.
- **ID**. This is a unique identification number for this item assigned
  automatically by Joomla. It is used to identify the item internally,
  and you cannot change this number. When creating a new item, this
  field displays "0" until you save the new entry, at which point a new
  ID is assigned to it.

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

- **Filter by published status.**

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Actions:** Reveals a list of actions for selected Items. Check one
  or more Item checkboxes to activate the list.
- **Enable**. Makes the selected item available for use on your website.
- **Disable**. Makes the selected items unavailable for use on your
  website.
- **Default:** Makes the selected item the default item. The default
  star symbol
  (<img src="https://docs.joomla.org/images/7/7e/Icon-16-default.png"
  decoding="async" data-file-width="30" data-file-height="20" width="30"
  height="20" alt="Icon 16 default.png" />) will show in the Default
  column, indicating that this is now the default item.
- **Check-In**. Checks-in the selected items. Works with one or multiple
  items selected.
- **Trash**. Changes the status of the selected items to indicate that
  they are trashed.Trashed items can still be recovered by selecting
  'Trashed' in the 'Select Status' filter and changing the status of the
  articles to Published or Unpublished as preferred.To permanently
  delete trashed items, select 'Trashed' in the 'Select Status' filter,
  select the items to be permanently deleted, then click the 'Empty
  Trash' toolbar icon.
- **Options.** Opens the Options window where settings such as default
  parameters can be edited.
- **Help**. Opens this help screen.
