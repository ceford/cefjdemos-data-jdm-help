<!-- Filename: Help4.x:Menu_Item:_Password_Reset / Display title: Menüeintrag: Passwort zurücksetzen -->

## Beschreibung

Der Menüeintragstyp **Password zurücksetzen** wird verwendet, um eine
Seite zu erstellen, die ein Formular zum Zurücksetzen des Passworts
enthält. Er fragt nach der mit dem Benutzerkonto verknüpften
E-Mail-Adresse und verschickt eine E-Mail mit einem Reset-Token an die
angegebene Adresse.

## Wie darauf zugreifen

Um einen neuen Menüeintrag *Passwort zurücksetzen* zu erstellen:

- Im Administrator-Menü **Menüs **→** „Name des Menüs“** auswählen
  (z.B.: **Menüs **→** Main Menu**). Dann ...
  - die Schaltfläche **+ Neu** in der Werkzeugleiste wählen. Dann...
  - in der Zeile: Menüeintragstyp, auf die Schaltfläche „Auswählen“
    klicken <img
    src="https://docs.joomla.org/images/thumb/1/1e/Help-4x-Menu-Item-Type-Select-Button-de.png/83px-Help-4x-Menu-Item-Type-Select-Button-de.png"
    decoding="async"
    srcset="https://docs.joomla.org/images/thumb/1/1e/Help-4x-Menu-Item-Type-Select-Button-de.png/125px-Help-4x-Menu-Item-Type-Select-Button-de.png 1.5x, https://docs.joomla.org/images/1/1e/Help-4x-Menu-Item-Type-Select-Button-de.png 2x"
    data-file-width="145" data-file-height="49" width="83" height="28"
    alt="Help-4x-Menu-Item-Type-Select-Button-de.png" />
  - Im modalen Fenster in der Liste „Benutzer“ anklicken und dann den
    Eintrag **Password zurücksetzen** wählen.

To edit an existing User Password Reset menu item:

