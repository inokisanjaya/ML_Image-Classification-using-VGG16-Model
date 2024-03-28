# Rock, Paper, Scissors Image Classification using Deep Learning

This project aims to classify images of rock, paper, and scissors using a deep learning model implemented in Python with TensorFlow and Keras. The model is trained on the rockpaperscissors dataset, which is divided into training and validation sets. Image augmentation is applied to enhance the model's ability to generalize to new data. The model is trained using an image data generator and a sequential model architecture.

## Project Requirements
- Use the rockpaperscissors dataset, which can be downloaded from [here](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip).
- Divide the dataset into a training set and a validation set, with the validation set comprising 40% of the total dataset.
- Implement image augmentation techniques.
- Use an image data generator for efficient data loading and augmentation.
- Implement the model using a sequential architecture.
- Train the model for a maximum of 30 minutes.
- Develop the program in Google Colaboratory.
- Achieve a minimum accuracy of 85%.
- The model should be able to predict uploaded images, similar to the images provided in the Colab notebook.

## Project Structure
- `data/`: Contains the rockpaperscissors dataset.
- `model.ipynb`: Jupyter notebook for the model implementation and training.
- `README.md`: This file, providing an overview of the project and instructions for running the code.

## How to Use
1. Download the rockpaperscissors dataset and extract it into the `data/` directory.
2. Open and run the `model.ipynb` notebook in Google Colaboratory.
3. Follow the instructions in the notebook to train and evaluate the model.
4. Ensure the model achieves an accuracy of at least 85%.
5. Use the trained model to predict new images by uploading them to the Colab environment.

## Dependencies
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pandas

## References
- [Rock, Paper, Scissors Dataset](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Keras Documentation](https://keras.io/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
