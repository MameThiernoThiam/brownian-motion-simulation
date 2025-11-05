# Brownian Motion Simulation

## 🎯 Objectif du projet
Simulation de trajectoires de mouvement brownien 1D, base des modèles stochastiques utilisés en finance quantitative (ex: modèle de Black–Scholes).

---

## 📈 Exemple de trajectoires

<img src="figures/brownian_paths.png" alt="Trajectoires mouvement brownien" width="500"/>

---

## 🧠 Mathématiques utilisées
Un mouvement brownien standard \(W_t\) vérifie :
- \(W_0 = 0\)
- Incréments gaussiens : \(W_{t+\Delta t} - W_t \sim \mathcal{N}(0, \Delta t)\)

Simulation avec :
\[
W_{t+\Delta t} = W_t + \sqrt{\Delta t} \cdot Z
\]
où \(Z \sim \mathcal{N}(0,1)\).

---

## 🧑‍💻 Installation
```bash
pip install numpy matplotlib
