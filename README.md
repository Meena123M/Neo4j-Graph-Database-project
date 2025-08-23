# 📊 Neo4j Graph Database Project  

## 📝 Description  
This project demonstrates how to work with **Neo4j Graph Database** and **LangChain experimental modules** for building and exploring relationships between nodes.  

## ⚙️ Workflow  
1. **Raw Text to Documents:**  
   - Converted raw text into documents using **LangChain Core Document**.  

2. **Document to Graph Format:**  
   - Utilized **LLMGraphTransformer** (from LangChain Experimental) with **Groq LLM** to transform documents into graph structures.  

3. **Graph Document Creation:**  
   - Generated **Graph Documents** containing nodes and relationships.  

4. **Node & Relationship Extraction:**  
   - Extracted all nodes and their relationships to build a structured graph.  

5. **Integration:**  
   - Used **LangChain + Groq + Neo4j** to access, query, and visualize the graph.  

## 🛠️ Tech Stack  
- **Database:** Neo4j  
- **Frameworks:** LangChain (Core, Experimental)  
- **LLM:** Groq  
- **Graph Tools:** LLMGraphTransformer  

## 🎯 Outcome  
- Built a pipeline from **raw text → documents → graph format → extracted nodes/relationships**.  
- Showcased how LLMs can automate **knowledge graph construction** from unstructured data.  
