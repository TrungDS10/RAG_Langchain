# RAG_Langchain

Implementing RAG with Chroma Langchain, following the pipeline below:

![image](https://github.com/TrungDS10/RAG_Langchain/assets/72665487/991d2163-fd27-4775-824b-e4caafca702d)
<img src="https://github.com/TrungDS10/RAG_Langchain/assets/72665487/991d2163-fd27-4775-824b-e4caafca702d" width="800" height="200">

<img src="https://github.com/TrungDS10/RAG_Langchain/assets/72665487/3d5d8367-c18c-4a6d-b089-2e015dfec5f2" width="800" height="400">


To start the API, navigate to the root directory of the source code in the terminal (in this case, it will be the rag_langchain/ directory), using the following command (after installing the necessary libraries as well as vector database):

uvicorn src.app:app --host "0.0.0.0" --port 5000 --reload

Note: if the error is due to a port already in use on your computer, you can change to another port
