<!-- Filename: Help4.x:Menu_Item:_Article_Archived / Display title: Меню: Материалы в архиве -->

## Описание

The Archived Articles Menu Item Type shows a customised list of articles
ordered by date or title.

Archived articles are no longer published but are still stored on the
site. Articles are Archived using the Articles list screen.
Articles assigned to the 'Uncategorised' Category will not show on the
Archived Article Menu Item.

## Как открыть

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Archived Articles** item.

To edit a Menu Item:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/e/e6/Help-4x-Menus-Item-Articles-Article-Archived-screen-ru.png/800px-Help-4x-Menus-Item-Articles-Article-Archived-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e6/Help-4x-Menus-Item-Articles-Article-Archived-screen-ru.png/1200px-Help-4x-Menus-Item-Articles-Article-Archived-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/e/e6/Help-4x-Menus-Item-Articles-Article-Archived-screen-ru.png/1600px-Help-4x-Menus-Item-Articles-Article-Archived-screen-ru.png 2x"
data-file-width="2880" data-file-height="1448" width="800" height="402"
alt="Menus Item Articles Article Archived screen" />

## Form Fields

- **Заголовок**. The title that will display for this menu item.
- **Алиас**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Подробности

#### Left Panel

- **Тип пункта меню**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Категория**. Select one or more categories from the dropdown list.
- **Ссылка**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Окно браузера**. Select from the dropdown list.
- **Стиль шаблона**. Select from the dropdown list.

#### Right Panel

- **Меню**. Shows which menu the link will appear in.

### Архив

Options include "Use Global". If this is selected, the setting from the
Articles: Options
will be used.

<img
src="https://docs.joomla.org/images/thumb/e/ee/Help-4x-Menus-Item-Articles-Article-Archived-archive-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Article-Archived-archive-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/ee/Help-4x-Menus-Item-Articles-Article-Archived-archive-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Article-Archived-archive-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/e/ee/Help-4x-Menus-Item-Articles-Article-Archived-archive-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Article-Archived-archive-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1250" width="600" height="260"
alt="Menus Item Articles Article Archived archive subscreen" />

- **Порядок материалов**.
  - Старые первыми: Articles are displayed starting with the oldest and
    ending with the most recent.
  - Новые первыми: Articles are displayed starting with the most recent
    and ending with the oldest.
  - Заголовок (по алфавиту): Articles are displayed by Title in
    alphabetical order (A to Z).
  - Заголовок (против алфавита): Articles are displayed by Title in
    reverse alphabetical order (Z to A).
  - Автор (по алфавиту): Articles are displayed by Author in
    alphabetical order (A to Z).
  - Автор (против алфавита): Articles are displayed by Author in reverse
    alphabetical order (Z to A).
  - Наиболее популярные: Articles are displayed by the number of hits,
    starting with the one with the most hits and ending with the one
    with the least hits.
  - Наименее популярные: Articles are displayed by the number of hits,
    starting with the one with the least hits and ending with the one
    with the most hits.
  - Порядок в Joomla: Articles are ordered according to the Order column
    entered in
    Articles.
- **Поле даты для сортировки**. The date used when articles are sorted
  by date.
  - Создано: Use the article created date.
  - Изменено: Use the article modified date.
  - Опубликовано: Use the article start publishing date.
- **Количество материалов в списке**. Number of articles shown in the
  list.
- **Фильтр**. Show a text field in the Frontend where a user can filter
  the articles.
- **Количество символов**. The maximum number of characters of the Intro
  Text to show. If the Intro Text is longer than this value, it will be
  truncated to this length.

### Параметры

The Options determine how the article will show on the Frontend Site
layout.

<img
src="https://docs.joomla.org/images/thumb/0/04/Help-4x-Menus-Item-Articles-Article-Archived-options-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Article-Archived-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/04/Help-4x-Menus-Item-Articles-Article-Archived-options-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Article-Archived-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/0/04/Help-4x-Menus-Item-Articles-Article-Archived-options-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Article-Archived-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Menus Item Articles Article Archived options subscreen" />

#### Макет

- **Вводный текст**.
  - Показать: The Intro Text of the article will show when you drill
    down to the article.
  - Скрыть: Only the part of the article after the Read More break will
    show.
- **Позиция информации о материале**.
  - Использовать параметры материала: Use the value from Articles: Edit.This
    setting allows you to have different options for different articles
    in the List layout.
  - Сверху: Puts the article information block above the text.
  - Снизу: Puts the article information block below the text.
  - Разделить: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Заголовок информации о материале**. Displays 'Details' on top of the
  article information block.

#### Категория

- **Категория**. Show the Article's Category Title.
- **Категория как ссылка**. Show the title as a link to that
  Category.Note: You can set this to be either a blog or list layout
  with the Choose a Layout
  option in the Category Tab.
- **Заголовок родительской категории**. Show the Article's Parent
  Category Title.
- **Родительская категория как ссылка**. Show the title as a link to
  that Category.Note: You can set this to be either a blog or list
  layout with the Choose a Layout
  option in the Category Tab.
- **Заголовок как ссылка**. Show the title as a link to the article.

#### Автор

- **Автор**. Show the author of the Article.
- **Автор как ссылка**. Show it as a link to a Contact layout for that
  author.Note: The author must be set up as a
  Contact.
  Also, a link will not show if there is an Author Alias
  value for the article.

#### Дата

- **Дата создания**. Show the Article's create date.
- **Дата изменения**. Show the Article's modify date.
- **Дата публикации**. Show the Article's start publishing date.

#### Параметры

- **Ссылки "Назад/Вперед"**. Show a navigation link 'Prev' or 'Next'
  when you drill down to the article.
- **Количество просмотров**. Show the number of times the article has
  been displayed by a user.

### Common Options

See Menus: New Item
for help on fields common to all Menu Item types, including:

- Right Panel
- Тип
  ссылки
- Страница
- Метаданные
- Связи
- Привязка
  модулей

## Панель инструментов

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Сохранить**. Saves the menu item and stays in the current screen.
- **Сохранить и закрыть**. Saves the menu item and closes the current
  screen.
  - **Сохранить и создать**. Saves the menu item and keeps the editing
    screen open and ready to create another menu item.
- **Закрыть**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Справка**. Opens this help screen.

## Быстрые советы

- The Archived Articles layout allows you to access old or outdated
  articles that you don't want to remove entirely from the site.
- If you want to be able to see old articles in a category blog or list,
  create a category for older articles and move them to this category
  (instead of changing the Published state to Archived).
