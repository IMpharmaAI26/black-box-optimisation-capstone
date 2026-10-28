Week 3 inputs and outputs were matched across all eight functions and appended to the original and earlier weekly observations. Week 3 produced new best values for Functions 2, 4 and 5. Functions 7 and 8 remained effectively at their identified maxima. Functions 1, 3 and 6 did not improve, so the fourth-round strategy combines targeted exploration, local surrogate refinement, empirical gradient testing and exact near-optimum perturbations.

**Week 3 results**

<img width="805" height="253" alt="image" src="https://github.com/user-attachments/assets/c37ac042-18ec-46d9-a974-a4d43c0aa6b9" />

The strongest gain was Function 5 (+72.0850). Function 2 exceeded its previous best by 0.0172033. Function 4 gained 0.000008217 after changing only x1 by one millionth, providing a clean local directional signal. Function 6's tests on both sides of its Week 1 point were worse, which supports interpolation between those points rather than another extrapolation.

**Fourth-round portal queries**

<img width="795" height="330" alt="image" src="https://github.com/user-attachments/assets/c6a33601-9e72-43ad-8bd8-128c6f7b4a6e" />


**Function-specific rationale**

Function 1 - Explore. Largest remaining unsampled corner; avoids repeating the near-zero Week 3 region.

Function 2 - Exploit. An anisotropic Gaussian-process mean peaks near x1 = 0.6963 and pushes x2 to its upper boundary.

Function 3 - Local refine. Returns to the best basin; RBF-SVR and neural-surrogate gradients favour slightly lower x1/x2 and higher x3.

Function 4 - Controlled step. A +0.000001 change in x1 improved the score; a cautious +0.001000 step isolates that observed gradient.

Function 5 - Directional exploit. Continues the same four-variable step that has improved yield in three consecutive evaluations.

Function 6 - Quadratic refine. Fits the three collinear local tests and samples their estimated one-dimensional maximum.

Function 7 - Exact local exploit. Combines the best six-decimal coordinates tested separately around the Hartmann-6 maximum.

Function 8 - Exact local exploit. Retains the fitted separable-quadratic optimum and perturbs the least-curved coordinate by two millionths.
