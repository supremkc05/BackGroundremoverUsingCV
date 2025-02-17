Background Removal Project
This project demonstrates how to remove the background from an image using OpenCV and the GrabCut algorithm in a Jupyter Notebook.

Requirements
Make sure you have the following packages installed:

opencv-python
numpy
matplotlib
pillow
ipywidgets
You can install the required packages using the following command:
pip install opencv-python numpy matplotlib pillow ipywidgets

Usage
Open the Project_File.ipynb notebook in Jupyter Notebook or JupyterLab.

Run the first cell to install the required packages (if not already installed).

Run the second cell to import the necessary libraries and define the remove_background function.

Run the third cell to create an upload button and define the on_upload_change event handler.

Upload an image using the upload button. The notebook will process the image to remove the background and display the result.

Functions
remove_background(image)
This function takes an image as input and removes the background using the GrabCut algorithm.

on_upload_change(change)
This function handles the image upload event, processes the uploaded image to remove the background, and displays the result.

