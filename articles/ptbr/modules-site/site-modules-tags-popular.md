<!-- Filename: Help4.x:Site_Modules:_Tags_-_Popular / Display title:   Módulos do site: Tags - Populares -->

## Descrição

O módulo **Tags - Populares** exibe as tags usadas no site em uma
disposição (layout) para listas ou nuvens. As tags podem ser ordenadas
por título ou pela quantidade dos itens marcados e limitadas a um
período específico.

## Como acessar

- Selecione **Sistema → Gerenciar (painel) → Módulos do site**
  no menu da administração. Então...
  - Para criar um novo módulo: selecione o botão **Novo** na barra das
    ferramentas. Então...
    - Selecione o tipo do módulo necessário.
  - Para editar um módulo existente:
    - Encontre o módulo na lista contendo os módulos instalados e
      selecione o link do título na coluna **Título**.

## Captura da tela

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-popular-tags-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-popular-tags-pt-br.png">800px</a>

## Campos do formulário

- **Título**: O título do módulo. Este também é o título exibido para o
  módulo dependendo do campo *Mostrar título* do formulário

### Aba (guia) Módulo

#### Painel esquerdo

- **Tag superior (principal, pai)**: Filtra as tags para mostrar apenas
  as tags filhas desta tag superior (principal, pai).
- **Máximo de tags**: (*1*/*2*/*3*/*4*/*5*/*6*/*7* /...). Define a
  quantidade máxima de tags a serem mostradas no módulo.
- **Período de tempo**: (*Todo o tempo*/*última hora*/*último
  dia*/*última semana*/*último mês*/*último ano* ). Define o período de
  tempo em que a popularidade será calculada.
- **Classificação**: (*Título*/*quantidade de itens*/*aleatória*). A
  ordem em que as tags serão mostradas.
- **Direção**: (*Crescente*/*decrescente*). Ordem da classificação. A
  decrescente é do maior para o menor. A crescente é do menor para o
  maior.
- **Mostrar a quantidade de itens**: (*Sim*/*não*). Escolha se a
  quantidade de itens marcados deve ser mostrada ao lado de cada tag.
- **Mostrar o texto "Sem resultados"**: (*Sim*/*não*). Mostrará uma
  mensagem se nenhuma tag correspondente for encontrada em vez de
  ocultar o módulo.

#### Painel direito

- **Mostrar título**: (Mostrar/Ocultar) Escolhe se mostra ou oculta o
  título dos módulos no front-end. O título será aquele no campo do
  formulário acima.
- **Posição**: Escolhe a posição do
  módulo
  na qual deseja que o módulo seja exibido. Uma posição de módulo
  personalizada pode ser inserida para uso com o plugin para carregar
  posição
  ou o botão de posição pode ser pressionado para selecionar uma posição
  de módulo do tema.
- **Estado**: O estado de publicação do item.
- **Acesso**: O nível de acesso de
  visualização
  para este item.
- **Ordenação dos módulos**: Isso mostra uma lista suspensa de cada
  módulo na posição em que o módulo em questão está. Esta é a ordem em
  que os módulos serão exibidos quando exibidos no frontend, bem como na
  página
  "Módulos".
- **Início da publicação**: Data e hora para iniciar a publicação. Use
  este campo se desejar inserir conteúdo antecipadamente e publicá-lo
  automaticamente no futuro.
- **Término da publicação**: Data e hora para o término da publicação.
  Use este campo se desejar que o conteúdo seja alterado automaticamente
  para o estado "Não publicado" em um momento futuro (por exemplo,
  quando não for mais aplicável).
- **Linguagem**: Linguagem do item.
- **Nota**: Isso normalmente é para uso da administração do site (por
  exemplo, para documentar informações sobre o item) e não aparece no
  frontend do mesmo.

### Aba (guia) Atribuição no(s) menu(s)

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-manager-site-module-menu-assignment-tab-pt-br.png"
class="new"
title="File:Help-4x-modules-manager-site-module-menu-assignment-tab-pt-br.png">600px</a>

- **Atribuição de módulo**: Selecione **Em todas as páginas**, **Nenhuma
  página**, **Apenas nas páginas selecionadas** ou **Em todas as
  páginas, exceto as selecionadas** da lista.
