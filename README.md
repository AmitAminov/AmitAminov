<div align="center">

<a href="https://amitaminov.github.io/">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=24&pause=1200&color=B9A7FF&center=true&vCenter=true&width=760&height=46&lines=Data+Scientist+%2F+ML+Researcher;Building+trustworthy+AI+systems;Theorem+proving+in+Lean+4+%C2%B7+honest+evaluation" alt="Data Scientist / ML Researcher — building trustworthy AI systems" />
</a>

<p>
  <a href="https://amitaminov.github.io/"><img src="https://img.shields.io/badge/Portfolio-amitaminov.github.io-6E56CF?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/amit-a-94a85822a"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:amit.aminov@mail.huji.ac.il"><img src="https://img.shields.io/badge/Email-Reach%20out-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://amitaminov.github.io/cv/amit-aminov-cv.pdf"><img src="https://img.shields.io/badge/CV-Download-78E7E7?style=flat-square&logo=readthedocs&logoColor=black" alt="CV"></a>
</p>

</div>

## Hi, I'm Amit 👋

I'm a data scientist and ML researcher, currently doing a research M.Sc. at the Hebrew University of Jerusalem. My bachelor's was in physics, at Bar-Ilan, through its gifted-in-math track.

For a few years before grad school my job was building models that people actually acted on — first leading an operations-research and data-science team in Unit 8200, later writing statistical models in the Air Force's Operations Research branch. Some of that work was recognized with the Israel Defense Prize, the highest award in Israel defence establishment.

One habit stuck from all of it: don't trust a number until you know how it came out. So a project of mine usually starts with formalizing the problem and looking for standard\open source solutions\conventions. 
Another thing I emphasize is defining a baseline and a train, test and validaiton split that can't leak, and may reward the fancier model.

## 🔬 What I'm working on

- **Formal reasoning** — reading a frozen **Lean 4** prover's internal states mid-proof to predict, early, which attempts will never close the goal, with every label settled by the Lean kernel rather than a proof server.
- **Rigorous evaluation** — chronological splits over shuffled ones, verifier-checked verdicts over a scorer's say-so, negative results reported as negative, artifact-scored reproductions, closed forms over Monte-Carlo intuition.
- **LLMs & agentic pipelines** — evaluation harnesses that score what a run actually produced on disk, not what the agent claims.
- **Statistics & operations research** — experimental design, uncertainty, optimization, and resource-allocation modeling.

## 📌 Selected projects

| Project | What it shows |
|---|---|
| **[Internal-State Probes for Kernel-Verified Theorem Proving](https://github.com/amitaminov-huji/Internal-State-Probes-for-Kernel-Verified-Theorem-Proving)** | My M.Sc. thesis: probes under **3M** parameters read a frozen Goedel-Prover-V2's hidden states and predict Lean-kernel failure at **ROC-AUC 0.89–0.92** — still **0.64–0.79** from only the first 250–4,000 generated tokens, where a token counter sits at chance. Steering generation on that signal is reported as a *negative* result. |
| **[Room Occupancy](https://github.com/AmitAminov/room-occupancy)** | How a shuffled split fabricates skill on sensor time series (macro-F1 inflated 21–62 pts); under an honest chronological holdout a simple QDA (~0.77) transfers while tree ensembles don't. |
| **[Gaussian Geometry](https://github.com/AmitAminov/gaussian-geometry)** | Three widely-taught covariance "facts" turned into exact, unit-tested statements — including that the "1σ" ellipse holds only **~39%** of the mass in 2D, not 68%. |
| **[Decision Boundary Atlas](https://github.com/AmitAminov/decision-boundary-atlas)** | SVM overfitting made visible as geometry: one kernel-width sweep fragments the boundary into **282** memorized islands exactly as test accuracy turns over. |
| **[Agentic Research Advisor](https://github.com/AmitAminov/agentic-research-advisor)** | An autonomous paper-reproduction harness graded on the artifacts it produces, not the agent's self-report — honest negatives are first-class. |
| **[Technical Interviewer](https://github.com/AmitAminov/technical-interviewer)** | Voice and motion-driven, **offline-first** technical AI interviewer. |
| **[TripWise](https://github.com/AmitAminov/tripwise)** | Couples' trip-planning as a decision-integrity problem — blind-rate-then-reveal enforced by **Postgres row-level security + triggers**, not the UI. *Built quickly with an AI-assisted (vibe-coding) workflow to plan an autumn trip to Italy with my girlfriend.* |

<div align="center">
  <img src="https://amitaminov.github.io/figures/early_window_auroc.png" width="640" alt="Two line charts, 8B and 32B: MLP and LSTM probes predict proof failure with ROC-AUC rising from about 0.65 to 0.85 using only the first 250 to 4,000 generated tokens, while the tokens-so-far feature stays at chance." />
  <br><sub>Failure prediction from the first N generated tokens: probes on the prover&rsquo;s internal state vs the tokens-so-far baseline, which stays at chance.</sub>
</div>

## 🛠️ Tech I work with

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML / DL** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Formal methods** &nbsp;
![Lean 4](https://img.shields.io/badge/Lean%204-2C2C2C?style=flat-square&logo=lean&logoColor=white)
![Mathlib](https://img.shields.io/badge/Mathlib-2C2C2C?style=flat-square)

**Scientific & data** &nbsp;
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Data & infra** &nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![HPC / Slurm](https://img.shields.io/badge/HPC%20%2F%20Slurm-2C3E50?style=flat-square)

## 📫 Get in touch

- 🌐 **Portfolio** — [amitaminov.github.io](https://amitaminov.github.io/)
- 👔 **LinkedIn** — [amit-a-94a85822a](https://www.linkedin.com/in/amit-a-94a85822a)
- 📧 **Email** — amit.aminov@mail.huji.ac.il

<!--
AmitAminov/AmitAminov — this README.md renders on the GitHub profile page.
-->
