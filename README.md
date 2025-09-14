# Yardstick Internship Assignment

This repository contains my submission for the internship assignment.  

## Contents
- **assignment.ipynb** → Google Colab notebook with both tasks.  
- **Task 1: Conversation Management & Summarization**  
   - Maintains running conversation history  
   - Supports truncation by turns and characters  
   - Performs summarization after every k-th run  

- **Task 2: JSON Schema Classification & Extraction**  
   - Uses Groq API with OpenAI-compatible SDK  
   - Extracts structured details (name, email, phone, location, age)  
   - Validates output against JSON schema  

## How to Run
1. Open the notebook in Google Colab.  
2. Install required packages (`pip install openai requests`).  
3. Add your Groq API key inside the notebook.  
4. Run cells for Task 1 and Task 2.  

## Notes
- API key should be kept private (I included mine only for testing in the notebook).  
