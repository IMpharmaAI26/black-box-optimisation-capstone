**Summary**

Week 12 is complete and its eight returned outputs are paired with the submitted inputs. Functions 4 and 5 achieved new best values of 0.230797 and 2098.410528. Functions 7 and 8 remained numerical near-ties, while Functions 1, 2, 3 and 6 did not materially improve. Function 2's decline shows that the preceding gain did not establish a reliable continuation direction.

**Week 12 performance**

<img width="788" height="335" alt="image" src="https://github.com/user-attachments/assets/2a888dde-687d-4d89-8916-15e2969d2849" />

Function 4 improved by 0.029931, equivalent to 14.90 percent of its previous positive best. Function 5 improved by 12.907448, or 0.62 percent. These gains are directly observed. Function 2 fell by 0.154450, about 19.12 percent below its previous best, so the latest x2 continuation was unsuccessful.
For Functions 7 and 8, the differences from the best are only about 1.81e-11 and 3.60e-12. An absolute reporting tolerance of 1e-10 treats these as numerical near-ties; it is not an estimate of measurement noise. Function 1 also has very small numerical differences, but its negligible signal should not be described as a successful plateau.
Functions 2, 3 and 6 show substantial score changes between nearly identical inputs. The current history does not establish whether the cause is evaluation noise, an unusually sharp response or another unmodelled effect. It therefore does not justify precise local gradients from these micro-steps. Replication at a fixed setting would be informative if the portal permits it.

Function 1  0.999999-0.774991
The coverage point returned an essentially zero value. It broadens the sampled space but identifies no useful improving direction.

Function 2  0.696000-0.999003
The x2 continuation fell by 0.154450 from the previous best. The preceding gain was not reproduced; a monotonic local response is not supported.

Function 3  0.492582-0.611593-0.340175
The lower x3 neighbour returned -0.035529, below the best -0.033408. Both sides of the latest x3 bracket underperformed the centre.

Function 4  0.409597-0.387026-0.377671-0.398887
Another isolated 0.002 increase in x1 created a new best. The gain was 0.029931, or 14.90 percent of the previous positive best.

Function 5  0.422644-0.805411-0.929410-0.999999
The projected step with x4 fixed at 0.999999 improved the best by 12.907448, or 0.62 percent. Individual effects of x1, x2 and x3 cannot be separated.

Function 6  0.424732-0.356999-0.661865-0.743416-0.000001
Increasing x4 by one millionth returned -0.187297, well below the best -0.035198. This does not support continuing that step.

Function 7  0.201689-0.150012-0.476874-0.275332-0.311652-0.657301
The distinct neighbouring point was lower by about 1.81e-11. It is a numerical near-tie, not a meaningful improvement.

Function 8  0.100000-0.150000-0.130000-0.150000-0.800000-0.500000-0.200000-0.600006
The six-millionth x8 perturbation returned 9.9999999999964. It is within 3.61e-12 of the best observed value of 10.



