**Summary**

The Week 9 inputs and outputs were matched across all eight functions and appended to the complete observation history. Functions 4 and 5 achieved new best values for the sixth consecutive round. Functions 7 and 8 remained effectively at their identified maxima. Functions 1, 2, 3 and 6 did not improve, so the tenth-round plan uses transparent information-gathering tests for those functions and preserves exploitation only where repeated evidence supports it.

**Week 9 results**

<img width="790" height="320" alt="image" src="https://github.com/user-attachments/assets/4d1ee541-05a4-4966-93b5-f805d832c44b" />

Function 5 made the largest numerical gain at 110.328539, and Function 4 improved by 0.030639. Both extend established directions. Function 2 recovered from Week 8 but remained 0.101809 below its best. Functions 3 and 6 also remained below their best values. The changes for Functions 1, 7 and 8 are negligible at the reporting tolerance.

**Tenth round portal queries**

<img width="790" height="408" alt="image" src="https://github.com/user-attachments/assets/fab7136e-fd3e-4a58-9b44-00059da255ab" />

**Function specific rationale**

Function 1  Coverage exploration  The ninth result remained effectively zero. A fixed-seed maximin search selected the point that is farthest from the nearest sampled location after rounding and applying the portal boundary rule. This adds information instead of repeating another near-zero corner or local point.

Function 2  One-coordinate boundary test  The x1 tests on both sides of 0.696000 did not beat the current best. The proposal restores x1 and moves x2 one millionth beyond the previously tested 0.999000 value. The change is isolated and reversible because nearby scores have varied sharply.

Function 3  Reverse x2 bracket  Increasing x2 by one millionth reduced the output from the established best. The tenth query keeps x1 and x3 fixed and tests an equal step below the best x2 value, completing a transparent local bracket.

Function 4  Verified directional continuation  The latest 0.002 increase in x1 produced a new best and a gain of 0.030639. The tenth query repeats the same step while holding the other three coordinates fixed, so any change can be attributed to x1.

Function 5  Final feasible line continuation  Nine successive points along the same four-variable direction have improved the output. The next equal vector step remains within the unit interval, although x4 reaches 0.994940, so no larger extrapolation is used.

Function 6  New-coordinate sensitivity test  The two x2 tests remained below the best and suggest that the centre value is preferable. The proposal returns to the best point and increases x3 by one millionth, testing a new local direction without combining changes.

Function 7  Near-optimum control  The Hartmann six maximum remains identified to six-decimal precision. Decreasing x3 by one millionth is the best unused single-coordinate neighbour of the best observed point under the identified benchmark surface.

Function 8  Near-optimum control  The separable quadratic optimum continues to return 10 to numerical precision. Increasing the least-curved eighth coordinate by five millionths creates a distinct query while retaining a negligible expected loss.

