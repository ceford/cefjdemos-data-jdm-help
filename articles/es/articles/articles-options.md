<!-- Filename: Help4.x:Articles:_Options / Display title: Artículos: Opciones -->

## Descripción

Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global'
is selected for an option in an Articles menu item.

For example, to show the 'Create Date' for an article in your Articles
menu items, then set that option to 'Show' here and it will be the
default value.

You do not need to set any of these options. Your Joomla site will work
with the default settings.

## Cómo Acceder
Seleccionar **Contenido → Artículos**

- Clic el botón **Opciones** en la Barra de Herramientas.

## Captura de pantalla

![Articles options screenshot](../../../images/es/articles/articles-options-articles-tab.png "Articles options")

## Campos del formulario

### Artículos

Options used in articles and the menu items
Blog,
List,
Featured Articles,
List All Categories,
and Single Article.

#### Presentación

- **Elegir presentación**. Select the default value for Single Article
  menu items.
- **Mostrar título**. Show the Article's Title.
- **Título enlazable**. Show the title as a link to the article.
- **Mostrar texto de introducción**.
  - Mostrar: The Intro Text of the article will show when you drill down
    to the article.
  - Ocultar: Only the part of the article after the Read More break will
    show.
- **Información de la posición del artículo**.
  - Encima: Puts the article information block above the text.
  - Debajo: Puts the article information block below the text.
  - Dividido: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Título de información del artículo**. Displays 'Details' on top of
  the article information block.

#### Categoría

- **Mostrar la categoría**. Show the Article's Category Title.
  - **Categoría enlazable**. Show the title as a link to that
    Category.Note: You can set this to be either a blog or list layout
    with the Choose a Layout
    option in the Category Tab.
- **Mostrar categoría principal**. Show the Article's Parent Category
  Title.
  - **Categoría principal enlazable**. Show the title as a link to that
    Category.Note: You can set this to be either a blog or list layout
    with the Choose a Layout
    option in the Category Tab.

#### Asociaciones

- **Mostrar asociaciones**. Show the associated flags or Language Code.
  Multilingual only.
  - **Usar indicadores de imagen**. Display language choice as image
    flags.

#### Autor

- **Mostrar autor**. Show the author of the Article.
  - **Autor enlazable**. Show it as a link to a Contact layout for that
    author.Note: The author must be set up as a
    Contact.
    Also, a link will not show if there is an Author Alias
    value for the article.

#### Fecha

- **Mostrar la fecha de creación**. Show the Article's create date.
- **Mostrar fecha de modificación**. Show the Article's modify date.
- **Mostrar fecha de publicación**. Show the Article's start publishing
  date.

#### Opciones

- **Mostrar navegación**. Show a navigation link 'Prev' or 'Next' when
  you drill down to the article.
- **Mostrar 'Leer más'**. Show the Read More link to link from the part
  of the article before the Read More break to the rest of the Article.
- '**Leer más' con título**.
  - Mostrar: The article title is part of the Read More link. The link
    will be in the format "Read More: \[article title\]".
  - Ocultar: The link will be "Read more".
- **Límite del 'Leer más'**. The maximum number of characters from the
  title to include.Note: This can prevent the Read More text to become
  excessively long if the article has a very long title.
- **Etiquetas**. Show the tags for each article.
- **Registrar impresiones**. Record the number of times the article has
  been viewed.
- **Mostrar impresiones**. Show the number of times the article has been
  displayed by a user.
- **Mostrar los enlaces no autorizados**.
  - Sí: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.
- **Posición de los enlaces**.
  - Encima: Links are shown above the content.
  - Debajo: Links are shown below the content.

### Opciones de edición

Options of the article editing page.

![Articles options editing layout tab](../../../images/es/articles/articles-options-editing-layout-tab.png "Articles options editing layout")

- **Permitir CAPTCHA al enviar**. Select the captcha plugin
  that will be used in the article submit form. If 'Use Global' is
  selected, make sure a captcha plugin is selected in Global Configuration.
- **Opciones de publicación**. Hide the Publishing Options tab
  in the Backend when editing Articles. This means that Backend users
  will not be able to edit the fields in this tab. These fields will
  always be set to their default values.
- **Opciones del artículo**. Hide the Article Options tab
  in the Backend when editing Articles. This means that Backend users
  will not be able to edit the fields in this tab. These fields will
  always be set to their default values.
