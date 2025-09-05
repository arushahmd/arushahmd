# 😃 Hi, I'm Aroosh Ahmad!

**AI / ML Engineer @ [CygnusPay](https://cygnuspay.com)** · MPhil (AI) @ [PUCIT](https://www.pu.edu.pk/)  
Specialized in **LLMs, NLP, Computer Vision, and MLOps**

**I build and deploy production-grade AI systems.**  
- ⚡ LLM / RAG pipelines (data → vector DB → retriever + LLM)
- 🛠️ Scalable deployment · MLOps · vector search  
- 🎯 Retrieval optimization · inference speed · cost reduction  
- 🚀 Hands-on with fine-tuning, hyperparameter tuning, and model serving  

**Open to:** LLM · NLP · Computer Vision · ML Engineering roles  

## ⚙️ Quick RAG Pipeline Example

```python
from langchain.document_loaders import PyPDFLoader
from langchain.text_splitter import RecursiveCharacterTextSplitter
from langchain.embeddings import HuggingFaceEmbeddings
from langchain.vectorstores import FAISS
from langchain.llms import OpenAI
from langchain.chains import RetrievalQA

# Load and split PDF
docs = PyPDFLoader("sample.pdf").load()
chunks = RecursiveCharacterTextSplitter(
    chunk_size=1000, chunk_overlap=200
).split_documents(docs)

# Embed + store in FAISS
embeddings = HuggingFaceEmbeddings(model_name="sentence-transformers/all-MiniLM-L6-v2")
db = FAISS.from_documents(chunks, embeddings)

# Retriever + LLM
qa = RetrievalQA.from_chain_type(
    llm=OpenAI(model="gpt-4", temperature=0),
    retriever=db.as_retriever(search_kwargs={"k": 5})
)

print(qa.run("What are the key findings in the PDF?"))

```

**📫 Let’s Connect**
<p align="left"> 
  <a href="mailto:arooshahmad.ai@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a> 
  <a href="https://www.linkedin.com/in/arushahmd"><img src="https://img.shields.io/badge/LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> 
  <a href="https://github.com/arushahmd"><img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white"/></a> 
</p>
