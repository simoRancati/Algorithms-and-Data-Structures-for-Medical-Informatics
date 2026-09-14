# Algorithms-and-Data-Structures-for-Medical-Informatics

This repository contains the slides and teaching materials from the course **Algorithms and Data Structures for Medical Informatics**, taught by **Prof. Simone Rancati, PhD**, for the ITS **Giulio Natta** at **San Raffaele Hospital**.

The course introduces the foundations of **algorithms, data structures, biomedical data representation, machine learning, and deep learning**, always connecting computer-science concepts with practical examples from **medical informatics and healthcare**.

---

## Course Overview

Modern healthcare systems generate many different types of data:

- electronic health records;
- laboratory measurements;
- physiological signals such as ECG, EEG, CGM, and blood pressure;
- medical images;
- genomic sequences;
- clinical text;
- patient, gene, and hospital networks.

Working effectively with these data requires more than knowing how to write code. It requires understanding how information is represented, how algorithms operate on different structures, how computational efficiency changes with data size, and how predictive models should be trained and evaluated.

Throughout the course, students progressively move from basic computational thinking to complete biomedical machine-learning pipelines.

> **Main question of the course:**  
> How can a biomedical problem be translated into a precise, efficient, reproducible, and clinically meaningful computational procedure?

---

## Learning Objectives

By the end of the course, students should be able to:

- understand what an algorithm is and distinguish it from a program or software system;
- identify inputs, processing steps, and outputs in a computational problem;
- represent algorithms using **pseudocode** and **flowcharts**;
- use the basic control structures:
  - sequence;
  - selection;
  - iteration;
- understand the fundamentals of **computational complexity** and Big-O notation;
- use and compare the main data structures covered in the course;
- understand searching, sorting, recursion, divide-and-conquer, greedy algorithms, and dynamic programming;
- represent biomedical data appropriately according to their structure;
- work conceptually with:
  - tabular clinical data;
  - time series;
  - physiological signals;
  - medical images;
  - genomic sequences;
  - graphs and networks;
- understand the main stages of a supervised machine-learning workflow;
- distinguish classification from regression;
- evaluate machine-learning models using appropriate metrics;
- recognize and avoid problems such as overfitting, class imbalance, and data leakage;
- understand the foundations of neural networks and deep learning;
- recognize the role of CNNs, recurrent/sequential models, and Transformers in biomedical applications;
- build and reason about a complete biomedical ML pipeline from dataset to evaluation.

---

# Course Program

The course is organized into **24 lessons** and progresses from foundational computer science to machine learning and deep learning in biomedicine.

---

## Part I — Algorithms and Computational Thinking

### Lesson 1 — Introduction to Algorithms and Data Structures

Topics:

- What is an algorithm?
- Input, processing, and output.
- Algorithm vs program vs software system.
- Properties of a well-defined algorithm.
- Introduction to data structures.
- Biomedical examples.
- Formalizing a clinical rule as an algorithm.

Examples:

- glucose classification;
- patient lookup;
- ECG analysis;
- hospital triage.

---

### Lesson 2 — Pseudocode, Flowcharts, and Programming Algorithms

Topics:

- Pseudocode.
- Flowcharts.
- Sequence.
- Selection.
- Iteration.
- `IF / ELSE`.
- `FOR` loops.
- `WHILE` loops.
- From algorithm to program.
- Input validation and edge cases.

Biomedical examples:

- BMI calculation;
- heart-rate classification;
- simple clinical alert systems.

---

### Lesson 3 — Algorithm Efficiency and Computational Complexity

Topics:

- Why efficiency matters.
- Time complexity.
- Space complexity.
- Big-O notation.
- `O(1)`.
- `O(log n)`.
- `O(n)`.
- `O(n log n)`.
- `O(n²)`.
- Scalability.
- Worst-case reasoning.

Biomedical perspective:

- one patient vs thousands of patients;
- one glucose value vs millions of measurements;
- computational cost in large-scale clinical data processing.

---

## Part II — Fundamental Data Structures

### Lesson 4 — Arrays, Vectors, Matrices, and Strings

Topics:

- Arrays.
- Indexing.
- Traversal.
- Vectors.
- Matrices.
- Rows and columns.
- Strings.
- Basic multidimensional structures.
- Introduction to tensors.

Biomedical examples:

- ECG as a vector;
- CGM measurements as an array;
- patient datasets as matrices;
- DNA as a string;
- medical images as matrices.

---