- **Editar opciones de pantalla**. Hide the Configure Edit Screen tab
  when editing Articles.
- **Permisos del artículo**. Hide the Permissions tab
  when editing Articles.
- **Asociaciones multiidioma**. Hide the Associations tab
  when editing Articles.
- **Guardar historial**. Save version history for Articles and
  Categories.
- **Versiones máximas**. The maximum number of versions to store for an
  Article or Category. If an Article or Category is saved and the
  maximum number of versions has been reached, the oldest version will
  be deleted automatically. If set to "0", then versions will never be
  deleted automatically. Aprende
  más.
- **Mostrar las 'Opciones de imágenes y enlaces' desde el sitio**. Hide
  the Images and Links tab in the Frontend article editor screen.
- **Mostrar las 'Opciones de imágenes y enlaces' desde la
  administración**. Hide the Images and Links tab
  in the Backend when editing Articles.
- **Ventana de destino para la URL 'A'**. Sets the default value for the
  target for the first Link in the article. Choices are:
  - Misma ventana: Opens the in the main browser window, replacing the
    current Joomla article.
  - Nueva ventana: Opens the link in a new browser window.
  - En una ventana emergente: Opens the link in a popup browser window
    (without full navigation controls).
  - Modal: Opens the link in a modal popup window.
- **Ventana de destino para la URL 'B'**. Sets the default value for the
  target for the second Link in the article. Same options as URL A.
- **Ventana de destino para la URL 'C'**. Sets the default value for the
  target for the third Link in the article. Same options as URL A.
- **Clase para la imagen de introducción**. Sets the class attribute for
  an Intro Image selected in the Intro Image field.
- **Clase para la imagen de texto completo**. Sets the class attribute
  for an Full Article Image selected in the Full Article Image field.

### Categoría

Options control how a Category and its articles will show. They are used
in categories and the menu items Blog, List, and List All Categories.

![Articles options category tab](../../../images/es/articles/articles-options-category-tab.png "Articles options category")


- **Elegir presentación**. Select the default layout to show when you
  click on a Category link.
- **Título de la categoría**. Show the title of the category.
- **Descripción de la categoría**. Show the description for the
  category.
- **Imagen de la categoría**. Show the category image.
- **Nivel de subcategorías**. Control how many levels of subcategories
  to show.
- **Categorías vacías**. Show categories that don't contain any articles
  or subcategories.
- **Mensaje para 'Sin artículos'**. Show a message "There are no
  articles in this category".
- **Encabezado de subcategorías**. Show the Subcategories as subheading
  on the page.
- **Descripción de subcategorías**. Show the descriptions for
  subcategories.
- **Cantidad de artículos en la categoría**. Show a count of the total
  number of articles in each category.
- **Etiquetas**. Show the tags for the category.

### Categorías

Options control the display of the menu item List All Categories.

![Articles options categories tab](../../../images/es/articles/articles-options-categories-tab.png "Articles options categories")

- **Descripción de la categoría principal**. Show the description for
  the top-level category.
- **Nivel de subcategorías**. Control how many levels of subcategories
  to show.
- **Categorías vacías**. Show categories that don't contain any articles
  or subcategories.
- **Descripción de subcategorías**. Show the description for
  subcategories.
- **Cantidad de artículos en la categoría**. Show a count of the total
  number of articles in each category.

### Opciones del formato del tipo blog o destacados

Options control the layout of the menu items Blog, Featured Articles,
and List All Categories.

![Articles options blog/featured layout tab](../../../images/es/articles/articles-options-blog-layouts-tab.png "Articles options blog/featured layout")

- **Cantidad de artículos de introducción**. Número de Artículos a
  mostrar usando todo el ancho de la zona de visualización principal.
  "0" significa que no se muestran Artículos al utilizar el ancho
  completo. Si un Artículo tiene un salto "Leer más...", sólo se
  mostrará la parte del texto antes del salto (el texto de
  Introducción).
- **Clase del artículo principal**. Puede añadir cualquier clase de CSS
  para sus propias ideas de estilo. Añada un borde en la parte superior
  con la clase 'boxed'.Para la posición de la imagen, use, por ejemplo,
  'image-left', 'image-right'. Añada una imagen alternativa para un
  orden alternativo de las imágenes de introducción.
