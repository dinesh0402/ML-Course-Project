# <center>ML Course Project - Face recognition & Traffic Sign recognition using Eigenfaces Approach 🧑🚸🔎</center>
***

## <u>Team Members : </u>
- TUPILI KRISHNA GOWTHAM REDDY
- B.V SAKETH RAMA
- JATHIN NADELLA
- K SAI DINESH

In this project, we have build a face recognition model by using the Eigenfaces Algorithm which relies on the concept of Principal Component Analysis (a.k.a PCA) for creating Eigenfaces for the given image dataset. We further extended this approach to "Traffic Sign Recognition", which we would like to call it "Eigensigns".

### <u>Some Important Libraries which we have used:</u>
- Pandas (for importing .csv files)
- Matplotlib (for plotting visualization graphs)
- Scikit Learn (for PCA, accuracy checking, etc.)
- OpenCV and PIL (for Image processing)

***

## <u>Basic flow of Face Recognition process:</u>
1. Load Training Images from the image dataset.
2. Convert all images to grayscale (dimensionality reduction from 3D to 2D)
3. Flatten out all the images to a 1D array using .flatten() method.
4. Pass this 1D grayscaled images to the PCA algorithm (available from the sklearn library) to obtain the Eigenfaces for the entire dataset.
5. Follow steps 1-4 for the testing images as well.
6. Now, import the .csv files for categorical labelling of the images in the dataset. This can be used for predicting the class of the test images and accuracy calculations.
7. Now, predict the class of the test images using the 1NN classifier.
8. (Optional) - You can display the confusion matrix and classification report for more clarity.

***

<u>Challenges faced while performing this project:</u>
- Biggest hurdle in this project is the dataset (Image dataset) collection.
- This involved considering the features like Lighting conditions, Facial Orientation, Fcaial Expression.
- Removing Oculsions on the faces(like mask, glasses, beard, etc.).
- Considering colored images only.

***
# <center>--- End of Description ---</center>