- **Seleção de menu**: Se as duas últimas opções forem selecionadas, uma
  lista mostrará todos os itens de menu. Isso permite que você atribua
  módulos à algumas, mas não à todas as páginas, e selecionando os links
  de menu aos quais deseja associar o módulo, você pode personalizar em
  quais páginas os módulos aparecem/não aparecem. Consulte [Como você
  atribui um módulo a páginas
  específicas?](https://docs.joomla.org/How_do_you_assign_a_module_to_specific_pages%3F/pt-br "How do you assign a module to specific pages?/pt-br")
  para mais informações.

### Aba (guia) Disposição (layout) para nuvem

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-site-module-manager-module-popular-tags-cloud-layout-pt-br.png"
class="new"
title="File:Help-4x-modules-site-module-manager-module-popular-tags-cloud-layout-pt-br.png">600px</a>

- **Tamanho mínimo da fonte**: O tamanho mínimo da fonte usada para as
  tags, proporcional ao tamanho da fonte padrão do site (por exemplo,
  "2" significa 200% do tamanho padrão).
- **Tamanho máximo da fonte**: O tamanho máximo da fonte usada para as
  tags, proporcional ao tamanho da fonte padrão do site (por exemplo,
  "2" significa 200% do tamanho padrão).

### Aba (guia) Avançado

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-manager-admin-module-site-advanced-options-pt-br.png"
class="new"
title="File:Help-4x-modules-manager-admin-module-site-advanced-options-pt-br.png">600px</a>

- **Disposição**: Se você definiu uma ou mais disposições (layouts)
  alternativas para um módulo no tema ou no núcleo do Joomla!, você pode
  selecionar a disposição (layout) a ser usada para este módulo.
- **Classe do módulo**: Um sufixo aplicado à classe CSS do módulo. Isso
  permite que você crie estilos CSS personalizados que serão aplicados
  apenas a este módulo. Você então modificaria o arquivo "user.css" do
  seu tema (modelo) para aplicar o estilo a essa nova classe. Insira
  este parâmetro com um espaço à esquerda para criar uma nova classe CSS
  para este módulo. Insira o parâmetro sem um espaço à esquerda para
  alterar o nome da classe CSS para este módulo.
- **Cache**: Usar global/sem cache. Se deve ou não armazenar em cache o
  conteúdo deste módulo. Definir a opção "Usar global" usará as
  configurações de cache da tela de configurações globais.
- **Tempo de cache**: O número de segundos para armazenar o item em
  cache localmente. Pode ser deixado com segurança no padrão.
- **Estilo do módulo**: Você pode usar esta opção para substituir o
  estilo do tema para sua posição.
- **Tag do módulo.** A tag de HTML para o módulo a ser colocada. Por
  padrão, esta é uma tag div, mas outros elementos da HTML5 também podem
  ser usados.
- **Tamanho do bootstrap**: (Valores de 0 a 12) Isso permite que você
  escolha a largura do módulo através do elemento span embutido no
  bootstrap.
- **Tag de cabeçalho**: A tag da HTML a ser usada para o cabeçalho ou o
  título dos módulos. Esta pode ser uma tag h1, h2, h3, h4, h5, h6 ou p.
  Observe que você deve usar um estilo de módulo (chrome) da html5 ou
  adicionar seus estilos de módulo personalizados em /html/modules.php.
- **Classe de cabeçalho**: Aqui você pode adicionar classes CSS
  opcionais para adicionar ao cabeçalho do módulo ou ao elemento de
  título.

### Aba (guia) Permissões

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-modules-manager-admin-module-administrator-permissions-pt-br.png"
class="new"
title="File:Help-4x-modules-manager-admin-module-administrator-permissions-pt-br.png">600px</a>

Para alterar as permissões, faça o seguinte.

- Selecione o **grupo** clicando em seu título localizado à direita.
- Localize a **ação** desejada. As ações possíveis são:
  - **Excluir**: Os usuários podem excluir o módulo.
  - **Editar**: Os usuários podem editar o módulo.
  - **Editar estado**: O usuário pode alterar o estado de publicação e
    as informações relacionadas ao módulo.
- Seleciona a permissão desejada para a ação que deseja alterar. As
  configurações possíveis são:
  - ***Herdado***: Herdado, para usuários neste grupo, das permissões
    das configurações globais, das opções do gerenciador de artigos ou
    das categorias.
  - ***Permitido***: Permitido para usuários deste grupo. Observe que,
    se esta ação for negada em um dos níveis mais altos, a permissão
    aqui não terá efeito. Uma configuração negada não pode ser
    substituída.
  - ***Negado***: Negado para usuários neste grupo.
- Selecione **salvar** na **barra de ferramentas**. Quando a tela for
  atualizada, a coluna "Configuração calculada" mostrará a permissão
  efetiva relacionada a este grupo e à esta ação.

## Barra das ferramentas

No topo da página você verá a barra de ferramentas mostrada na [captura
de tela](#Captura_de_tela) acima. As funções são:

- **Salvar**: Salva o item e permanece na tela atual.
- **Salvar fechar**: Salva o item e fecha a tela atual.
- **Salvar & novo**: Salva o item e mantém a tela de edição aberta e
  pronta para criar outro item.
- **Salvar como cópia**: Salva suas alterações em uma cópia do item
  atual. Não afeta o item atual. Este ícone da barra de ferramentas não
  é exibido se você estiver criando um novo item.
- **Fechar**: Fecha a tela atual e retorna à tela anterior sem salvar
  nenhuma modificação que tenha feito. Este ícone da barra de
  ferramentas não é exibido se você estiver criando um novo item.
- **Ajuda**: Abre a tela de ajuda.
