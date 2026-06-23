# Project Grading

Congratulations to all groups for completing the final machine learning projects.

## Badges Awarded

<table>
<tr>
<td align="center">
<img src="badges/best-tech-smart.png" width="80"><br>
<b>Best tech smart</b><br>
<strong><span style="font-size:15px;">Group 1 — Spotify Mood Classification</span></strong><br>
Clear baseline-to-improved-model comparison: Logistic Regression → Random Forest, with around 4% accuracy improvement.
</td>

<td align="center">
<img src="badges/best-error-analysis.png" width="80"><br>
<b>Best error analysis</b><br>
<strong><span style="font-size:15px;">Group 2 — Heart Disease Prediction</span></strong><br>
Strongest interpretation of model mistakes, recall/F1 trade-off, and health-risk consequences.
</td>

<td align="center">
<img src="badges/best-real-world-problem.png" width="80"><br>
<b>Best real-world problem formulation</b><br>
<strong><span style="font-size:15px;">Group 2 — Heart Disease Prediction</span></strong><br>
The prevention framing made the ML task meaningful and well connected to real-world use.
</td>
</tr>

<tr>
<td align="center">
<img src="badges/best-feature-engineering.png" width="80"><br>
<b>Best feature engineering idea</b><br>
<strong><span style="font-size:15px;">Group 3 — IMDb Sentiment Prediction</span></strong><br>
Strong NLP preprocessing and representation work: HTML cleaning, stopword discussion, max features, Word2Vec, and overfitting awareness.
</td>

<td align="center">
<img src="badges/best-visualization.png" width="80"><br>
<b>Best visualization</b><br>
<strong><span style="font-size:15px;">Group 4 — Pokémon Strength Classifier</span></strong><br>
Nice PCA visualization and clear visual explanation of class distribution and model limitations.
</td>

<td align="center">
<img src="badges/best-critical-llm-use.png" width="80"><br>
<b>Best critical use of an LLM</b><br>
<strong><span style="font-size:15px;">Group 4 — Pokémon Strength Classifier</span></strong><br>
Good reflection that LLM suggestions need external validation and cannot replace critical thinking.
</td>
</tr>
</table>

Each badge adds **+0.25 bonus points** to the group project grade.

**Final group project grade = Rubric project grade + badge bonus**

The group project grade is capped at **20/20**.

| Group | Project | Number of badges | Badge bonus |
|---|---|---:|---:|
| Group 1 | Spotify Mood Classification | 1 | +0.25 |
| Group 2 | Heart Disease Prediction | 2 | +0.50 |
| Group 3 | IMDb Sentiment Prediction | 1 | +0.25 |
| Group 4 | Pokémon Strength Classifier | 2 | +0.50 |

---

## Project Grade

Each group project was graded out of **20 points**.

| Main task | Points | Sub-tasks and evidence expected |
|---|---:|---|
| Problem formulation and dataset understanding | 3 pts | **Dataset introduced clearly**: dataset name, size, source, main variables.<br><br>**ML task defined correctly**: classification/regression/clustering/NLP task explained correctly.<br><br>**Input and output identified**: clear explanation of features `X` and target `Y`. |
| Data preprocessing and feature preparation | 3 pts | **Data cleaning/preprocessing explained**: missing values, encoding, text cleaning, scaling, or other relevant preprocessing.<br><br>**Data leakage avoided**: train/test split done correctly; preprocessing fitted only on training data where relevant.<br><br>**Feature choices justified**: explanation of why features were kept, removed, transformed, or engineered. |
| Baseline model | 2 pts | **Baseline model implemented**: simple baseline exists.<br><br>**Baseline model explained**: students can explain what the baseline learns and why it is appropriate. |
| Improved model or improved pipeline | 3 pts | **One improvement implemented**: model, preprocessing, feature engineering, regularization, threshold tuning, PCA, or another justified change.<br><br>**Improvement justified**: group explains why the change might help and whether it actually helped. |
| Fair evaluation and metrics | 3 pts | **Metrics chosen appropriately**: accuracy, precision, recall, F1, MSE, etc. selected according to task.<br><br>**Baseline and improvement compared fairly**: same split, same metric, comparable setup.<br><br>**Results interpreted, not only reported**: students explain what the numbers mean. |
| Error analysis | 3 pts | **Three model mistakes shown**: concrete examples with true value and prediction.<br><br>**Mistakes explained using ML concepts**: explanation linked to missing features, imbalance, preprocessing, overfitting, noisy labels, or representation limits.<br><br>**Next improvement proposed**: reasonable next step based on errors. |
| Critical AI assistant use | 1 pt | **LLM use described**: what was asked, what was suggested, what was implemented.<br><br>**LLM use evaluated or limitations discussed**: measured or critically discussed whether it helped, misled, hallucinated, or required validation. |
| GitHub repository organization and reproducibility | 1 pt | **GitHub repository organized**: clear folder/file structure, meaningful filenames, notebook/script easy to find.<br><br>**README and reproducibility**: README explains project goal, files, dependencies, and how to run or understand the work. |
| Presentation clarity and oral answers | 1 pt | **Presentation clear and within time**: clear slides, understandable narrative, and ability to answer course-based questions. |

**Total: 20 points**

---

## Individual Oral Question Bonus

The oral questions were used in two ways:

1. They contributed to the **presentation clarity and oral answers** part of the group project rubric.
2. They also produced an **individual oral bonus** to reflect each student’s own understanding of the course concepts.

The individual project grade is calculated as:

**Individual project grade = Final group project grade + oral bonus**

The individual project grade is also capped at **20/20**.

