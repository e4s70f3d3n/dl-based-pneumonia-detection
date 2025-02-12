# #CAP5516
# Deep Learning-based Pneumonia Detection via Chest X-Ray Images
**CAP 5516 - Medical Image Computing** 
**Assignment 1**
---
## Project Overview 
This project implements deep learning techniques to classify pediatric chest X-ray images into two categories: Pneumonia and Normal. The dataset used for this assignment consists of anterior-posterior chest X-ray images of children aged 1 to 5 years, organized into training, validation, and testing sets. The goal is to achieve high classification accuracy by employing two deep learning approaches using the ResNet-18 architecture. 

---
## Subtasks 
### Task 1.1: Train the Model from Scratch 
- Train a ResNet-18 model from scratch, initializing the weights randomly. 
- Employ data augmentation and model regularization techniques to optimize performance.

### Task 1.2: Fine-Tune a Pre-Trained Model 
- Use a pre-trained ResNet-18 model (trained on ImageNet) and fine-tune it on the chest X-ray dataset. 
- Adjust hyperparameters and apply training tricks to enhance performance.

---

### The following outputs and analyses are provided for both implemented models: 
1. **Implementation Details**: 
   - Network architecture, learning rate, batch size, training epochs, etc. 
2. **Training and Validation Metrics**:
   - Per epoch training accuracy, training loss, validation accuracy, and validation loss. 
   - Graphs displaying training and validation loss curves. 
3. **Testing Metrics**: 
   - Overall testing classification accuracy and testing classification loss.
   - Testing classification accuracy per class (i.e., Normal and Pneumonia).
4. **Failure Analysis**: 
   - Misclassified images (both false negatives and false positives) and the actual and predicted labels, respectively, associated with the misclassified image. 
   - (Optional) Visual explanations using Class Activation Maps (CAM) or Grad-CAM. 
5. **Confusion Matrix**: 
   - A confusion matrix visualizing true positives, true negatives, false positives, and false negatives.

---

## How to Run the Notebook 
1. **Start the Notebook Execution**: 
   - Click on the **"Runtime"** menu at the top of the Colab interface and select **"Run all"**. 
2. **Upload `kaggle.json`**: 
   - When prompted, upload your `kaggle.json` file, which contains your Kaggle API keys, to allow the notebook to download the Chest X-Ray dataset from Kaggle. 
     **Note**: If you do not have a Kaggle API key, you can generate one by: 
     - Navigating to your [Kaggle Account Settings](https://www.kaggle.com/account). 
     - Scrolling down to the **"API"** section and clicking **"Create New API Token"**. 
     - This will download the `kaggle.json` file to your computer. 
3. **Automatic Resumption**: 
   - Once the `kaggle.json` file is uploaded, the notebook will automatically resume running and download the dataset. 
   
---
