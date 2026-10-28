**Summary**

The supplied Week 4 inputs and outputs were matched across all eight functions and appended to the earlier observations. Week 4 produced new best values for Functions 4, 5 and 6. Functions 7 and 8 remained effectively tied at their identified maxima, while Functions 1-3 did not improve. The fifth-round plan therefore combines one coverage-driven exploration, two controlled returns to strong regions, three evidence-based local refinements and two near-optimum control queries.

**Week 4 results**

<img width="786" height="248" alt="image" src="https://github.com/user-attachments/assets/550d6d64-4681-4ddf-887c-280f7895931e" />

Function 5 gained 77.371694 and extended its repeated upward trend. Function 6 improved by 0.089991, validating the local line-search refinement. Function 4 gained 0.008836 after changing only x1, creating a clean directional signal. The Function 2 drop demonstrates sharp local sensitivity, while Function 3 remained close to, but below, its established best.

**Fifth-round portal queries**

<img width="788" height="344" alt="image" src="https://github.com/user-attachments/assets/7c16eb4e-02d1-4a79-847d-8aaeeab7cbe8" />


**Function-specific rationale**

Function 1 - Explore. The latest corner again returned effectively zero. The new point is the farthest unsampled boundary corner under a maximin distance rule, so it increases coverage without revisiting the known negative pockets.

Function 2 - Controlled exploit. Week 4 fell below the 0.628409 best after a very small move. This point returns to the Week 3 high-score region and changes x1 by only one millionth, testing local sensitivity while protecting performance.

Function 3 - Best-region exploit. The Week 4 local candidate was close but did not exceed the existing best. The proposal uses a new six-decimal point immediately beside the strongest observed three-dimensional location.

Function 4 - Confirmed direction. Increasing x1 by 0.001 raised the output by 0.008836 while the other inputs stayed fixed. The next query repeats that isolated step so the observed gradient remains interpretable.

Function 5 - Directional exploit. Four successive points along the same direction have improved the result. The next equal step continues that empirical trend while all coordinates remain comfortably inside the permitted range.

Function 6 - Boundary refine. The quadratic line search produced a major improvement. The new query holds the successful first four coordinates fixed and tests the fifth variable at its exact lower boundary.

Function 7 - Near-optimum control. The Hartmann-6 maximum is already identified to six-decimal precision. A one-millionth change in x4 creates a new admissible point with negligible predicted loss.

Function 8 - Near-optimum control. The separable quadratic optimum remains exactly identified. x8 has the lowest fitted curvature, so a two-millionth downward perturbation preserves an output effectively equal to 10.
