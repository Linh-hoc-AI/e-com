# Multimodal retrieval: A contrastive learning approach 

![image](https://github.com/user-attachments/assets/88e7499c-6ee5-4a60-a69e-edd71b9d4938)

## Text Encoder

![image](https://github.com/user-attachments/assets/8b5e2f1c-fb43-46ff-91b7-b069d49db3a5)

## Vision Encoder

![image](https://github.com/user-attachments/assets/1f374539-b6c7-49d3-afff-da526061c95e)


Download the dataset from the following Google Drive link: [Dataset Link](https://drive.google.com/drive/folders/1-IX2zjtLHTClm66vRHRwvo_-s0X5v8FM?usp=drive_link)

The downloaded file is data.zip. Extract it to create the data folder.

```bash
e-com/
├── data/
│   ├── images/
│   ├── label_test.json
│   ├── label_train.json
│   ├── test.csv
│   └── train.csv
│   
├── fig/
│   ├── fig1.png
│   ├── fig2.png
│   ├── fig3.png
│   ├── fig4.png
│   ├── fig5.png
│   ├── fig6.png
│   ├── fig7.png
│   ├── fig8.png
│   ├── fig9.png
│   └── fig10.png
├── e-com.ipynb
├── e-com.pt
├── README.md
└── training_log.txt
```

## Folder Structure and Contents
### 1. data/

images/: Contains product images, where each image file is named using the product ID (e.g., 123.png for a product with ID 123).

train.csv: Contains product IDs and their corresponding description labels for training.

test.csv: Contains product IDs and their corresponding description labels for testing.

label_train.json: Statistics of the number of samples per description label in the training set.

label_test.json: Statistics of the number of samples per description label in the test set.

### 2. fig/

Contains illustrative images (e.g., fig1.png, fig2.png, etc.) used for visualization or documentation purposes.

### 3. training_log.txt

Logs information about the model training process, such as epochs, loss,...

### 4. e-com.pt

The trained model weights file for the e-commerce model.

### 5. e-com.ipynb

The source code notebook containing the implementation of the model, including data preprocessing, training, and evaluation steps.

