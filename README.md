# 🧠 Machine Learning Journey

Welcome to my Machine Learning GitHub repository — a living, growing notebook where I document my hands-on learning across the machine learning landscape. Whether it's linear models or deep reinforcement learning, this repo serves as both a **learning companion** and a **knowledge hub**. 🌱

---

## 🔍 Why this Repository?

I wanted to:

- Learn machine learning in a structured, topic-wise manner
- Reinforce concepts with experiments, notes, and mini-projects
- Make it easy for others (and future me!) to follow along

Each topic contains:

- 📝 A `README.md` to explain the concept
- 📓 Jupyter notebooks with implementations
- ✅ Checklists to track progress
- 🧠 Reflections, notes, and resources

---

## 📚 Repository Structure

| Section                                                                                                        | Description                                                   |
| -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| [`00_foundations`](./00_foundations/)                                                                          | Math (Linear Algebra, Stats), Python, and Pandas essentials   |
| [`01_supervised_learning`](./01_supervised_learning/)                                                          | Core models like Linear Regression, Decision Trees, SVMs, KNN |
| [`02_unsupervised_learning`](./02_unsupervised_learning/)                                                      | Clustering, Dimensionality Reduction, and Anomaly Detection   |
| [`03_model_evaluation`](./03_model_evaluation/)                                                                | Metrics, validation strategies, bias-variance tradeoff        |
| [`04_advanced_models`](./04_advanced_models/)                                                                  | Neural networks, CNNs, RNNs, Transformers, RL                 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;↳ [`reinforcement_learning`](./04_advanced_models/reinforcement_learning/) | Value-based, Policy-based, Deep RL, and environments          |
| [`05_real_world_projects`](./05_real_world_projects/)                                                          | Domain-specific end-to-end mini projects                      |
| [`06_MLops_and_production`](./06_MLops_and_production/)                                                        | Model deployment, versioning, monitoring, CI/CD               |
| [`07_notes_and_resources`](./07_notes_and_resources/)                                                          | Book summaries, paper reviews, online course notes            |

---

## 🧭 How to Use This Repo

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/machine-learning-journey.git
   cd machine-learning-journey
   ```

2. Navigate to a section you want to study

3. Read through the `README.md`, run the notebooks, and take notes ✍️

---

## 🏁 Progress Tracker

| Section                | Status         |
| ---------------------- | -------------- |
| Foundations            | 🟩 In Progress |
| Supervised Learning    | ⬜ Not Started |
| Unsupervised Learning  | ⬜ Not Started |
| Evaluation & Tuning    | ⬜ Not Started |
| Advanced Models        | ⬜ Not Started |
| Reinforcement Learning | ⬜ Not Started |
| Real-world Projects    | ⬜ Not Started |
| MLOps                  | ⬜ Not Started |

---

## ✨ Goals

- Build depth in theory and implementation
- Apply concepts to real-world mini-projects
- Learn deployment and production-readiness for ML
- Document and reflect continuously

---

## 🙌 Contributions & License

This is a personal learning repository. If you'd like to collaborate, feel free to open a discussion or PR.  
All content here is shared under the MIT License. Attribution is appreciated.

---

> “The best way to learn is by doing — and documenting.”  
> — _me, probably after debugging for hours_

---

## 🛠️ Setup Instructions

To run the notebooks locally, you can use either `venv` or `conda`. Below are the recommended steps for **macOS** using Conda.

### 🍏 Setup Using Conda (macOS)

1. **Create a new Conda environment**

   ```bash
   conda create -n ml python=3.10
   ```

2. Activate the environment:

   ```bash
   conda activate ml
   ```

3. Install packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Add the environment as Jupyter Kernel:

   ```bash
   python -m ipykernel install --user --name=ml --display-name="ml"
   ```

5. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

Now you can select the "Python (ml-env)" kernel to run the notebooks.
