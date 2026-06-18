# HealthAIAgent
Overview

Health Insurance Assistance AI Agent is an Agentic AI solution that helps users find suitable health insurance plans based on their age, family size, medical history, location, and budget. The system simplifies policy comparison and provides personalized recommendations with clear explanations.

Features
Personalized health insurance recommendations
User profile and health risk assessment
Policy comparison and analysis
Premium estimation
Easy-to-understand policy explanations
Conversational AI support
Role of Agentic AI

The solution uses multiple AI agents to:

Collect user information
Analyze insurance requirements
Evaluate available plans
Compare benefits and costs
Generate personalized recommendations
Tech Stack
Python
LangChain / LangGraph
IBM Granite / OpenAI Models
FastAPI / Flask
ChromaDB / FAISS
Installation
git clone https://github.com/your-username/health-insurance-ai-agent.git
cd health-insurance-ai-agent
pip install -r requirements.txt
python app.py
Example Input
{
  "age": 35,
  "city": "Mumbai",
  "family_members": 4,
  "medical_conditions": ["Hypertension"],
  "budget": 25000
}
Output
Recommended insurance plans
Premium estimates
Coverage comparison
Explanation of recommendations
Novelty
Multi-agent AI architecture
Personalized decision-making
Explainable recommendations
Simplified insurance understanding
