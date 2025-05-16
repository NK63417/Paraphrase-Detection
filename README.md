# Paraphrase Detection using Transformers and Graphs

An NLP model that combines BERT with Graph Attention Networks (GAT) to detect paraphrased sentence pairs from the MRPC dataset.

---

## 🚀 Project Highlights

- Combines **transformer-based contextual modeling** with **graph-based token interaction**
- Achieved **F1-score of 0.873** on the MRPC dataset
- Built using **TensorFlow**, **BERT (bert-base-uncased)**, and **custom GAT layers**
- Compared against baseline BERT-only model

---

## 🧠 Methodology

- **Input**: Sentence pairs from MRPC
- **Backbone**: BERT extracts contextual embeddings
- **Graph Attention**: Learns semantic relationships between token embeddings
- **Output**: Binary classification – paraphrase or not

---

## 📊 Results

| Metric        | Hybrid Model | Base BERT |
|---------------|--------------|------------|
| Accuracy      | 0.8145       | 0.664      |
| Precision     | 0.798        | 0.664      |
| Recall        | 0.965        | 1.0        |
| F1 Score      | 0.873        | 0.798      |

---

## 📁 File Structure

Paraphrase-Detection/
├── report/             # Final PDF paper
├── presentation/       # PPT slides
├── notebooks/          # Model development notebooks (if public)
├── src/                # Custom code (e.g., GAT layers)
├── requirements.txt    # Python dependencies
├── README.md
└── LICENSE

---

## ⚙️ Installation

```bash
git clone https://github.com/NK63417/Paraphrase-Detection.git
cd Paraphrase-Detection
pip install -r requirements.txt
```

---

🧪 Run the Model

```python
python train_model.py
```

---

📚 References
  •	GLUE Benchmark
	•	BERT: Devlin et al. (2018)
	•	GAT: Velickovic et al. (2017)

 ---

 🙋‍♂️ About Me

Nanda Kishore Kappaganthula
Graduate, Computer Science – Western University
Reach me at: nandakishore02aug@gmail.com

---
