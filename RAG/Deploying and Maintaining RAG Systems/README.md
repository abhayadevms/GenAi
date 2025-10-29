<div style="background-color:#000000; color:#ffffff; padding:20px; border-radius:10px;">

<img src="img/image.png" alt="Overview" width="700"/>

## ⚠️ Problems

1️⃣ **LLM has not seen private or recent data**  
2️⃣ **Poor response quality**

---

### 🏢 Enterprise Data

#### ⚙️ Context Limitations
- **Limited Context Window**  
- **Quality Degradation**

---

## 🤖 RAG System

RAG operates with **two main pipelines**:

1️⃣ **Ingestion Pipeline**  
2️⃣ **RAG Pipeline**

<br>

**<span style="color:#00bfff;">1) Enterprise Data</span> → <span style="color:#32cd32;">Data Parsing and Chunking</span> → <span style="color:#ffa500;">Chunks</span> → <span style="color:#ff69b4;">Embedding Model</span> → <span style="color:#9370db;">Index Store (Vector DB)</span> → <span style="color:#00bfff;">Query Embedding</span> ← <span style="color:#ff69b4;">Embedding Model</span> ← <span style="color:#32cd32;">Query</span> ← <span style="color:#ffa500;">User</span>**

<img src="img/image-1.png" alt="RAG Pipeline" width="700"/>

<br><br>

---

## 🌟 Merits

| 🌐 | **Feature** | **Description** |
|:--:|:-------------|:----------------|
| 🔒 | **Includes Your Private & Recent Data** | Seamlessly integrates with your enterprise or personal datasets, ensuring responses stay contextually relevant and always up to date. |
| 💰 | **Low LLM Cost Based on Usage** | Designed to minimize token usage by reusing embeddings and optimizing retrieval, resulting in significantly lower operational costs. |
| 🧠 | **Grounded Responses & Reduced Hallucination** | Enhances factual accuracy by grounding answers in verified and reliable data sources. |
| 📚 | **Source Citations & Attribution** | Automatically provides references and citations for each response to ensure transparency and traceability. |

<br>

---

## 🧩 RAG Framework

<img src="img/image-2.png" alt="RAG Framework" width="700"/>

</div>
