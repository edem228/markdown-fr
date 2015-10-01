Markdown supporte deux styles de liens: inline et de référence.

Dans les deux styles, le texte du lien est délimité par des [crochets].

Pour créer un lien en ligne, utiliser un ensemble de parenthèses réguliers immédiatement après le lien TEXTA crochet fermant € ™ s. A l'intérieur des parenthèses, mettre l'URL où vous voulez que le lien vers le point, avec un titre optionnel pour le lien, entourée de guillemets. Par example:
`` `démarque
[Je suis un lien inline-style] (https://www.google.com)

[Je suis un lien inline-style avec le titre] (https://www.google.com "page d'accueil de Google»)

[Je suis un lien référence de style] [arbitraire texte de référence insensible à la casse]

[Je suis une référence par rapport à un fichier référentiel] (../ blob / master / LICENCE)
`` `

Les liens par référence utilisent une deuxième série de crochets, à l'intérieur duquel vous placez une étiquette de votre choix pour identifier le lien:
`` `démarque
Ceci est [un exemple] lien [id] référence de style.
`` `

Vous pouvez éventuellement utiliser un espace pour séparer les jeux de supports:
`` `démarque
Ceci est [un exemple] lien [id] référence de style.
`` `

Ensuite, n'importe où dans le document, vous définissez votre étiquette de lien comme ça, sur une ligne par lui-même:
`` `démarque
[id]: http://example.com/ "Titre optionnel Voici"
`` `

** GitHub ** et ** ** GitBook soutient URL autolinking. Ils seront AutoLink URL standard, donc si vous voulez faire un lien vers une URL (au lieu de mettre le texte du lien), vous pouvez simplement entrer l'URL et il sera transformé en un lien vers cette URL.


---

Voici un quiz sur les liens de démarques.

Sélectionnez les liens valides:
- [X] `[un lien] (http://google.fr)`
- [] `(Un lien) [http://google.fr]`

> Le texte du lien est délimité par des [crochets].

Quelles sont les informations correctes à partir de ce lien: `` `[un lien] (http://google.fr« Google »)` ``
- [] Le lien est https://google.fr
- [X] le titre du lien est "google"
- [] Il va montrer le texte "google"
- [X] il va montrer le texte "un lien"

> Liens peuvent avoir 3 parties: le texte, l'URL et un titre.

---