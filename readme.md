# This file is only for interview

Bonus Question

Please explain the fundamental principles of flow cytometry and walk through the step-by-step process of how it works? Additionally, highlight some common applications of flow cytometry in scientific research and clinical settings.

steps:
1. dying the cell
2. let one cell go through a pipe at a time.
3. Using different lasser beam to get spectrum of cell reflect or dyes
4. analyze the cell

clinical pratices (from wiki and some website):
Cell counting
Cell sorting
Determining cell characteristics and function
Detecting microorganisms
Biomarker detection
Protein engineering detection
Diagnosis of health disorders such as blood cancers
Measuring genome size

Below are plots of selected cell surface biomarkers of blood cell samples. Researchers are interested in picking out cells marked in yellow (accupying a high-density chunk at the bottom-right) for further analysis. How would you suggest a method to automatically identify these cells?

If the data set well mark enough, I will choose a classifier to detect.
If we have enough data, but few of them is marked. Maybe considerate a semi-supervised learning. Then, train a classifier
If just only this case, we can use grouping like kmean and set the start point at the target and choice two class.

