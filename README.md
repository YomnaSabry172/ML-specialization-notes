# 📘 ML Specialization Notes

**Personal, visualized study notes for the [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) (DeepLearning.AI × Stanford Online, taught by Andrew Ng)** — built while taking the course, and shared here for anyone who wants to recap a topic, review before an interview, or just see the whole specialization laid out in one place.

> 🎓 Made for educational purposes. I built these for myself while going through the specialization, and I'm sharing them alongside my certificate of completion in case they're useful to anyone else on the same path.

---

## 📑 Table of Contents

- [What this repo is](#-what-this-repo-is)
- [How to use it](#-how-to-use-it)
- [What each note looks like](#-what-each-note-looks-like)
- [Course 1 — Supervised Machine Learning: Regression and Classification](#-course-1--supervised-machine-learning-regression-and-classification)
- [Course 2 — Advanced Learning Algorithms](#-course-2--advanced-learning-algorithms)
- [Course 3 — Unsupervised Learning, Recommenders, Reinforcement Learning](#-course-3--unsupervised-learning-recommenders-reinforcement-learning)
- [Full topic index](#-full-topic-index)
- [Notes on structure](#-notes-on-structure)
- [Contact](#-contact)

---

## 📖 What this repo is

This repository holds **~25 self-contained HTML study notes** covering all three courses of the specialization, from linear regression all the way to deep reinforcement learning. They're not a copy of the lecture slides — each note **explains the material in its own words**, adds the "why does this exist" reasoning behind each concept, works through small examples by hand, and includes **custom diagrams built specifically to illustrate that topic** (architecture diagrams, decision boundaries, gradient descent paths, MDP loops, Bellman equation breakdowns, and more).

The goal was to end up with something that:
- 🔁 **Recaps fast** — jump straight to one topic without re-watching a video
- 🧠 **Explains, not just restates** — every concept gets an intuition/analogy alongside the formal definition
- 🎨 **Is visual** — inline diagrams instead of walls of text wherever a picture helps
- 🗂️ **Stays organized** — one file per lecture "chunk," grouped by course and week

---

## 🚀 How to use it

Every note is a **single, self-contained `.html` file** — no build step, no server needed.

1. Clone or download this repository
2. Open any `.html` file directly in your browser
3. Use the **table of contents card** at the top of each file to jump to a section

```bash
git clone https://github.com/<your-username>/ML-specialization-notes.git
cd ML-specialization-notes
# then just open any .html file in your browser
```

You can also click through the links in the tables below directly on GitHub — GitHub will render a preview, though opening the raw file locally (or via a tool like [htmlpreview.github.io](https://htmlpreview.github.io/)) gives you the full styled version with working navigation.

---

## 🎨 What each note looks like

All notes share a consistent visual system, so once you're used to one, you're used to all of them:

| Element | What it's for |
|---|---|
| 🔵 **Navy gradient header** | Title + one-line summary of what the file covers |
| 📋 **Table-of-contents card** | Jump links to every section in the file |
| 🟧 **"Why this matters" box** | The reasoning behind a concept — why it exists, not just what it is |
| 🟩 **Analogy box** | A real-world comparison to build intuition |
| 🔷 **Note box** | Useful context, caveats, or things worth double-checking |
| 🔴 **Warning box** | Common mistakes or points of confusion |
| 🖼️ **Inline SVG diagrams** | Custom-built visuals — network architectures, MDP loops, decision boundaries, etc. — instead of screenshots |
| 💻 **Code blocks** | Key implementation snippets (NumPy, TensorFlow/Keras) |
| 📊 **Summary tables** | A one-page cheat-sheet at the end of every file |

---

## 📗 Course 1 — Supervised Machine Learning: Regression and Classification

| Week | Note | Topics covered |
|---|---|---|
| Overview | [`ML course1.html`](<./Course 1/ML course1.html>) | Full Course 1 recap — regression & classification fundamentals |
| Week 2 | [`gradient_descent_multiple_linreg_explained W2.html`](<./Course 1/W2/gradient_descent_multiple_linreg_explained W2.html>) | Gradient descent for **multiple** linear regression, vectorized form |
| Week 2 | [`gradient_descent_in_practice_complete2ndPart_explained W2.html`](<./Course 1/W2/gradient_descent_in_practice_complete2ndPart_explained W2.html>) | Feature scaling, learning rate choice, feature engineering, polynomial regression |
| Week 2 | [`numpy_reference.html`](<./Course 1/W2/Python and Numpy W2/notes/numpy_reference.html>) | Complete 1D & 2D NumPy reference (vectors, matrices, broadcasting, indexing) |
| Week 2 | [`matrices_before_numpy.html`](<./Course 1/W2/Python and Numpy W2/notes/matrices_before_numpy.html>) | Matrices explained from first principles, before introducing NumPy syntax |
| Week 2 | [`C1_W2_Lab01_Python_Numpy_Vectorization_Soln.ipynb`](<./Course 1/W2/Python and Numpy W2/C1_W2_Lab01_Python_Numpy_Vectorization_Soln.ipynb>) | Official course lab notebook — Python & NumPy vectorization |
| Week 3 | [`ML_Spec_Week3_part1_Logistic_Regression_and_cost_fun.html`](<./Course 1/W3/ML_Spec_Week3_part1_Logistic_Regression_and_cost_fun.html>) | Logistic regression: sigmoid, decision boundary, cost function, loss derivation |
| Week 3 | [`ML_Spec_Week3_Part2_GradientDescent_Regularization.html`](<./Course 1/W3/ML_Spec_Week3_Part2_GradientDescent_Regularization.html>) | Gradient descent for logistic regression, overfitting, and regularization |

---

## 📘 Course 2 — Advanced Learning Algorithms

| Week | Note | Topics covered |
|---|---|---|
| Week 1 | [`C2_W1_Part1_NN_Intuition_and_Model.html`](<./Course 2/week 1/C2_W1_Part1_NN_Intuition_and_Model.html>) | Neural network intuition — neurons, layers, why deep learning works |
| Week 1 | [`C2_W1_Part2_TensorFlow_Implementation.html`](<./Course 2/week 1/C2_W1_Part2_TensorFlow_Implementation.html>) | Building and training a neural network in TensorFlow/Keras |
| Week 1 | [`C2_W1_Part3_Forward_Prop_NumPy_Scratch.html`](<./Course 2/week 1/C2_W1_Part3_Forward_Prop_NumPy_Scratch.html>) | Implementing forward propagation from scratch in plain NumPy |
| Week 1 | [`C2_W1_Part4_Vectorization_MatrixMultiplication.html`](<./Course 2/week 1/C2_W1_Part4_Vectorization_MatrixMultiplication.html>) | Vectorizing a neural network layer with matrix multiplication |
| Week 2 | [`w2_p1_training_activations.html`](<./Course 2/week 2/w2_p1_training_activations.html>) | Training a neural network in TensorFlow, activation functions (ReLU, sigmoid, linear) |
| Week 2 | [`w2_p2_multiclass_softmax.html`](<./Course 2/week 2/w2_p2_multiclass_softmax.html>) | Multiclass classification, softmax, multi-label classification |
| Week 2 | [`w2_p3_adam_layers_backprop.html`](<./Course 2/week 2/w2_p3_adam_layers_backprop.html>) | Adam optimizer, alternative layer types, backpropagation & computation graphs |
| Week 3 | [`w3_p1_evaluation_cv_selection.html`](<./Course 2/week 3/w3_p1_evaluation_cv_selection.html>) | Train/CV/test splits, model evaluation, model selection |
| Week 3 | [`w3_p2_bias_variance.html`](<./Course 2/week 3/w3_p2_bias_variance.html>) | Bias vs. variance, diagnosing and fixing high bias/high variance |
| Week 3 | [`w3_p3_ml_development_process.html`](<./Course 2/week 3/w3_p3_ml_development_process.html>) | The iterative ML development loop, error analysis, data augmentation, transfer learning |
| Week 3 | [`w3_p4_skewed_datasets.html`](<./Course 2/week 3/w3_p4_skewed_datasets.html>) | Skewed/imbalanced datasets — precision, recall, F1 score |
| Week 4 | [`w4_p1_decision_trees.html`](<./Course 2/week 4/w4_p1_decision_trees.html>) | Decision trees, entropy, information gain, one-hot encoding for trees |
| Week 4 | [`w4_p2_tree_ensembles.html`](<./Course 2/week 4/w4_p2_tree_ensembles.html>) | Tree ensembles, random forests, XGBoost |

---

## 📙 Course 3 — Unsupervised Learning, Recommenders, Reinforcement Learning

| Week | Note | Topics covered |
|---|---|---|
| Week 1 | [`c3_w1_p1_kmeans.html`](<./Course 3/week 1/c3_w1_p1_kmeans.html>) | K-means clustering — algorithm, initialization, choosing K |
| Week 1 | [`c3_w1_p2_anomaly_detection.html`](<./Course 3/week 1/c3_w1_p2_anomaly_detection.html>) | Anomaly detection with the Gaussian distribution |
| Week 2 | [`c3_w2_p1_collaborative_filtering.html`](<./Course 3/week 2/c3_w2_p1_collaborative_filtering.html>) | Collaborative filtering recommender systems, binary labels, mean normalization |
| Week 2 | [`c3_w2_p2_content_based_filtering.html`](<./Course 3/week 2/c3_w2_p2_content_based_filtering.html>) | Content-based filtering, deep learning architecture, scaling to large catalogs, ethics of recommenders |
| Week 3 | [`c3_w3_p1_rl_fundamentals.html`](<./Course 3/week 3/c3_w3_p1_rl_fundamentals.html>) | RL fundamentals — return, discount factor, policy, the MDP framework |
| Week 3 | [`c3_w3_p2_bellman_stochastic.html`](<./Course 3/week 3/c3_w3_p2_bellman_stochastic.html>) | The state-action value function Q(s,a), a full derivation of the Bellman equation, stochastic environments |
| Week 3 | [`c3_w3_p3_dqn_lunar_lander.html`](<./Course 3/week 3/c3_w3_p3_dqn_lunar_lander.html>) | Continuous state spaces, the Lunar Lander problem, Deep Q-Learning (DQN), ε-greedy, mini-batching, soft updates |

---

## 🗂️ Full topic index

<details>
<summary><strong>Click to expand — every topic in the specialization, in one flat list</strong></summary>

**Course 1:** Linear regression · Gradient descent · Multiple linear regression · Vectorization · Feature scaling & engineering · Polynomial regression · Logistic regression · Sigmoid & decision boundary · Cost & loss functions · Overfitting · Regularization

**Course 2:** Neural network intuition · TensorFlow implementation · Forward propagation from scratch · Matrix multiplication vectorization · Activation functions · Multiclass & softmax · Multi-label classification · Adam optimizer · Backpropagation · Train/CV/test evaluation · Model selection · Bias vs. variance · The ML development process · Error analysis · Transfer learning · Precision/recall/F1 for skewed data · Decision trees · Entropy & information gain · Random forests · XGBoost

**Course 3:** K-means clustering · Anomaly detection · Collaborative filtering · Content-based filtering · Deep learning for recommenders · Retrieval & ranking at scale · Ethics of recommender systems · Reinforcement learning fundamentals · Return & discount factor · Policies · Markov Decision Processes · The Q function · The Bellman equation · Stochastic environments · Continuous state spaces · Deep Q-Networks (DQN) · Experience replay · ε-greedy exploration · Soft updates

</details>

---

## 🧩 Notes on structure

- Folder names follow the course's own numbering (`Course 1`, `week 2`, etc.) — capitalization is a little inconsistent between courses since these were organized on the go while studying, not restructured afterward.
- Files are split by "part" roughly along natural lecture boundaries, not strictly by video — a "part" is usually a self-contained chunk of related concepts.
- The Course 1, Week 2 folder also includes the official course lab notebook (`.ipynb`) for reference, alongside the custom notes.

---

## 📬 Contact

If you spot an error, have a suggestion, or just want to talk about the specialization:

**📧 yomnasabry252@gmail.com**

⭐ I hope you take benefit of it!
