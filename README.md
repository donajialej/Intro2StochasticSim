# Introduction to numerical methods for stochastic models.

In this repository, you will find the worksheet for the NICER workshop by ADHR and AJL

## Workshop description

Many ODE based models, such as SIR and Lotka-Volterra models, represent complex systems involving many interacting individuals as simple deterministic models, with continuous time and variables. This method is correct at some scales of the analysis, but at other scales the intrinsic noise of the system is important to consider.

In this workshop we will focus on this intrinsic noise of the system; the noise coming from the underlying physical processes (the number of infected people, the variability of the susceptible people, the contact process.). You and your teammates will construct and simulate stochastic epidemic models, assuming either discrete or continuous population sizes (with half of the participants focused on each). We’ll explore a particular SIS type epidemic model, and study when each of the two algorithms is most appropriate. All participants will become familiar with both continuous and discrete stochastic modeling by the end of the workshop and will be able to use them when appropriate.

1. Gillespie’s Algorithm - Discrete variables: Epidemics do not consist of a continuous mass of sick and healthy people, but are instead made out of many interacting individuals. In this part or the workshop, we consider models at the micro scale; tracking discrete events and population counts using the Gillespie algorithm. Students will implement and explore Gillespie’s algorithm using Python, and explore its effectiveness in a variety of parameter regimes. This part of the workshop will be led by Alastair.
1. Stochastic differential equations - Continuous variables: This part of the workshops will be led by Alejandra. We will consider and construct stochastic differential equations (SDE) models equivalent to the common epidemic models. We will have an introduction of what the SDE model represents but we will not get into the theory of SDE. We will focus on the construction of models and simulation of tracks. 

### Prior reading/prerequisites:
- Students should be familiar with at least one `scripting’ language (such as R, python, matlab, julia or Octave).
- Please have Python installed on your computer (3.5 or higher), along with a suitable workbook program (such as Jupyter notebook) to work with, and the python package “numpy”. Make sure these are all working before the workshop, as there will not be time during the workshop to get them set up.
- You should have familiarity with basic probability theory, and either (1) Markov chains (2) central limit theorem and a basic knowledge of Brownian noise. If you are unfamiliar with these topics, please look them up before attending.
- You do not need to be familiar with Gillespie’s algorithm or Stochastic Differential Equations.
- A more detailed reading list is the file: __Prereading.pdf__

