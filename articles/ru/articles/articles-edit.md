<!-- Filename: Help4.x:Articles:_Edit / Display title: Материалы: Создание материала -->

## Описание

This screen is used to add a new or edit a existing Article, usually
using a Wysiwyg editor. The default editor is TinyMCE but if other
editors are installed the default editor may be set to something else
for the site as a whole or for individual users.

Most parameters have suitable defaults but you might wish to set a
specific Category or provide article-specific Metadata.

## Как открыть

**Контент → Материалы**

To add a Article:

- click the **New** toolbar button

To edit a Article:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/8/84/Help-4x-content-article-manager-add-new-article-en.png/800px-Help-4x-content-article-manager-add-new-article-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/84/Help-4x-content-article-manager-add-new-article-en.png/1200px-Help-4x-content-article-manager-add-new-article-en.png 1.5x, https://docs.joomla.org/images/thumb/8/84/Help-4x-content-article-manager-add-new-article-en.png/1600px-Help-4x-content-article-manager-add-new-article-en.png 2x"
data-file-width="2880" data-file-height="1584" width="800" height="440"
alt="content article manager add new article" />

## Form Fields

- **Заголовок**. The Title for this article.
- **Алиас**. The internal name of this article. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Материал

#### Left Panel

- **Текст материала**. This is where you enter the contents of the
  article. Joomla includes 3 editors, the default Editor - TinyMCE
  is shown here.

<img
src="https://docs.joomla.org/images/thumb/7/7a/Help-4x-Article-Editor-buttons-ru.png/600px-Help-4x-Article-Editor-buttons-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7a/Help-4x-Article-Editor-buttons-ru.png/900px-Help-4x-Article-Editor-buttons-ru.png 1.5x, https://docs.joomla.org/images/thumb/7/7a/Help-4x-Article-Editor-buttons-ru.png/1200px-Help-4x-Article-Editor-buttons-ru.png 2x"
data-file-width="1966" data-file-height="758" width="600" height="231"
alt="Article Editor buttons" />

The CMS Content dropdown list provides for access to link to an Article,
Contact, Field, Media, Menu, or Module.



- **Выключить редактор**. A Toggle Editor button show below the edit
  window. This button allows you to toggle between TinyMCE and Editor - None.

#### Right Panel

- **Состояние**. The published status of this article.
  - Опубликовано: Article is visible in the Frontend of the site.
  - Не опубликовано: Article is will not be visible to guests in the
    Frontend of the site. It may be visible to logged in users who have
    edit state permission for the article.
  - В архиве: Article will no longer show on menu items
    or [Category
    List.](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/en "Help4.x:Menu Item: Category List/en")
  - В корзине: Article is deleted from the site but still in the
    database.
- **Категория**. Select the Category for this article.
- **Избранный**. Select Yes if article will be shown in the Featured menu item
- **Доступ**. Select the viewing access level for this article. The
  access levels depend on what has been set up in Users: Access Levels.
- **Язык**. Select the language for this article. Keep the default of
  'All' if you are not using the multi-language feature.
- **Теги**. Assign tags to this article. You may select a tag from a
  pre-defined list or
  enter a new tag by typing the name in the field and pressing enter.
- **Примечание**. This is normally for the administrator's use (for
  example, to document information about this article) and does not show
  in the Frontend.
- **Примечание версии**. Optional field to identify the version of this
  article in the article's Version History.

### Изображения и ссылки

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
This section lets you display images and links in your articles using
standardised layouts.

<img
src="https://docs.joomla.org/images/thumb/7/7a/Help-4x-screenshot-article-edit-images-links-ru.png/600px-Help-4x-screenshot-article-edit-images-links-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7a/Help-4x-screenshot-article-edit-images-links-ru.png/900px-Help-4x-screenshot-article-edit-images-links-ru.png 1.5x, https://docs.joomla.org/images/thumb/7/7a/Help-4x-screenshot-article-edit-images-links-ru.png/1200px-Help-4x-screenshot-article-edit-images-links-ru.png 2x"
data-file-width="2880" data-file-height="1244" width="600" height="259"
alt="screenshot article edit images links" />

**Изображение вводного текста**

- **Изображение вводного текста**. Click the Select button to select an
  image to be displayed in a fixed location in the Intro Text of this
  article. This will open a window that allows you to select an image
  from your images folder.
- **Описание**. Set the alt attribute for this image. A few descriptive
  words for screen readers.
- **Без описания**. Check in the rare instance of a purely decorative
  image. Note that if the Image Description is empty and the No
  Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **CSS-класс**. Введите CSS-класс изображения для стилизации. Например,
  для позиционирования изображения вы можете использовать классы \$1,
  \$2.

- **Подпись**. Create a caption for this image.

**Изображение полного текста**

