# TIPE : Optimisation d'un Moteur Thermique par Injection d'Eau
## Cas d'étude : Système WaterBoost (BMW S55 / M4 GTS)

Ce dépôt contient le script de simulation numérique développé dans le cadre de mon TIPE en filière MP.

### Objectif du Jumeau Numérique
Résoudre pas-à-pas les équations d'état du cycle de Beau de Rochas (Otto) afin de modéliser l'impact thermodynamique de la chaleur latente de vaporisation de l'eau ($L_v$) et quantifier le gain de travail utile induit par le débridage du turbocompresseur.

### Équations Fondamentales Simulées
- Chute de température lors de la vaporisation isochore ($2 \to 2'$) :
  $$T_{2'} = T_2 - \frac{m_{eau} \cdot L_v}{m_g \cdot C_v}$$
- Évolution de la pression sur les phases adiabatiques (Loi de Laplace) :
  $$P_i \cdot V_i^{\gamma} = \text{Cte}$$
