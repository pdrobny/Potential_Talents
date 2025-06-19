# Potential_Talents

## Project Overview
Develop an automated system to predict how fit a candidate is for a given role based on their available information.

## Goals
- Rank candidates based on a fitness score.
- Re-rank candidates when a candidate is starred.
   
## Project Structure
```potential_talents
├── data
│  ├── Extended Dataset for Potential Talents.xlsx
│  ├── talents.csv
├── notebooks
│  ├── EDA_Embeddings.ipynb  #Data prep, EDA, Embedding models 
│  ├── Learn_to_rank.ipynb  # Pairwise ranking using Ranknet 
│  ├── starred_candidates.ipynb  # re-ranking candidates based on previously evaluated "starred candidates"
│  ├── HF_qwen.ipynb # Using LLMs to find top 5 candidates based on search term with Hugging Face and Qwen
│  ├── HF_Llama.ipynb # Using LLMs to find top 5 candidates based on search term with Hugging Face and Llama
│  ├── HF_gemma.ipynb # Using LLMs to find top 5 candidates based on search term with Hugging Face and Gemma
│  ├── HF_gemma_instructiontuning.ipynb # improving model performance with prompt instruction tuning
│  ├── HF_gemma_finetuning.ipynb # improving model performance with finetuning
│  ├── API_groq.ipynb # Using LLMs to find top 5 candidates based on search term with Groq API
├── README.md
```
##  Installation and Setup
Editor Used:  Google Colab
Python Version:  3.11
Python Packages:  pandas, numpy, matplotlib, seaborn, gdown, warnings, logging, pycaret, random, hyperopt, sklearn, duckdb, optuna, UMAP, T-SNE

## Data Description
The data comes from the clients sourcing efforts. Any field that could directly reveal personal details was removed and each candidate was given a unique identifier. 

Attributes:

- id: unique identifier for candidate (numeric)

- title: job title for candidate (text)

- location: geographical location for candidate (text)

- screening_score: pre-determined score 0-100 (numeric)

## Methods  
Data Collection and Preparation:  

Expoloratory Data Analysis: Visualizations for exploratory data analysis intially performed using seaborn and matplotlib in python.  Tableau was later used to produce visualization from the source data.

Modeling: 
-  Embedding Models: 
-  LLM(local model)Prompt Engineering :
-  LLMs (API) Prompt Engineering:  
## Conclusions