- **Изображение полного текста**. Click the Select button to select an
  image to be displayed in a fixed location in the Full Text of this
  article. This will open a window that allows you to select an image
  from your images folder.
- **Описание**. Set the alt attribute for this image. A few descriptive
  words for screen readers.
- **Без описания**. Check in the rare instance of a purely decorative
  image. Note that if the Image Description is empty and the No
  Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **CSS-класс**. Введите CSS-класс изображения для стилизации. Например,
  для позиционирования изображения вы можете использовать классы \$1,
  \$2.

- **Подпись**. Enter an optional caption for this image.

**URL ссылки A**

- **URL ссылки A**. The URL for the first link to be displayed in a
  fixed location in the article text. This must be a full URL, not
  relative. For example, it normally would start with 'https://'.
- **Заголовок ссылки A**. The text used for Link A. If blank, the URL
  will be displayed.
- **Окно браузера**. Sets the default value for the target for the first
  Link in this article. Choices are:
  - Родительское окно: Opens the in the main browser window, replacing
    the current Joomla article.
  - Новое окно: Opens the link in a new browser window.
  - Всплывающее окно: Opens the link in a pop-up browser window (without
    full navigation controls).
  - Модальное окно: Opens the link in a modal pop-up window.

**URL ссылки B**, **URL ссылки C**: Same options as Link A.

### Отображение

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
This is a set of options you can use to control how this article will
show in the Frontend.

<img
src="https://docs.joomla.org/images/thumb/c/c9/Help-4x-screenshot-article-edit-article-options-ru.png/600px-Help-4x-screenshot-article-edit-article-options-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c9/Help-4x-screenshot-article-edit-article-options-ru.png/900px-Help-4x-screenshot-article-edit-article-options-ru.png 1.5x, https://docs.joomla.org/images/thumb/c/c9/Help-4x-screenshot-article-edit-article-options-ru.png/1200px-Help-4x-screenshot-article-edit-article-options-ru.png 2x"
data-file-width="2880" data-file-height="1244" width="600" height="259"
alt="screenshot article edit article options" />

**Макет**

- **Макет**. Use a layout from the supplied article view or overrides in the templates.
- **Заголовок**. Show the Article's Title.
- **Заголовок как ссылка**. Show the title as a link to the article.
- **Теги**. Enter tags for this article. Select existing tags by
  entering in the first few letters or create new tags by entering them
  here.
- **Вводный текст**.
  - Показать: The Intro Text of the article will show when you drill
    down to the article.
  - Скрыть: Only the part of the article after the Read More break will
    show.
- **Позиция информации о материале**.
  - Сверху: Puts the article information block above the text.
  - Снизу: Puts the article information block below the text.
  - Разделить: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Заголовок информации о материале**. Displays 'Details' on top of the
  article information block.

**Категория**

- **Категория**. Show the Article's Category Title.
- **Категория как ссылка**. Show the title as a link to that Category.
- **Заголовок родительской категории**. Show the Article's Parent
  Category Title.
- **Родительская категория как ссылка**. Show the title as a link to
  that Category.

**Связи**

- **Языковые связи**. Show the associated flags or Language Code.
  Multilingual only.

**Автор**

- **Автор**. Show the author of the Article.
- **Автор как ссылка**. Show it as a link to a Contact layout for that
  author.Note: The author must be set up as a Contact.

**Дата**

- **Дата создания**. Show the Article's create date.
- **Дата изменения**. Show the Article's modify date.
- **Дата публикации**. Show the Article's start publishing date.

**Параметры**

- **Ссылки "Назад/Вперед"**. Show a navigation link 'Prev' or 'Next'
  when you drill down to the article.
- **Количество просмотров**. Show the number of times the article has
  been displayed by a user.
- **Неавторизованные ссылки**. If Yes, the Intro Text for restricted
  articles will show. Clicking on the Read more link will require users
  to log in to view the full article content.
- **Позиция ссылок.**
  - Сверху: Links are shown above the content.
  - Снизу: Links are shown below the content.
- **Текст вместо "Подробнее"**. Customise the text that shows for the
  default wording 'Read more'.
- **Заголовок страницы в браузере**. Text for the Browser page title to
  be used when the article is viewed with a non-article menu item. If
  blank, the article's title is used instead.

### Поля

This section shows the custom fields
which are defined for this article.

<img
src="https://docs.joomla.org/images/thumb/d/dc/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-ru.png/600px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/dc/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-ru.png/900px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/d/dc/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-ru.png/1200px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="730" width="600" height="152"
alt="Content Article Manager Edit Fields options subscreen" />

### Публикация

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
This section allows you to enter parameters and
Metadata
for this Article.

<img
src="https://docs.joomla.org/images/thumb/c/c4/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-ru.png/600px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c4/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-ru.png/900px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/c/c4/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-ru.png/1200px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1244" width="600" height="259"
alt="Content Article Manager Edit publishing options subscreen" />

