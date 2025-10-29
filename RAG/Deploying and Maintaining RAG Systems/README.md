![alt text](img/image.png)

## Problems

1) LLM has not seen private or recent data
2) Poor response

### Enterprise data

### context -> Linited context window
###         -> Quality degradation


## RAG System
### RAG has 2 pipeline
1) ingestion pipeline
2) RAG Pipeline
    
    **<span style="color:#00bfff;">1) Enterprise Data</span> → <span style="color:#32cd32;">Data Parsing and Chunking</span> → <span style="color:#ffa500;">Chunks</span> → <span style="color:#ff69b4;">Embedding Model</span> → <span style="color:#9370db;">Index Store (Vector DB)</span> → <span style="color:#00bfff;">Query Embedding</span> ← <span style="color:#ff69b4;">Embedding Model</span> ← <span style="color:#32cd32;">Query</span> ← <span style="color:#ffa500;">User</span>**

    ![alt text](img/image-1.png)

    
<br>
<br>

|  🌐 | **Feature**                                    | **Description**                                                                                                                       |
| :-: | :--------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------ |
|  🔒 | **Includes Your Private & Recent Data**        | Seamlessly integrates with your enterprise or personal datasets, ensuring responses stay contextually relevant and always up to date. |
|  💰 | **Low LLM Cost Based on Usage**                | Designed to minimize token usage by reusing embeddings and optimizing retrieval, resulting in significantly lower operational costs.  |
|  🧠 | **Grounded Responses & Reduced Hallucination** | Enhances factual accuracy by grounding answers in verified and reliable data sources.                                                 |
|  📚 | **Source Citations & Attribution**             | Automatically provides references and citations for each response to ensure transparency and traceability.    
<br>

## RAG Framework
![alt text](img/image-2.png)


