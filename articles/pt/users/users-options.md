<!-- Filename: Help4.x:Users:_Options / Display title: Utilizadores: Opções -->

## Descrição

User Options set globally for all users include

- Captcha,
- registration allowed and type of registration,
- default user group for new users,
- reset password or username counter,
- new user registration email notice to administration and more.

## Como Aceder
Selecione **Utilizadores → Gerir**

- click the **Options** toolbar button

## Captura de Ecrã

<img
src="https://docs.joomla.org/images/thumb/9/9d/Help-4x-Users-Options-screen-en.png/800px-Help-4x-Users-Options-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9d/Help-4x-Users-Options-screen-en.png/1200px-Help-4x-Users-Options-screen-en.png 1.5x, https://docs.joomla.org/images/thumb/9/9d/Help-4x-Users-Options-screen-en.png/1600px-Help-4x-Users-Options-screen-en.png 2x"
data-file-width="2400" data-file-height="1500" width="800" height="500"
alt="Users Options screen" />

## Dos Campos

### Utilizadores - Opções

- **Permitir o registo de novos utilizadores**.
  - Sim: Users can register from the Frontend of the site using the
    'Create an Account' link provided on the
    <a href="https://docs.joomla.org/Help4.x:Site_Modules:_Login/pt"
    class="new"
    title="Special:MyLanguage/Help4.x:Site Modules: Login/pt (page does not exist)">Login
    module</a>.
  - Não: The 'Create an Account' link will not show.
- **Grupo para novos utilizadores**. The
  <a href="https://docs.joomla.org/Help4.x:Users:_Groups/pt" class="new"
  title="Special:MyLanguage/Help4.x:Users: Groups/pt (page does not exist)">group</a>
  that users are assigned to by default when they register on the site.
  Defaults to 'Registered'.
- **Grupo para convidados**. The group that guests are assigned to
  (Guests are visitors to the site who are not logged in). It is
  possible to create content on the site that is visible to guests but
  not visible to logged in users.
- **Enviar senha**. If set to 'Yes' the user's first password will be
  emailed to the user as part of the registration mail.
- **Ativação de novos utilizadores**.
  - Nenhum: A conta do utilizador irá estar ativa imediatamente sem ser
    necessária nenhuma ação.
  - Próprio: User will receive an email with an activation link. The
    account will be activated when the user clicks the activation link.
  - Administração: User will receive an email with an activation link.
    When the user clicks this link, the Site Admin will be notified via
    email and the Site Admin needs to activate the user's account.
- **Enviar email de notificação aos administradores**. Send email
  notification to administrators with 'New User Account Activation' set
  to 'None' or 'Self'.
- **Captcha**. Use
  <a href="https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt"
  class="new"
  title="Special:MyLanguage/Help4.x:Site Global Configuration/pt (page does not exist)">Captcha</a>
  for User Account Registration, User Password reminder and Username
  reminder.
- **Parâmetros de utilizadores da área de visitantes**.
  - Exibir: Users will be able to modify their
    <a href="https://docs.joomla.org/Help4.x:Users:_Edit_Profile/pt"
    class="new"
    title="Special:MyLanguage/Help4.x:Users: Edit Profile/pt (page does not exist)">Basic
    Settings</a> from the Frontend of the site.
  - Ocultar: User will not be able to change these settings.
  - Idioma da área de visitantes. Default site language.
- **Alterar o nome de utilizador**. Allow user to change Username.

### Opções de domínio do email

<img
src="https://docs.joomla.org/images/thumb/5/58/Help-4x-Users-Options-email-domain-subscreen-en.png/600px-Help-4x-Users-Options-email-domain-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/58/Help-4x-Users-Options-email-domain-subscreen-en.png/900px-Help-4x-Users-Options-email-domain-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/5/58/Help-4x-Users-Options-email-domain-subscreen-en.png/1200px-Help-4x-Users-Options-email-domain-subscreen-en.png 2x"
data-file-width="2002" data-file-height="1074" width="600" height="322"
alt="Users Options email domain subscreen" />

