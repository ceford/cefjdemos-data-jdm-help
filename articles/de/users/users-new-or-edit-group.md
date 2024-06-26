<!-- Filename: Help4.x:Users:_New_or_Edit_Group / Display title: Benutzer: Gruppe neu erstellen oder bearbeiten -->

## Beschreibung

Mit der Installation von Joomla! wird eine Reihe von Benutzergruppen
installiert, die für die Verwaltung von Standard-Sites geeignet sind.
Die Standardgruppen sollten nicht bearbeitet werden! Neue Gruppen können
für spezielle Zwecke erstellt werden. Zum Beispiel könnte eine Gruppe
erstellt werden, die nur den Zugriff auf eine einzelne Komponente
erlaubt.

## Wie darauf zugreifen

- Select **Users → Groups** from the Administrator menu. Then...
  - Select the **New** button from the Toolbar. Or...
  - Select a link from the **Group Title** column to edit an existing
    group.

## Screenshot

<img
src="https://docs.joomla.org/images/3/33/Help-4x-users-user-manager-add-new-user-group-en.png"
decoding="async" data-file-width="600" data-file-height="281"
width="800" height="375"
alt="users user manager add new user group" />

## User Group Details

- **Group Title:** Enter a Title for the Group.
- **Group Parent:**
  (*Public*/*Guest*/*Manager*/*Administrator*/*Registered*/*Author*/*Editor*/...).
  Choose a Parent for this Group.

User Groups control what actions a user can take on the site. Actions
include things like creating a new article, changing options for a
component, or logging in. The site administrator assigns permissions for
various actions to each group. Permissions for actions can be assigned
at different levels in the component hierarchy (Global Configuration,
component options, categories, and articles). If a user does not have
permission for a given action, the user cannot perform that action.

User groups also control which objects a user can view on the site.
Objects include categories, articles, modules, menu items, and others.
When you create an access level, one or more user groups are assigned to
it. Then, when you create an object (such as a menu item or module), the
object is assigned an access level. If a user is a member of a group
that is assigned to an access level, this user can view any object
assigned to that access level. If not, then that user cannot view that
object.

User groups can be arranged in a hierarchy. If so, then all child groups
inherit the action permissions and access levels of a parent group. If
used wisely, this feature can save a lot of time setting up your
security system, since it means that you don't have to enter duplicate
setup information.

## Toolbar

At the top you will see the toolbar shown in the Screenshot above. The
functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Save & New**. Saves the item and keeps the editing screen open and
  ready to create another item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Quick tips

- If a new group will have similar permissions to an existing group, you
  can save work by making the new group a child of the existing group.
  That way, you only need to change the permissions that are different
  for the new group.
