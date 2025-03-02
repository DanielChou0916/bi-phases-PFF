# Bi-Phases Phase-Field Fracture (PFF) Model

This repository provides an example of a **Phase-Field Fracture (PFF) model** applied to **bi-phases materials** in a **2D plane strain condition**—specifically, **cemented-aggregates (concrete)**.

## 📌 Phase-Field Energy Split Formulation

The phase-field formulation used in this study is based on:

> **Navidtehrani, Yousef, Covadonga Betegon, and Emilio Martinez-Paneda (2022).**  
> *A general framework for decomposing the phase field fracture driving force, particularised to a Drucker–Prager failure surface.*  
> Theoretical and Applied Fracture Mechanics, **121**, 103555.  
> [DOI: 10.1016/j.tafmec.2022.103555](https://doi.org/10.1016/j.tafmec.2022.103555)

This approach provides a **relatively simple way to incorporate material strength parameters** through the **Drucker–Prager yield criterion**.

---

## 🛠 Key Features

1. **Explicit Stress Decomposition**  
   - The **activated** and **inactivated** stress components are explicitly derived based on the energy-splitting method proposed in the literature.  

2. **Implementation in MOOSE**  
   - MOOSE does not inherently support this particular phase-field formulation.  
   - This repository demonstrates how to **implement the method into MOOSE** for bi-phases materials.  

---

## 🔧 Simulation Setup

- **Loosely coupled system**:  
  - Equilibrium / **Linear Elasticity**  
  - **Phase-Field Damage** evolution  

---

## 🚀 Future Work

- Extend this formulation to a **3D numerical model** for more realistic simulations.  

---

## 📫 Contact

For questions or discussions, feel free to reach out via [LinkedIn](https://linkedin.com/in/daniel-t-chou-1b51661b2).  
