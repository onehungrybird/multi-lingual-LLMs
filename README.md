# multi-lingual-LLMs

# MBART English-to-French Translation

This project fine-tunes **MBART (Multilingual BART)** on the OPUS Books dataset for **English-to-French translation**.

## 🚀 Setup
- Install dependencies: `pip install transformers datasets torch`
- Train the model using the provided script.
- Use the model to translate English text to French.

## 📂 Project Structure
- `train.py` → Fine-tunes MBART on OPUS Books  
- `translate.py` → Translates English text to French  
- `README.md` → Project documentation  

## 📌 Notes
- Uses `facebook/mbart-large-50-many-to-many-mmt`  
- Handles **device compatibility (CPU/GPU)** automatically  
- Outputs **fully translated French text**  

Happy translating! 🚀  
