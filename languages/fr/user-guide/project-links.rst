.. contents::
   :depth: 3
..

Liens inter-projet
==================

Les liens inter-projet structurent les projets Tuleap, rendant visible
leurs relations sur la page d'accueil du projet. Ces relations sont de
plusieurs types :

-  Des familles de projet : un projet parent peut accéder facilement à
   ses projets enfants.
-  Des relations autour d'un point/cercle d'intérêts : plusieurs projets
   peuvent décider qu'ils ont suffisamment en commun pour souhaiter être
   liés (par exemple les projets qui utilisent la même technologie),
   sans relation hiérarchique, où chacun est libre d'adhérer ou de
   quitter le point d'intérêt.

Pour créer une relation, un projet définit d'abord un type de lien puis
se lie à autant de projets qu'il le souhaite. Le nom donné au type de
lien doit être unique dans le projet, par exemple "sous-projets",
"projets connexes", "Division", "Team", "Projects Java". Ce nom sert de
rubrique pour lister les projets liés.

Lorsque vous référencez un lien de parenté, le projet qui administre le
lien en est le propriétaire et le projet référencé par le lien est la
cible du lien. Un type de lien spécifie également un nom inverse, qui
est utilisé quand un projet répertorie les projets dont il est la cible.
Par exemple, "enfants" peut être le nom d'un type de lien et "Parent" le
nom du lien inverse pour ce même type de lien. Les projets liés de cette
façon seront inscrits sous la rubrique «enfants» dans le projet
propriétaire, et pourront voir la relation (inverse) du «parent».

Pour créer un "cercle d'intérêts", quelqu'un doit prendre la
responsabilité de créer (et gérer) un projet qui l'administre (celui-ci
se comporte comme un projet parent dans une famille de projet mais sa
seule fonction est d'être le propriétaire de ce lien) - l'administrateur
de ce lien doit prendre la responsabilité de l'animer. Pour rejoindre un
cercle d'intérêt, un projet doit demander au projet administrateur de
créer un lien avec lui dans son projet.

Quand un nouveau projet est créé à partir d'un modèle de projet, il
hérite d'une copie de tous les liens de projet. De plus, tout projet qui
fait référence à un modèle en tant que cible aura un lien vers le
nouveau projet. Ainsi, un projet peut garder un œil sur tous les projets
créés à partir d'un modèle. Il existe également un mécanisme qui permet
aux projets de resynchroniser les types de lien avec leur modèle. Les
nouveaux liens sont mis en évidence avec une étoile jaune -
principalement pour mettre en avant les liens créés à partir des
modèles.

Le projet liste les liens inverses (les projets pour lesquels il est la
cible d'un lien) sur sa page d'accueil.
