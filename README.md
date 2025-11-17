## 🏛️ VerdictAI: Supreme Court Judgment Analysis and Briefing System
### This project implements a comprehensive Legal-Tech pipeline to analyze metadata and full-text judgments from the Indian Supreme Court. It combines traditional NLP techniques (NLTK, SVM) with modern Generative AI (LLM concepts) to automate the creation of structured case briefs and extract critical legal insights.

💡 Project Objectives
The primary goal is to transform long, unstructured legal documents into actionable, summarized data points.

Automatic Summarization (Gen AI): Generate concise, meaningful summaries of long judgments using Transformer-based models (conceptualized with BART/T5).

Key Information Extraction (NLP/Regex): Extract structured data like parties (petitioner/respondent), advocates, case number, and judgment date from the unstructured text and metadata.

Legal Section Recognition (NER): Identify and extract relevant statutory mentions, including IPC, CrPC, and Constitution articles.

Judgment Classification (ML/SVM): Classify cases into categories (e.g., Criminal, Civil, Constitutional) based on textual content using a trained classifier (SVM + TF-IDF).

Outcome Detection (Gen AI/LLM): Detect the final disposition/stance of a judgment: Allowed, Dismissed, or Partly Allowed.

Chronological Timeline (LLM Prompting): Extract and order key events and dates mentioned in the judgment text to build a case timeline.

User Interface (Streamlit): Deploy a searchable, user-friendly application to instantly generate structured case briefs upon uploading a judgment file.
