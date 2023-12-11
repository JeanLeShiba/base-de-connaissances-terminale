---
tags:
  - hors-cours
auteurs:
  - Jean-François
complété: false
---
Pour construire une base commune de connaissances, il est nécessaire d'imposer des règles sur le format des notes et la manière de réaliser les synthèses de cours.
# 1. Format d'une page
Lorsque vous créez une nouvelle note dans un dossier matière, celle-ci doit comporter **un titre explicite** (idéalement simple ou celui du cours) et des **propriétés définies**.

Pour ajouter des propriétés, commencez par marquer `---` (trois tirets consécutifs) en haut de la page. Vous pourrez ainsi ajouter des tags, le prénom des auteurs, indiquer si le contenu est complet et, optionnellement, des alias.
## Tags
Dans la catégorie des tags, incluez le nom de la matière et les concepts clés abordés dans le cours. Par exemple, pour une note sur [[Vecteurs de l'espace]], les tags pourraient être #maths et #maths-vecteurs.

>Note : Les noms des notions doivent suivre le format "matière-notion", séparés par un trait d'union.
## Auteurs
Il est important d'insérer votre prénom lors de la création ou la contribution à une note. Cela permet de garder une trace des participants et facilite la communication en cas de besoin de clarification ou de débat sur l'exactitude des informations ou la méthodologie employée.
# 1.5 Formatage markdown
Pour ceux qui ne sont pas familiers avec le markdown, voici un guide rapide :

| Élément de contenu | Syntaxe | Rendu |
|--------------------|---------|-------|
| En-tête            | `# H1`<br>`## H2`<br>`### H3` | *Rendu visible sur cette note.* |
| Gras               | `**texte en gras**` | Voici comment rendre le texte **en gras** |
| Italique           | `*texte en italique*` | Voici comment mettre un texte en *italique* |
| Citation           | `> citation` | Utilisez `>` pour citer un texte. *Rendu visible sur cette note.* |
| Liste ordonnée     | `1. Élément`<br>`2. Élément`<br>`3. Élément` | 1. Premier élément<br>2. Deuxième élément<br>3. Troisième élément |
| Liste non ordonnée | `- Élément`<br>`- Élément`<br>`- Élément` | - Premier élément<br>- Deuxième élément<br>- Troisième élément |
| Séparation horizontale  | `---` | Utilisez `---` pour une séparation claire. *Rendu visible au bas de la page.*
| Lien               | `[Texte](URL)` | Pour insérer un lien : [Exemple](http://exemple.com) |
| Image              | `![Alt](image.jpg)` | Pour insérer une image : `![Description](lien.jpg)`. *Rendu impossible sur un tableau.* |

Pour du code, utilisez trois backticks `` ` `` *(ALT GR + touche è)* avant et après le code. Préciser le langage, comme `python`, active la coloration syntaxique. Exemple :
```python
def find_divisors(num):
    divisors = []
    for i in range(1, num + 1):
        if num % i == 0:
            divisors.append(i)
    return divisors
```

Les expressions mathématiques s'insèrent entre deux `$` pour une ligne ou `$$` pour un bloc :
$$
f(x) = ax^2 + bx + c
$$
>Apprenez en plus en suivant [ce guide](https://lizengo.fr/productivite/comment-ecrire-des-notations-mathematiques-dans-obsidian/) sur les notations mathématiques dans Obsidian.

# 2. Synthèse
La synthèse de chaque cours doit être concise et claire. Elle doit résumer les points clés, les formules importantes et inclure des exemples pour illustrer les concepts. Chaque synthèse doit commencer par une brève introduction du sujet ou une définition, suivie des titres des sections principales, et se terminer par une conclusion récapitulative (+ optionnellement des sources).

Utilisez des listes à puces pour énumérer des éléments et des tableaux pour présenter des données comparatives ou chronologiques. Les images, diagrammes ou graphiques sont encouragés pour une compréhension visuelle des concepts.

Je vous invite à faire cela à votre manière, mais si vraiment vous ne savez pas trop par où commencer, inspirez vous des notes des autres ou de celle-ci.
## Liens internes
Si Obsidian a été choisi c'est parce que le logiciel propose des moyens de lier des idées et des notes entre elles (un peu comme le fonctionnement du web), ce qui peut s'avérer très utile lorsqu'un chapitre nécessite des notions d'un autre.

Pour créer un lien avec une note, créez deux crochets `[[]]` dans lequel vous insérerez la note que vous souhaitez référer. Exemples :

| Markdown | Rendu |
|------------|--------|
| `[[Méthodologie]]` | [[Méthodologie]] |
| `[[Méthodologie#Notions fondamentales]]` pour faire référence à une sous partie | [[Méthodologie#Notions fondamentales]] |
## Notions fondamentales
Dans chaque dossier de matière, vous êtes en possibilité de créer un dossier `Notions fondamentales` qui contiennent des notions qui se doivent d'êtres maîtrisées ou qui méritent d'être revues afin de comprendre pleinement un chapitre par exemple.
# Mise à jour
Blablabla flemme de rédiger krkrkrkr

---

>Voilà ! C'est tout. Après avoir lu cette note vous devriez avoir une vision globale de comment tout doit être agencé. Si vous avez toujours des questions, n'hésitez pas à en faire notice à Jean-François sur Discord.