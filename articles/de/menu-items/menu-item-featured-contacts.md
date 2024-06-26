<!-- Filename: Help4.x:Menu_Item:_Featured_Contacts / Display title: Menüeintrag: Hauptkontakte -->

## Beschreibung

Der Menüeintrags-Typ **Hauptkontakte** wird verwendet, um eine Liste der
Hauptkontakte anzuzeigen.

## Wie darauf zugreifen

Um einen neuen Menüeintrag „Hauptkontakte“ zu erstellen:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the New button in the Toolbar. Then...
  - Select the Menu Item Type Select button <img
    src="https://docs.joomla.org/images/1/1e/Help-4x-Menu-Item-Type-Select-Button-de.png"
    decoding="async" data-file-width="145" data-file-height="49" width="145"
    height="49" alt="Menu Item Type Select Button" />
  - In the modal dialog select the Contacts item to open a list and then
    select the **Featured Contacts** item.

To edit an existing Featured Contacts menu item:

- Select its Title in the Menus: Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/8/84/Help-4x-Menus-Menu-Item-Contact-FeaturedContacts-screen-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Menus Menu Item Contact FeaturedContacts screen" />

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Details Tab

#### Left Panel

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window.** Select from the drop-down list.
- **Template Style.** Select from the drop-down list.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.
- **Parent Item.** The parent menu item for this menu item. Used to
  determine whether a Menu Item is a top-level item or a submenu item.
  Select 'Menu Item Root' (the default value) if this is a top-level
  Menu Item. Otherwise, select the Menu Item that is this item's parent.
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
- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter content ahead of time and then have it
  published automatically at a future time.
- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have content automatically changed to Unpublished
  state at a future time (for example, when it is no longer applicable).
- **Default Page**. If Yes, this menu item is the default or home page
  for the site. There must be exactly one menu item set as the default
  page. You can change the default page in two ways:
  1.  Click on the Home column of the desired menu item in the Menus: Items
      screen.
  2.  Open the menu item for the new default page and change the Default
      Page setting to Yes.
- **Access**. The viewing Access  Level   for this item.
- **Language**. Item language.
- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

### List Layouts Tab

List Layout Options control the appearance of the list layout.

<img
src="https://docs.joomla.org/images/9/95/Help-4x-Menus-Menu-Item-Contact-Category-list-layout-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="269"
width="600" height="269"
alt="Menus Menu Item Contact Category list layout options parameters" />

- **Display Select.** (Use Global/Hide/Show) Whether to hide or show the
  Display \# control that allows the user to select the number of items
  to show in the list. An example of how it is shown in the Front End
  (website) view below.

<img
src="https://docs.joomla.org/images/0/09/Help30-article-category-list-display-select-en.png"
decoding="async" data-file-width="198" data-file-height="125"
width="198" height="125"
alt="Help30 article category list display select en.png" />

If there are more items than this number, you can use the page
navigation buttons (Start, Prev, Next, End, and page numbers) to
navigate between pages. Note that if you have a large number of items,
it may be helpful to use the Filter options, located above the column
headings, to limit which items display.

- **Table Headings.** (Use Global/Hide/Show) Table Headings show a
  heading above a list, like generic heading image shown below.

<img
src="https://docs.joomla.org/images/8/8b/Help30-article-category-list-table-headings-en.png"
decoding="async" data-file-width="670" data-file-height="28" width="670"
height="28" alt="Help30 article category list table headings en.png" />

If set to *Show*, this heading will show above the list. If set to
*Hide*, the list will show with no headings.

- **Position**. Show or hide a Position column in the list of Contacts.
- **Email**. Set to control the Email's display in list.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show in list.
- *Hide:* Do not show in list.
- **Phone**. Set to control the Phone's display in list.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show in list.
- *Hide:* Do not show in list.
- **Mobile**. Set to control the Mobile's display in list.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show in list.
- *Hide:* Do not show in list.
- **Fax**. Set to control the Fax's display in list.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show in list.
- *Hide:* Do not show in list.
- **City or Suburb**. Set to control the City or Suburb's display in
  list.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show in list.
- *Hide:* Do not show in list.
- **State or County**. Set to control the State or County's display in
  list.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show in list.
- *Hide:* Do not show in list.
- **Country**. Set to control the Country's display in list.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show in list.
- *Hide:* Do not show in list.
- **Pagination.** Hide or Show Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page. An example is shown below.

