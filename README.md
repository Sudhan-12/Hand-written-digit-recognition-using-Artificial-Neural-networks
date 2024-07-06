# Handwritten Digit Recognition with Neural Networks

This project demonstrates the implementation of handwritten digit recognition using Artificial Neural Networks (ANNs) from scratch. The primary goal is to build a simple yet effective neural network to classify digits from the MNIST dataset, which is a well-known benchmark dataset for this type of task.

## Project Overview

The project involves several key components:
- **Artificial Neural Network**: Implemented to recognize and classify handwritten digits.
- **Cost Function**: Custom-designed to measure the performance of the neural network.
- **Backpropagation**: Implemented from scratch to optimize the network's weights and biases.

### Technologies Used
- **Python**: The primary programming language used for implementation.
- **NumPy**: For numerical operations and matrix manipulations.
- **Matplotlib**: To visualize data and results.
- **Random**: For generating random numbers and initializing weights.

### Key Features
- **From Scratch Implementation**: Both the cost function and backpropagation algorithms are implemented without relying on high-level libraries or pre-built functions.
- **Training and Testing**: The neural network is trained on the MNIST dataset and evaluated for its accuracy in digit classification.
- **Visualization**: Training progress and performance metrics are visualized using Matplotlib.

### Getting Started

To get started with this project, clone the repository and install the required Python libraries. You can then run the provided scripts to train the neural network and evaluate its performance.

```bash
git clone https://github.com/your-username/handwritten-digit-recognition.git
cd handwritten-digit-recognition
pip install numpy matplotlib
python main.py
```

### Folder Structure
- `main.py`: The entry point for training and testing the neural network.
- `network.py`: Contains the implementation of the neural network, cost function, and backpropagation.
- `data_loader.py`: Handles loading and preprocessing of the MNIST dataset.
- `visualizations.py`: Includes functions for plotting training progress and results.

### Contributing

Feel free to contribute to this project by submitting issues, feature requests, or pull requests. Your contributions and feedback are welcome!

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize it further based on the specifics of your project or any additional features you have.
