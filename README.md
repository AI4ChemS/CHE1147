# 🫎 CHE1147: Chemical Data Science and Engineering 
<!-- **Fall 2025 · University of Toronto** -->

Our course combines {Data + Chemistry + Engineering}. We’ll explore how **machine learning and data science** can solve real chemical engineering problems with a mix of:
- Lectures with chemical examples and datasets 📊
- Hands-on sessions 👩‍💻
- Group projects 💡

This repo is where lectures, tutorials, assignments, and project guidelines will live for our course. 

---

## 🗂 Repo Map
Here’s where to find stuff:
- `lectures/` → demo notebooks  
- `tutorials/` → in-class hands-on exercises  
- `projects/` → group project information  
- `data/` → small sample datasets used in tutorials  
<!-- - `syllabus/` → syllabus & policies   -->
<!-- - `resources/` → cheat sheets, papers, links   -->
<!-- - `assignments/` → homework with starter code   -->

## 👨‍🏫 Lectures

| Week | Topic | Slides |
|:-----|:------|:-------|
| Week 01 | Introduction to Machine Learning & Course Overview | [Open in Google Slides](https://docs.google.com/presentation/d/111YeW6a_pOGGlDclQf9Y6icHKTzszC-cKIZvfnUfHjE/edit?usp=sharing) |
| Week 02 | Data, Representation, and Exploratory Data Analysis | [Open in Google Slides](https://docs.google.com/presentation/d/1YGTtq_Nu8aPcm2Vj_WyhWyoEcSZdc9hEilq8GYlzYuc/edit?usp=sharing) |
| Week 03 | Supervised Learning Workflow | [Open in Google Slides](https://docs.google.com/presentation/d/1LPjHi8CAZs9CAHbfF02WlK_FsRVA6rcaeJB9pzARbqY/edit?usp=sharing) |
| Week 04 | Modelling well: complexity, regularization and model selection | [Open in Google Slides](https://docs.google.com/presentation/d/1u1AdL-scpyeaR5d0hK_btRJvx8Km8-dxQAJNSNve0PA/edit?usp=sharing) |
| Week 05 | Model Zoo: Different Ways of Learning from Data | [Open in Google Slides](https://docs.google.com/presentation/d/1RV-7lC08JGl5_aa-zNddAz6aUnUB60LsTWs2sjgAOu8/edit?usp=sharing) |
| Week 06 | Logistic Regression & Classification | [Open in Google Slides](https://docs.google.com/presentation/d/14T6Ocg9k1TSchSnId3mE_8C0z7EsBw66a6QU7CWCiW8/edit?usp=sharing) |
| Week 07 | Unsupervised Learning | [Open in Google Slides](https://docs.google.com/presentation/d/1HgSgHS4dFjfjFpIVh97lzhPABvHbRZlCU4ffc-Osawc/edit?usp=sharing) |
<!-- | Week 08 | Explainability & Data Quality| [Open in Google Slides](LINK) |
| Week 09 | Trustworthy ML, uncertainty and OOD  | [Open in Google Slides](LINK) |
| Week 10 | Bayesian Optimization | [Open in Google Slides](LINK) | -->


<!-- - **Lecture W01 slides:** [Open in Google Slides](https://docs.google.com/presentation/d/111YeW6a_pOGGlDclQf9Y6icHKTzszC-cKIZvfnUfHjE/edit?usp=sharing)
- **Lecture W02 slides:** [Open in Google Slides](https://docs.google.com/presentation/d/1YGTtq_Nu8aPcm2Vj_WyhWyoEcSZdc9hEilq8GYlzYuc/edit?usp=sharing)
- **Lecture W03 slides:** [Open in Google Slides](https://docs.google.com/presentation/d/1LPjHi8CAZs9CAHbfF02WlK_FsRVA6rcaeJB9pzARbqY/edit?usp=sharing)
- **Lecture W04 slides:** [Open in Google Slides](https://docs.google.com/presentation/d/1u1AdL-scpyeaR5d0hK_btRJvx8Km8-dxQAJNSNve0PA/edit?usp=sharing)
- **Lecture W05 slides:** [Open in Google Slides](https://docs.google.com/presentation/d/1RV-7lC08JGl5_aa-zNddAz6aUnUB60LsTWs2sjgAOu8/edit?usp=sharing)
- **Lecture W06 slides:** [Open in Google Slides](https://docs.google.com/presentation/d/14T6Ocg9k1TSchSnId3mE_8C0z7EsBw66a6QU7CWCiW8/edit?usp=sharing)
- **Lecture W07 slides:** [Open in Google Slides](https://docs.google.com/presentation/d/1HgSgHS4dFjfjFpIVh97lzhPABvHbRZlCU4ffc-Osawc/edit?usp=sharing)
 -->


## 📚 Tutorials

|Week| Tutorial | Colab Link |
|----|----------|------------|
| W01   | 1. Python Refresher                        | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI4ChemS/CHE1147/blob/main/tutorials/tutorial_01_python_refresher.ipynb) |
|       | 2. Linear Algebra                          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI4ChemS/CHE1147/blob/main/tutorials/tutorial_02_linear_algebra.ipynb) |
| W02   | 3. RDKit and EDA                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI4ChemS/CHE1147/blob/main/tutorials/tutorial_03_eda_and_rdkit.ipynb) |
| W03–06| 4. Supervised Learning — Regression        | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI4ChemS/CHE1147/blob/main/tutorials/tutorial_04_supervised_learning.ipynb) |
| W07   | 5. Supervised Learning — Classification    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/AI4ChemS/CHE1147/blob/main/tutorials/tutorial_05_classification.ipynb) |

## ⚙️ Setup
To reproduce the Python environment:

```bash
conda env create -f environment.yml
conda activate che1147 
```
## 💬 Feedback, Suggestions, & Support 

Tell me what to improve or any other requests using this totally anonymous form:

[![Give Feedback](https://img.shields.io/badge/Google%20Form-Feedback-blue)](https://forms.gle/j8uGpyt4QSPDn7sr5)



Or open a GitHub issue if you found a bug, typo, or broken link:

[![Open an issue](https://img.shields.io/badge/GitHub-Issues-black?logo=github)](https://github.com/AI4ChemS/CHE1147/issues/new/choose)

Found this useful? Please consider **starring the repo** 🌟 — it helps others discover the project and shows your support!

[![GitHub stars](https://img.shields.io/github/stars/<org>/<repo>?style=social)](https://github.com/AI4ChemS/CHE1147/stargazers)

## 🤝 Contribute

We welcome:
- 🐛 **Bug reports** (broken notebook cells, path issues, typos)
- 📚 **Content improvements** (clearer explanations, new examples)
- 🧪 **New exercises/tutorials/content** (small, focused PRs work best)

<!-- **Quick start**
1. Fork → create a branch: `feat/topic-name`
2. Make changes; keep cells runnable
3. Run `nbstripout` (or clear outputs) for clean diffs
4. Open a Pull Request (PR) with a short description -->

---


## 🫸💥🫷Developers and Maintainers

This course is being created by the [AI4ChemS](https://github.com/AI4ChemS) team and TAs:

- [Lya Chiñas](https://github.com/lyach)
- [Thomas Pruyns](https://github.com/iamthomaspruyn)
- [Mahyar Rajabi Kochi](https://github.com/Mahyar-rajabi94)
- [Sartaaj Khan](https://github.com/sartaajkhan)

A shout-out as well to our friends at the [Chemical Cognition Lab](https://github.com/chemcognition-lab) 👋.  
They run CHE1148, which builds on this course. CHE1147 is the foundation, CHE1148 takes it further to neural nets and representation learning. We’ve been inspired by each other’s ideas along the way.  


## 🙏 Acknowledgements

The content, examples, figures, and ideas are inspired from many textbooks, and other open courses which we will reference properly. The main references include:

- Christopher Bishop’s *[Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)* (Springer, 2006)
- Simon Prince’s *[Understanding Deep Learning](https://udlbook.github.io/udlbook/)* (Cambridge University Press, 2023)
- Kevin M. Jablonka for [ML-MolSim](https://github.com/kjappelbaum/ml_molsim)




<!-- Helpful links:
- [Contribution guide](./CONTRIBUTING.md)
- [Code of Conduct](./CODE_OF_CONDUCT.md)
- [Open issues](https://github.com/<org>/<repo>/issues)
- [Discussions](https://github.com/<org>/<repo>/discussions) _(Q&A, ideas)_ -->
