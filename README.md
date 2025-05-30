# Diabetic Retinopathy Detection - RETINA-VISTA

This project leverages deep learning and large language models (LLMs) to detect Diabetic Retinopathy (DR) from retinal images and generate diagnostic reports.

## 🔍 Features
- Automatic detection of DR stages using CNNs (e.g., ResNet-50)
- Image preprocessing using OpenCV (green channel extraction, denoising)
- Natural Language Explanation using LLM (Hugging Face Transformers)
- User-friendly interface for image upload and results
- Supports binary and multi-class DR classification

## 🛠️ Tools & Technologies Used
- Python
- PyTorch
- OpenCV
- Hugging Face Transformers (LLM)
- Streamlit / Flask (for deployment)
- Kaggle EyePACS dataset

## 📁 Project Structure
- `models/` - Pretrained and fine-tuned models
- `data/` - Sample images and preprocessed datasets
- `app.py` - Main application file
- `utils.py` - Helper functions for preprocessing and model inference

## 🚀 How to Run
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the app: `python app.py`

## 📊 Results
Achieved [insert accuracy]% accuracy on the test set using ResNet-50 with preprocessing.

## 📜 License
[Insert license type here]
