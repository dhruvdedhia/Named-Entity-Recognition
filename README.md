🏷️ Named Entity Recognition (NER)

A Natural Language Processing project implementing Named Entity Recognition to identify and classify entities (people, organisations, locations, dates) in unstructured text using Python and NLP libraries.

📊 Project Overview

Named Entity Recognition (NER) is a core NLP task with applications across finance, healthcare, legal, and media industries. This project builds and evaluates NER models to extract structured information from raw text - turning unstructured content into usable, categorised data.

Entity types identified:

👤 Person names

🏢 Organisations

📍 Locations / GPE

📅 Dates and times

💰 Monetary values


🛠️ Tech Stack

Tool Usage Python Core development spaCyNER model implementation and evaluation HuggingFace Transformers Transformer-based NER comparison pandas Data processing and results analysis Jupyter Notebook Experimentation and reporting

📁 Project Structure

├── data/              # Text datasets for training/testing

├── models/            # NER model training scripts

├── notebooks/         # Analysis and evaluation notebooks

├── outputs/           # Extracted entities and results

└── README.md

🚀 How to Run

bash# Clone the repo
git clone https://github.com/dhruvdedhia/Named-Entity-Recognition.git
cd Named-Entity-Recognition

# Install dependencies
pip install -r requirements.txt

# Run the NER pipeline
python models/ner_pipeline.py

💡 Business Relevance

NER is foundational for information extraction in legal, finance, and media analytics
Demonstrates ability to work with unstructured text and convert it into structured, queryable data
Transferable to document processing, contract analysis, and news monitoring use cases


👤 Author

Dhruv Dedhia — Data Analyst | MSc Data Science, University of Surrey