### Lesson 5 — Search, Recursion, and Divide-and-Conquer

Topics:

- Linear search.
- Binary search.
- Sorted data.
- Recursion.
- Base case.
- Recursive case.
- Call stack.
- Divide-and-conquer.

Biomedical examples:

- searching patient archives;
- retrieving ordered clinical records.

---

### Lesson 6 — Sorting Algorithms

Topics:

- Why sorting is useful.
- Sorting keys.
- Ascending and descending order.
- Bubble sort.
- Selection sort.
- Insertion sort.
- Merge sort.
- Quicksort.
- Complexity comparison.

Biomedical examples:

- sorting patients by waiting time;
- ordering measurements;
- ranking patients by risk score.

---

### Lesson 7 — Lists, Stacks, Queues, and Priority Queues

Topics:

- Lists.
- Stack.
- LIFO behavior.
- `push`, `pop`, and `peek`.
- Queue.
- FIFO behavior.
- `enqueue` and `dequeue`.
- Priority queue.

Biomedical examples:

- clinical software navigation;
- patient waiting lines;
- emergency-department triage;
- urgency-based patient prioritization.

---

### Lesson 8 — Dictionaries, Hash Tables, and Sets

Topics:

- Dictionaries.
- Key-value pairs.
- Hash tables.
- Hash functions.
- Collisions.
- Average `O(1)` lookup.
- Sets.
- Membership tests.

Biomedical examples:

- patient ID → medical record;
- diagnosis sets;
- medication sets;
- rapid patient lookup.

---

### Lesson 9 — Linked Lists and Dynamic Data Management

Topics:

- Nodes.
- References.
- Head and tail.
- Singly linked lists.
- Doubly linked lists.
- Circular linked lists.
- Dynamic data structures.
- Traversal.
- Insertion and deletion.

Biomedical examples:

- continuously acquired wearable data;
- dynamic clinical-event sequences.

---

### Lesson 10 — Trees, Binary Search Trees, Heaps, and Priority Queues

Topics:

- Tree structures.
- Root, parent, child, leaf.
- Binary trees.
- Binary Search Trees.
- Tree traversal.
- Heaps.
- Min-heaps and max-heaps.
- Priority queues.

Biomedical examples:

- clinical decision trees;
- hierarchical clinical reasoning;
- emergency triage.

---

## Part III — Graphs and Algorithmic Paradigms

### Lesson 11 — Graph Representation and Data Structures

Topics:

- Graphs.
- Vertices.
- Edges.
- Directed and undirected graphs.
- Weighted graphs.
- Adjacency matrices.
- Adjacency lists.
- Edge lists.
- Sparse vs dense graphs.

Biomedical examples:

- patient-contact networks;
- gene networks;
- protein-protein interaction networks;
- brain connectivity networks;
- hospital referral networks.

---

### Lesson 12 — Graph Algorithms

Topics:

- Graph traversal.
- Breadth-First Search (BFS).
- Depth-First Search (DFS).
- Queues and stacks in graph traversal.
- Shortest paths.
- Dijkstra's algorithm.

Biomedical examples:

- infection-contact networks;
- hospital pathways;
- metabolic networks;
- referral networks.

---

### Lesson 13 — Greedy Algorithms and Dynamic Programming

Topics:

- Greedy algorithms.
- Local vs global optimum.
- Greedy-choice property.
- Scheduling problems.
- Dynamic programming.
- Optimal substructure.
- Overlapping subproblems.
- Memoization.
- Tabulation.

Biomedical examples:

- healthcare-resource scheduling;
- biological sequence alignment.

---

## Part IV — Biomedical Data Structures

### Lesson 14 — Digital Healthcare Data Structures

Topics:

- Electronic Medical Records (EMR).
- Electronic Health Records (EHR).
- Relational tables.
- Primary and foreign keys.
- JSON.
- XML.
- Clinical coding.
- Clinical terminologies.
- HL7.
- FHIR.
- Healthcare interoperability.

Examples:

- Patient;
- Encounter;
- Observation;
- Condition;
- Medication information.

---

### Lesson 15 — Temporal Biomedical Data and Physiological Signals

Topics:

- Time series.
- Timestamps.
- Sampling rate.
- Sampling interval.
- Regular and irregular sampling.
- Missing data.
- Noise and artifacts.
- Resampling.
- Interpolation.
- Sliding windows.

Biomedical examples:

- ECG;
- EEG;
- CGM;
- blood pressure;
- wearable sensors.

