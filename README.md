# 🧠📸 Multilingual Image Captioning and Translation
  This project focuses on generating descriptive captions for images using four different state-of-the-art image captioning algorithms and translating the outputs into Arabic. It combines both Natural Language      Processing (NLP) and Computer Vision (CV) techniques to automate visual scene understanding and multilingual interpretation.

## 🚀 Key Features

- ✅ **Implemented Four Image Captioning Models**:
  - **LSTM-based Captioning**
  - **BiLSTM-based Captioning**
  - **ViT-GPT2** (Vision Transformer with GPT-2)
  - **BLIP** (Bootstrapping Language-Image)

- 🖼️ **Dataset**: Utilized the **Flickr8k** dataset for training and evaluation.

- 🌐 **Translation**: Built a custom-trained **Arabic translation model** to translate the English-generated captions into Arabic automatically.

- 💬 **User Interface**: Developed a real-time, interactive **Gradio web app** where users can upload images and receive captions in **English and Arabic**.

- 📊 **Evaluation**: Captions from each model are evaluated for **accuracy and relevance**, showcasing differences in performance and expressiveness between architectures.

## 🧪 Technologies Used

- Python
- TensorFlow / PyTorch
- Hugging Face Transformers
- Vision Transformer (ViT)
- GPT-2
- BLIP by Salesforce
- Gradio
- Flickr8k Dataset
- NLTK / spaCy (for preprocessing)
- Custom Arabic NLP pipeline

## 🌍 Outcome

This project demonstrates how visual understanding and sequential language models can be integrated to generate meaningful and multilingual descriptions of images. It highlights:
- The **strengths and limitations** of each captioning model.
- The importance of **multilingual support** in AI applications.
- The potential of **cross-domain integration** in CV and NLP.

## 🛠️ Setup Instructions
  1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Image-Captioning-Generator.git
   cd Image-Captioning-Generator
  ```
  2. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
  3. Run the Gradio interface:
   ```bash
   python app/gradio_ui.py
   ```
     

