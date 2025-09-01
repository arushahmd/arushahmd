## 😃 Hi I am Aroosh Ahmad!.
<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExbGh6b2xuM3hubWl6ZTg5eThnOTJtNHZsNGduaHVrazl3ZnM5M3JzeiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/coxQHKASG60HrHtvkt/giphy.gif" width=320 align="right" /> 

<b>AI Engineer · NLP • LLMs • CV • MLOps</b>  <br>
MPhil (AI) candidate <b>@</b> [PUCIT](https://www.pu.edu.pk/)<br>
<b>Research → </b> LLM finetuning, hyperparameter optimization & production-grade LLM systems

### 💼 Open To
- **Roles:** LLM / NLP / Computer Vision / ML Engineering
- **Strengths:** Model deployment, RAG pipelines, vector search, and optimization

######
```python
from langchain.embeddings import HuggingFaceEmbeddings
from langchain.vectorstores import FAISS
from langchain.llms import OpenAI
from langchain.chains import RetrievalQA

# Create embeddings and vector store
emb = HuggingFaceEmbeddings(model_name="sentence-transformers/all-MiniLM-L6-v2")
index = FAISS.from_documents(chunks, emb)

# Retriever + LLM
retriever = index.as_retriever(search_kwargs={"k": 5})
llm = OpenAI(model="gpt-4", temperature=0)
qa_chain = RetrievalQA.from_chain_type(llm=llm, retriever=retriever)
print(qa_chain.run("Explain the key findings"))

```
### Key Repositories
<p align="center">
<a href="https://github.com/arushahmd/ai-projects">🔹 ai-projects</a> •
<a href="https://github.com/arushahmd/ai-labs">🔹 ai-labs</a> •
<a href="https://github.com/arushahmd/pose-estimation-correction-ui-emgucv">🔹 pose-detection</a> •
<a href="https://github.com/arushahmd/urdu-ocr-media-utils">🔹 urdu-ocr-media-utils</a> •
<a href="https://github.com/arushahmd/datamatrix-recovery">🔹 data-matrix-recovery</a>
</p>

### 🧩 Example: End-to-End RAG Pipeline
<details>
<summary>Click to expand</summary>
  
```python
from langchain.embeddings import HuggingFaceEmbeddings
from langchain.vectorstores import FAISS
from langchain.llms import OpenAI
from langchain.chains import RetrievalQA

# Create embeddings and vector store
emb = HuggingFaceEmbeddings(model_name="sentence-transformers/all-MiniLM-L6-v2")
index = FAISS.from_documents(chunks, emb)

# Retriever + LLM
retriever = index.as_retriever(search_kwargs={"k": 5})
llm = OpenAI(model="gpt-4", temperature=0)
qa_chain = RetrievalQA.from_chain_type(llm=llm, retriever=retriever)
print(qa_chain.run("Explain the key findings"))

```
</details>

<p align="left">
<span>
<img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="40" style="vertical-align: middle; margin-right: 8px;" />
<em><b>Thanks for visiting!</b></em> I'm open to AI/ML roles in NLP, CV, and LLM-focused teams.
Feel free to explore my repositories or reach out — <strong>always happy to connect and collaborate 🤝</strong>
</span>
</p>

<p align="center">
<a href="https://linkedin.com/in/arushahmd">
<img src="https://img.shields.io/badge/in-LinkedIn-0077B5?style=flat-square" />
</a>
<a href="https://github.com/arushahmd">
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
</a>
<a href="https://www.kaggle.com/arooshahmadds">
<img src="https://img.shields.io/badge/Kaggle-5AC8FA?style=flat-square&logo=kaggle&logoColor=white" />
</a>
<a href="https://www.geeksforgeeks.org/user/arooshahxf10/">
<img src="https://img.shields.io/badge/GeeksforGeeks-0F9D58?style=flat-square&logo=geeksforgeeks&logoColor=white" />
</a>
<a href="https://www.hackerrank.com/profile/arooshahmad_data">
<img src="https://img.shields.io/badge/HackerRank-24292F?style=flat-square&logo=hackerrank&logoColor=white" />
</a>
</p>









  
