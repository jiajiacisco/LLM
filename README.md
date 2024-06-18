# LLM RAG Model

**Background:** <br/> Utilise open-source frameworks to build a LLM that uses RAG for enterprise document retrieval and summarization 
<br/>

**Product Description:** <br/>
Chatbot that you can interact with and ask questions about the PDF documents you uploaded into the file directory or through the drag-down UI <br/>

**Product Overview**<br/>
1. **Starting the app**:<space> Upload pdf doucements into the local directory. Run `streamlit run app.py` to start the app  <br/>
![App Interface Diagram](https://github.com/jiajiacisco/LLM/blob/main/images/a1.png)
2. **Loading the documents>** Wait some time until you see the done on the side bar as the PDF documents need to be embedded and indexed into the vector database <br/>
![App Interface Diagram](https://github.com/jiajiacisco/LLM/blob/main/images/a2.png)
3. **Begin Interaction** Since documents loaded are Cisco SD-WAN related, the questions will be based on SD-WAN <br/>
![App Interface Diagram](https://github.com/jiajiacisco/LLM/blob/main/images/a3.png)

# App Design <br />
![Overall Block Diagram]

**Technolgies Used:** 
Streamlit, Python, FAISS, Huggingface and LangChain
