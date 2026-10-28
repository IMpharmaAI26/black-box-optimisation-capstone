**Summary**

The Week 8 inputs and outputs were matched across all eight functions and appended to the observation history. Functions 4 and 5 achieved new best values and extended their steady improvement paths. Functions 7 and 8 remained effectively at their identified maxima. Functions 1, 2, 3 and 6 did not improve, so the ninth-round plan uses cautious information-gathering tests for those surfaces rather than larger extrapolations.

**Week 8 results**

<img width="793" height="321" alt="image" src="https://github.com/user-attachments/assets/1efbbbc9-249e-4c60-beb1-d611843d865c" />

Function 5 made the largest numerical gain at 102.757515, and Function 4 improved by 0.028487. Both gains exceeded the previous round's improvement, supporting one more equal step. Function 3 and Function 6 recovered from their latest tests but did not beat their running bests. Function 2 declined again around a nearly identical input, confirming that the local response is not reliably smooth at six-decimal resolution.

**Ninth round portal queries**

<img width="794" height="369" alt="image" src="https://github.com/user-attachments/assets/57f2cf1b-3ee5-48b9-9660-c5e8e5bc32fe" />

**Function specific rationale**

Function 1  Interior maximin exploration  The upper corner again returned essentially zero. The proposed interior point maximises its minimum distance from all 18 sampled locations, adding the largest remaining coverage while avoiding the two observed negative pockets.

Function 2  Bracketed local test  A one-millionth reduction in x1 at the best x2 value underperformed. The ninth query tests the opposite x1 direction by one millionth while holding x2 fixed, completing a controlled local bracket.

Function 3  Orthogonal local test  The negative x1 step and the earlier larger positive x1 step both reduced performance. The proposal restores the best x1 and x3 values and changes x2 upward by one millionth to test a new local direction.

Function 4  Confirmed directional continuation  The latest 0.002 increase in x1 created a new best and a gain of 0.028487. One equal step is repeated while the other coordinates remain fixed, preserving a directly observed improvement path.

Function 5  Proven line continuation  Eight consecutive points along the same four-variable direction have improved the objective, with the latest gain increasing to 102.757515. The next equal vector step remains inside all bounds.

Function 6  Opposite x2 sensitivity test  The positive one-millionth x2 change remained below the best but performed better than the recent x1 tests. The query returns to the best point and tests x2 one millionth in the opposite direction.

Function 7  Near-optimum control  The Hartmann six maximum remains identified to six-decimal precision. Among unused single-coordinate neighbours, increasing x3 by one millionth has the smallest calculated loss.

Function 8  Near-optimum control  The separable quadratic optimum continues to return 10 to numerical precision. The next unused symmetric x8 perturbation remains effectively optimal and provides a distinct admissible input.
