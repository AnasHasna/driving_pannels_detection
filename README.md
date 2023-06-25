# driving_pannels_detection
This is a driving pannel detection with deep learning using scikit-learn


Image to Vector Conversion
This code  demonstrates how to convert an image into a vector representation using Python. It also includes an example of using the converted vector to make predictions using a machine learning model.

Description: 
The provided code converts an image into a vector representation using the img_to_vec function. It performs the following steps:

Reads the image from the specified file path.
Converts the image to grayscale.
Resizes the image to a dimension of (28, 28).
Normalizes the pixel values between 0 and 1.
Flattens the image array into a 1D vector of size 784.
After converting the image into a vector, the code utilizes a pre-trained machine learning model (mlp) to make predictions based on the vector representation. It includes two examples where the vector is used for prediction and prints the corresponding result.

Usage: 
Make sure you have the required dependencies installed (e.g., Pillow, numpy, scikit-learn).
Replace the path variable with the path to your image file.
Run the code.


Make sure to replace the file paths with the actual paths to your images. You may also need to adjust the prediction logic depending on the specific machine learning model and its classes.

Feel free to modify the code according to your specific use case and requirements.
