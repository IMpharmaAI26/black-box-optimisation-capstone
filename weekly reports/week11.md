**Summary**

The Week 10 inputs and outputs were matched across all eight functions and appended to the complete history. The dataset now contains 255 paired observations. Functions 4 and 5 produced new best values. Functions 7 and 8 remained effectively at their known maxima. Functions 2, 3 and 6 did not improve, while Function 1 remained unresolved because its values are numerically tiny across most sampled points.

**Week 10 results**

<img width="789" height="309" alt="image" src="https://github.com/user-attachments/assets/0a4782de-95e4-4326-aa33-a702e8fa3e25" />

Function 5 made the largest numerical gain at 118.463354, and Function 4 improved by 0.031615. Function 2 remained 0.039683 below its best; Function 3 remained 0.019938 below; and Function 6 remained 0.045936 below. Functions 7 and 8 stayed within the reporting tolerance of their maxima. Function 1 was also an effective numerical tie, but this does not establish a useful optimum because almost all observed outputs are close to zero.

**Eleventh round portal queries**

<img width="789" height="338" alt="image" src="https://github.com/user-attachments/assets/7a229b15-d553-4936-8558-85a2a37ec2ff" />

**Function specific rationale**
Function 1  Maximin exploration  No stable high-output cluster has emerged. A fixed-seed maximin search selected the rounded point whose nearest sampled neighbour is approximately 0.223 away. This broadens coverage instead of treating numerically tiny values as a reliable local trend.

Function 2  Boundary cluster extension  The strongest observations form a compact group around x1 = 0.696 and x2 near 0.999. The proposal keeps the apparent centroid coordinate x1 fixed and advances x2 by one millionth beyond the latest point to test whether the high boundary region persists.

Function 3  Orthogonal local test  The best observations form a narrow group around (0.492582, 0.611593, 0.340176). Recent x2 tests did not improve the best, so the proposal restores x2 and changes only x3 by one millionth. This separates a genuine local gradient from noise.

Function 4  Directional cluster continuation  A sequence with x2, x3 and x4 fixed has improved as x1 increased. Week 10 created a new best, so the proposal repeats the observed 0.002 step in x1 and leaves every other coordinate unchanged.

Function 5  Boundary-tightened line continuation  The highest outputs lie on one correlated four-variable path, and Week 10 produced another large gain. The next step follows the same direction but is shortened so x4 reaches 0.999999 without leaving the permitted range.

Function 6  Reverse local bracket  The best point remains isolated inside a highly sensitive local group. Increasing x3 by one millionth did not improve the score. The proposal returns to the best values and tests the equal step below x3, changing only one coordinate.

Function 7  Near-optimum neighbour  Repeated points form a dense near-optimal group around the identified Hartmann-six maximum. The proposal uses a previously untested one-millionth change in x5, preserving performance while satisfying the requirement for a distinct query.

Function 8  Near-optimum neighbour  The observed points cluster tightly around the separable quadratic maximum and continue to return 10 within numerical tolerance. A symmetric five-millionth reduction in x8 creates a new input with negligible expected loss.
