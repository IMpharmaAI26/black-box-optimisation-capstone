The Week 2 results establish new best values for Functions 4 and 5. Functions 7 and 8 remain effectively at their maxima. Functions 1-3 and 6 require either model-guided exploration or cautious corrective refinement. The Week 3 plan combines a soft-margin RBF SVM assessment with support-vector regression, smooth surrogates and observed trends.

**Week 2 result assessment**

<img width="786" height="306" alt="image" src="https://github.com/user-attachments/assets/875ac235-7329-4b0b-80ad-a4fa7dd837d7" />

Functions 4 and 5 improved their running best. Function 2 and Function 3 improved relative to their Week 1 submissions but did not exceed the initial best. Function 6 declined slightly. The numerical differences for Functions 7 and 8 are negligible at the reported precision.

**Week 3 Queries**

<img width="789" height="602" alt="image" src="https://github.com/user-attachments/assets/845ed63e-0dae-4bc4-bce3-dfbc558b382f" />


**How SVMs informed the strategy**

•	Promising observations were defined using a top-quartile output threshold for each function separately, avoiding comparisons between incompatible output scales.

•	A soft-margin classifier was used because the small samples overlap and a strict boundary would be unrealistic.

•	An RBF kernel allowed curved performance regions; RBF support-vector regression supplied a continuous prediction for comparison.

•	SVM evidence was strongest for Functions 1-3. Direct improvement trends remained more persuasive for Functions 4-8.
