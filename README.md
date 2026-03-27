# 🧠 Vector Space Proximity Workshop

## 👥 Group Information

**Group Name:** Group 8  

**Members:**

- Haibo Yuan (Student ID: 9010929)  
- Abdalla Mohamed (Student ID: 9089339)  

---

## 📊 Dataset

We used the **20 Newsgroups dataset** from scikit-learn.

- Number of documents: ~11,000  
- Number of categories: 20  
- Domain: Technology, science, politics, recreation, and more  

This dataset is suitable for Information Retrieval tasks because it contains diverse topics and a large number of documents.

---

## ⚙️ Retrieval Approach

We implemented an Information Retrieval system using:

- Text preprocessing (tokenization, normalization, stop-word removal, stemming)  
- Vector space representations:
  - Binary incidence  
  - Term Frequency (TF)  
  - TF-IDF  
- Cosine similarity for document retrieval  

---

## 📈 Evaluation

We evaluated the system using:

- Confusion Matrix  
- Precision, Recall, F1-score  
- Precision@K  
- Average Precision (AP)  
- Mean Reciprocal Rank (MRR)  
- Cohen’s Kappa (for agreement analysis)  

---

## 🎯 Key Insight

TF-IDF combined with cosine similarity provides better retrieval performance because it highlights important terms while reducing the impact of common words.

The evaluation shows that relevant documents are ranked higher, demonstrating that retrieval is based on the **information need**, not just keyword matching.