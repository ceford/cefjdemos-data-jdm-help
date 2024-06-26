<!-- Filename: Help4.x:Menu_Item:_List_Contacts_in_a_Category / Display title: Menüeintrag: Kontakte in einer Kategorie auflisten -->

## Beschreibung

The **List Contacts in a Category** menu item type is used to show
contacts in a given Category in a list layout. Settings include: Contact
Details, Contact Form, presentation(slider, tabs, plain view), and Email
subject and message filters.

## Wie darauf zugreifen

Um eine neue Kontaktliste in einem Kategorie-Menüeintrag zu erstellen:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**).
  - Select the **New** Toolbar button. Then...
  - Select the Menu Item Type Select button <img
    src="https://docs.joomla.org/images/d/d7/Help30-Menu-Item-Type-Select-Button-en.png"
    decoding="async" data-file-width="82" data-file-height="28" width="82"
    height="28" alt="Help30 Menu Item Type Select Button en.png" />
  - In the modal dialog select the Contacts item to open a list and then
    select the **List Contacts in a Category** item.

To edit an existing List Contacts in a Category menu item:

- Select its Title in the Menus: Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/8/85/Help-4x-Menus-Menu-Item-Contact-Category-screen-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Menus Menu Item Contact Category screen" />

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
- **Select a Category.** Select a contact category to display.
- **Target Window.** This determines how the new page will be opened.
  Options are:
  - *Parent* Open new menu item in parent window. This is the default.
  - *New Window With Navigation* Open menu item in a new window with
    full browser navigation (for example, "back" button).
  - *New Without Navigation* Open menu item in a new window without
    browser navigation.
- **Template Style.** Controls the template style for this menu item. A
  list box will show the available template styles for your site,
  similar to the following:

<img
src="https://docs.joomla.org/images/a/a6/Help-4x-menu-item-template-style-en.png"
decoding="async" data-file-width="600" data-file-height="118"
width="600" height="118"
alt="menu item template style" />

Select "Use Default" to use the default style for the site. Select a
specific template style to always show this menu item with that style.

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

### Category Tab

The Category Options control the way that category information is shown
in the layout. The Category List Layout has the following Category
Options, as shown below.

<img
src="https://docs.joomla.org/images/c/c6/Help-4x-Menus-Menu-Item-Contact-Category-category-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="417"
width="600" height="417"
alt="Menus Menu Item Contact Category category options parameters" />

- **Category Title.** (Use Global/Hide/Show) If Show, the Category Title
  will show as a subheading on the page. The subheading is usually
  displayed inside the "H2" tag.
- **Category Description**. (Use Global/Hide/Show) Show or hide the
  description of the selected Category.
- **Category Image.** (Use Global/Hide/Show) Whether to hide or show the
  category image.
- **Subcategory Levels.** (Use Global/All/1-5) The number of levels of
  subcategories to show in the layout. Select *All* to show all levels
  in the subcategory hierarchy.
- **Empty Categories.** (Use Global/Hide/Show) Whether to hide or show
  the categories that contain no content items or subcategories.
- **Subcategories Descriptions.** (Use Global/Hide/Show) Whether to hide
  or show the category description of subcategories.
- **\# Contacts in Category**. (Use Global/Hide/Show) Whether to hide or
  show the number of Contact in a Contact Category.

### List Layouts Tab

List Layout Options control the appearance of the list layout.

<img
src="https://docs.joomla.org/images/b/b4/Help-4x-Menus-Menu-Item-Contact-Category-category-list-layout-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="687"
width="600" height="687"
alt="Menus Menu Item Contact Category category list layout options parameters" />

- **Filter Field.** (Use Global/Hide/Show) The Filter Field creates a
  text field for the front-end user to enter some part of a contact name
  to search for.
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

- **Image**. (Use Global/Hide/Show) Show or hide an Image column in the
  list of Contacts.
- **Position.** (Use Global/Hide/Show) The position this contact holds
  in the organisation. For example CEO, Secretary, Janitor.
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
- **Sort by**. Choose the field name to sort.

