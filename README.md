# Syrus Hackathon

## Topic: FinTech in Startups
# AI Loan Approval System

Solution implemented using [Uptiq AI](uptiq.ai).

![CodeZilla_C3_Working](https://github.com/user-attachments/assets/1479385d-e1e9-4577-9a28-08f9509b43c0)

## Project Overview
The **AI Loan Approval & Risk Assessment System** is built to revolutionize the loan approval process by integrating AI-driven analytics. The system evaluates loan eligibility by estimating credit scores and assessing financial risk through **Retrieval-Augmented Generation (RAG)**, ensuring precise and data-backed decisions.

## Team Information
- **Team Name**: CodeZilla  
- **Institute**: Vivekanand Education Society’s Institute of Technology  

## System Workflow
1. **AI-Driven Credit Scoring**: Specialized AI agents compute credit scores using a **vector RAG-based approach**.
2. **Probability Estimation**: The AI system analyzes financial parameters to predict loan approval chances.
3. **Seamless API Integration**: Real-time assessment leveraging **OpenAI 4o** and **Gemini 1.5 Flash**.

## Core Features
- **User-Friendly Interface**: Simplified input fields for users to enter financial details seamlessly.
- **AI-Powered Credit Score Calculation**: Leverages **RAG models** to determine creditworthiness.
- **Loan Approval Prediction**: Analyzes multiple factors to estimate approval probability.
- **Intuitive Visualization**: Displays results in a structured and easy-to-understand manner.

## Key Innovation
The system’s **Credit Score RAG container** democratizes financial assessments, enabling individuals **without financial expertise** to understand their credit standing. This fosters financial inclusion and accessibility.

## Development Challenges
While building the system, we tackled several hurdles:
1. **Optimization of AI Workflow**: Our initial approach using Chain-of-Thought (COT) reasoning led to inconsistencies, requiring workflow refinements.
2. **API Endpoint Identification**: Finding appropriate endpoints for seamless UI functionality necessitated redesign efforts.

## Future Enhancements
- **Advanced AI Decision-Making**: Implement **ML-driven risk analysis and fraud detection**.
- **Expanded API Support**: Increase integrations with multiple **financial service providers**.
- **Self-Learning Mechanism**: Enable AI to adapt and refine credit scoring models over time.
- **Explainability in AI Decisions**: Incorporate **transparent insights** into approval rationales.
- **Scalability for Global Markets**: Adjust AI models to comply with **various financial regulations**.
- **Enhanced User Experience**: Further improve the **custom widget’s interactivity**.

## Challenges Faced

### 1. Editing Issues in JS Code  
We encountered persistent **network errors** when attempting to modify JavaScript code within the project files. This made it difficult to iterate on our initial approach, leading us to **scrap the chain-of-thought idea** for the project.  
![Alt Text](test.jpg)

### 2. API Limitations for Uptiq.ai  
Our original **UI design had to be abandoned** due to the unavailability of a public **API for Uptiq.ai**. Without a reliable API, integrating our frontend with the agent we were building became unfeasible, forcing us to reconsider our implementation strategy.


