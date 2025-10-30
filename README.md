# Animal Image Classification using CNN

This project implements a Convolutional Neural Network (CNN) to classify images of dogs and cats using TensorFlow 2.x.

## Dataset Description

- Training set: 8005 images (dogs and cats)
- Test set: 2023 images (dogs and cats)
- Two classes: Dogs and Cats
- Image dimensions: 150x150 pixels

## Model Architecture

The project implements three CNN models with increasing complexity:

1. Basic CNN (Model 0)
   - Convolutional layers
   - ReLU activation
   - MaxPooling
   - Dense layers
   - Sigmoid activation for output

2. CNN with Dropout (Model 1)
   - Added dropout layers
   - Early stopping
   - Learning rate reduction
   - Adam optimizer

3. Enhanced CNN (Model 2)
   - Additional improvements for better accuracy

## Requirements

- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Python Image Library (PIL)

## Project Structure

```
├── Animal_Image_Classification.ipynb   # Main notebook with implementation
├── README.md                          # Project documentation
└── .gitignore                         # Git ignore file
```

## Usage

1. Open the notebook in Jupyter/Google Colab
2. Ensure GPU runtime is enabled
3. Mount Google Drive (if using Colab)
4. Run all cells sequentially

## Model Features

- Image data augmentation
- Dropout for preventing overfitting
- Early stopping
- Learning rate reduction
- Performance visualization
- Real-time predictions

## Results

The models are evaluated using:
- Accuracy metrics
- Loss curves
- Validation performance
- Real-time predictions on test images

## License

This project is open source and available under the MIT License.