- **Cantidad de artículos después de los de introducción**. Determina el
  número de Artículos a mostrar después del Artículo inicial. Estos
  Artículos se mostrarán en el número de columnas de las Columnas
  configuradas a continuación. Si un Artículo tiene un salto "Leer
  más...", sólo se mostrará el texto antes del salto (Texto de
  introducción), seguido por un "Leer más...". El orden en que se
  muestran los artículos se determina por el Orden de las categorías y
  Orden de los artículos de los siguientes parámetros.
- **Clase del artículo**. Puede añadir cualquier clase de CSS para sus
  propias ideas de estilo. Añada un borde en la parte superior con la
  clase 'boxed'.Para la posición de la imagen, use, por ejemplo,
  'image-left', 'image-right'. Añada una imagen alternativa para un
  orden alternativo de las imágenes de introducción.
- **Cantidad de columnas**. El número de columnas a utilizar en la zona
  del Texto de Introducción. Este es normalmente entre 1 y 3
  (dependiendo de la plantilla que estás utilizando). Si se utiliza 1,
  El texto de Introducción de los Artículos se mostrará con el ancho
  completo de la pantalla, así como el Artículos Principal.
- **Orden en columnas múltiples**. En el diseño blog de columnas
  múltiples, sirve para ordenar los artículos en formato hacia Abajo o
  Cruzado de las columnas.
  - Abajo: Orden de los artículos van hacia abajo en la primera columna
    y, a continuación, a la siguiente columna, por ejemplo:

-
  - Cruzado: El orden de los artículos va a través de las columnas y, a
    continuación, vuelve a la primera columna, por ejemplo:

-
- **Cantidad de enlaces**. El número de Enlaces a mostrar en los "Links"
  de la página. Estos enlaces permiten a un Usuario ver enlaces a otros
  Artículos, si no caben más Artículos en la primera página del Diseño
  Blog.
- **Incluir subcategorías**.
  - Ninguno: Only articles from the current category will show.
  - Todos: All articles from the current category and all subcategories
    will show.
  - 1-5: All articles from the current category and subcategories up to
    and including that level will show.
- **Imagen de introducción enlazada**. If Yes, a click on the intro
  image shows the article.

### Opciones del formato del tipo lista o tabla

Options control the layout of the menu items List and List All Categories.

![Articles options list layouts tab](../../../images/es/articles/articles-options-list-layouts-tab.png "Articles options list layouts")

- **Seleccionar 'Cantidad a mostrar'**. Show the Display \# control that
  allows the user to select the number of articles to show.
- **Campo 'Filtrar'**. Show a text field in the Frontend where a user
  can filter the articles.Options in the Backend menu item edit.
  - Ocultar: Don't show a filter field.
  - Título: Filter on article title.
  - Autor: Filter on the author's name.
  - Veces visto: Filter on the number of article hits.
  - Etiquetas: Filter on the article tags.
  - Mes (pubicado): Filter on the month of published articles.
- **Encabezados de la tabla**. Show a heading in the article list in the
  Frontend.
- **Mostrar fecha**. Show a date in the list.
  - Ocultar: Don't show any date.
  - Creado: Show the created date.
  - Modificado: Show the date of the last modification.
  - Publicado: Show the start publishing date.
- **Mostrar impresiones en la lista**. Show the number of hits for
  articles.
- **Mostrar autor en la lista**. Show the name of the author.
- **Cantidad de artículos a listar**. Number of articles shown in the
  list.

### Compartido

Options shared by the menu items Blog, List, and Featured Articles.

![Articles options shared tab](../../../images/es/articles/articles-options-shared-tab.png "Articles shared")

- **Orden de las categorías**.
  - Sin ordenar: Articles are ordered only by the Article Order, without
    regard to Category.
  - Título alfabético: Categories are displayed in alphabetical order (A
    to Z).
  - Título alfabético invertido: Categories are displayed in reverse
    alphabetical order (Z to A).
  - Orden de las categorías: Categories are ordered according to the
    Order column entered in Articles: Categories.
