# CS5710 Machine Learning — Home Assignment 4

## Student Information

**Name:** Sunil Kumar Vuta
**Course:** CS5710 — Machine Learning
**Semester:** Fall 2025
**Department:** Computer Science & Cybersecurity, University of Central Missouri

---

## Overview

This README explains the work completed for **Home Assignment 4**. The assignment consists of three main parts:

* **Part A:** Manual clustering calculations
* **Part B:** Short‑answer conceptual questions
* **Part C:** Coding tasks involving NLP preprocessing and Named Entity Recognition

All written answers are included in the submitted document, and all coding tasks are implemented in the accompanying Jupyter Notebook.

---

## Repository Contents

```
├── HW4 700772302.docx       # Written answers for Parts A & B
├── HW_CODING.ipynb          # Python code for Part C (tokenization, lemmatization, NER)
├── README.md                # This file
```

---

## Part A — Clustering Calculations

This section includes:

* Constructing the **Euclidean distance matrix** for the given points
* Applying **Average Linkage** and **Single Link (MIN)** techniques
* Updating distance matrices step‑by‑step
* Drawing dendrograms for both methods

All calculations and dendrogram sketches are provided in the `.docx` file.

---

## Part B — Short-Answer Questions

The written document contains detailed explanations for:

* Agglomerative vs. divisive hierarchical clustering
* Inter‑cluster vs. intra‑cluster distances
* Linkage criteria (single, complete, average)
* Ambiguity in NLP (word sense, pronoun reference)
* POS tagging dependencies

---

## Part C — Coding

All Python implementation is located in **HW_CODING.ipynb**.

### **Q1 — NLP Preprocessing Pipeline**

The notebook includes Python code to:

1. **Tokenize** the input sentence
2. **Remove stopwords**
3. **Lemmatize tokens** (using WordNetLemmatizer)
4. **Apply POS tagging**
5. **Keep only verbs and nouns**

Input example used:

> "John enjoys playing football while Mary loves reading books in the library."

### **Q2 — Named Entity Recognition + Pronoun Ambiguity Warning**

The code performs:

* Named Entity Recognition using an NLP model (e.g., spaCy)
* Detection of pronouns (`he`, `she`, `they`, etc.)
* Prints the warning:

  > "Warning: Possible pronoun ambiguity detected!"
  > when applicable

Input example:

> "Chris met Alex at Apple headquarters in California. He told him about the new iPhone launch."

---

## How to Run the Code

1. Open the notebook:

   ```
   HW_CODING.ipynb
   ```
2. Ensure the necessary libraries are installed:

   ```bash
   pip install spacy nltk
   python -m spacy download en_core_web_sm
   ```
3. Execute each cell in order.

---

## Notes

* All code has been **commented clearly** as required.
* README includes all required student information.
* All parts of the assignment have been completed and organized.

---

## Contact

If clarification is needed, feel free to reach out.

**Student:** Sunil Kumar Vuta
