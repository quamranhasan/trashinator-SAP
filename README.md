# trashinator-SAP
This is our GitHub repository for MSB481(B)-SAP project

## About The Project
![image](https://drive.google.com/uc?export=view&id=1u7GWhxMdGJ3v4QP2b1bVZguEznEXhwqa)
our project introduction ( please help me to fill this!)

## Getting Started
To get start, follow the following steps:

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
2. Install dependencies
   ```sh
   pip3 install -r requirements.txt
   ```
3. Take a look at the repository structure below
4. Happy coding!


## Repository Structure
This is the general structure of our repository

    .
    ├── AI                         # folder for the AI implementation code
    ├── aicore-pipelines           # folder for the SAP AI Core pipeline
    ├── models                     # trained models generated by the AI pipeline
    ├── .gitignore                  
    └── README.md

### AI Folder
`AI` folder consists of several files

    .
    ├── ...
    ├── AI                               
    │   ├── convert_model.ipynb          # Load and stress tests
    │   └── train_model.ipynb            # Unit tests
    └── ...
    
#### train_model.ipynb
This is the code that we use to make and train our model. you can skip this code if you want to use our trained model provided in the `models` folder. However, If you want to train with your own model, a detailed explanation regarding the code is available inside the ipynb file.

#### convert_model.ipynb
This is the same code that was previously used in the class. One difference, however, is that we use RGB images (3 channels) instead of greyscale (1 channel). The respective change is explained inside the file.

### aicore-pipelines
This is the folder for the training process of our AI pipeline in the SAP AI Core.

### models Folder
The folder consists of the model we trained and used for trash classification, available in three different file formats (h5, tflite, and cc).

