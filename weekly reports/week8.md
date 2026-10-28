**Summary**
The Week 7 inputs and outputs were matched across all eight functions and appended to the observation history. Functions 4 and 5 achieved new best values. Functions 7 and 8 remained effectively at their identified maxima, while Functions 1, 2, 3 and 6 did not improve. The eighth-round plan therefore uses one coverage-based exploration, four controlled local tests, one confirmed line continuation and two near-optimum controls.

**Week 7 results**

<img width="788" height="318" alt="image" src="https://github.com/user-attachments/assets/d4b320fd-9925-48af-b0ff-a6d30e6275c6" />

Function 5 made the largest numerical gain at 95.711491. Function 4 improved by 0.025274. Function 2 fell by 0.110674 after changing x2 by one millionth, while the larger Function 3 x1 step and both Function 6 x1 directions also underperformed. These results support isolated coordinate tests rather than larger local moves for Functions 2, 3 and 6.

**Eighth round portal queries**

<img width="790" height="365" alt="image" src="https://github.com/user-attachments/assets/de4fba58-07b6-4f6c-9f4f-aa4a7388230f" />

**Function specific rationale**

Function 1  Maximin exploration  The seventh-round boundary sample again returned essentially zero. Among admissible six-decimal points, the opposite upper corner provides the largest remaining separation from the 17 observed locations, so it adds coverage without revisiting a known negative pocket.

Function 2  Controlled local probe  The latest one-millionth reduction in x2 lost 0.110674 relative to the best. The new query restores the best x2 value and lowers x1 by one millionth, isolating the other coordinate around the strongest observed setting.

Function 3  Bracketed local test  Increasing x1 by 0.000100 reduced the output. The proposal returns to the best basin and tests the opposite side by one millionth while holding x2 and x3 fixed.

Function 4  Confirmed directional step  The 0.002 increase in x1 produced a new best and the largest gain yet on this local path. One equal 0.002 step is continued while the other coordinates remain unchanged.

Function 5  Proven line continuation  Seven consecutive points along the same four-variable direction have improved the objective. The next query repeats that vector once, remaining inside every input bound.

Function 6  Orthogonal sensitivity test  Both one-millionth x1 perturbations performed poorly. The query returns to the best observed point and changes x2 by one millionth, separating coordinate sensitivity from possible local variability.

Function 7  Near-optimum control  The Hartmann six optimum remains identified to six-decimal precision. This unused x4-adjacent point has the smallest calculated loss among the remaining one-millionth coordinate changes.

Function 8  Near-optimum control  The fitted separable quadratic optimum still returns 10 to numerical precision. The next unused symmetric x8 perturbation preserves the optimum region while satisfying the requirement for a new query.
