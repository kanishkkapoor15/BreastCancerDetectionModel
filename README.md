# BreastCancerDetectionModel
Breast Cancer Detection Model using CNN Framework in R
Dataset: https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images
 ![12886_idx5_x201_y501_class1](https://github.com/user-attachments/assets/79e11fec-0126-4a04-8730-55eae4a5dee2)
![12886_idx5_x451_y301_class1](https://github.com/user-attachments/assets/5555d958-64e1-4609-80b5-a690f844ee4f)

In this project, we developed a Convolutional Neural Network (CNN) to classify images for binary classification of cancer detection using a dataset of medical images. After preprocessing the data and splitting it into training, validation, and test sets, we built a model that successfully learned to differentiate between the two classes (cancerous vs. non-cancerous).
<img width="655" alt="Screenshot 2025-04-11 at 11 30 18 AM" src="https://github.com/user-attachments/assets/312d433d-ab0e-4d25-8ed8-b3accd81874c" />


Key Insights:
	1.	Model Architecture:
	•	The CNN architecture included multiple convolutional and max-pooling layers, followed by dense layers and dropout for regularization. This architecture helped the model effectively capture spatial hierarchies and reduce overfitting.
	2.	Model Performance:
	•	On the training dataset, the model achieved an accuracy of 82.1% and on the test dataset, it achieved 79.2% accuracy, showing strong generalization capabilities. The validation accuracy was slightly lower at 77.5%, but still competitive.

3.	Learning Progress:
	•	The training and validation losses decreased steadily over the course of 10 epochs, indicating the model’s ability to learn effectively from the data.
	•	Early stopping could further improve performance by preventing overfitting and optimizing the model’s accuracy.

 <img width="1019" alt="Screenshot 2025-04-11 at 11 28 31 AM" src="https://github.com/user-attachments/assets/56eb343d-bf18-43dd-8201-f0a8eaa42b9a" />
	4.	Visualizations:
	•	Accuracy and Loss plots provided a clear view of the training process, helping to visualize the improvement across epochs.
	•	A performance comparison bar chart effectively communicated the model’s evaluation on different datasets, highlighting <img width="1189" alt="Screenshot 2025-04-11 at 11 36 51 AM" src="https://github.com/user-attachments/assets/2ff62672-3ad7-41da-9f38-78e2f9f611d6" />
the model’s robustness.


