# Model Calibration Examples

## Brief description

This project has different examples of model calibration from:

- Physics
- Chemistry
- Epidemiology
- System Dynamics

Different examples illustrate different techniques or calibration application to different problem domains. 

There a couple of tutorials with that deal with progressively more challenging problems: 

- "Calibration of System Dynamics Models Tutorial", Part 1
  
    - Small Epidemiological Compartmental Models (ECMs)
 
- "Calibration of System Dynamics Models Tutorial", Part 2

    - Large ECMs
  
## Bigger picture

This project does not deal with the 
[bigger picture](https://github.com/antononcube/SystemModeling/raw/master/Projects/Coronavirus-propagation-dynamics/Diagrams/Model-development-and-decision-making.jpeg)
of the place and formal organization of the calibration process. 
(In research, teams, etc.)

These two documents show the interaction the stakeholders, modelers, and calibrators:

- ["Modelers questionnaire"](https://github.com/antononcube/SystemModeling/blob/master/org/Modelers-questionnaire.org)

- ["Calibrators questionnaire"](https://github.com/antononcube/SystemModeling/blob/master/org/Calibrators-questionnaire.org)

## Epidemiological examples 

This mind-map gives a fairly good idea of what is the reasoning and organization behind the ECM documents and examples:

[![](./Diagrams/Calibration-of-System-Dynamics-models-mind-map.png)](./Diagrams/Calibration-of-System-Dynamics-models-mind-map.pdf)

## Programming languages

Most of the examples are with Mathematica / Wolfram Language (WL).

Some examples, especially epidemiology related ones, are also planned to be programmed in R. 

The directory [WL-notebooks](./WL-notebooks) has WL notebooks that can be used for run the examples.

## References

### Mathematica functions

- [`NDSolve`](https://reference.wolfram.com/language/ref/NDSolve.html)

- [`NMinimize`](https://reference.wolfram.com/language/ref/NMinimize.html)

- [`ParametricNDSolve`](https://reference.wolfram.com/language/ref/ParametricNDSolve.html)
  
### Mathematica tutorials

- ["Advanced Numerical Differential Equation Solving in the Wolfram Language](https://reference.wolfram.com/language/tutorial/NDSolveOverview.html)

- ["Constrained Optimization"](https://reference.wolfram.com/language/tutorial/ConstrainedOptimizationOverview.html)

- ["Numerical Nonlinear Global Optimization"](https://reference.wolfram.com/language/tutorial/ConstrainedOptimizationGlobalNumerical.html)
