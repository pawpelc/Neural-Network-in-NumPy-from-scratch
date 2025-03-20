# Neural-Network-in-NumPy-from-scratch
This project provides a simple implementation of a neural network using only NumPy. The primary component is a Jupyter Notebook that guides users through the entire process, with modular functions covering key steps in the neural network workflow:
  * Parameter initialization: `initialize_parameters`
  * Activation functions and their derivatives: `sigmoid`, `tanh`, `relu`, `leaky_relu` (and their derivatives: `d_sigmoid`, `d_tanh`, `d_relu`, `d_leaky_relu`)
  * Forward propagation: `forward_propagation`
  * Cost computation: `compute_cost`
  * Backward propagation: `backward_propagation`
  * Parameter updates: `update_parameters`
  * End-to-end neural network execution: `neural_network`

The project also includes fake data for testing and observing the network's performance. The data files are:
  * `data.xlsx`: Contains the complete dataset.
  * `x_test.csv`, `x_train.csv`, `y_test.csv`, `y_train.csv`: Include only the relevant subsets of data, as indicated by their filenames.

This project is perfect for those looking to understand the fundamentals of neural networks and backpropagation in a clean, transparent, and fully customizable way.