- Select its Title in the Menus: Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/a/af/Help-4x-Menus-Menu-Item-User-Password-Reset-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Help-4x-Menus-Menu-Item-User-Password-Reset-en.png" />

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces. [Learn
  more.](https://docs.joomla.org/Alias/de "Special:MyLanguage/Alias/de")

### Details Tab

**Left Panel**

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window.** Select from the drop-down list.
- **Template Style.** Select from the drop-down list.

**Right Panel**

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
    height="23" alt="Help30-Ordering-colheader-icon.png" /> in the Table
    heading to make it the active ordering item. The ordering icons in
    each row will change from light grey to dark grey and the pointer
    will change to a drag arrow on hover.
  - Select one of the Ordering icons <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Help30-Ordering-colheader-grab-bar-icon.png" /> and
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
  1.  Click on the Home column of the desired menu item in the [Menus:
      Items](https://docs.joomla.org/Help4.x:Menus:_Items/de "Special:MyLanguage/Help4.x:Menus: Items/de")
      screen.
  2.  Open the menu item for the new default page and change the Default
      Page setting to Yes.
- **Access**. The [viewing Access
  Level](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/de "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/de")
  for this item.
- **Language**. Item language.
- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

### Common Options

See [Menus: Edit/New
Item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en "Help4.x:Menu Item: New Item/en")
for help on fields common to all Menu Item types located in the
following Tabs:

- **Link Type**
- **Page Display**
- **Metadata**
- **Associations**
- **Module Assignment**

## Toolbar

At the top of the page you will see the toolbar shown in the
[Screenshot](#Screenshot) above. The functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Save & New**. Saves the item and keeps the editing screen open and
  ready to create another item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Front End Screenshot

*Example Front End Site images are generic images using Joomla! core
installation supplied free Front End Templates. The actual view can
depend on the installed custom template used and the template's style
for those views on a Joomla! website.* User Password Reset shown:

<img
src="https://docs.joomla.org/images/6/65/Help-4x-Menus-Menu-User-Password-Reset-front-end-screenshot-en.png"
decoding="async" data-file-width="600" data-file-height="205"
width="600" height="205"
alt="Help-4x-Menus-Menu-User-Password-Reset-front-end-screenshot-en.png" />

## Related Information

|                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Related Help Screens                                                                                                                                              | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Users: Options](https://docs.joomla.org/Help4.x:Users:_Options/en "Help4.x:Users: Options/en")                                                                   | User Options configuration allows setting of parameters used globally for all users. Control the use of Captcha, registration allowed and type of registration, default user group new users, reset password or username counter, and new user registration email notice to administration.                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Users](https://docs.joomla.org/Help4.x:Users/en "Help4.x:Users/en")                                                                                              | The Users list is used to find, add, and edit users.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Users: Viewing Access Levels](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/en "Help4.x:Users: Viewing Access Levels/en")                         | In this screen you have the ability to look at a list of your Access Levels and sort them in different ways. You can also edit and create Access Levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [Users: Edit Viewing Access Level](https://docs.joomla.org/Help4.x:Users:_Edit_Viewing_Access_Level/en "Help4.x:Users: Edit Viewing Access Level/en")             | Access levels control which users can view which objects on your site. Objects include menu items, modules, categories, and component items (articles, contacts, and so on). Each object in the site is assigned to one access level. User groups are also assigned to each access level.If a user is a member of a group that in turn has permission for an access level, then that user can view all objects assigned to that access level. It is important to understand that user groups can be arranged in a parent-child hierarchy. If so, then a child group has access to all access levels that the parent group has access to. So you don't need to assign a child group access to levels that its parent group already has access to. |
| [Permissions for Group](https://docs.joomla.org/Help4.x:Permissions_for_Group/en "Help4.x:Permissions for Group/en")                                              | The Debug Permissions report maps out the exact permissions for any given user group across all assets on your Joomla! installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Permissions for User](https://docs.joomla.org/Help4.x:Permissions_for_User/en "Help4.x:Permissions for User/en")                                                 | The Debug Permissions report allows you to map out the exact permissions for any given user across all extensions on your Joomla installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Users: Groups](https://docs.joomla.org/Help4.x:Users:_Groups/en "Help4.x:Users: Groups/en")                                                                      | User Groups control what actions a user may take on the site and which objects a user can view. This screen allows you to create, view, edit, and delete User Groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [Users: New or Edit Group](https://docs.joomla.org/Help4.x:Users:_New_or_Edit_Group/en "Help4.x:Users: New or Edit Group/en")                                     | User groups play a central role in what a user can do and see on the site. Creating user groups is normally the first step in setting up the security system for your site.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Mass Mail Users](https://docs.joomla.org/Help4.x:Mass_Mail_Users/en "Help4.x:Mass Mail Users/en")                                                                | The Mass Mail screen allows Users who are members of the "Super Administrator" group to send an email message to registered users for the site. Users can be selected based on groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [Users: Edit Profile](https://docs.joomla.org/Help4.x:Users:_Edit_Profile/en "Help4.x:Users: Edit Profile/en")                                                    | In this screen, you have the ability to create a new user (if you clicked on the 'New' button in the User Manager), or edit an existing user (if you selected a user and clicked on the 'Edit' button in the User Manager, or clicked on the name of a user).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [User Notes: Categories](https://docs.joomla.org/Help4.x:User_Notes:_Categories/en "Help4.x:User Notes: Categories/en")                                           | This screen allows you to look at a list of your user note categories and sort them in different ways. You can also edit and create user note categories and access levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [User Notes: New or Edit Category](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit_Category/en "Help4.x:User Notes: New or Edit Category/en")             | This is where you can add a new Category or edit an existing Category. Categories are used to organize the User Notes. Categories allow you to display related User notes together on a page and to filter User Notes in the User Notes Manager. All User Notes are assigned either to a Category that you create or to the special Category called 'Uncategorized'.                                                                                                                                                                                                                                                                                                                                                                             |
| [User Notes](https://docs.joomla.org/Help4.x:User_Notes/en "Help4.x:User Notes/en")                                                                               | User notes are pieces of information which can be assigned to registered users on your Joomla! site. These notes can contain for example comments about 'offending' or 'difficult' users etc.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [User Notes:New or Edit](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit/en "Help4.x:User Notes: New or Edit/en")                                         | In this screen you can create an user note or edit an user note. The 'editor' will be the chosen 'editor' for the user editing the note. Examples: TinyMCE - JCE - Codemirror.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Menu Item: Password Reset](https://docs.joomla.org/Help4.x:Menu_Item:_Password_Reset/en "Help4.x:Menu Item: Password Reset/en")                                  | Used to create a form which allows a user to reset their password with an email sent to the user's email associated with the account.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [Menu Item: User Profile](https://docs.joomla.org/Help4.x:Menu_Item:_User_Profile/en "Help4.x:Menu Item: User Profile/en")                                        | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Menu Item: Edit User Profile](https://docs.joomla.org/Help4.x:Menu_Item:_Edit_User_Profile/en "Help4.x:Menu Item: Edit User Profile/en")                         | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Menu Item: Registration Form](https://docs.joomla.org/Help4.x:Menu_Item:_Registration_Form/en "Help4.x:Menu Item: Registration Form/en")                         | Used to create a default User Registration form for user registration. Default form contains basic information: Name, Username, Password, and Email Address.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [Menu Item: Username Reminder Request](https://docs.joomla.org/Help4.x:Menu_Item:_Username_Reminder_Request/en "Help4.x:Menu Item: Username Reminder Request/en") | Used to create a form which allows a user to request an e-mail with their username.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
