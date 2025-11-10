
# The Small Talk Hypothesis: Do Smaller Language Models Explain Themselves Better?

### 📄 Description
(Note: Open *Models_clean.ipynb* if you are not able to access *Models.ipynb*)
This project investigates how model size affects explainability in transformer-based NLP models. Using **DistilBERT** and **BERT** fine-tuned on the **SST-2 sentiment analysis dataset**, we compare their performance and explanation quality using **SHAP** and **LIME** interpretability methods.

### 📊 Key Goals
- Compare accuracy and F1-score between models of different sizes.  
- Measure **fidelity** (how well explanations match model behavior).  
- Measure **stability** (consistency of explanations under small input changes).  
- Generate SHAP visualizations for model interpretability.  

### 🧪 Dataset
**Stanford Sentiment Treebank (SST-2)** via Hugging Face (`glue`, subset: `sst2`).

### 🧰 How to Run
1. **Clone this repository:**
   ```bash
   git clone https://github.com/shambhavi-tiwari/The-Small-Talk-Hypothesis.git
   cd The-Small-Talk-Hypothesis
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**

   ```bash
   jupyter notebook Models_clean.ipynb
   ```

   or open it directly in **Google Colab**.

### 📈 Results

| Model      | Accuracy | F1   | Notes                      |
| ---------- | -------- | ---- | -------------------------- |
| DistilBERT | 0.89     | 0.88 | Faster, lightweight        |
| BERT       | 0.91     | 0.90 | More accurate, less stable |

SHAP visualizations show that smaller models tend to produce simpler and more stable explanation patterns.

### 🧑‍💻 Author

**Shambhavi Tiwari**
VIT Vellore | 5th Sem


