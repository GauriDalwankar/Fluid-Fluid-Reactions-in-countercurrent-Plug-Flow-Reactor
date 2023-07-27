# Fluid-Fluid-Reactions-in-countercurrent-Plug-Flow-Reactor

## Overview

This project focuses on the study and application of fluid-fluid reaction systems, which are a vital part of most chemical industries. The principal aim is to decrease the concentration of gaseous impurities in air to a specified level using two different methods: physical absorption and chemical absorption. We leverage mass transfer mechanisms for the former and add a liquid reactant for the latter. 

The system's complexities require us to make several assumptions, including one-phase dissolution, liquid-phase reactions only, solution diluteness, countercurrent contacting, and instantaneous reactions between reactants. To navigate these complexities, we've applied Henry's Law and the two-film theory extensively. 

## Approach

Our approach is grounded in material balance analysis for each system component. We then derive an overall rate expression for each component's balance equation. The project revolves around managing materials across two phases and ensuring proper contact between these phases for effective reactions. 

Python's 'solve_bvp' function is used to solve a system of Ordinary Differential Equations (ODEs) and overall rate expressions, with 'interp1d' for interpolation purposes.

## Key Features

1. Detailed exploration of fluid-fluid reaction systems.
2. Comprehensive analysis of mass transfer and chemical reactions.
3. Python-based solver implementation for system equations.
4. Extensive use of Henry's Law and the two-film theory.
5. Documentation of results and discussions for each problem.
   
## Assumptions

1. Gaseous impurities dissolve in their liquid phase, not vice versa.
2. Chemical reactions occur only in the liquid phase.
3. The solution is dilute.
4. The system operates under a countercurrent contacting scheme.
5. The reaction between the two reactants is instantaneous.

## Results

Through rigorous material balance analysis and solver implementation, we've developed a fluid-fluid reaction system model capable of effectively reducing gaseous impurities in air. The results have been thoroughly documented and discussed for each problem.

## Conclusion

This project offers valuable insights into fluid-fluid reaction systems and their application in air purification. Our study opens up possibilities for further research in improving existing models and developing more efficient purification techniques.

## Note

The project assumes a reasonable understanding of chemical engineering principles, particularly those related to fluid-fluid reaction systems and mass transfer operations.
