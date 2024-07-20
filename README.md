# Facial Recognition and Emotion Detection

![Demo](https://github.com/user-attachments/assets/10d0a67e-9088-430a-bd2f-4576c82d96e7)

## Overview

Humans are used to non-verbal communication. The emotions expressed increase the clarity of any thoughts and ideas. It becomes quite interesting when a computer can capture this complex feature of humans, i.e., emotions. This project involves building a model that can detect emotions from an image.

## Emotion Detection

### Data Gathering and Augmentation

The dataset used is **"fer2013"**. It can be downloaded from the following link: [fer2013 Dataset](https://github.com/npinto/fer2013). Image augmentation was performed on this data to enhance the dataset.

### Model Building

The model architecture consists of:

- **CNN Layer**
- **Max Pooling**
- **Flatten**
- **Dropout Layers**

### Training

The model was trained using various configurations of the above layers and by adjusting hyperparameters. The best model achieved a **60.1% validation accuracy**.

### Testing

The model was tested with sample images. Results can be seen below:

![Happy](https://github.com/user-attachments/assets/794a5496-8a10-436f-94ac-fc01a489dc96)
![Neutral](https://github.com/user-attachments/assets/93b5bac8-bd70-4883-abe4-f147f5430252)
![Surprise](https://github.com/user-attachments/assets/d60cf560-87af-4ba5-a08c-e8fc78639f40)

## Emotion Detection Model

**The model is capable of detecting the following 7 types of emotions:**  
Angry, Sad, Neutral, Disgust, Surprise, Fear, and Happy

## Usage

### For Face Detection and Emotion Detection Code

Refer to the notebook [Emotion_Detection.ipynb](Emotion_Detection.ipynb).  
The trained weights of the emotion detection model are available in the `/Models` directory.

### Train your Emotion Detection Model

To train your own emotion detection model, refer to the notebook [facial_emotion_recognition.ipynb](facial_emotion_recognition.ipynb).

### For Emotion Detection using Webcam

**Steps to follow:**

1. Clone the repository:
    ```sh
    git clone <repo_url>
    ```
2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
3. Run the emotion detection script:
    ```sh
    python Emotion_Detection.py
    ```
---
[(https://github.com/Azayyadav/Face_And_Emotion_Detection-master/tree/main)]
# Thank You!
Thank you for taking the time to explore this project. Your support and interest are greatly appreciated!
---
Feel free to contribute, raise issues, or reach out if you have any questions or suggestions.
Happy coding!

