---
title: "Documentation"
menu: "main"
weight: 2
---

### The MULTIBINIT Ecosystem

The **MULTIBINIT ecosystem** began as a software platform designed for the automatic construction of atomic potentials using second-principles models. These models are essential for enabling large-scale molecular dynamics simulations. Over time, the platform has evolved into a comprehensive ecosystem, incorporating additional degrees of freedom such as magnetism and electronic structures. The MULTIBINIT ecosystem now includes a wide range of actively developed software tools.

#### Key Components of the MULTIBINIT Ecosystem

1. **[MULTIBINIT-Lattice]()**:
   This is the foundational module of MULTIBINIT. It focuses on constructing atomic potentials and is implemented in the initial version of the MULTIBINIT software.

2. **[MULTIBINIT-Spin](https://docs.abinit.org/tutorial/spin_model/)**:
   This module implements atomistic spin dynamics based on the extended Heisenberg model and Landau-Lifshitz-Gilbert equations. It is designed to integrate seamlessly with MULTIBINIT-Lattice, enabling spontaneous spin-lattice dynamics.

3. **MULTIBINIT-LWF**:
   A sub-package of MULTIBINIT, this module specializes in lattice dynamics using Lattice Wannier Functions (LWFs).

4. **Agate** and **QAgate**:
   - [Agate](https://github.com/piti-diablotin/agate): A software tool for visualizing and post-processing simulation results from MULTIBINIT and ABINIT.
   - [QAgate](https://github.com/piti-diablotin/qagate): A quantum-focused extension of Agate for advanced post-processing tasks.

5. **[TB2J](https://tb2j.readthedocs.io/)**:
   Initially developed to provide parameters for spin models in MULTIBINIT, TB2J has become a versatile tool for spin interaction calculations.

6. **[LaWaF](https://lawaf.rtd.io)**:
   A package dedicated to constructing Lattice Wannier Functions (LWFs) and building minimalist atomic potential models. It also supports the creation of other Wannier functions, such as electron and magnon Wannier functions.

7. **Matjes**:
   A feature-rich spin dynamics and Monte Carlo simulation code. Matjes includes advanced features like high-order spin interactions, making it a powerful tool for complex simulations.

8. **[ABINIT](https://www.abinit.org/)**:
   The MULTIBINIT software is developed and deployed within the broader **ABINIT project**, a well-established initiative for first-principles calculations. MULTIBINIT leverages ABINIT outputs to train its atomic models, ensuring a robust and integrated workflow.