---

### Lesson 16 — Medical Imaging, Genomics, and Multidimensional Structures

Topics:

- Pixels.
- Voxels.
- Image matrices.
- Multidimensional arrays.
- Tensors.
- DICOM.
- Imaging metadata.
- DNA and RNA sequences.
- One-hot encoding.
- k-mers.

Biomedical examples:

- radiographs;
- CT;
- MRI;
- genomic sequences.

---

## Part V — Machine Learning for Medical Informatics

### Lesson 17 — Introduction to Machine Learning as an Algorithm

Topics:

- Machine learning as a computational procedure.
- Dataset.
- Sample.
- Feature.
- Target.
- Training.
- Model.
- Inference.
- Classification.
- Regression.
- Train / validation / test split.
- Overfitting.
- Data leakage.

Biomedical examples:

- diagnosis;
- prognosis;
- risk prediction;
- glucose forecasting;
- medical-image classification.

---

### Lesson 18 — Supervised Machine Learning: Classification and Regression

Topics:

- Supervised learning.
- k-Nearest Neighbors.
- Distance metrics.
- Feature scaling.
- Linear regression.
- Logistic regression.
- Sigmoid function.
- Decision thresholds.
- Classification vs regression.

Biomedical examples:

- sick vs healthy classification;
- future glucose prediction.

---

### Lesson 19 — Decision Trees, Random Forests, and Ensemble Algorithms

Topics:

- Decision trees.
- Root nodes.
- Internal nodes.
- Leaves.
- Splitting criteria.
- Gini impurity.
- Entropy.
- Tree depth.
- Overfitting.
- Pruning.
- Random forests.
- Bootstrap sampling.
- Random feature subsets.
- Bagging.
- Ensemble learning.
- Feature importance.

Biomedical example:

- clinical-risk prediction using decision trees.

---

### Lesson 20 — Evaluating Machine Learning Algorithms in Medicine

Topics:

- Training, validation, and test sets.
- Cross-validation.
- Stratification.
- Patient-level splitting.
- Temporal splitting.
- External validation.
- Overfitting.
- Confusion matrix.
- Accuracy.
- Sensitivity / Recall.
- Specificity.
- Precision.
- F1 score.
- ROC curve.
- ROC-AUC.
- Class imbalance.
- Data leakage.
- Confidence intervals.

Clinical perspective:

- screening vs confirmatory testing;
- false positives and false negatives;
- choosing metrics according to the clinical use case.

---

## Part VI — Deep Learning in Biomedicine

### Lesson 21 — Deep Learning and Neural Networks

Topics:

- Artificial neuron.
- Weights.
- Bias.
- Activation functions.
- ReLU.
- Sigmoid.
- Neural-network layers.
- Hidden layers.
- Forward propagation.
- Loss functions.
- Gradient descent.
- Learning rate.
- Backpropagation.
- Epochs.
- Mini-batches.
- Regularization.
- Early stopping.

Biomedical examples:

- tabular clinical data;
- physiological signals;
- medical imaging.

---

### Lesson 22 — CNNs, Sequential Models, and Transformers in Biomedicine

Topics:

- Convolutional Neural Networks.
- Convolutional filters.
- Feature maps.
- Pooling.
- 1D CNNs.
- Recurrent Neural Networks.
- Hidden states.
- LSTM.
- GRU.
- Transformers.
- Self-attention.
- Query, Key, Value.
- Multi-head attention.
- Positional information.
- Embeddings.
- Transfer learning.

Biomedical applications:

- CNNs for radiographs;
- ECG classification;
- CGM forecasting;
- clinical-text analysis;
- DNA and protein sequences.

---

## Part VII — Hands-On Biomedical Machine Learning

### Lesson 23 — Laboratory: Building a Complete Biomedical ML Pipeline

The laboratory integrates the topics covered throughout the course.

```text
Clinical dataset
        ↓
Data representation
        ↓
Preprocessing
        ↓
Train / test split
        ↓
Algorithm
        ↓
Training
        ↓
Prediction
        ↓
Evaluation
        ↓
Error analysis
```

Topics:

- defining the clinical question;
- feature matrix `X`;
- target vector `y`;
- missing-value imputation;
- categorical encoding;
- numeric standardization;
- `ColumnTransformer`;
- ML pipelines;
- logistic regression;
- random forest;
- probability prediction;
- decision thresholds;
- evaluation metrics;
- class imbalance;
- cross-validation;
- error analysis;
- model interpretation;
- saving and reusing a fitted pipeline.

