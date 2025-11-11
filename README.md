# AgarAi-RSTMF-LIVE-DEMO-
A Convolutional Neural Network Model based on MobileV2, that can predict from Agarwood (Aquilaria mallacensis) from Specific Non-Agarwood Trees(caimito, narra, red cedar, and mango).

# DEPENDENCIES
This CNN requieres the following software to run:
  - Python
  - Jupyter NoteBook

For dependencies, the following are needed to run the test code:
  - Tensorflow: This handles Keras models, image loading, and prediction.
  - Numpy: This is essential for array manipulation, especially when preparing the image batch (np.expand_dims).
  - Matplotlib: This is used for plotting and displaying the image (plt.imshow, plt.show).
  - Opencv-python: This provides the cv2 functionality used for reading and color conversion (cv2.imread, cv2.cvtColor).

The following is the install command if you lack the dependencies 
```bash
pip install tensorflow numpy matplotlib opencv-python
```
# USAGE
To use the software:
  1. Ensure that you have the software and necesarry dependencies to run the model, also including the files and the model itself.
  2. Change the filepaths from the ```LiveDemo.ipynb``` file, inside the  ```### (VERY IMPORTANT) INSERT FILE PATHS ###``` section of the code
     - ```model_path``` must be changed to the current filepath that the model is located on your local machine.
     - ```image_path``` must be changed to the current filepath that your selected image is located on your local machine.
  3. Run the code, and enjoy the prediction of the model.
