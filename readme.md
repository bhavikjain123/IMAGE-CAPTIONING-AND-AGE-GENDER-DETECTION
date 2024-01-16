### Project Overview:
Developed a comprehensive computer vision project integrating age and gender detection with image captioning, showcasing a unique blend of **deep learning** and innovative methodologies.

### Technologies Used:
1. **Deep Learning Models:**
    - Utilized **Convolutional Neural Networks (CNN)** - CNN-5, VGG16, VGG-19 for feature extraction from images.
    - Integrated **Recurrent Neural Networks (RNN)** with **Long Short-Term Memory (LSTM)** for language processing.

2. **Dataset:**
    - Employed the **Flickr8-cite-21 dataset** with 8,092 JPEG photos, each paired with five unique captions.
    - Developed a specialized dataset with diverse facial images annotated with age and gender information.

3. **Image Processing:**
    - Implemented face and image detection for accurate identification of faces within input images.
    - Applied three different CNNs to extract characteristics, resulting in a 4,096-dimensional vector.

4. **Caption Generation:**
    - Leveraged CNN models for image processing and LSTM RNN layers for text representation.
    - Employed a forget gate, input gate, and output gate for sequential caption generation.

5. **Evaluation Metrics:**
    - Utilized **BLEU scores** for evaluating the model's ability to extract image features with annotations.
    - Evaluated against state-of-the-art transfer learning models like VGG-16 and VGG-19.

6. **Learning Rate Analysis:**
    - Explored the impact of different learning rates (0.01, 0.001, 0.0001) on the CNN-5 model.
    - Determined that a learning rate of 0.01 yielded the highest BLEU score
