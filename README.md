# image-captiioning
# 🖼️ Image Captioning with Deep Learning

This project implements an **image captioning** system using deep learning techniques. The system combines **ResNet50** as a feature extractor with a **sequence model** (e.g., LSTM) to generate textual descriptions of images. The dataset used is **Flickr8k**.

## 📁 Project Structure

- `image_captioning.ipynb`: Main Jupyter Notebook with all the steps — data loading, preprocessing, training, and evaluation.
- 📸 Uses **ResNet50** (pre-trained on ImageNet) to extract image features.
- 📝 A language model (e.g., LSTM) decodes visual features into natural language captions.
- 📊 Evaluation with BLEU scores and sample visualizations.

## 📦 Requirements

This project uses Python 3 and the following libraries:

```bash
tensorflow
keras
numpy
pandas
matplotlib
Pillow
tqdm
nltk
