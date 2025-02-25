# Flu & Respiratory Illness Chatbot  

## 📖 Project Overview  
The **Flu & Respiratory Illness Chatbot** is an AI-powered assistant designed to help users differentiate between **flu, colds, RSV, and allergies** by providing **trusted medical guidance** based on information from **PubMed, the CDC, and  web searches** using TavilyTool. This chatbot leverages **Retrieval-Augmented Generation (RAG) with agentic decision-making** to ensure **accurate and up-to-date** responses.  

## 📑 Project Report  
For a detailed breakdown of the problem, solution, data sources, and technical stack, refer to the full project report:  
[📄 Read the Report](https://docs.google.com/document/d/1YM3vneXg1P_WfJo2YHwCqwWrTlwXV9oKg3834zbwYOA/edit?usp=sharing)  

## 🎥 Solution Walkthrough  
Watch a video presentation of the chatbot:  
[▶️ Watch on Loom](https://www.loom.com/share/5bab2092b7f64a69a81b6d0daff74214?sid=9da01a96-1606-4e1a-abd5-6ddd157b603a)  

# 📂 Notebooks Overview  
This project includes two key notebooks:  

### 🔹 **Fine-Tuned Embeddings & RAGAS Evaluation**  
- **Notebook Name**: [`Fine_tune_embeddings_and_ragas.ipynb`](Fine_tune_embeddings_and_ragas.ipynb)  
- **Purpose**: Fine-tunes the **Snowflake Arctic-Embed-L** embeddings to improve retrieval quality.  
- **Evaluation**: Uses **RAGAS** to compare the **base model vs. fine-tuned embeddings**, assessing improvements in retrieval accuracy.  

### 🔹 **Chatbot Creation & Testing**  
- **Notebook Name**: [`Flue_chatbot.ipynb`](Flue_chatbot.ipynb) 
- **Purpose**: Implements the chatbot, integrating **RAG with Qdrant and TavilyTool** for external search when needed.  
- **Testing**: Runs sample user queries to evaluate response quality and system performance.  

These notebooks provide insights into the **model fine-tuning process, retrieval effectiveness, and overall chatbot performance**.  

