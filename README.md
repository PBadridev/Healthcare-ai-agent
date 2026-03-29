#  AI Healthcare Insurance Claim Approval System

##  Overview
This project is an intelligent healthcare insurance analysis system designed to evaluate whether a patient’s medical condition is covered under various government and private insurance policies.

It combines **rule-based decision logic** with **AI-powered reasoning** to provide clear, explainable outcomes such as:
- Approved ✅
- Under Review ⚠️
- Not Covered ❌

---

##  Problem Statement
Understanding insurance eligibility is often complex and unclear for patients.  
This system simplifies that process by:
- Mapping diseases to policy rules
- Automating eligibility checks
- Providing AI-generated explanations

---

##  Key Features

###  Smart Analysis Modes
- **Manual Mode**: User selects disease and specific policy
- **Auto Mode**: System evaluates across all policies

###  Policy Evaluation
- Covers both **Government** and **Private Insurance**
- Includes:
  - Coverage amount 
  - Eligibility criteria 
  - Rules & conditions 

###  AI Reasoning
- Uses **Groq API (LLaMA 3.1 model)**  
- Generates human-readable explanations for decisions

###  Professional UI
- Built with **Streamlit**
- Clean healthcare-themed interface
- Dynamic decision display

---

##  Tech Stack

- **Frontend/UI**: Streamlit  
- **Backend Logic**: Python  
- **AI Integration**: Groq API (LLaMA 3.1)  
- **Data Storage**: JSON (Policies & Diseases)  

---

##  Project Structure

 Healthcare-ai-agent/
 
│── app.py # Main Streamlit application

│── ai_reason.py # AI reasoning logic (Groq API)

│── data/

│ ├── diseases.json

│ └── policies.json

│── requirements.txt

│── README.md

