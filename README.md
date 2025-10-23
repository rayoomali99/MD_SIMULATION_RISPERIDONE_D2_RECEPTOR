# 🧬 Molecular Dynamics (MD) Simulation: Risperidone – D2 Dopamine Receptor (6CM4)

### 🧠 Overview
This project performs a **Molecular Dynamics (MD) simulation** for the Risperidone–D2 Dopamine receptor complex (PDB ID: 6CM4).  
The simulation was conducted using **GROMACS** to assess the **structural stability, density, pressure, and temperature** of the complex over the 5 ns trajectory.

---

### ⚙️ System Setup
| Step | File | Description |
|------|------|-------------|
| 1 | `minimized_complex.pdb` | Energy-minimized complex before solvation |
| 2 | `em.mdp`, `em.gro` | Energy minimization input/output |
| 3 | `ions.mdp`, `topol.top`, `lig.itp` | Ion addition and topology generation |
| 4 | `NVT.mdp`, `nvt.gro` | NVT equilibration – constant volume |
| 5 | `NPT.mdp`, `npt.gro` | NPT equilibration – constant pressure |
| 6 | `MD.mdp`, `md.tpr`, `md.edr` | 5 ns production run |
| 7 | `density.xvg`, `pressure.xvg`, `temp.xvg`, `volume.xvg`, `epot.xvg` | Thermodynamic output plots |

---

### 🧪 Simulation Details
- **Software:** GROMACS 2023  
- **Force Field:** CHARMM36  
- **Water Model:** TIP3P  
- **Temperature:** 300 K (NVT phase)  
- **Pressure:** 1 bar (NPT phase)  
- **Simulation Time:** 5 ns  
- **Integrator:** Leap-frog (2 fs time step)  

---

 ### 📊 Output Summary
During the 5 ns MD run:
- Simulation completed successfully without instabilities or energy divergence.
- Density, temperature, and pressure files were generated for system evaluation.
- Further post-analysis (RMSD, RMSF, SASA, Rg, FEL) is required to confirm structural stability.


---

### 📁 Files Included
em.gro
ions.mdp
lig.itp
NVT.mdp
NPT.mdp
MD.mdp
md.tpr
topol.top
density.xvg
pressure.xvg
temp.xvg
volume.xvg
epot.xvg
minimized_complex.pdb

---

### 🧍‍♀️ Author
**Reem Mohamednur**  
Bioengineer | Research Intern  
📍 Riyadh, Saudi Arabia  
[LinkedIn](https://www.linkedin.com/in/reem-mohamednur-924a54244) | [GitHub](https://github.com/rayoomali99)

---

> “Each atom dances to the rhythm of molecular dynamics.”



