---
tags:
  - maths
  - maths-dérivée
  - maths-convexité
auteurs:
  - Jean-François
complété: 
aliases:
  - Convexité
---
La dérivée seconde d'une fonction $f$ est la *dérivée de la dérivée*. Elle se note $f''$.

>Avant de continuer je vous conseille de revoir [[Dérivation#Formules de dérivation]] si ce n'est pas pleinement acquis.

Un exemple :
$$f(x)=4e^{2x}+2$$
$$f''(x)=(8e^{2x})'=16e^{2x}$$

Elle joue un rôle crucial dans l'étude de la courbure de la courbe représentative de cette fonction. Elle permet de déterminer les intervalles où la fonction est **convexe** ou **concave**, ainsi que les **points d'inflexion**.
## Convexité et Concavité
Une fonction est dite **convexe** sur un intervalle si, pour tous points $A$ et $B$ de cet intervalle, la corde $AB$ se situe au-dessus de la courbe. Mathématiquement, $f$ est convexe sur un intervalle si sa dérivée seconde $f''$ est positive sur cet intervalle.
![[Fct-convexe-01.jpg]]
Courbe d'une fonction convexe sur $[1;6]$.*

Inversement, une fonction est **concave** sur un intervalle si la corde $AB$ se trouve en dessous de la courbe. Ceci correspond à une dérivée seconde $f''$ négative sur l'intervalle.
![[Fct-concave-01.jpg]]
*Courbe d'une fonction concave sur $[1;6]$.*

Un **point d'inflexion** est un point où la courbe change de concavité. Cela se produit lorsque la dérivée seconde change de signe. À un point d'inflexion, $f''(x)=0$ (mais ce n'est pas une condition suffisante).
![[Fct-convexe-concave-01.jpg]]
Sur cette courbe elle se trouve sur $f(2)$.

---
# Application
#### Exemple 1
**Soit $f(x)=x^3-1,5x^2-3x+6$ :**

On dérive une première fois la fonction : $f'(x)=3x^2-3x-3$
Puis une deuxième fois : $f''(x)=6x-3$
On résout $6x-3=0 \leftrightarrow x=0,5$.

Nous pouvons ainsi dresser le tableau suivant :