| Oral performance | Bonus |
|---|---:|
| Strong answer | +0.50 |
| Good answer | +0.25 |
| Partial answer | +0.15 |

---

## Exercise Grade

In addition to the project, students submitted exercises through pull requests.

There were **7 exercises in total**, one for each course topic.

The exercise grade is individual.

| Exercise status | Points |
|---|---:|
| Complete, correct, and submitted through PR | 1 |
| Submitted but incomplete or with important issues | 0.5 |
| Not submitted | 0 |

The exercise score is calculated as:

**Exercise score /7 = sum of exercise points**

**Exercise grade /20 = (Exercise score / 7) × 20**


## Group Project Grades

| Group | Project | Rubric Project Grade /20 | Badges | Badge Bonus | Final Group Project Grade /20 | Main Strengths | Main Weaknesses |
|---|---|---:|---:|---:|---:|---|---|
| Group 1 | Spotify Mood Classification | 16 | 1 | +0.25 | 16.25 | Clear baseline-to-improved-model comparison; Logistic Regression to Random Forest; measurable accuracy improvement. | Error analysis felt too LLM-dependent; LLM contribution not clearly evaluated. |
| Group 2 | Heart Disease Prediction | 19 | 2 | +0.50 | 19.50 | Strong real-world problem formulation; good feature engineering; good recall/F1 discussion; strong error analysis. | LLM component should have been evaluated more explicitly. |
| Group 3 | IMDb Sentiment Prediction | 17 | 1 | +0.25 | 17.25 | Good NLP preprocessing; awareness of overfitting; discussion of Naive Bayes, Word2Vec, stopwords, and feature size. | Needs clearer final model comparison and more concrete error examples. |
| Group 4 | Pokémon Strength Classifier | 17 | 2 | +0.50 | 17.50 | Strong visualization; PCA discussion; class imbalance awareness; critical LLM reflection. | PCA/model choice could be justified more deeply; ordinal tier labels not fully discussed. |

---

## Individual Project Grades and Exercises

The table below shows the current individual project grades and the exercise submission status.

The exercise submissions are still being verified. If your number of submitted exercises is marked as **To verify**, please check your pull request and contact me if you believe your exercises were submitted.

| Student ID | Student | Group | Exercises Submitted /7 | Exercise Grade /20 | Oral Bonus | Final Group Project Grade /20 | Individual Project Grade /20 | Final Grade /20 |
|---:|---|---|---:|---:|---:|---:|---:|---:|
| 2410013 | Vũ Đức An | Group 1 | 7 |  | +0.25 | 16.25 | 16.50 |  |
| 2410076 | Phan Nam Anh | Group 1 | To verify |  | +0.15 | 16.25 | 16.40 |  |
| 2411000 | Nguyễn Anh Tuấn | Group 1 | 7 |  | +0.25 | 16.25 | 16.50 |  |
| 2410702 | Trần Khoa Nam | Group 1 | 7 |  | +0.50 | 16.25 | 16.75 |  |
| 2410088 | Phạm Đức Anh | Group 2 | 7 |  | +0.25 | 19.50 | 19.75 |  |
| 2410003 | Huỳnh Gia An | Group 2 | To verify |  | +0.25 | 19.50 | 19.75 |  |
| 2410612 | Nguyễn Tân Nhật Minh | Group 2 | To verify |  | +0.15 | 19.50 | 19.65 |  |
| 2410148 | Cao Chí Bảo | Group 2 | 7 |  | +0.50 | 19.50 | 20.00 |  |
| 2410255 | Nguyễn Xuân Dương | Group 3 | 7 |  | +0.50 | 17.25 | 17.75 |  |
| 2410315 | Nguyễn Minh Hoàng | Group 3 | To verify |  | +0.50 | 17.25 | 17.75 |  |
| 2410473 | Vũ Trần Nam Khánh | Group 3 | To verify |  | +0.50 | 17.25 | 17.75 |  |
| 2410481 | Nguyễn Đăng Khôi | Group 3 | To verify |  | +0.50 | 17.25 | 17.75 |  |
| 2410478 | Chu Ngọc Minh Khôi | Group 4 | 7 |  | +0.50 | 17.50 | 18.00 |  |
| 2410630 | Nguyễn Thiện Minh | Group 4 | To verify |  | +0.50 | 17.50 | 18.00 |  |
| 2410710 | Bùi Tuấn Nghĩa | Group 4 | 7 |  | +0.25 | 17.50 | 17.75 |  |
| 2410780 | Nguyễn Hải Phú | Group 4 | To verify |  | +0.25 | 17.50 | 17.75 |  |
| 2410299 | Nguyễn Xuân Hiển | Group 4 | To verify |  | +0.15 | 17.50 | 17.65 |  |

---

## Final Grade

The final individual grade combines the **individual project grade** and the **exercise grade**.

The raw final grade is then calculated as: **Raw Final Grade = 0.70 × Individual Project Grade + 0.30 × Exercise Grade**

After all raw final grades are computed, grades will be smoothed across the class distribution using the class mean and standard deviation: **z_i = (Raw Final Grade_i - μ_raw) / σ_raw** → **Smoothed Grade_i = μ_target + z_i × σ_target**

The final grade will be capped between **0** and **20**: **Final Grade_i = max(0, min(20, Smoothed Grade_i))**

Where:

|  |  |
|---|---|
| `μ_raw` | Mean of all raw final grades |
| `σ_raw` | Standard deviation of all raw final grades |
| `μ_target` | Target class average after smoothing |
| `σ_target` | Target standard deviation after smoothing |

---