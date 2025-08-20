Hello,

I am experimenting with RAG system Web app that involve with structured dataset (Question and Answer). As most RAG system is based unstructured data (pdf/text file etc), there a lack of tutorial/example code 
for structured dataset (or there is, it just that I dont know haha). Nothing too complicated. The code is in python in Google colab. The LLM inference locally (do change to T4 GPU in colab for faster inference)

The system task includes:
1. Pull dataset from huggingface
1. Encoding and Vector searh (FAISS)
2. LLM inference using transformers
3. Web App using Gradio

This is my first interation of the system. Works okay (just need more tweaks). Will update for better implementation. Just share this in case anyone interested
