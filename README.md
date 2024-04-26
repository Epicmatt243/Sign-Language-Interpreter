This project is a computer vision model that recognizes letters in american sign language.

'asl_dataset(LettersOnly)' contains the dataset.  Retrieved from https://www.kaggle.com/datasets/ayuraj/asl-dataset.  Data for numbers has been removed to lessen the number of classes that the model needs to be able to recognize.  

'SignLanguageDetector.v1i.yolov8(2)' contains the notebook and training/valid/test sets that was used to train the model.

'ModelTesting' contains the most recent version of the trained model, a script to create a flask webserver at localhost:8080 to test the model, and some sample images to use.