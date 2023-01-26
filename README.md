# Tumor classification using CNN

More information about this project is in "Projekt Zaliczeniowy PDF.pdf" (only in Polish).

Collection of analyzed data (MRI images): https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

We processed 3200 MRI images of brain cancer with different classifications.

We aimed to create a classification model for patients with suspected brain tumor development based on MRI images.

The project consisted of below points:
1. Import of libraries and modules
2. Data preparation
3. Dividing our data into testing and learning sets
4. Downloading the EfficienNetV2B0 model
5. Setting up the downloaded model accordingly
6. Compilation of the model
7. Appropriate setting of the reduction function 'leaning rate'
8. Training the model
9. Making a prediction


Examples of the functions we use from the Keras package from the TensorFlow package:

- tf.keras.applications.EfficientNetV2B0 
- tf.keras.callbacks.TensorBoard
- tf.keras.callbacks.ModelCheckpoint
- tf.keras.callbacks.ReduceLROnPlateau
- tf.keras.Model.fit()

Finally, we presented the results with the use of the Seaborn library - simple charts with an accuracy of learning and validation, training loss and validation, and heatmaps with classification of each tumor. 
![](https://github.com/Michello077/tumor-classification-using-CNN/commit/c00cd1c9d0e01f7e6c773c24955ee0a07ce567c8#diff-0dc6fd297b2971c93b8a6d0998710ed4370ae50f5021aa78a45b96e91abcac0b)
![](https://github.com/Michello077/tumor-classification-using-CNN/commit/c00cd1c9d0e01f7e6c773c24955ee0a07ce567c8#diff-8deac688f1ece4ac5d58d602d1f34cf15f8e23d23ea3354f7d0a80229bf5a6e5)
