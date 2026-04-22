# AI-Powered Demand Forecasting & Knowledge Assistant
## 📌 Project Overview
This project is an Agentic AI system designed to automate demand prediction for electronic products and provide intelligent, data-driven business insights
. It bridges the gap between traditional Machine Learning (ML) and modern Retrieval-Augmented Generation (RAG) by using a specialized "Decision Agent" to route user queries to the most appropriate processing engine
.
## 🚨 Problem Statement
Businesses often struggle to manually analyze large datasets and accurately predict product demand
. This system automates those processes, enabling users to forecast demand based on features like price, rating, and location, while also providing high-level strategic recommendations through a conversational chatbot
.

--------------------------------------------------------------------------------
## 🚀 Key Features
Predictive Modeling: Uses a Random Forest Regressor to forecast demand scores with high precision
.
Intelligent RAG System: Employs FAISS and SentenceTransformers for fast, similarity-based retrieval of relevant business data
.
## Agentic Architecture:
Decision Agent: Routes queries based on intent (Prediction vs. Analysis)
.
Prediction Agent: Uses an LLM to extract JSON features from natural language to feed the ML model
.
RAG Agent: Combines retrieved data context with Gemini AI to generate human-like insights
.
Strategic Insights: Capable of "PRO LEVEL" thinking, answering complex questions about business strategy, pricing, and stock optimization
.

--------------------------------------------------------------------------------
## 🛠️ Tech Stack
Core: Python, Pandas, NumPy
Machine Learning: Scikit-learn (Random Forest, StandardScaler)
Embeddings: SentenceTransformers (all-MiniLM-L6-v2)
Vector Database: FAISS
LLM: Google Gemini (gemini-flash-latest)

--------------------------------------------------------------------------------
## 📊 Performance
The predictive model was trained on a comprehensive electronic device dataset, achieving a highly accurate result:
Mean Absolute Error (MAE): 0.0199

--------------------------------------------------------------------------------
## 🏗️ Project Structure
Data Preprocessing: Cleaning missing values (Mean/Mode), removing duplicates, and applying One-hot encoding
.
Feature Scaling: Standardizing data to ensure model stability
.
Vectorization: Converting dataset text into 384-dimensional embeddings stored in a FAISS index
.
Inference Pipeline: A unified chatbot interface that processes natural language into actionable intelligence
.

--------------------------------------------------------------------------------
## 💬 Example Queries
The system is designed to handle three levels of complexity
:
Level
Example Query
Data Insights (RAG)
"What are the low-demand products?"
Predictions (ML)
"Predict demand for a Samsung TV in Mumbai."
Intelligent (Agent)
"Should I increase price or discount to improve demand?"

--------------------------------------------------------------------------------
## ⚙️ Installation & Usage
Install Dependencies:
Set Up API Keys: Ensure you have a GOOGLE_API_KEY for Gemini and an HF_TOKEN for Hugging Face embeddings
.
Run the Chatbot: Execute the chatbot() function to begin interacting with your data
.

--------------------------------------------------------------------------------
## 📜 Conclusion
This assistant demonstrates the power of Agentic AI in a business context, transforming raw data into a conversational partner that provides both hard numerical forecasts and high-level strategic recommendations
