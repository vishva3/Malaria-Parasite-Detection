**Malaria_Detection_Deep_CNN**

*Introduction*

This repository contains code for a malaria parasite detection system using Convolutional Neural Networks (CNNs). The system is designed to classify whether a given blood cell image is infected with malaria parasites (Plasmodium) or uninfected.

*Dataset*
The dataset used for training and testing the model consists of two classes:

1. Parasitized: Blood cell images infected with malaria parasites.
2. Uninfected: Normal blood cell images without malaria parasites.

The dataset is organized into separate folders for each class.

*Usage*

1. Clone the repository to your local machine.
2. Ensure you have the required libraries installed (numpy, pandas, opencv-python, keras, etc.).
3. Run the provided Jupyter Notebook or Python script to train and test the model.
4. Use the trained model (a95e30model.h5) for malaria parasite detection in new images.






**Blood_Smear_Bounding_Box**

*Introduction*

This repository contains code for detecting and extracting bounding boxes around objects in images using OpenCV and image processing techniques.

*Loading the Dataset*
The dataset is loaded from a specified directory (/content/drive/MyDrive/malaria/images). The dataset contains images with objects that need bounding boxes.

*Displaying Sample Images*
A few sample images from the dataset are displayed to showcase the images' content.

*Extracting Bounding Boxes*
Image processing techniques like thresholding, morphological operations, and watershed segmentation are used to extract bounding boxes around objects in the images. Contours are detected, and bounding rectangles are drawn around them.

*Visualization of Image Processing Steps*
Various stages of image processing such as thresholding, sure background detection, distance transformation, and watershed segmentation are visualized to understand the process better.

*Usage*
1. Clone the repository to your local machine.
2. Ensure you have the necessary libraries installed (numpy, matplotlib, opencv-python, etc.).
3. Run the provided Jupyter Notebook or Python script to perform bounding box detection on your images.
4. Modify the code as needed for your specific dataset or image processing requirements.

*Additional Notes*
1. Experiment with different thresholding techniques and parameters for better object detection.
2. Explore advanced image processing algorithms to improve bounding box accuracy and robustness.

Feel free to reach out if you have any questions or suggestions regarding this project.
