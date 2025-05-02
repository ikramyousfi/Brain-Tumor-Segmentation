# **Brain Tumor Segmentation Using U-Net**

## **Overview**

This project uses a U-Net architecture to segment brain tumors in medical images. The pipeline involves the following steps:

1. **Loading and Preprocessing the Dataset**  
   The dataset is sourced from Kaggle. You can find it [here](https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation).  

2. **Defining the U-Net Model for Segmentation**  
   The U-Net model is a convolutional neural network designed for biomedical image segmentation. You can learn more about U-Net [here](https://idiotdeveloper.com/what-is-unet/).  

3. **Training and Evaluating the Model**  
   The model is trained and evaluated on key metrics, including:
   - **F1-score**
   - **Jaccard Index**
   - **Precision**
   - **Recall**

4. **Visualizing Predictions**  
   The predictions are visualized alongside the ground truth masks, providing an intuitive understanding of the model's performance.

## **Example Result**
Here is an example of the result, showcasing the test image, the mask, and the predicted mask:  

![107](https://github.com/user-attachments/assets/3d262e17-b400-4204-977c-52c6e4c26250)  

**Image: 107.png**  
- **F1-Score**: 0.9680232558139535  
- **Jaccard Index**: 0.9380281690140845  
- **Precision**: 0.9746341463414634  
- **Recall**: 0.9615014436958614  

