# IT326-Project-
IT326-DataMining Project

# Project Description
This project studies students academic outcomes based on their characteristics and academic information. The main goal is to apply data mining techniques to analyze student data and identify patterns related to their academic status.

For the Classification task, students will be classified into three categories: Dropout, Enrolled, and Graduate.

For the Clustering task, students will be grouped based on similarities in their characteristics to identify meaningful groups within the dataset.

# Project Motivation
**Why we chose this problem?**

  We chose this problem because student dropout is a major challenge in universities. Instead of waiting for students to fail, we want to use data mining to identify early warning signs and help students before they decide to leave.

* **Why is this topic important?**
  1. **Early Intervention:** Detecting at-risk students early allows academic advisors to step in and offer support in time.
  2. **Multiple Influencing Factors:** Student performance is affected by many factors at once—academic grades, financial status, and personal background. Machine learning helps us analyze all these factors together accurately.
  3. **Data-Driven Decisions:** The results provide clear insights that help universities improve their student support systems and retention rates.

# Dataset
- **Name:** Predict Students' Dropout and Academic Success
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
- **Size:** 4,424 students, 36 attributes and 1 class attribute (`Target`)
- **Classes:** Graduate (49.93%), Dropout (32.12%), Enrolled (17.95%)

# Project Phases
| Phase | Content | File |
|---|---|---|
| Phase 1 | Problem, data mining task, dataset description | `Reports/Phase1.ipynb` |
| Phase 2 | Data analysis and data preprocessing | `Reports/Phase2.ipynb` |
| Phase 3 | Final report: all phases, decision tree classification (Gini and Information Gain), K-means clustering, findings | `Reports/Phase3.ipynb` |

# Main Results
- **Classification:** The best tree was the Gini tree on the 90/10 partition, with 73.81% accuracy. Averaged over the three partitions, Information Gain (72.08%) and Gini (71.73%) performed almost the same.
- **Clustering:** K = 2 had the highest average silhouette width (0.0696), but all silhouette widths were low, so the cluster structure is weak. K = 6 was the most informative, separating groups with over 60% dropout from groups with mostly graduates.
- **Key finding:** The number of courses passed in the first semester and whether tuition fees are up to date are the strongest indicators of whether a student drops out.

# Student's Names
1. Rawan ALDawood
2. Lamar Alanteet
3. Aroub Alawad
4. Joury Alsudairi
5. Lian Alzahrani 