- **Nome de domínio**. Adicione uma lista de domínios de endereços de
  email permitidos e não permitidos. Por padrão, todos os domínios são
  permitidos.Pode utilizar asteriscos (\*). Por exemplo:
  - \* (Asteriscos): Permite ou não todos os domínios,
  - \*.com: Permite ou não todos os domínios em '.com',
  - \*.joomla.org: Permite ou não todos os subdomínios pertencentes a
    'joomla.org'.
- **Regra** Selecione se deseja permitir ou bloquear o domínio.

### Opções de senha

<img
src="https://docs.joomla.org/images/thumb/1/17/Help-4x-Users-Options-password-subscreen-en.png/600px-Help-4x-Users-Options-password-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/17/Help-4x-Users-Options-password-subscreen-en.png/900px-Help-4x-Users-Options-password-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/1/17/Help-4x-Users-Options-password-subscreen-en.png/1200px-Help-4x-Users-Options-password-subscreen-en.png 2x"
data-file-width="2001" data-file-height="1231" width="600" height="369"
alt="Users Options password subscreen" />

- **Máximo de reposições**. The maximum number of password resets
  allowed within the time period. Zero indicates no limit.
- **Tempo de reposição (horas)**. The time period, in hours, for the
  reset counter.
- **Mínimo de caracteres**. Set the minimum lenght for a password.
- **Mínimo de números**. Set the minimum number of integers that must be
  included in a password.
