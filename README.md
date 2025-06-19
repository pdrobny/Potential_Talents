# Potential_Talents
Predicting how fit a candidate is based on available information

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
