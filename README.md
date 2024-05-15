# Single Layer Perceptron Algorithm for Logic Gates

This project implements a single-layer perceptron algorithm to model various logic gates. The implemented gates include AND, NAND, OR, NOR, AND NOT, NOT AND, OR NOT, and NOT OR gates.

## Description

The single-layer perceptron algorithm is a simple neural network model that can learn to classify linearly separable data. It consists of an input layer and an output layer, with a sigmoid activation function applied to the output layer. The algorithm learns to adjust weights and bias to minimize the error between predicted and actual outputs.

## Gates Implemented

- **AND Gate:** Outputs 1 if both inputs are 1, otherwise outputs -1.
- **NAND Gate:** Outputs -1 if both inputs are 1, otherwise outputs 1.
- **OR Gate:** Outputs 1 if at least one input is 1, otherwise outputs -1.
- **NOR Gate:** Outputs -1 if at least one input is 1, otherwise outputs 1.
- **AND NOT Gate:** Outputs -1 if the first input is 1 and the second input is -1, otherwise outputs 1.
- **NOT AND Gate:** Outputs -1 if the first input is -1 and the second input is 1, otherwise outputs 1.
- **OR NOT Gate:** Outputs 1 if the first input is 1 and the second input is -1, otherwise outputs -1.
- **NOT OR Gate:** Outputs 1 if the first input is -1 and the second input is 1, otherwise outputs -1.

## Usage

1. Ensure you have the required Python environment set up.
2. Run the provided Python script to train and test the perceptron for different gates.
3. The outputs for each gate will be saved in Markdown files in the `outputs` folder.

<video width="600" height="400" controls>
  <source src="video_description.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Files

- `perceptron_logic_gates.py`: Python script containing the implementation of the perceptron algorithm and logic gates.
- `outputs/`: Folder containing the output Markdown files for each gate.

## Requirements

- Python 3.x
- Markdown Preview extension for Visual Studio Code (for viewing Markdown files)

## Contributors

- [Rafiq7M](https://github.com/Rafiq7M) - Software Engineering student at Taiz University.

## Note
This, the code is a simple code to understand the algorithm only, and to display the outputs in a different, easy and convenient way. It was presented in order to quote simple ideas on how to display the algorithms’ outputs in an easy and comfortable way. The code was not made complicated or the concepts of design patterns or the like applied in order to make it easier for beginners. Understand the code