- **Mínimo de símbolos**. Set the minimum number of symbols (such
  as !@#\$) required in a password.
- **Mínimo de maiúsculas**. Set the minimum number of upper case
  alphabetical characters required for a password.
- **Mínimo de minúsculas**. Set the minimum number of lower case
  alphabetical characters required for a password.

### Multi-factor Authentication

<img
src="https://docs.joomla.org/images/thumb/4/4f/Help-4x-Users-Options-multi-factor-authentication-subscreen-en.png/600px-Help-4x-Users-Options-multi-factor-authentication-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4f/Help-4x-Users-Options-multi-factor-authentication-subscreen-en.png/900px-Help-4x-Users-Options-multi-factor-authentication-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/4/4f/Help-4x-Users-Options-multi-factor-authentication-subscreen-en.png/1200px-Help-4x-Users-Options-multi-factor-authentication-subscreen-en.png 2x"
data-file-width="2003" data-file-height="1518" width="600" height="455"
alt="Users Options multi factor authentication subscreen" />

- **Allowed frontend module positions**. When displaying the frontend
  Multi-factor Authentication page all modules will be hidden except
  those in the positions selected here.
- Show title in frontendLanguages: Overrides.
- **Allowed backend module positions**. When displaying the backend
  Multi-factor Authentication page all modules will be hidden except
  those in the positions selected here. Please note that modules in the
  'title' position are always shown: this is required to show the
  backend page icon and title.
- **Disable Multi-factor Authentication**. Any user who belongs in *any*
  of the selected user groups will be exempt from Multi-factor
  Authentication. Even if they have set up Multi-factor Authentication
  methods they will not be asked to use them when they are logging in,
  nor will they be able to view them, remove them, or change their
  configuration.
- **Enforce Multi-factor Authentication**. Any user who belongs in *any*
  of the selected user groups will be required to enable Multi-factor
  Authentication before being able to use the site.
- **Frontend template style**. Choose the frontend template style to use
  in the Multi-factor Authentication page. Select 'Use Default" to use
  the default site template style.
- **Multi-factor Authentication after silent login**. Should the user
  have to go through Multi-factor Authentication after a silent user
  login? Silent logins are those which do not require a username and
  password for example the Remember Me feature, WebAuthn etc.
- **Silent login authentication response types (for experts)**. For
  experts. A comma–separated list of Joomla authentication response
  types which are considered silent logins. The default is 'cookie' (the
  Remember Me feature) and 'passwordless' (WebAuthn).
- **Onboard new users**. If the user has not yet set up Multi-factor
  Authentication and this option is enabled they will be redirected to
  the Multi-factor Authentication setup page or the custom URL you set
  up below. This is meant to be a simple way to to let your users know
  that Multi-factor Authentication is an option on your site.
- **Custom redirection URL**. If it's not empty redirects to this URL
  instead of the Multi-factor Authentication setup page when the option
  above is enabled.Warning: This must be a URL inside your site. You
  cannot log in to an external link or to a different subdomain.

### Notas de utilizador - Histórico

<img
src="https://docs.joomla.org/images/thumb/7/70/Help-4x-Users-Options-user-notes-history-subscreen-en.png/600px-Help-4x-Users-Options-user-notes-history-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/70/Help-4x-Users-Options-user-notes-history-subscreen-en.png/900px-Help-4x-Users-Options-user-notes-history-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/7/70/Help-4x-Users-Options-user-notes-history-subscreen-en.png/1200px-Help-4x-Users-Options-user-notes-history-subscreen-en.png 2x"
data-file-width="2002" data-file-height="564" width="600" height="169"
alt="Users Options user notes history subscreen" />

- **Ativar versões**. Save version history for User Notes.
- **Número máximo de versões**. The maximum number of versions to store
  for a User Note. If a User Note is saved and the maximum number of
  versions has been reached, the oldest version will be deleted
  automatically. If set to 0, then versions will never be deleted
  automatically.Learn more.

### Email em massa a utilizadores

<img
src="https://docs.joomla.org/images/thumb/5/5f/Help-4x-Users-Options-mass-mail-users-subscreen-en.png/600px-Help-4x-Users-Options-mass-mail-users-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/5f/Help-4x-Users-Options-mass-mail-users-subscreen-en.png/900px-Help-4x-Users-Options-mass-mail-users-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/5/5f/Help-4x-Users-Options-mass-mail-users-subscreen-en.png/1200px-Help-4x-Users-Options-mass-mail-users-subscreen-en.png 2x"
data-file-width="2002" data-file-height="878" width="600" height="263"
alt="Users Options mass mail users subscreen" />

- **Prefixo de assunto**. Enter optional text to be inserted
  automatically before the subject of the mass email.
- **Sufixo de conteúdo do email**. Enter optional text to be inserted
  automatically after the body of the email (for example, a signature).

### Integração

<img
src="https://docs.joomla.org/images/thumb/f/f9/Help-4x-Users-Options-integration-subscreen-en.png/600px-Help-4x-Users-Options-integration-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f9/Help-4x-Users-Options-integration-subscreen-en.png/900px-Help-4x-Users-Options-integration-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/f/f9/Help-4x-Users-Options-integration-subscreen-en.png/1200px-Help-4x-Users-Options-integration-subscreen-en.png 2x"
data-file-width="2002" data-file-height="593" width="600" height="178"
alt="Users Options integration subscreen" />

- **Editar campos personalizados**. Enable the creation of custom
  fields.

### Permissões

This section lets you set up the default Access Control List
permissions for all users.

<img
src="https://docs.joomla.org/images/thumb/f/f8/Help-4x-Users-Options-permissions-subscreen-en.png/600px-Help-4x-Users-Options-permissions-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f8/Help-4x-Users-Options-permissions-subscreen-en.png/900px-Help-4x-Users-Options-permissions-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/f/f8/Help-4x-Users-Options-permissions-subscreen-en.png/1200px-Help-4x-Users-Options-permissions-subscreen-en.png 2x"
data-file-width="2002" data-file-height="1496" width="600" height="448"
alt="Users Options permissions subscreen" />

To change the permissions for users, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Configurar lista de controlo de acessos e opções**. Users can
      edit the options and permissions.
    - **Configurar opções**. Users can edit the options exept the
      permissions.
    - **Aceder à interface administrativa**. Users can access user
      administration interface.
    - **Criar**. Users can create users.
    - **Eliminar**. Users can delete users.
    - **Editar**. Users can edit users.
    - **Editar estatuto**. User can change the published state and
      related information.
    - **Editar valor de campo personalizado**. Users can edit any value
      of custom fields submitted in users.
3.  Select the desired permission for the action you wish to change.
    - **Herdado**. Inherited for users in this Group from the
      <a href="https://docs.joomla.org/Help4.x:Site_Global_Configuration/pt"
      class="new"
      title="Special:MyLanguage/Help4.x:Site Global Configuration/pt (page does not exist)">Global
      Configuration</a> permissions.
    - **Permitido**. Allowed for users in this Group.Note: If this
      action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Negado**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Barra de Ferramentas

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Guardar**. Saves the users options and stays in the current screen.
- **Guardar e fechar**. Saves the users options and closes the current
  screen.
- **Fechar**. Fecha o ecrã atual e volta ao ecrã anterior sem guardar
  quaisquer modificações que tenham sido efetuadas.
- **Toggle Inline Help**. Show help text below some options.
- **Ajuda**. Opens this help screen.

## Dicas Rápidas

If you are a beginning user, you can just keep the default values here
until you learn more about using global options.

## Informação relacionada

|                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ecrãs de Ajuda Relacionados                                                                                                                                       | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| <span class="mw-selflink selflink">Utilizadores: Opções</span>                                                                                                    | User Options configuration allows setting of parameters used globally for all users. Control the use of Captcha, registration allowed and type of registration, default user group new users, reset password or username counter, and new user registration email notice to administration.                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Users:**                                                                                             | The Users list is used to find, add, and edit users.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Users: Viewing Access Levels                         | In this screen you have the ability to look at a list of your Access Levels and sort them in different ways. You can also edit and create Access Levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Users: Edit Viewing Access Level. Each object in the site is assigned to one access level. User groups are also assigned to each access level.If a user is a member of a group that in turn has permission for an access level, then that user can view all objects assigned to that access level. It is important to understand that user groups can be arranged in a parent-child hierarchy. If so, then a child group has access to all access levels that the parent group has access to. So you don't need to assign a child group access to levels that its parent group already has access to. |
| Permissions for Group                                              | The Debug Permissions report maps out the exact permissions for any given user group across all assets on your Joomla! installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Permissions for User                                                 | The Debug Permissions report allows you to map out the exact permissions for any given user across all extensions on your Joomla installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Users: Groups                                                                      | User Groups control what actions a user may take on the site and which objects a user can view. This screen allows you to create, view, edit, and delete User Groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Users: New or Edit Group                                     | User groups play a central role in what a user can do and see on the site. Creating user groups is normally the first step in setting up the security system for your site.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Mass Mail Users                                                                | The Mass Mail screen allows Users who are members of the "Super Administrator" group to send an email message to registered users for the site. Users can be selected based on groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Users: Edit Profile.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| User Notes: Categories                                           | This screen allows you to look at a list of your user note categories and sort them in different ways. You can also edit and create user note categories and access levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| User Notes: New or Edit Category             | This is where you can add a new Category or edit an existing Category. Categories are used to organize the User Notes. Categories allow you to display related User notes together on a page and to filter User Notes in the User Notes Manager. All User Notes are assigned either to a Category that you create or to the special Category called 'Uncategorized'.                                                                                                                                                                                                                                                                                                                                                                             |
| User Notes                                                                               | User notes are pieces of information which can be assigned to registered users on your Joomla! site. These notes can contain for example comments about 'offending' or 'difficult' users etc.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| User Notes:New or Edit                                         | In this screen you can create an user note or edit an user note. The 'editor' will be the chosen 'editor' for the user editing the note. Examples: TinyMCE - JCE - Codemirror.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Menu Item: Password Reset                                  | Used to create a form which allows a user to reset their password with an email sent to the user's email associated with the account.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Menu Item: User Profile                                        | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Menu Item: Edit User Profile                         | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Menu Item: Registration Form                         | Used to create a default User Registration form for user registration. Default form contains basic information: Name, Username, Password, and Email Address.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Menu Item: Username Reminder Request | Used to create a form which allows a user to request an e-mail with their username.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
