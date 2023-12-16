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
|---------------------------|----------------------------|--------------|
| $C$ (constante)           | $0$                        | $\mathbb{R}$ |
| $mx$                      | $m$                        | $\mathbb{R}$ |
| $mx+p$                    | $m$                        | $\mathbb{R}$ |
| $x^n$ ($n\neq 0$)         | $n\times x^{n-1}$                 | $\mathbb{R}$ |
| $\frac{1}{x}$             | $-\frac{1}{x^2}$           | $\mathbb{R}^*$|
| $\sqrt{x}$                | $\frac{1}{2\sqrt{x}}$      | $\mathbb{R}^+$|
| $e^{nx}$                  | $ne^{nx}$                  | $\mathbb{R}$ |

# Formules de dérivation : 
On considère $u$ et $v$ deux fonctions dérivables sur un intervalle $\mathbb{I}$ et $k$ un réel fixe.

| Fonction                          | Fonction dérivée                            | Dérivabilité |
|-----------------------------------|---------------------------------------------|--------------|
| Somme $f(x) = u + v$              | $f'(x) = u' + v'$                           | $\mathbb{I}$ |
| Produit par k $f(x) = ku$         | $f'(x) = ku'$                               | $\mathbb{I}$ |
| Produit $f(x) = uv$               | $f'(x) = u'v + uv'$                         | $\mathbb{I}$ |
| Inverse $f(x) = \frac{1}{u}$      | $f'(x) = -\frac{u'}{u^2}$                    | $\mathbb{I}$ où $u$ non nul |
| Quotient $f(x) = \frac{u}{v}$     | $f'(x) = \frac{u'v - uv'}{v^2}$              | $\mathbb{I}$ où $v$ non nul |
| Carré $f(x) = u^2$                | $f'(x) = 2u'\times u$                              | $\mathbb{I}$ |
| Composée $f(x) = u(ax + b)$       | $f'(x) = au'(ax + b)$                       | $\mathbb{I}$ |

Quelques cas particuliers (en rapport avec la [[Dérivée seconde]]) :

| Fonction                   | Fonction dérivée          | Dérivabilité         |
|----------------------------|---------------------------|----------------------|
| Puissance $f(x)=u^n$          | $f'(x)=nu'u^{n-1}$        | $\mathbb{I}$         |
| Racine carrée $f(x)=\sqrt{u}$ | $f'(x)=\frac{u'}{2\sqrt{u}}$ | $\mathbb{I}$ où $u>0$ |
| Exponentielle de e $f(x)=e^u$ | $f'(x)=u'e^u$            | $\mathbb{I}$         |
