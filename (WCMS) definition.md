WCMS est l'acronyme de "Web Content Management System", en français "Système de Gestion de Contenu Web". Il s'agit d'un ensemble d'outils logiciels utilisé pour créer, gérer, organiser et publier du contenu sur des sites Web. Un WCMS est généralement utilisé pour faciliter la création et la gestion de sites Web, sans avoir besoin de compétences techniques avancées. Il permet également de gérer efficacement les différents types de contenu, tels que les images, les vidéos, les textes et les pages Web, en offrant des fonctionnalités telles que la gestion des versions, la collaboration et la gestion des flux de travail.

**`PageTemplate`** : un modèle de page qui définit la structure et la disposition des contenus et des composants de la page.

**`ContentPage`** : une page dans laquelle vous pouvez ajouter des composants pour afficher du contenu, tels que du texte, des images et des vidéos.

**`ContentSlotName`** : le nom d'un emplacement de contenu sur une page. Les noms d'emplacement de contenu sont utilisés pour associer des composants à une page.  il définit la position de `ContentSlot` dans notre  `PageTemplate`

**`ContentSlotForTemplate`** : une définition d'emplacement de contenu dans un modèle de page. Les emplacements de contenu peuvent être remplis avec des composants sur des pages créées à partir de ce modèle. il contient le mappage entre `ContentSlot` et `ContentSlotName`

**`CMSParagraphComponent`** : un composant qui permet d'ajouter du texte formaté à une page.

**`ContentSlot`** : un emplacement sur une page où vous pouvez ajouter des composants. Il contient la liste des composants du CMS, il est liée grace a un `ContentSlotForTemplate` ou/et `ContentSlotForPage`

**`ContentSlotForPage`** : une définition d'emplacement de contenu sur une page. Les emplacements de contenu peuvent être remplis avec des composants sur cette page spécifique.

**`CMSNavigationNode`** : un noeud de navigation dans la structure de navigation de votre site. Les noeuds de navigation peuvent avoir des enfants pour créer des sous-menus.

**`CMSNavigationEntry`** : une entrée dans la structure de navigation de votre site. Les entrées de navigation peuvent être liées à des noeuds de navigation pour créer des liens de menu.

**`CMSLinkComponent`** : un composant qui permet de créer des liens vers d'autres pages, des fichiers ou des URL externes.