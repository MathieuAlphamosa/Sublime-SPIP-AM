# Pourquoi ?

Le [plugin de phenix-factory](https://github.com/phenix-factory/Sublime-SPIP) m'a bien dépanné pendant des années mais j'avais besoin de quelque chose de moins intrusif, à jour pour Sublime Text 3/4, et avec une colorisation basé sur Monokai.


# Installation

A glisser dans votre dossier `User`.

Sur macOS : `~/Library/Application Support/Sublime Text 3/Packages/User/`


# Différences avec le plugin phenix-factory

`SPIP.sublime-package/spip.sublime-completions`
Ajout de quelques snippets, mise en commentaire d'autres que je n'utilise pas beaucoup.
scope : `text.html - source.php`

`SPIP.sublime-package/spip-php.sublime-completions`
Similaire, limité au scope `source.php`

`SPIP.sublime-syntax`
Transformation du format TextMate en format sublime-syntax

`SPIP.sublime-color-scheme`
Basée sur le thème Monokai avec des ajouts liées à la syntaxe SPIP.

Simplification des snippets SPIP.

# Attention

1 - Ce package est fourni à titre d'exemple pour vous servir de base à la construction de votre propre package.
2 - Les filtres `|image_optimise` et `|image_webp` sont des filtres utilisées en interne ici à Alphamosa. Il vous faudra les supprimer des snipppets.
