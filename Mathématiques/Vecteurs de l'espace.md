---
tags:
  - maths
  - maths-vecteurs
auteurs:
  - Jean-François
complété: 
aliases:
  - Vecteurs dans l'espace
---
Un vecteur dans l'espace est un objet mathématique représentant une grandeur ayant une direction, un sens et une norme. Il est souvent visualisé comme une flèche partant d'un point à un autre dans un espace tridimensionnel.

>Avant de continuer, il est recommandé d'aller voir les rappels sur les vecteurs dans [[Vecteurs dans le plan]], afin de revoir des choses comme la *relation de Chasles* et d'autres notions.

# Combinaison linéaire
Soit 3 vecteurs $\vec{u}$, $\vec{v}$ et $\vec{w}$.
On dit que $\vec{w}$ est **combinaison linéaire** des vecteurs $\vec{u}$ et $\vec{v}$ s'il existe deux réels $a$ et $b$ tels que : $$\vec{w}=a \vec{u} + b \vec{v}$$
## Application
$ABCD$ est un tétraèdre avec $I$ milieu de $[AB]$ et $J$ un point sur $[CD]$.
![[Pasted image 20231216130446.png]]
Pour exprimer $\vec{IJ}$ comme une combinaison linéaire des vecteurs $\vec{AB}$, $\vec{AC}$ et $\vec{AD}$ :
$$\vec{IJ}=\vec{IB}+\vec{BJ}=\frac{1}{2}\vec{AB}+\frac{3}{4}\vec{BC}+\frac{1}{4}\vec{BD}$$
$$\vec{IJ}=\frac{1}{2}\vec{AB}+\frac{3}{4}\vec{BA}+\frac{3}{4}\vec{AC}+\frac{1}{4}\vec{BA}+\frac{1}{4}\vec{AD}$$
$$\vec{IJ}=-\frac{1}{2}\vec{AB}+\frac{3}{4}\vec{AC}+\frac{1}{4}\vec{AD}$$
# Colinéarité
