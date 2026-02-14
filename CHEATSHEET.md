# 🧬 Cheatsheet: RNA Thermoswitch Design
**File:** `rna-thermoswitch-design/CHEATSHEET.md`

### 1. The Variables
| Variable | Scientific Name | What it represents |
| :--- | :--- | :--- |
| **`Tm`** | **Melting Temp** | The "Switch Point": Temperature where 50% is unfolded. |
| **`n`** | **Hill Coefficient** | **Cooperativity:** How "sharp" or "binary" the switch is. |
| **`MFE`** | Thermodynamic Stability | Energy needed to hold the shape. Lower = more stable. |
| **`RBS`** | Target Region | The part of RNA the ribosome must "grab" to start. |

### 2. The Logic & The "Why"
*   **The Hill Equation:** We used non-linear curve fitting. *Why?* Biology doesn't happen in straight lines. The Hill Equation captures the "S-Curve" (Sigmoidal) nature of molecular folding.
*   **XGBoost Upgrade:** Linear Regression ($R^2=0.80$) missed the complex folding physics. XGBoost ($R^2=0.90$) uses **Gradient Boosted Decision Trees** to capture non-linearities, providing a 12% boost in accuracy.

### 3. Interview Script
> "I replicated my MSc research but upgraded the architecture. By implementing **XGBoost**, I achieved an $R^2$ of 0.90. This effectively solves the 'Computational Bottleneck' by allowing us to screen 50,000 sequences in milliseconds rather than hours of thermodynamic simulation."

