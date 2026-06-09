<div align="center">
  <h1>🎯 Expectation Decider Main</h1>
  <p><em>A probability and statistics project that analyzes student exam outcomes to explain expectations, conditional probability, distributions, and decision-making using a synthetic student dataset</em></p>
</div>

---

[![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](Expectation_Decider_Main.ipynb) [![Dataset](https://img.shields.io/badge/Dataset-CSV-blue?logo=filezilla)](Student_Dataset.csv)

<div align="center">
  
[![Explore Analysis](https://img.shields.io/badge/Explore-Analysis-green)](https://github.com/DevanshiBachhote2007/Expectation_Decider_Pr1_Maths#analysis-workflow)
[![View Insights](https://img.shields.io/badge/View-Insights-blue)](https://github.com/DevanshiBachhote2007/Expectation_Decider_Pr1_Maths#key-findings)
[![Download Data](https://img.shields.io/badge/Download-Data-orange)](Student_Dataset.csv)
[![Documentation](https://img.shields.io/badge/Question-Link-purple)](https://docs.google.com/document/d/19SRd0N1yGJNn-tiI-aD7c7M0NiEBaixCmDRBsljkJVY/edit?tab=t.0)

</div>

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-preparation">Data Preparation</a>
- <a href="#analysis-workflow">Analysis Workflow</a>
- <a href="#key-findings">Key Findings</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#conclusion">Conclusion</a>
- <a href="#video-explanation">Video Explanation</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

`Expectation_Decider_Main.ipynb` explores how probability theory and empirical data combine to explain student exam success. The project uses a cohort of 200 students to estimate pass likelihoods, evaluate conditional probabilities, and demonstrate decision-making under uncertainty using real behavioral factors.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

In educational analytics, understanding which behaviors predict exam success helps teachers and students make better decisions. This project seeks to:
- Measure the probability of passing the final exam based on real student data
- Compare empirical outcomes with classical probability assumptions
- Analyze how study habits, attendance, and group discussions affect success
- Use conditional probability and Bayes' Theorem to quantify evidence-based decisions
- Compute expected values for sampling outcomes in small groups

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- `Student_Dataset.csv` containing 200 synthetic student records
- Key fields include:
  - `study_hours`
  - `attendance`
  - `group_discussion`
  - `previous_test_score`
  - `final_exam_pass`
- The dataset supports probability experiments, conditional checks, and distribution modeling

---
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook 

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
Expectation Decider/
│
├── Expectation_Decider_Main.ipynb
├── Expectation_Decider_Readme.md
└── Student_Dataset.csv
```

---
<h2><a class="anchor" id="data-preparation"></a>Data Preparation</h2>

- Loaded `Student_Dataset.csv` into a pandas DataFrame
- Inspected data using `head()` and summary statistics
- Defined event criteria for study hours, attendance, and pass/fail status
- Built contingency tables for categorical comparisons
- Prepared counts for empirical, joint, marginal, and conditional probability analysis

---
<h2><a class="anchor" id="analysis-workflow"></a>Analysis Workflow</h2>

1. Empirical probability of passing the final exam
2. Theoretical probability comparisons for binary exam outcomes
3. Binomial distribution analysis for sampling 3 students
4. Expected value and variance computation
5. Venn diagram assessment of study and attendance overlap
6. Contingency table analysis for group discussion versus pass rate
7. Independence and mutual exclusivity checks
8. Bayes' Theorem application for attendance-based pass probability

---
<h2><a class="anchor" id="key-findings"></a>Key Findings</h2>

- Overall pass rate in the dataset: **86.5%**
- Classical blind pass assumption: **50%**
- Expected number of passes in a sample of 3 students: **2.595**
- Pass probability given group discussion: **93.07%**
- Joint probability of group discussion and pass: **47.0%**
- Study hours and attendance are strongly overlapping, but group discussion is a more powerful pass signal
- The events are not mutually exclusive and show dependency
- Bayes' Theorem confirms that high attendance significantly raises the probability of passing

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Open the folder in Jupyter Notebook or VS Code.
2. Ensure `Expectation_Decider_Main.ipynb` and `Student_Dataset.csv` are in the same directory.
3. Install required packages if needed:
```bash
pip install pandas numpy matplotlib seaborn scipy
```
4. Run the notebook cells from top to bottom.
5. Review the visualizations, probability calculations, and final summary sections.

---
<h2><a class="anchor" id="conclusion"></a>Conclusion</h2>

This project demonstrates how empirical student data can be used to make evidence-based probability decisions. The analysis highlights that attendance and group study behavior provide meaningful predictors of exam success, validating the use of conditional probability and Bayes' Theorem in educational contexts.

---
<h2><a class="anchor" id="video-explanation"></a>Video Explanation</h2>

Watch the narrated walkthrough of this project here: [Watch Video Explanation](https://drive.google.com/file/d/1N2nne1LMbwzyp4uworGrtxHyVWKEz2Sg/view?usp=sharing)

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Devanshi Bachhote**   
📧 Email: devanshibachhote.@gmail.com  