**Публикация**

- **Начало публикации**. Date and time to start publishing. Enter
  article ahead of time and then have it published automatically at a
  future time.
- **Завершение публикации**. Date and time to finish publishing. The
  article is automatically changed to Unpublished state at a future
  time.
- **Начало избранного**. Date and time to start featured state. Enter
  article ahead of time and then have it featured automatically at a
  future time.
- **Завершение избранного**. Date and time to finish featured state. The
  article is automatically changed to Unfeatured state at a future time.
- **Дата создания**. The current time when the Article was created.
  Enter in a different date and time or click on the calendar icon to
  find the desired date.
- **Автор**. Name of the User who created this Article. This will
  default to the currently logged-in user. If you want to change this to
  a different user, click the Select User button.
- **Псевдоним автора**. Enter in an alias for the Author of this
  Article. This allows you to display a different Author name.
- **Дата изменения**. Date of last modification.
- **Изменил**. Username who performed the last modification.
- **Версия**. Number of revisions to this Article.
- **Кол-во просмотров**. The number of times this Article has been
  viewed.
- **ID**. A unique identification number for this Article, you cannot
  change this number. When creating a new Article, this field displays
  "0" until you save the new entry.

**Метаданные**

- **Метатег Description**. An paragraph to be used as the description of
  the page.
- **Ключевые слова**. Entry for keywords.
- **Метатег Robots**. The instructions for web 'robots' that browse to
  this page. Set 'Use Global' in Global Configuration.
- **Автор**. Entry for an Author name within the metadata.
- **Метатег Rights**. Describe what rights others have to use this
  content.

### Связи

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
Tab is shown on Multilingual Sites
only.

<img
src="https://docs.joomla.org/images/thumb/5/5d/Help-4x-screenshot-article-edit-associations-ru.png/600px-Help-4x-screenshot-article-edit-associations-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/5d/Help-4x-screenshot-article-edit-associations-ru.png/900px-Help-4x-screenshot-article-edit-associations-ru.png 1.5x, https://docs.joomla.org/images/thumb/5/5d/Help-4x-screenshot-article-edit-associations-ru.png/1200px-Help-4x-screenshot-article-edit-associations-ru.png 2x"
data-file-width="2880" data-file-height="1244" width="600" height="259"
alt="screenshot article edit associations" />

### Форма

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.

<img
src="https://docs.joomla.org/images/thumb/0/07/Help-4x-screenshot-article-edit-configure-edit-screen-ru.png/600px-Help-4x-screenshot-article-edit-configure-edit-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/07/Help-4x-screenshot-article-edit-configure-edit-screen-ru.png/900px-Help-4x-screenshot-article-edit-configure-edit-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/0/07/Help-4x-screenshot-article-edit-configure-edit-screen-ru.png/1200px-Help-4x-screenshot-article-edit-configure-edit-screen-ru.png 2x"
data-file-width="2880" data-file-height="1140" width="600" height="238"
alt="screenshot article edit configure edit screen" />

