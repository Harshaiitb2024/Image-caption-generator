🖼️ 2. Image Caption Generator (CNN + LSTM)
📄 Overview

A deep learning project that generates natural language captions for input images using a CNN + LSTM hybrid model.
The CNN extracts visual features from images, and the LSTM sequentially generates descriptive text.

🧩 Features

Feature extraction using InceptionV3 / VGG16 (TensorFlow/Keras).

Caption generation with LSTM decoder trained on Flickr8k dataset.

Integrated with NLTK for tokenization and sequence handling.

Tested on multiple real-world images.

⚙️ Technologies

Python, TensorFlow, Keras, NLTK, NumPy, Pandas, Matplotlib

🚀 Usage
git clone https://github.com/Harshaiitb2024/Image-caption-generator.git
cd Image-caption-generator
pip install -r requirements.txt
python train_model.py

📊 Results
Metric	Value
BLEU-1	0.58
BLEU-2	0.42
🧠 Model Architecture

CNN → Feature Embedding → LSTM Decoder → Word Prediction

🤝 Open Source Contribution

This repository is open-source under the MIT License.
Developers can fine-tune the captioning model, use pretrained weights, or contribute new decoder designs.
