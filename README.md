#  CNF Toy Grammar Parser

This project demonstrates a **toy grammar in Chomsky Normal Form (CNF)** using **NLTK (Natural Language Toolkit)**.  
It allows parsing of **POS-tagged sequences** and **raw sentences**, visualizing parse trees inline, and testing grammar validity.  

The notebook (`cfg_toygrammer.ipynb`) was built and tested on **Google Colab**.

---

##  Features
- Define and load a **custom CFG grammar**  
- Parse **POS-tag sequences** (e.g., `PRP VBD DT NN .`)  
- Parse **raw English sentences** (tokenize + POS tag + simplify tags)  
- Visualize parse trees using **Matplotlib & NetworkX**  
- Batch evaluation support with datasets (`train.tsv`)  
- Interactive parsing modes:  
  - Mode 1 → Input POS-tag sequences  
  - Mode 2 → Input raw sentences  

---

## 🛠️ Tech Stack
- **Python 3**
- **NLTK**
- **Pandas**
- **Matplotlib**
- **NetworkX**
- **Jupyter Notebook / Google Colab**

---

## 📂 Project Structure




---

## ▶️ How to Run

### Option 1: Run on Google Colab
1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload `cfg_toygrammer.ipynb`.  
3. Run all cells.  

### Option 2: Run Locally
1. Clone this repository:  
   ```bash
   git clone https://github.com/gopaljee96/cfg-toy-grammar.git
   cd cfg-toy-grammar

### 2.  Install dependencies:
pip install nltk pandas matplotlib networkx pillow ipywidgets

### 3. Open the notebook in Jupyter:
jupyter notebook cfg_toygrammer.ipynb

