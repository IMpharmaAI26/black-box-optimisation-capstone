**Summary**
The Week 6 inputs and outputs were matched across all eight functions and appended to the complete observation history. Functions 2, 4 and 5 achieved new best values. Function 3 repeated its best value, while Functions 7 and 8 remained effectively at their identified maxima. Function 1 remained uninformative and Function 6 confirmed severe local sensitivity. The seventh-round plan therefore combines one coverage-based exploration, four evidence-led local steps, one reverse sensitivity test and two near-optimum controls.

**Week 6 results**

<img width="789" height="322" alt="image" src="https://github.com/user-attachments/assets/c3176293-25e1-4ad3-a17a-974074e89b25" />

Function 5 made the largest numerical gain at 89.154146. Function 2 improved by 0.078937 and Function 4 by 0.011148. Function 3 was unchanged. Function 6 remained 0.160765 below its best after a one-millionth x1 change, so the next test moves to the opposite side of the best observed point.

**Seventh round portal queries**

<img width="790" height="374" alt="image" src="https://github.com/user-attachments/assets/4e26e5d3-bfa7-470f-a4f8-5ffbac5c4c2f" />


**Function specific rationale**

Function 1  Maximin exploration  The sixth-round point returned an almost zero value and did not identify a useful basin. The proposed boundary point maximises its minimum distance from all 16 sampled locations, adding the greatest available spatial coverage.

Function 2  Micro-step exploitation  Reducing x2 by one millionth produced a new best of 0.707345. The same controlled x2 step is repeated while x1 remains fixed, preserving a directly observed local direction.

Function 3  Tuned local step  The latest one-millionth x1 change produced no measurable improvement. The step is increased to one ten-thousandth in the positive x1 direction, which the compact polynomial model favours, while the other inputs remain fixed.

Function 4  Expanded directional step  Three successive positive x1 steps improved the result. The step is increased from 0.001 to 0.002 to test whether the confirmed rise continues without changing the other coordinates.

Function 5  Proven line continuation  Every completed move along the same four-variable direction has raised the objective, including a Week 6 gain of 89.154146. The seventh query applies one more equal vector step.

Function 6  Reverse sensitivity test  A positive one-millionth x1 change remained well below the best result. The query returns to the best setting and tests the opposite x1 direction by one millionth while retaining x5 at 0.000001.

Function 7  Near-optimum control  The Hartmann six optimum remains identified to six-decimal precision. This unused adjacent point has the smallest calculated loss among available one-millionth coordinate changes.

Function 8  Near-optimum control  The separable quadratic optimum still returns 10. The least-curved coordinate x8 is moved upward by one additional millionth to create a new admissible point with negligible expected loss.

**Hyperparameter tuning decisions**
Tuning focused on parameters that change effective model complexity or the size of the next experiment. Compact searches and leave-one-out validation were used because the datasets remain small, while each returned portal value was treated as the decisive out-of-sample check.
