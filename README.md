# Garbage Segregator GUI App
This is a GUI app that classifies garbage as biodegradable or non-biodegradable using Machine Learning. This app is built using python. User can import the image of a waste product in the app by browsing images in his/her device and the app will classify the waste.

## How to run the app
1. Clone the repository.
2. Place the .weights and .cfg files from 3_Implementation folder, in appropriate directory and provide the same path in the files for testing the model and GUI app.
3. Run the file for testing model to test trained model on you custom (self clicked) images.
4. Run the GUI app file to run the GUI app.

## How to browse the image
1. Click the browse button in the app.
2. A window for selecting image will open. Select images to be classified from appropriate directory.
3. The app will display the browsed image and also will output its type of waste.

## How the app is built
1. The app contains a YOLO trained model in the backend, trained to classify images as biodegradable or non-biodegradable.
2. The user interface of the app is built using python Tkinter library

## Interface of the app
1. A wide screen to display image
2. A long flex type display to display the output i.e. the type of the garbage.
3. A browse button to select image from the device
4. An exit button to exit the app

## How the app looks
![alt text](https://github.com/jatin-kumar-123/First_Sprint_Mini_Project/blob/main/App_Interface.JPG)
