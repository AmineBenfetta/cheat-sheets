Syntaxe Markdown
Titres

Les titres sont créés en utilisant des dièses (#). Le nombre de dièses détermine le niveau du titre.

    # Titre 1 : Titre de niveau 1
    ## Titre 2 : Titre de niveau 2
    ### Titre 3 : Titre de niveau 3
    #### Titre 4 : Titre de niveau 4

Exemple :

# Titre 1
## Titre 2
### Titre 3

Paragraphes

Les paragraphes sont créés en séparant les blocs de texte par des lignes vides.

Exemple :

Voici un premier paragraphe.

Voici un deuxième paragraphe.

Gras et Italique

    Gras : Utilisez deux astérisques (**) ou deux tirets bas (__).
    Italique : Utilisez un astérisque (*) ou un tiret bas (_).

Exemple :

**Ceci est du texte en gras**
__Ceci est aussi du texte en gras__

*Ceci est du texte en italique*
_Ceci est aussi du texte en italique_

Listes
Liste non ordonnée

Les listes non ordonnées sont créées avec des astérisques (*), des tirets (-), ou des plus (+).

Exemple :

- Élément 1
- Élément 2
  - Sous-élément 1
  - Sous-élément 2

Liste ordonnée

Les listes ordonnées utilisent des numéros suivis d'un point (1.).

Exemple :

1. Premier élément
2. Deuxième élément
   1. Sous-élément A
   2. Sous-élément B

Liens

Les liens sont créés en utilisant des crochets ([]) pour le texte du lien et des parenthèses (()) pour l'URL.

Exemple :

[Google](https://www.google.com)

Images

Les images sont insérées de manière similaire aux liens, mais avec un point d'exclamation (!) avant les crochets.

Exemple :

![Texte alternatif](https://example.com/image.jpg)

Citations

Les citations sont créées en utilisant le symbole >.

Exemple :

> C'est une citation célèbre.

Code
Code en ligne

Le code en ligne est encadré par des backticks (`).

Exemple :

Voici un exemple de `code en ligne`.

Bloc de code

Les blocs de code sont créés en entourant le code avec trois backticks (```).

Exemple :

Voici un bloc de code. Il peut être multi-lignes.

Code avec syntaxe spécifique

Si vous souhaitez spécifier la syntaxe du code (par exemple, pour les langages de programmation), ajoutez le nom du langage après les trois backticks.

Exemple :

```python
def hello():
    print("Hello, world!")


### Tableaux

Les tableaux sont créés en utilisant des tirets (`-`) pour les lignes et des barres verticales (`|`) pour séparer les colonnes.

**Exemple** :
```markdown
| Nom      | Âge | Ville     |
|----------|-----|-----------|
| Alice    | 25  | Paris     |
| Bob      | 30  | New York  |
| Charlie  | 35  | Londres   |

Séparateurs

Un séparateur est une ligne horizontale, créé avec trois tirets (---), trois astérisques (***) ou trois underscores (___).

Exemple :

---

Emoticônes

Les émoticônes peuvent être insérées en utilisant les codes de GitHub ou de Slack.

Exemple :

:smile: :heart: :rocket:

Escaper les caractères spéciaux

Pour afficher des caractères spéciaux, vous pouvez les échapper avec une barre oblique inverse (\).

Exemple :

\*Cela sera affiché comme du texte normal, pas du texte en italique\*
