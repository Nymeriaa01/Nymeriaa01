<h1 align="center">Hi there, I'm Florian 👋</h1>

<p align="center">
  <a href="mailto:florian.magnan@ip-paris.fr">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/florian-magnan-549915284">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<p align="center">
  <b>🎯 Looking for a 6-month Data Science / Machine Learning internship starting April 2027</b><br>
  <sub>Currently based in France — open to opportunities in <b>Switzerland</b> 🇨🇭</sub>
</p>

---

### About Me

MSc student in **Data Science (M2DS)** at Institut Polytechnique de Paris, on a dual-degree
track with Centrale Lille. What draws me to machine learning isn't just getting a model to be
right — it's understanding **why** it decides what it decides.

- 🎓 **Education:** MSc Data Science at **Institut Polytechnique de Paris** (École Polytechnique) | MEng at **Centrale Lille** | Exchange semester at **Politecnico di Torino** | CPGE PCSI/PC, Lycée Hoche
- 💼 **Experience:** a gap year at **Swissgrid**, the Swiss electricity transmission system operator, working on data engineering and analysis
- 🌱 **Currently exploring:** model interpretability (SHAP, local → global explanations), federated learning, and what it takes to move data work from a notebook into something that actually runs
- 🗣️ **Languages:** French (native) · English (C1) · German (B2) · Italian (B1)

---

### 💻 Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

**Machine Learning & Deep Learning**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/SHAP-8A2BE2?style=for-the-badge" alt="SHAP" />
</p>

**Data Engineering & Tools**
<p>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark" />
  <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge" alt="Delta Lake" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX" />
</p>

---

### 🚀 Projects

> The three repositories below are **forks** of projects I co-authored — I don't claim
> ownership of them. Each one contains a `CONTRIBUTION.md` file spelling out exactly what I
> did and crediting my co-authors.

#### 🔬 [Federated Learning Under the Lens of Model Editing](https://github.com/Nymeriaa01/federated-learning-project)
`PyTorch` · `Vision Transformers` · `CIFAR-100` — *done Feb – Jul 2025 · added to this profile in Sep 2026*

FedAvg on CIFAR-100 with a DINO-pretrained ViT-S/16, then model editing through sparse
fine-tuning guided by Fisher sensitivity masks. Sparse fine-tuning lifts the centralized model
from **74.6% to 84.3%** test accuracy while updating only 10% of parameters. Graded **28/30**.

**My part —** with Réda Ouzzane, designing and implementing the **IID and non-IID federated
architecture**: client partitioning, the FedAvg loop, the full fine-tuning campaign and the
testing protocol. We worked as a pair, taking turns on the same files.

**Co-authors —** [Giovanna Brod Zamojska](https://github.com/giovannabrod) (main author of the codebase), [Réda Ouzzane](https://github.com/redaouzz), Niloofar Vazirpanah.

#### 🔍 [Hybrid RankingSHAP — interpretability for ranking models](https://github.com/Nymeriaa01/XAI-Ranking-SHAP-Project)
`SHAP` · `LIME` · `LambdaMART` · `LightGBM` — *done Feb – Jul 2025 · published Aug 2025 · added to this profile in Sep 2026*

A method for deriving faithful **global** feature-importance profiles for ranking models by
aggregating **local** listwise RankingSHAP explanations (MQ2008 / LETOR 4.0). Retraining on the
selected features alone retains **98% of the full model's performance** (NDCG@10: 0.468 vs
0.476), and a surrogate model confirms fidelity at **R² = 0.74**.

**My part —** equal co-author with [Réda Ouzzane](https://github.com/redaouzz): methodology, implementation,
experiments and writing, all done as a pair with no strict split of tasks.

#### ⚽ [Deep Learning on football data](https://github.com/Nymeriaa01/Deep-Learning-Football)
`Keras` · `TensorFlow` · `Web scraping` — *done spring 2024 · published Aug 2025 · added to this profile in Sep 2026*

Our first real dive into deep learning: working through François Chollet's *Deep Learning with
Python* and throwing as many architectures as we could at a noisy, real-world football dataset.

**My part —** implementing and benchmarking the deep learning models. The web scraping was done
by [Réda Ouzzane](https://github.com/redaouzz).

#### 🏥 Hospital shift scheduling with a multi-agent system
`Python` · `Metaheuristics` — *done Sep 2024 – Feb 2025 · academic project, no public repository*

A multi-agent system for scheduling medical shifts at Lille University Hospital under legal and
stochastic constraints, solved with tabu search, simulated annealing and genetic algorithms.
**+12% performance** over the department's existing schedules; shortlisted for deployment.

---

### 💼 Experience

#### Data Intern — [Swissgrid](https://www.swissgrid.ch)
**September 2025 – June 2026 · Aarau, Switzerland** *(gap year)*

Worked on the internal data platform of Swissgrid, the Swiss electricity transmission system
operator.

- Designed and shipped an **API-driven ETL pipeline** collecting Europe-wide planned grid
  outage data from the public ENTSO-E transparency platform
- Designed a **data refresh automation pipeline** feeding a market simulation tool, replacing a
  manual process
- Contributed to a **seasonal adequacy analysis** (*Seasonal Outlook*) during my extension,
  from March to June 2026
- These automations are the **first building blocks** of work the team is continuing after my
  departure

> The results and deliverables of this internship are confidential. This section is a written
> description only: no code, configuration or company-owned data is published here.

---

<details>
<summary>ℹ️ Why the git history of these repositories doesn't reflect my contribution</summary>

<br>

These projects were built in pairs and on Google Colab, then pushed to GitHub in a single batch
by my co-authors. As a result, the git history doesn't document how the work was actually
divided — not for them, and not for me. Rather than leave that ambiguous, each fork carries a
`CONTRIBUTION.md` stating what I did, what I didn't do, and who did the rest.

</details>

---

<p align="center">
  <b>📫 Let's talk!</b> Data science, model interpretability, or an internship opportunity —
  reach me on <a href="https://www.linkedin.com/in/florian-magnan-549915284">LinkedIn</a> or by
  <a href="mailto:florian.magnan@ip-paris.fr">email</a>.
</p>
