---
tags:
  - maths-dérivée
  - maths
  - maths-exponentielle
  - fondamental
  - maths-ensembles
auteurs:
  - Jean-François
complété: true
---
# Dérivation des fonctions usuelles :

| Fonctions usuelles $f(x)$ | Fonctions dérivées $f'(x)$ | Dérivabilité |
|---------------------------|--------------------------|--------------|
| $C$ (constante)             | $0$                        | $\mathbb{R}$|
| $mx$                    | $m$                    | $\mathbb{R}$|
| $mx+p$                  | $m$                    | $\mathbb{R}$|
| $x^n$ (n entier naturel non nul) | $nx^{n-1}$     | $\mathbb{R}$|
| $\frac{1}{x}$           | $-\frac{1}{x^2}$       | $\mathbb{R}^*$|
| $\sqrt{x}$              | $\frac{1}{2\sqrt{x}}$  | $]0, +\infty[$|
| $e^{nx}$                   | $ne^x$                  | $\mathbb{R}$|
# Formules de dérivation : 
On considère u et v deux fonctions dérivables sur un intervalle I et k un réel fixe.

| Fonction             | Fonction dérivée                           | Dérivabilité         |
|----------------------|--------------------------------------------|----------------------|
| Somme $f(x) = u(x) + v(x)$        | $f'(x) = u'(x) + v'(x)$ | $\mathbb{I}$ |
| Produit par k $f(x) = k*u'(x)$  | $f'(x) = k*u'(x)$       | $\mathbb{I}$ |
| Produit $f(x) = u(x) * v(x)$      | $f'(x) = u'(x) * v(x) + u(x) * v'(x)$ | $\mathbb{I}$ |
| Inverse $f(x) = 1/u(x)$         | $f'(x) = -\frac{u'(x)}{(u(x))^2}$ | dérivable sur l’intervalle $\mathbb{I}$ où $u(x)$ est non nul |
| Quotient $f(x) = u(x)/v(x)$      | $f'(x) = \frac{u'(x) * v(x) - u(x) * v'(x)}{(v(x))^2}$ | dérivable sur l’intervalle $\mathbb{I}$ où $v(x)$ est non nul |
| Carré $f(x) = (u(x))^2$           | $f'(x) = 2 * u'(x) * u(x)$ | $\mathbb{I}$ |
| Composée $f(x) = u(ax + b)$ avec a et b deux nombres réels | $f'(x) = a * u'(ax + b)$ | $\mathbb{I}$ |
