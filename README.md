![download](https://github.com/user-attachments/assets/f908c397-8a89-4274-a0b3-b8d5f88b213b)1. Project Title
   # Text Summarization Tool using NLP and Transformers
2. Project Description
   This project provides a robust text summarization system that combines extractive and abstractive techniques.
It processes PDF documents, extracts and cleans the text, splits it into manageable chunks, and generates both extractive summaries using TF-IDF and abstractive summaries using transformer models (e.g., BART from Hugging Face). The tool also includes a Streamlit interface for interactive usage and visualization.
3. Features
   - 📄PDF Text Extraction
- 🧹 Text Preprocessing and Cleaning
- ✂️ Text Chunking
- 📝 Extractive Summarization (TF-IDF based)
- 🤖 Abstractive Summarization (BART Transformer)
- ☁️ WordCloud Visualization
- 📊 Token Count Chart
- 🌐 Streamlit Web Interface
4. Tech Stack
  - Python
- NLTK
- scikit-learn
- Hugging Face Transformers (BART)
- PDFMiner
- Streamlit
- Matplotlib
- WordCloud
5. Installation
  # Clone the repository
git clone https://github.com/your-username/text-summarization-tool.git
cd text-summarization-tool

# Install dependencies
pip install -r requirements.txt

# For Streamlit interface
pip install streamlit
6. Usage
CLI/Notebook
python textsummarizationproject1.py
Streamlit UI
streamlit run textsummarizationproject1.py
7. Example Output
![download](https://github.com/user-attachments/assets/c5923253-515d-4f0b-9dae-e51625ca2197)
![download](https://github.com/user-attachments/assets/9bfb8530-d9cb-4a8a-b745-7c328ab36b40)
![download](https://github.com/user-attachments/assets/85040a95-09fb-4416-baff-99a595e13289)
![download](https://github.com/user-attachments/assets/70a611d1-e875-40e0-98e1-86c603b3c69d)
![Screenshot (233)](https://github.com/user-attachments/assets/fd51fb29-799b-49a8-ad60-7b968a88aaf9)
![Screenshot (234)](https://github.com/user-attachments/assets/98ba314e-693a-41f4-a7bd-0448d5604c22)
![Screenshot (235)](https://github.com/user-attachments/assets/c76167d1-da80-4de8-aa14-393a2955b686)
![Screenshot (236)](https://github.com/user-attachments/assets/5a70e835-ac2a-4ceb-bffb-0d73d5452076)
8. Project Structure
├── textsummarizationproject1.py
├── requirements.txt
├── README.md
└── sample.pdf
9. To-Do
- [ ] Add support for DOCX files
- [ ] Include more summarization models (e.g., T5, Pegasus)
- [ ] Add download button for summary in Streamlit
10. Author
👤 Shalini K R  
📧 shaalinikumar512@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/k-r-shalini-1709ab24a) | [GitHub](https://github.com/shalz510)
