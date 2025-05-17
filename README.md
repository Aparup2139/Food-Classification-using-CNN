<H1>🍽️ Food Classification App with EfficientNetB0 & Food-101</H1>
A deep learning-based Food Classification App that uses a pre-trained EfficientNetB0 model to classify food images into one of 101 food categories. Built using TensorFlow/Keras and trained on the popular Food-101 dataset.

<H1>🧠 Overview</H1>
📊 Model: Transfer learning using EfficientNetB0

📦 Dataset: Food-101

📷 Input: Food image

🏷️ Output: Predicted food category (e.g., pizza, sushi, ice cream)

🖥️ App: Simple UI for uploading and classifying food images

<H1>🗂️ Dataset - Food-101</H1>
101 food classes (e.g., pad thai, fries, pancakes)

101,000 images (750 training + 250 test per class)

Diverse and real-world food photos

Downloaded from: https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/

<H1>⚙️ Model Architecture</H1>
🧠 Base Model: EfficientNetB0 (pre-trained on ImageNet)

🔄 Transfer Learning: Fine-tuned on Food-101

<H1>🔗 Top Layers:</H1>

Global Average Pooling

Dropout

Dense layer with 101 units (softmax)

📦 Optimizer: Adam

📉 Loss Function: Categorical Crossentropy

