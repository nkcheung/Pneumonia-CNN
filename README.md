# Pneumonia CXR classification with CNN
In this project, a deep Convolutional Neural Network is trained to classify normal and pneumonia chest X-rays. An accuracy of 84.84% is reached after 15 epochs of training. The open-source machine learning library, Pytorch, is used and the model is trained using the free K80 Tesla GPU provided on the Google Colaboratory platform.

## Data
The dataset is provided by Kaggle and is accessible with [this link](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

**Normal CXR:**
![normal2-im-1360-0001 copy 2](https://user-images.githubusercontent.com/44185972/50142754-d375f480-02e5-11e9-87a6-087e83c79f24.jpeg)

**Pneumonia CXR:**
![person1923_bacteria_4831](https://user-images.githubusercontent.com/44185972/50142821-fe604880-02e5-11e9-85fd-084a4142b713.jpeg)






## Model
ResNet34 is used for transfer learning for this project.
