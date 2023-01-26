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

- _tf.keras.applications.EfficientNetV2B0_ 
- _tf.keras.callbacks.TensorBoard_
- _tf.keras.callbacks.ModelCheckpoint_
- _tf.keras.callbacks.ReduceLROnPlateau_
- _tf.keras.Model.fit()_

Finally, we presented the results with the use of the Seaborn library - simple charts with an accuracy of learning and validation, training loss and validation, and heatmaps with classification of each tumor.

![](https://github.com/Michello077/tumor-classification-using-CNN/blob/4344f59c1d397dc91127bbef2bf6876a89cf84c7/results/CNN001.png)

![](https://github.com/Michello077/tumor-classification-using-CNN/blob/4344f59c1d397dc91127bbef2bf6876a89cf84c7/results/CNN002.png)
