# MachineLearningImage

 The MachineLearningImage project is an iOS application that leverages machine learning to classify images selected from the user's photo library. Using CoreML and the Vision framework, the app processes images using a pre-trained machine learning model called MobileNetV2 to recognize objects and provide a classification result.
 The app displays the classification result in terms of the object detected in the image, as well as the confidence percentage, which tells the likelihood of the detected object being accurate.

## Purpose:
This project demonstrates how to integrate CoreML for image classification on iOS devices. By using Vision and CoreML, it provides a practical application of machine learning on mobile devices. The project can be useful for various purposes:
- Real-time object recognition in images.
- Image classification tasks for various applications (e.g., identifying animals, objects, or even food items).
- Exploring machine learning integration within mobile applications.

## Technologies Used:
 - `CoreML`: Apple's framework for integrating machine learning models into iOS apps. It enables the app to use a pre-trained model (in this case, MobileNetV2) to make predictions based on images.
 - `Vision`: A framework for image analysis, used here to request image classification from the machine learning model.
 - `UIImagePickerController`: This is used to allow the user to select images from their photo library.

## Features:
 -  `Image Picker`: Users can choose an image from their photo library.
 -  `MobileNetV2 Model` : The app uses the MobileNetV2 model to classify the selected image into categories, such as recognizing objects and animals.
 - `Result Display`:  Once an image is classified, the app shows the classification label and the confidence percentage.
 - `User-Friendly Interface`: A simple UI to upload images and display results.

## How It Works:
#### 1.Image Selection:
When the user selects an image from their photo library, the app converts it into a format that the machine learning model can process (using CIImage).

#### 2.Image Classification:
The image is passed to the MobileNetV2 model via the Vision framework to classify the image.

#### Display Results:
The app displays the top classification result with a confidence percentage, which shows how certain the model is about the classification.


https://github.com/user-attachments/assets/ffb5c0e2-7fb3-4c3e-94b3-af9a2839916a





