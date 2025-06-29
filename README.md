# **Image Captioning Using CNN and LSTM**

Caption generation is a challenging artificial intelligence problem where a textual description must be generated for a given photograph. It requires:
- **Computer Vision** techniques to understand the content of the image.
- A **Language Model** from the field of Natural Language Processing (NLP) to turn the understanding into words in the correct order.

Recently, **deep learning methods** have achieved state-of-the-art results in caption generation problems. The most impressive part of these methods is that a single end-to-end model can predict a caption for a given photo without requiring sophisticated data preparation or multiple specifically designed models.

---

## **Dataset**
- **Flickr 8k**: [Download from Kaggle](https://www.kaggle.com/adityajn105/flickr8k)  
- **Description File**: [Flickr8k Text](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)

---

## **Model Architecture**

### **Model Diagram**
<div align="center">
  <img src="https://user-images.githubusercontent.com/42632417/111032980-f8119600-8434-11eb-8dca-913f52e33d20.jpg" alt="Model Diagram" width="600">
</div>

---

### **Training Diagram**
<div align="center">
  <img src="https://user-images.githubusercontent.com/42632417/111032996-0c559300-8435-11eb-879e-75cca8d961c7.png" alt="Training Process" width="600">
</div>

---

## **Final Results**

### **Successful Examples**
<div align="center">
  <img src="https://user-images.githubusercontent.com/42632417/111033154-d5cc4800-8435-11eb-9654-6e6f2ae441b3.png" alt="Successful Example 1" width="400">
  <img src="https://user-images.githubusercontent.com/42632417/111033194-fbf1e800-8435-11eb-846a-61b5f2d4e1ec.png" alt="Successful Example 2" width="400">
</div>

---

## **Failure Examples**
<div align="center">
  <img src="https://user-images.githubusercontent.com/42632417/111033307-92bea480-8436-11eb-9f24-5878893c2150.png" alt="Failure Example 1" width="400">
  <img src="https://user-images.githubusercontent.com/42632417/111033310-9ce0a300-8436-11eb-9d09-d1753b577618.png" alt="Failure Example 2" width="400">
</div>

---

# **Image-Captioning-Using-CNN-and-LSTM**
This repository implements a deep learning approach combining CNN and LSTM for generating image captions. The method leverages both visual and textual data to provide accurate, context-aware captions for images.