<img src="https://docs.joomla.org/images/8/81/Help30-pagination-en.png"
decoding="async" data-file-width="299" data-file-height="29" width="299"
height="29" alt="Help30 pagination en.png" />

The following options are available.

- *Use Global:* Use the default value from the component options screen.
- *Auto:* Pagination links shown if needed.
- *Show:* Pagination links shown if needed.
- *Hide:* Pagination links not shown. Note: In this case, Users will not
  be able to navigate to additional pages.
- **Pagination Results.** Hide or Show the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.

### Form Tab

Form Options control the appearance of the list layout.

<img
src="https://docs.joomla.org/images/thumb/6/67/Help-4x-Menus-Menu-Item-Contact-featured-contact-form-parameters-en.png/600px-Help-4x-Menus-Menu-Item-Contact-featured-contact-form-parameters-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/67/Help-4x-Menus-Menu-Item-Contact-featured-contact-form-parameters-en.png/900px-Help-4x-Menus-Menu-Item-Contact-featured-contact-form-parameters-en.png 1.5x, https://docs.joomla.org/images/6/67/Help-4x-Menus-Menu-Item-Contact-featured-contact-form-parameters-en.png 2x"
data-file-width="1113" data-file-height="427" width="600" height="230"
alt="Menus Menu Item Contact featured contact form parameters" />

**Common Contact Form Fields** are:

- **Tags**. Display the contact's *Tags*.
- **Contact Information**. Display the contact's *Contact Information*.
- **vCard**. Display the contact's *vCard*.
- **Miscellaneous Information**. Display the contact's *Miscellaneous
  Information*.
- **User Articles**. Display the contact's *User Articles*.
- **\# Articles to List**. Display the contact's *\# Articles to List*.
- **Contact Links**. Display the contact's *Contact Links*.
- **Link Label**.
  Labels (5) to override shown link's label.

### Mail Options Tab

Contact Mail Options control the appearance of a Contact's
 → *Contact Form* if it is enabled.

<img
src="https://docs.joomla.org/images/8/8b/Help-4x-Menus-Menu-Item-Contact-Category-contact-mail-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="291"
width="600" height="291"
alt="Menus Menu Item Contact Category contact mail options parameters" />

- **Show Contact Form**. Display the contact's *contact form*.

It has the following options available:

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Display this.
- *Hide:* Do not display.
- **Send Copy to Submitter**. Display the a check box to allow a
  Submitter to send a copy of email to themselves.

It has the following options available:

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Display this.
- *Hide:* Do not display.
- **Session Check**. Check for the existence of session cookie. Users
  without cookies enabled will not be able to send emails.

It has the following options available:

- *Use Global:* Use the default value from the contacts options screen.
- *Yes:* Check for session cookie.
- *No:* Do not check for session cookie.
- **Custom Reply**. Turn on or off the custom message reply to contact
  form's submitter, allowing for Plugins to handle integration with
  other systems.

It has the following options available:

- *Use Global:* Use the default value from the contacts options screen.
- *Yes:* Send an automated reply email.
- *No:* Do not send an automated reply email.
- **Contact Redirect**. Enter alternative URL to redirect submitter
  after email is sent.

### Common Options

See Menus: Edit/New Item
for help on fields common to all Menu Item types located in the
following Tabs:

- **Link Type**
- **Page Display**
- **Metadata**
- **Associations**
- **Module Assignment**

## Toolbar

At the top of the page you will see the toolbar shown in the Screenshot
above. The functions are:

- **Save.** Saves the menu item and stays in the current screen.
- **Save & Close**. Saves the menu item and closes the current screen.
- **Save & New**. Saves the menu item and keeps the editing screen open
  and ready to create another menu item.
- **Save as Copy**. Saves your changes to a copy of the current menu
  item. Does not affect the current menu item. This toolbar icon is not
  shown if you are creating a new menu item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. Or
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Quick Tips

- In order to make your contact featured do one of the following: From
  the Contacts list,
  either click on the Featured symbol (circle with a star) in the
  Featured column, or click on the Item select check box and select
  Feature in the Actions drop-down list in the Toolbar. Several items
  can be selected to Feature or Unfeature via the Actions list.

<img
src="https://docs.joomla.org/images/5/56/Help-4x-Components-Contacts-Contacts-list-en.png"
decoding="async" data-file-width="800" data-file-height="329"
width="800" height="329"
alt="Components Contacts Contacts list" />
