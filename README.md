Accelerating Cleantech Advancements through NLP-Powered Text Mining and Knowledge Extraction

Overview

This project uses Natural Language Processing (NLP) techniques to analyze cleantech datasets, providing insights into trends, gaps, and innovations. The workflow progresses through exploratory analysis, embedding models, and advanced question-answering systems to drive actionable insights in cleantech research and innovation.

Goals

Enhanced Text Analytics:
Apply topic modeling and embeddings to analyze cleantech datasets.
Identify overlaps and gaps in the innovation landscape.
Advanced Knowledge Representation:
Train embeddings and question-answering systems specific to cleantech.
Driving Cleantech Innovation:
Highlight opportunities by comparing market trends and patented technologies.
Project Pipeline

Stage 1: Exploratory Text Analysis
Objectives:
Clean and preprocess datasets for analysis.
Conduct exploratory analysis to uncover trends and gaps.
Key Outputs:
Preprocessed datasets.
Visualizations (e.g., word clouds, topic clusters).
Notebooks:

Preprocessing: Stage_1_patent_preprocessing.ipynb, Stage1_media_preprocessing.ipynb
EDA: Stage_1_patent_EDA.ipynb, Stage_1_media_EDA.ipynb
Stage 2: Embedding Models
Objectives:
Train word and sentence embeddings tailored to cleantech datasets.
Compare thematic overlaps and insights between media and patent data.
Key Outputs:
Optimized embedding models.
Visualizations (e.g., t-SNE, PCA) and analyses.
Notebooks:

Media Training: Stage_2_media_model_training and visualisations.ipynb
Patent Training: Stage_2_patent_embedding_model_training+eval.ipynb
Stage 3: Advanced Question-Answering and Information Retrieval
Objectives:
Summarize datasets and generate question-answer (QA) pairs.
Fine-tune transformer models for cleantech-specific QA systems.
Evaluate model performance and inference capabilities.
Key Steps

Summary Generation: Summarize abstracts from media and patent datasets using pre-trained language models.
Notebooks:
Media Summaries: Stage_3.1_media_Summary-Gen.ipynb
Patent Summaries: Stage_3.1_Patent_Summary_Gen.ipynb
QA Pair Generation: Create QA pairs for fine-tuning transformer models.
Notebooks:
Media QA Pairs: Stage_3.2_media_QA_pairs.ipynb
Patent QA Pairs: Stage_3.2_Patent_QA_pairs.ipynb
Fine-Tuning Preparation: Prepare datasets and transformer models for fine-tuning QA systems.
Notebooks:
Media Fine-Tuning: Stage_3.3_media_finetuning_prep.ipynb
Patent Fine-Tuning: Stage3.3_Patent_finetuning_prep.ipynb
Combined Dataset and Fine-Tuning: Combine QA pairs, fine-tune models, and save for deployment.
Notebook:
Combined Fine-Tuning: Stage_3.4_combined_datasets+fine_tuning+Inferencing.ipynb
Model Evaluation: Evaluate fine-tuned models using baseline and advanced evaluation metrics.
Notebook:
Model Evaluation: Stage_3.5_Model_Evaluation_LLM_JUDGE.ipynb
