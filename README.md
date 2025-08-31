This project explores the design and evaluation of a multilingual healthcare chatbot focused on diabetes management.
It combines Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG) pipelines and fine-tuning to deliver safe, empathetic, and context-aware responses.

Project Overview

LLM Backbone: BloomZ-3b and related Hugging Face models

Fine-Tuning: LoRA (PEFT) on healthcare datasets such as MedQuAD, MedDialog, MedicationQA

RAG Pipeline: Integrated WHO and ADA diabetes guidelines for grounded answers

Languages Supported: English, Spanish, French

Evaluation Metrics:

BLEU = 0.00

BERTScore (F1) ≈ 0.7873

Key Features: Empathy-driven prompting, multilingual support, and explainable healthcare recommendations

Repository Contents

NLP_Milestone3_part1.ipynb → Data preparation, model setup, initial experiments

NLP_Milestone3_part2.ipynb → RAG pipeline integration, evaluation, and results

(Optional) requirements.txt → Python dependencies for reproducibility
Quickstart
1. Clone Repository
git clone https://github.com/your-username/healthcare-chatbot-nlp.git
cd healthcare-chatbot-nlp

2. Install Dependencies
pip install -r requirements.txt


If requirements.txt is missing, install manually:

pip install transformers accelerate torch langchain faiss-cpu sentence-transformers scikit-learn

3. Open Jupyter Notebooks
jupyter notebook


Run in order:

NLP_Milestone3_part1.ipynb

NLP_Milestone3_part2.ipynb

Key Results

Demonstrated feasibility of a multilingual diabetes management assistant

Showed potential of RAG + fine-tuning for domain adaptation

Highlighted challenges in empathy, medical safety, and multilingual handling

⚠️ Disclaimer

This project is for research and educational purposes only.
It is not a certified medical product and should not be used for real patient care.
