## <center> COVID DETECTOR CLASSIFIER</center>

### MODEL TRAINING

- The dataset is from the kaggle <a href='https://www.kaggle.com/datasets/andyczhao/covidx-cxr2'> Click Here </a>to download the dataset.

- Image augmentations are done with the libraries' preprocess module and with some custom made augmntations.

- The model training is an important and difficult task in every Artificial Intelligence and Deep learning projects.

- There are three different models trained for the problem.

- They include the resnet based model, xception based model and finally the inceptiion based model.

- Install the dependencies with the following command,

  > python3 install -r requirements.txt

  Run the above command in the requirements.txt path then the required modules will install one by one.

- If the system contains gpu make sure to install the cuda toolkit and the cudnn for better performance.

- If GPU isn't present in the system the it will consume a huge amount of time to get the model trained.

## FEATURES

### Transfer Learning:

- The process of using the pretrained model with pretrained weights to have better performance metrics.
- This also requires low computation power than that of the real computation power needed for the entire model to train.

- The following image will show the illustration of the tranfer learning technique.

### Ensemble Learning:

- Ensemble learning is the process of using two or more model for better predictions.

* We must use some technique to be get the predictions from those models.
* In this project we have chosen the upvoting technique, which refers to taking the model of the predictions of all the three model.
* This process really makes the very good accuracy.

* The following image shows the emsemble learning in visual way,

### Note

If you use colab upload the dataset in the drive and continue the process.

connecting google drive with colab,

        from google.colab import drive
        drive.mount('/content/drive')

###### <center> This Model is trained for educational purpose only </center>
