# Object Localization with TensorFlow

All emojis designed by [OpenMoji](https://openmoji.org/) – the open-source emoji and icon project. License: CC BY-SA 4.0

## Overview
This notebook demonstrates object localization using TensorFlow. It includes the following steps:
1. Download and visualize data: Download emojis dataset and visualize a sample of emojis.
2. Create examples: Create examples with random emojis and positions.
3. Plot bounding boxes: Visualize the bounding boxes for the created examples.
4. Data generator: Generate batches of data for training.
5. Model: Build a simple convolutional neural network (CNN) model for object localization.
6. Custom metric: Implement a custom metric for Intersection over Union (IoU) calculation.
7. Compile the model: Compile the model with categorical crossentropy and mean squared error losses.
8. Custom callback: Implement a custom callback for testing the model on sample images.
9. Model training: Train the model for 50 epochs.

## Instructions
1. Run the notebook sequentially from top to bottom.
2. Ensure you have TensorFlow 2.3 installed.
3. Download the emojis dataset for visualization.
4. The notebook includes data generation, model creation, and training.
5. The `test_model` function visualizes the model's predictions on sample images after training.

## Dependencies
- TensorFlow 2.3
- Numpy
- Matplotlib
- PIL

## How to Run
1. Open the notebook in Google Colab.
2. Run each cell sequentially by pressing Shift + Enter.
3. Follow the instructions in each cell.