---

### Lesson 24 — Project Work, Discussion, and Course Recap

The final lesson is dedicated to:

- project work;
- discussion of complete biomedical-computing workflows;
- integration of algorithms and data structures;
- review of the main course concepts;
- discussion of design choices;
- interpretation of computational results;
- final recap.

---

# Biomedical Examples Used Throughout the Course

| Computer Science Concept | Biomedical Example |
|---|---|
| Scalar | Single glucose measurement |
| Array / Vector | ECG, CGM, heart-rate measurements |
| Matrix | Patient-feature dataset |
| String | DNA / RNA sequence |
| Queue | Patient waiting line |
| Priority Queue | Emergency triage |
| Dictionary | Patient ID → medical record |
| Tree | Clinical decision process |
| Graph | Patient-contact or gene network |
| Sorting | Patients ordered by waiting time or risk |
| Search | Patient-record retrieval |
| Dynamic Programming | Biological-sequence alignment |
| Time Series | ECG, EEG, CGM |
| Matrix / Tensor | Medical images |
| Classification | Sick vs healthy |
| Regression | Future glucose prediction |
| CNN | Radiograph analysis |
| Sequential Model | ECG / CGM modeling |
| Transformer | Clinical text and biological sequences |

---

# Teaching Approach

The course follows a progressive and application-oriented approach.

Each topic is introduced using a combination of:

1. **Conceptual explanation**
2. **Formal algorithmic representation**
3. **Pseudocode**
4. **Flowcharts and diagrams**
5. **Biomedical examples**
6. **Small exercises**
7. **Hands-on computational tasks**

The goal is not only to teach programming syntax, but to develop a way of thinking:

> **Understand the problem → structure the data → choose the algorithm → implement it correctly → evaluate the result.**

---

# Course Progression

```text
Computational thinking
        ↓
Algorithms
        ↓
Pseudocode and control flow
        ↓
Computational complexity
        ↓
Fundamental data structures
        ↓
Search and sorting
        ↓
Trees and graphs
        ↓
Algorithmic paradigms
        ↓
Biomedical data representations
        ↓
Machine Learning
        ↓
Deep Learning
        ↓
Complete biomedical AI pipeline
```

---

# Suggested Repository Structure

```text
Algorithms-and-Data-Structures-for-Medical-Informatics/
│
├── Lesson_01_Introduction/
├── Lesson_02_Pseudocode_Flowcharts/
├── Lesson_03_Computational_Complexity/
├── Lesson_04_Arrays_Vectors_Matrices_Strings/
├── Lesson_05_Search_Recursion/
├── Lesson_06_Sorting/
├── Lesson_07_Lists_Stacks_Queues/
├── Lesson_08_Dictionaries_HashTables_Sets/
├── Lesson_09_Linked_Lists/
├── Lesson_10_Trees_Heaps_PriorityQueues/
├── Lesson_11_Graph_Representation/
├── Lesson_12_Graph_Algorithms/
├── Lesson_13_Greedy_Dynamic_Programming/
├── Lesson_14_Digital_Health_Data/
├── Lesson_15_Biomedical_Time_Series/
├── Lesson_16_Medical_Imaging_Genomics/
├── Lesson_17_Introduction_Machine_Learning/
├── Lesson_18_Supervised_Machine_Learning/
├── Lesson_19_Trees_Random_Forest_Ensembles/
├── Lesson_20_ML_Evaluation/
├── Lesson_21_Deep_Learning/
├── Lesson_22_CNN_Sequential_Transformers/
├── Lesson_23_Biomedical_ML_Lab/
└── Lesson_24_Project_and_Recap/
```

---

# Instructor

**Prof. Simone Rancati, PhD**

**Course:** Algorithms and Data Structures for Medical Informatics  
**Program:** ITS Giulio Natta  
**Location:** San Raffaele Hospital

---

# Final Perspective

Medical informatics lies at the intersection of **computer science, biomedical data, and healthcare**.

Understanding algorithms and data structures provides the foundation for:

- healthcare software;
- biomedical signal processing;
- electronic health-record analysis;
- medical imaging;
- computational genomics;
- machine learning;
- deep learning;
- clinical artificial intelligence.

The core idea of the course is:

> **Before building intelligent biomedical systems, we must understand how data are represented, how algorithms operate on them, and how computational decisions are evaluated.**