- **Orden del artículo**.
  - Los recientes primero: Articles are displayed starting with the most
    recent and ending with the oldest.
  - Los antiguos primero: Articles are displayed starting with the
    oldest and ending with the most recent.
  - Título alfabético: Articles are displayed by Title in alphabetical
    order (A to Z).
  - Título alfabético invertido: Articles are displayed by Title in
    reverse alphabetical order (Z to A).
  - Autor-Alfabéticamente: Articles are displayed by Author in
    alphabetical order (A to Z).
  - Autor-Alfabéticamente invertido: Articles are displayed by Author in
    reverse alphabetical order (Z to A).
  - Más vistos: Articles are displayed by the number of hits, starting
    with the one with the most hits and ending with the one with the
    least hits.
  - Menos visto: Articles are displayed by the number of hits, starting
    with the one with the least hits and ending with the one with the
    most hits.
  - Orden: Articles are ordered according to the Order column entered in
    Articles.
  - Invertir orden: Articles are ordered reverse to the according of the
    Order column entered in
    Articles.
- **Ordenar por fecha**. The date used when articles are sorted by date.
  - Creado: Use the article created date.
  - Modificado: Use the article modified date.
  - Publicado: Use the article start publishing date.
- **Paginación**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Ocultar: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Mostrar: Pagination links shown if needed.
  - Automático: Pagination links shown if needed.
- **Resultados de la paginación**. Show the current page number and
  total pages (e.g., "Page 1 of 2") at the bottom of each page.
- **Artículos destacados**.
  - Mostrar: Display featured articles and non-featured articles.
  - Ocultar: Display only non-featured articles.
  - Solo: Display only featured articles.

### Integración

Options control how Articles integrate News Feeds, Routing, Custom
Fields, and Workflow.

![Articles options integration tab](../../../images/es/articles/articles-options-integration-tab.png "Articles options integration")

#### Canales electrónicos

- **Sindicar el enlace**. If set to Show, a Feed Link will show up as a
  feed icon in the address bar of most browsers.
- **Incluir noticia sindicada**.
  - Texto de introducción: Only the article's intro text will show in
    the feed.
  - Texto completo: The entire text of the article will show in the
    feed.
- **Mostrar "Leer más"**. Show a "Read more" link in the feed.

#### Enrutamiento

- **Eliminar ID de URL**. Remove the database id of articles in a link.

#### Campos personalizados

- **Habilitar campos personalizdos**. Enable the creation of custom
  fields. Aprende
  más.

#### Flujo de trabajo

- **Habilitar flujo de trabajo**. Use customised workflows to manage
  articles. Aprende
  más.

### Permisos

This section lets you set up the default Access Control List
permissions for all articles in all categories.

![Articles options permissions tab](../../../images/es/articles/articles-options-permissions-tab.png "Articles options permissions")

To change the permissions for articles and categories, do the following.

1.  Selecciona el **Grupo** haciendo clic en el título que se encuentra
    a la izquierda.
2.  Find the desired **Action**.
    - **Configurar**. Users can edit the options and permissions.
    - **Solo opciones de configuración**. Users can edit the options
      exept the permissions.
    - **Acceso a la interfaz de administración**. Los usuarios pueden
      tener acceso a la interfaz de administración de usuarios.
    - **Crear**. Users can create articles and categories.
    - **Borrar**. Users can delete articles and categories.
    - **Editar**. Users can edit articles and categories.
    - **Editar estado**. User can change the published state and related
      information.
    - **Editar propios**. Users can edit own created articles and
      categories.
    - **Editar valor de campo personalizado**. Users can edit any value
      of custom fields submitted in articles and categories.
    - **Gestionar flujos de trabajo**. Users can manage workflows.
    - **Ejecutar transición**. Users can execute transitions.
3.  Select the desired permission for the action you wish to change.
    - **Heredado**. Inherited for users in this Group from the Global Configuration
      permissions.
    - **Permitido**. Allowed for users in this Group.Note: If this
      action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Denegado**. Denied for users in this Group.
4.  Has clic en **Guardar** en la **Barra de herramientas** en la parte
    superior. Cuando la pantalla se actualiza, la columna Configuración
    Calculada mostrará el permiso efectivo para este Grupo y Acción.

## Barra de herramientas

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Guardar**. Saves the articles options and stays in the current
  screen.
- **Guardar y cerrar**. Saves the articles options and closes the
  current screen.
- **Cerrar**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Alternar la ayuda interna**. Show help text below some options.
- **Ayuda**. Se abre esta pantalla de ayuda.

## Consejos Rápidos

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here. When you set up menu items and create articles,
  you will be able to accept the default values for most options.
- All values set here can be overridden at the menu item, category, or
  article level.