- **Публикация**. If Hide, the Publishing Options tab
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Отображение**. If Hide, the Article Options tab
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Изображения и ссылки (панель управления)**. If Yes, the [Images and
  Links
  tab](https://docs.joomla.org/Help4.x:Articles:_Edit/en#imagesandlinks "Help4.x:Articles: Edit/en")
  will show.
- **Изображения и ссылки (сайт)**. If Yes, the Images and Links tab will
  show in the Frontend article editor screen.

### Права доступа

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
This is where you can enter permissions for this article.

<img
src="https://docs.joomla.org/images/thumb/7/7e/Help-4x-screenshot-article-edit-permissions-ru.png/600px-Help-4x-screenshot-article-edit-permissions-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7e/Help-4x-screenshot-article-edit-permissions-ru.png/900px-Help-4x-screenshot-article-edit-permissions-ru.png 1.5x, https://docs.joomla.org/images/thumb/7/7e/Help-4x-screenshot-article-edit-permissions-ru.png/1200px-Help-4x-screenshot-article-edit-permissions-ru.png 2x"
data-file-width="2880" data-file-height="1244" width="600" height="259"
alt="screenshot article edit permissions" />

To change the permissions for this article, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Удалить**. Users can delete this article.
    - **Редактировать**. Users can edit this article.
    - **Изменить состояние**. User can change the published state and
      related information for this article.
3.  Select the desired permission for the action you wish to change.
    - **Унаследовано**. Inherited for users in this Group from the
      Global Configuration,
      Articles Options,
      or Articles Category.
    - **Разрешено**. Allowed for users in this Group.Note: If this
      action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Запрещено**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Панель инструментов

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Сохранить**. Saves the article and stays in the current screen.
- **Сохранить и закрыть**. Saves the article and closes the current
  screen.
  - **Сохранить и создать**. Saves the article and keeps the editing
    screen open and ready to create another article.
  - **Сохранить в меню**. Saves the article to a menu item and opens the
    menu item screen.
  - **Сохранить как копию**. Saves your changes to a copy of the current
    article. Does not affect the current article.
- **Закрыть**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Версии**. Opens the Article Version History window to show any prior
  versions of this article. This allows you to view older versions of
  this article and, if desired, restore from an older version.
- **Просмотреть**. Opens a modal dialog showing a site view of this
  article. Requires shared sessions
  or being logged in into the Frontend.
- **Проверить доступность**. Opens a window showing accessibility check
  results of the article.
- **Связать элемент**. With a specific language set for an article,
  allows side by side editing in another language. This icon is shown on
  Multilingual Sites
  only.
- **Подсказки**. Show help text below some options.
- **Справка**. Opens this help screen.

## Быстрые советы

- There are 2 methods to insert an image into article using the TinyMCE
  editor.
  1.  The CMS Content
      dropdown list provides access to the Media screen
      that lets you browse image files and upload images.
  2.  The 'Insert' dropdown list is a simple form for which you need to
      know the image url. It is used for external images.
- **Read more**
  breaks allow you to save space on the Front Page or on any blog layout
  page by showing just the first portion of an Article. Page break
  allow you to provide multi-page navigation for long Articles. You can
  use both on one Article, if desired.For example, you could put a Read
  more break after the first paragraph of a multi-page article, and have
  Page breaks after each page. No page navigation would display on the
  Front Page until the User selects the Read more link. At that time,
  the Article's table of contents would display showing links to every
  page.

## Связанная информация

- This
  [Portal](https://docs.joomla.org/Portal:Joomla_4/en "Portal:Joomla 4/en")
  brings together information related specifically to Joomla 4.

|                                                                                                                                        |                                                                                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Related Help Screens                                                                                                                   | Описание                                                                                                                                                                                    |
| [Материалы: Настройки](https://docs.joomla.org/Help4.x:Articles:_Options/ru "Help4.x:Articles: Options/ru")                            | Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global' is selected for an option in an Articles menu item.                   |
| [Материалы](https://docs.joomla.org/Help4.x:Articles/ru "Help4.x:Articles/ru")                                                         | Список материалов используется для поиска, отметки избранных, добавления и редактирования материалов.                                                                                       |
| <span class="mw-selflink selflink">Материалы: Создание материала</span>                                                                | This is where you can add and edit Articles. You can also select the Category for an Article and indicate whether or not it is Published and if it is selected to appear on the Front Page. |
| [Материалы: Избранные материалы](https://docs.joomla.org/Help4.x:Articles:_Featured/ru "Help4.x:Articles: Featured/ru")                | Used to control which 'Featured Articles' are displayed on the Front Page and in what order they are displayed.                                                                             |
| [Материалы: Категории](https://docs.joomla.org/Help4.x:Articles:_Categories/ru "Help4.x:Articles: Categories/ru")                      | The Articles Categories list is used to find, add, and edit articles categories.                                                                                                            |
| [Меню: Материалы в архиве](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/ru "Help4.x:Menu Item: Article Archived/ru")    | Shows a customised list of articles ordered by date or title. Archived articles are no longer published but are still stored on the site.                                                   |
| [Меню: Блог категории](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/ru "Help4.x:Menu Item: Category Blog/ru")              | Used to show articles belonging to a specific Category in a blog layout. Controls the Leading Articles, Intro Articles and additional links to more Articles.                               |
| [Меню: Материалы](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/ru "Help4.x:Menu Item: Category List/ru")                   | Used to show articles belonging to a specific Category in a list layout.                                                                                                                    |
| [Меню: Создать материал](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/ru "Help4.x:Menu Item: Create Article/ru")          | Allows users to submit an article. Normally this is available only to users who have logged in to the Frontend of the site. Users must have permission to create articles.                  |
| [Меню: Избранные материалы](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/ru "Help4.x:Menu Item: Featured Articles/ru") | Used to show all Articles that have been tagged as Featured. Articles are shown in a Blog Layout.                                                                                           |
| [Меню: Категории](https://docs.joomla.org/Help4.x:Menu_Item:_List_All_Categories/ru "Help4.x:Menu Item: List All Categories/ru")       | Used to show a hierarchical list of Categories. Depending on the selected options for this layout, you can click on a category Title to show the articles in that category.                 |
| [Меню: Материал](https://docs.joomla.org/Help4.x:Menu_Item:_Single_Article/ru "Help4.x:Menu Item: Single Article/ru")                  | Used to show one article.                                                                                                                                                                   |
