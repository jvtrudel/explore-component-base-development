# Explore component based web development

This exploration topic aims to better understand component based approach in web development. This pattern have been popularised by major front-end web libraries/framework as angular, react and vue. These technology are at the root of the extention of web standard: webcomponent.


# Demonstrations

We illustrate this approach by implementing the same prototype application with different tools.

  - [with Angular](https://github.com/La-Isla-Disruptiva/demo-angular-structured-document-editor)

# Que sont les composants web et quels problèmes résoudent-ils?

Les "webcomponents" est une technique de développement (une meta-specification selon webcomponents.org) qui peut être implémentée nativement avec les standards web grâce à l'extension des spécifications web:

  - Custom Elements Specification (intégré à la DOM specificaiton)
  - Shadow DOM specification
  - HTML Templates specification
  - ES Module specification (extension of the HTML specification)

Il s'agit de créer de nouveaux tags html qui permettent d'étendre la sémantique html afin de personaliser certains objets du DOM.

C'est méthode simple d'encapsuler des fonctionalités plus complexes et de les réutiliser de manière "naturelle" à partir des mêmes principes sémantiques et des outils standard du HTML.

## Émergence de nouveaux enjeux

  - extension de la sémantique
  - applications

L'introduction d'éléments personnalisés enrichi le language html, mais ceci entraine également une complexification obligeant à de nouvelles considérations.

Notamment, ceci permet de composer de nouveaux objets à partir de la combinaison d'autres éléments. Jusqu'alors, l'héritage et le modèle des boites étaient les paradigmes dominants. Bien que ceux-ci avaient été étendus de différentes manières, notamment avec l'introduction de flexbox et des gridbox, la logique restaient inchangée: un objet dispose de certaines propriétés (lesquels sont associés à une sémantique), sont comportement peut être modulé en fonction de certains attributs et propriétés du DOM, et il peut avoir certaines interactions (faibles) avec ses parents, enfants ou voisins. C'est d'ailleurs relativement à ces relations que les récentes améliorations des standard HTML et CSS ont contribués (flex, grid, css...).

Or, les développeurs web sont en forte demande d'interactions fortes entre les éléments du DOM. En fait, tout le travail du développeur web consiste à sculter de tels relations entre les éléments afin de créer de nouveau objets qui ont un tout cohérent.

La sémantique HTML est fortement teinté des origines du web qui a d'abord été un outil de partage d'information, des documents. Or, cette sémantiqu n'est pas adaptée aux besoins des applications web (Single Page Application) et des nouveaux



# References

## Blogs

  - [A brief history of WebComponents and a tutorial to make yours by Lior Chamla](https://medium.com/apprendre-le-web-avec-lior/a-brief-history-of-webcomponents-and-a-tutorial-to-make-yours-a52d329913e7)

## Official sources

  - [Webcomponents Specifications by webcomponents.org](https://www.webcomponents.org/specs)

## Standards, specifications, etc.

  - []
  - [HTML Templates Specification by W3C](https://www.w3.org/TR/html-templates/)
