# CNN-in-Action-Real-World-Image-Classification-Scenarios

##### Name : Nathin R
##### Reg.No.: 212222230090
##### Batch 25 

### CNN Image Classification using PyTorch
This project implements a Convolutional Neural Network (CNN) for image classification using a **custom dataset** in PyTorch. The goal is to learn how CNNs work for feature extraction and classification of images.

### Performance Summary

-  **Training Accuracy**: ~98.8%
-  **Loss**: Reduced from 0.85 to 0.04 over 15 epochs
-  **Accuracy**: Improved steadily from 56% to 98.8%
-  **Evaluation**: Tested on unseen data with strong performance

  
#### Dataset 
```
import kagglehub

# Download latest version
path = kagglehub.dataset_download("sohampatel26/animal-detection-dataset-cats-dogs-and-pandas")

print("Path to dataset files:", path)
```

### Key Learnings

- Built a CNN from scratch using PyTorch
- Implemented a full training and validation loop
- Visualized model performance
- Learned how to deal with small custom image datasets

## Conclusion:
The implemented CNN effectively learns meaningful patterns from a small custom dataset and performs high-accuracy classification. The model is efficient and suitable for baseline image classification tasks. The training process and architecture are well-optimized for educational and real-world prototyping use cases.
