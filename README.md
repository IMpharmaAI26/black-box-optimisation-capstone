**Black Box Optimisation Capstone Project**

**1 Project overview**

The capstone investigated how to maximise eight unknown functions when their equations are unavailable and evaluations are limited. Each new experiment used the accumulated input-output pairs to balance exploration of unfamiliar regions with exploitation of promising settings. The project developed a practical process for making sequential decisions under uncertainty.

**2 Inputs and outputs**

Each function accepts a numerical vector with two to eight coordinates in the interval [0, 1] and returns one scalar score. Higher scores are preferred, including when outputs are negative. The verified record contains 175 starter observations and 96 evaluations across twelve processed rounds, giving 271 paired observations. Each round adds one response per function.

**3 Project Objectives**

The objectives were to improve each function's best observed score within the evaluation budget, select valid and informative queries, adapt decisions to returned feedback, and document a reproducible workflow. Performance was assessed separately for each function because their score scales differ.

**4 Approach**

After each processed round, inputs and outputs were validated, compared with the previous best, and used to revise the next query. Spatial coverage supported exploration where the signal was weak; controlled local changes supported exploitation where results repeatedly improved. Original downloads were preserved, while cumulative records were reconciled without counting earlier observations twice.

**7 Results for all functions across the weekly rounds**

The table reports actual returned scores for all twelve verified rounds. Start is the best starter observation; Best is the best observed score across the starter data and all twelve rounds. Round 13 proposals are kept separate because their processed outputs are not available.

<img width="888" height="485" alt="image" src="https://github.com/user-attachments/assets/5fe031b6-5226-4789-b903-91d62cdadfa9" />

Function 5 showed strong sustained progress, improving from 1088.859618 to 2098.410528, approximately 92.72 percent above its starter best. Function 4 improved from -4.025542 to 0.230797. Their late-round gains supported continued local refinement, although Function 5's improvements became smaller. Functions 7 and 8 retained best observed scores near 3.322368 and 10, while Function 1 remained unresolved.
The results show that higher dimensionality alone did not determine difficulty. Functions 2, 3 and 6 produced appreciable variation among nearly identical inputs, so tiny coordinate changes did not establish reliable gradients. Stable local scores do not prove a global maximum, and the differently scaled function scores should not be summed into an assumed leaderboard total.

