# A phase-field model for electro-mechanical fracture with an open-source implementation of it using Gridap in Julia

In this paper, we propose a phase-field model for electro-mechanical fracture in brittle materials and provide an open-source implementation of the proposed model using a newly 
developed finite element (FE) toolbox, Gridap in Julia. Here, we have considered electric potential as an additional kinematic descriptor along with the displacement and phase-field
variable. Using the virtual power principle, we have derived force balances for the electro-mechanical forces and a force balance associated with the damage. To incorporate the strong 
electro-mechanical coupling effect into the model, we have considered the Helmholtz free energy as a function of the electric field vector, strain tensor, phase-field variable, and the
gradient of the phase-field variable. The proposed model ensures that the constitutive relations of the thermodynamic fluxes are on the satisfaction of the thermodynamic laws and can 
readily accommodate dissipative energy effects whenever needed. The proposed model provides complex crack paths as a solution to the governing partial differential equations (PDEs), 
and thus bypasses the need for re-meshing, enrichment of FE shape functions, and an explicit tracking of the crack surfaces. The use of Gridap makes the FE implementation of the proposed
model exceedingly compact and user-friendly requiring very low memory usage and providing a high degree of flexibility to the users in defining weak forms of the governing PDEs. We have 
validated the proposed model and its implementation against a compact tension test on a single edge notched plate and a set of three-point bending tests on a notched beam made of lead
zirconium titanate (PZT)-4 piezoelectric ceramics.

# See the details using the link below:

https://journals.sagepub.com/doi/abs/10.1177/10812865221133860

# Cite this article:

@article{behera2023phase,
  title={A phase-field model for electro-mechanical fracture with an open-source implementation of it using Gridap in Julia},
  author={Behera, Akash Kumar and Unnikrishna Pillai, Ayyappan and Rahaman, Mohammad Masiur},
  journal={Mathematics and Mechanics of Solids},
  volume={28},
  number={8},
  pages={1877--1908},
  year={2023},
  publisher={SAGE Publications Sage UK: London, England}
}
