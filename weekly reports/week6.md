**Summary**

The Week 5 data were matched to the fifth-round queries and appended to the complete history for all eight functions. Functions 3, 4 and 5 achieved new best values. Function 2 remained close to its best, while Functions 7 and 8 stayed effectively at their established maxima. Function 6 showed that changing x5 from 0.000001 to zero is harmful. The sixth-round plan therefore combines one coverage-based exploration, four evidence-led local refinements, one recovery query and two near-optimum controls.

**Week 5 results**

<img width="791" height="254" alt="image" src="https://github.com/user-attachments/assets/e915a77f-e6b4-40eb-acfa-ec6148520f43" />

Function 5 made the largest numerical gain at 83.051482. Function 4 improved by 0.010030 and Function 3 by 0.001428. Function 2 finished only 0.009522 below its best. Function 6 lost 0.193385 after the one-millionth boundary change in x5, so the next experiment restores the previous x5 value rather than extrapolating further.

**Sixth round portal queries**

<img width="789" height="311" alt="image" src="https://github.com/user-attachments/assets/73a78de5-3e55-4b7e-b461-f039f9a199a9" />

**Function specific rationale**

Function 1  Maximin exploration  The fifth-round corner returned zero and did not reveal a positive basin. This point maximises the distance to all sampled two-dimensional locations, so the next evaluation adds the most new spatial information.

Function 2  Near-best exploit  The fifth-round output of 0.618886 was close to the 0.628409 best. A one-millionth decrease in x2 keeps the query beside the best observed point while testing the sharp local response conservatively.

Function 3  Confirmed local step  The fifth-round query established a new best of -0.033408. Increasing x1 by one millionth while holding x2 and x3 fixed tests whether that local improvement continues.

Function 4  Directional exploit  A second 0.001 increase in x1 improved the score by 0.010030. Repeating the isolated step preserves a directly observed direction and leaves the other coordinates unchanged.

Function 5  Directional exploit  The established four-variable step improved the result again, this time by 83.051482. The same increment is continued because every completed step along this line has increased the objective.

Function 6  Best-basin recovery  Changing x5 from 0.000001 to exactly zero reduced the score from -0.035198 to -0.228583. The query restores x5 to the successful value and changes only x1 by one millionth.

Function 7  Near-optimum control  The Hartmann-6 optimum remains identified to six-decimal precision. The best unused adjacent point changes x2 by one millionth and has negligible predicted loss.

Function 8  Near-optimum control  The fitted separable quadratic still reaches 10 at the known optimum. The least-curved coordinate x8 is moved upward by three millionths to create a new point with negligible expected loss.
