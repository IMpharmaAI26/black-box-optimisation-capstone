**Summary**

The Week 11 inputs and outputs were matched across all eight functions and appended to the complete history. The dataset now contains 263 paired observations. Functions 2, 4 and 5 achieved new best values. Functions 7 and 8 remained effectively at their identified maxima. Functions 1, 3 and 6 did not improve.

**Week 11 results**

<img width="794" height="312" alt="image" src="https://github.com/user-attachments/assets/34058a1c-7841-493f-a0c9-f14db3b556ea" />

**Twelfth round portal queries**

<img width="791" height="306" alt="image" src="https://github.com/user-attachments/assets/efccdc3e-4131-4573-9614-cbc9799c67fa" />

**Function specific rationale**

Function 1  Maximin exploration  The latest value remained numerically negligible and no output-bearing principal direction is credible. Multi-start maximin search selected the largest remaining coverage gap. Its nearest sampled neighbour is approximately 0.225008 away.

Function 2  Boundary continuation  The recent query path is almost entirely aligned with x2, and the latest one-millionth increase produced a new best. The proposal keeps x1 at 0.696000 and advances x2 by one further millionth.

Function 3  Reverse x3 bracket  The established local centre remains best. Increasing x3 by one millionth reduced the output, so the proposal restores x1 and x2 and tests the previously unobserved equal step below x3.

Function 4  Verified x1 continuation  Rounds 2 to 11 reduce to one varying direction, x1, and the latest 0.002 step improved the best by 0.031373. The proposal repeats that step while fixing x2, x3 and x4.

Function 5  Projected principal direction  The high-output query path has one dominant direction and every completed step has improved the score. Because x4 has reached 0.999999, the proposal holds it at the boundary and repeats the latest feasible changes in x1, x2 and x3.

Function 6  New-coordinate local test  The two x3 neighbours underperformed the centre, and the dominant recent variation involves x3 and x4. The proposal restores the best x3 value and begins an x4 bracket with a one-millionth increase.

Function 7  Near-optimum neighbour  The Hartmann-six maximum remains identified to six-decimal precision. The proposed x2 increase is the highest-valued unused single-coordinate micro-neighbour, with a theoretical value of approximately 3.322368011375.

Function 8  Least-sensitive neighbour  The exact separable quadratic fit identifies x8 as the least-curved variable. The next unused x8 perturbation remains distinct and has a predicted value of approximately 9.9999999999964.
