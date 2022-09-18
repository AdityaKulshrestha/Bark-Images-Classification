# Bark-Images-Classification

This project works on the dataset of bark images classification acquired from kaggle.com 

The model has following chapters
1. Importing Libraries
2. Reading the dataset 
3. Splitting the dataset
4. Visualizing Images
5. Data Normalization
6. Data Augmentation
7. Training the dataset 
8. Plotting the accuracy
9. Visualizing the predictions

The model uses a 6 layers Deep Learning CNN architecture.

  **1 layer** - Conv2D with 32 filters and (3,3) kernel size & MaxPooling of (2,2) kernel size & activation 'ReLu'
  
  **2 layer** - Conv2D with 64 filters and (3,3) kernel size & MaxPooling of (2,2) kernel size & activation 'ReLu'
  
  **3 layer** - Conv2D with 128 filters and (3,3) kernel size & MaxPooling of (2,2) kernel size & activation 'ReLu'
  
  **4 layer** - Conv2D with 128 filters and (3,3) kernel size & MaxPooling of (2,2) kernel size & activation 'ReLu'
  
  **5 layer** - Conv2D with 64 filters and (3,3) kernel size & MaxPooling of (2,2) kernel size & activation 'ReLu'
  
  **6 layer** - Conv2D with 64 filters and (3,3) kernel size & MaxPooling of (2,2) kernel size & activation 'ReLu'
  
  Finally it uses Flatten and 2 Dense layers with 64 and 50 neurons respectively.
  
### Predictions by the model

![alt text](https://www.linkpicture.com/q/Bark-Image-Classification.png)
  
The model uses **Adam** as its compilation algorithm and **SparseCategoricalEntropy** for loss measurement and for metrics it uses **Accuracy**

#### The model has achieved approximately 85% accuracy.