### Contact Display Tab

Contact Display fields control the appearance of the list layout.

<img
src="https://docs.joomla.org/images/7/72/Help-4x-Menus-Menu-Item-Contact-Category-category-contact-display-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="691"
width="600" height="691"
alt="Menus Menu Item Contact Category category contact display options parameters" />

- **Choose a Layout.** Select from the list of templates.
- **Contact Category**. Set to control the Contacts Category display
  view.

The following options are available.

- *Use Global:* Use the default value from the contacts options screen.
- *Hide:* Do not show the Category name of the contacts.
- *Show Without Link:* Show Category name of contacts as heading styled
  text only.
- *Show With Link* Show Category name of contacts as heading styled text
  linked to Category.
- **Show Contacts List**. Allow the user to use a drop down list of all
  contacts in one contact category. Set one of the following options:
- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show to allow users to select a contact in a drop down list.
- *Hide:* Do not display the Contact list.
- **Tags**. Whether to hide or show any tags for this item.

**Common Contact Display Fields** are:

- **Name**. Display the contact's *Name*.
- **Contact's Position**. Display the contact's *Contact's Position*.
- **Email**. Display the contact's *Email*.
- **Street Address**. Display the contact's *Street Address*.
- **City or Suburb**. Display the contact's *City or Suburb*.
- **State or County**. Display the contact's *State or County*.
- **Postal Code**. Display the contact's *Postal Code*.
- **Country**. Display the contact's *Country*.
- **Telephone**. Display the contact's *Telephone*.
- **Mobile phone**. Display the contact's *Mobile phone*.
- **Fax**. Display the contact's *Fax*.
- **Webpage**. Display the contact's *Webpage*.
- **Misc. Information**. Display the contact's *Misc. Information*.
- **Image**. Display the contact's *Image*.
- **vCard**. Display the contact's *vCard*.
- **Show User Articles**. Display the contact's *Articles*.
- **\# Articles to List**. Display the contact's *Number of Articles*.
- **Show Links**. Display the contact's *additional links*. These could
  be links to Social Media accounts, such as Twitter, Facebook, Skype...

All of the **Common Contact Display Fields** have the following options
available:

- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show this field.
- *Hide:* Do not display this field.
- **Link Label**.
  Labels (5) to override shown link's label.

### Mail Options Tab

Contact Mail Options control the appearance of a Contact's
 → *Contact Form* if it is enabled.

<img
src="https://docs.joomla.org/images/1/1e/Help-4x-Menus-Menu-Item-Contact-Category-category-contact-mail-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="294"
width="600" height="294"
alt="Menus Menu Item Contact Category category contact mail options parameters" />

- **Contact Form**. Display the contact's *contact form*.
- **Send Copy to Submitter.** (Use Global/Hide/Show) Display the a check
  box to allow a Submitter to send a copy of email to themselves.
- **Session Check.** (Use Global/No/Yes) Check for the existence of
  session cookie. Users without cookies enabled will not be able to send
  emails.
- **Custom Reply.** (Use Global/No/Yes) Turn on or off the custom
  message reply to contact form's submitter.
- **Contact Redirect.** Enter alternative URL to redirect submitter
  after a successful contact form email was sent.

### Integration Tab

The List Contacts in a Category Menu Item has the following Integration
Options.

<img
src="https://docs.joomla.org/images/7/7c/Help-4x-Menus-Menu-Item-Contact-Category-integration-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="190"
width="600" height="190"
alt="Menus Menu Item Contact Category integration options parameters" />

These determine whether a news feed will be available for the page and
what information it will show.

- **Show Feed Link.** (Use Global/Hide/Show) Whether to Hide or Show a
  link to a news feed (RSS Feed). If set to Show, a Feed Link will show
  up as a feed icon in the address bar of most modern browsers.

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
- **Save & Close**. Saves the menu item and closes the current screen.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Quick Tips

- The Category List layout is a convenient way to list a compact
  directory of contacts in a category that can include filtering and
  searching.
