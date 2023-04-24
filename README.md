# Character-Recognition-Perceptron-Adaline
## Perceptron and Adaline Network for Classifying Letters from Different Fonts

This project contains a Python code that implements Perceptron and Adaline networks from scratch to classify letters from different fonts. The data consists of 42 txt files, each containing a 9x7 matrix of pixels, with six different font types of each letter A, B, C, D, E, J, and K. The "#" symbol indicates the on pixels, "." indicates the off pixels, "@" indicates wrongly on pixels, and "o" indicates wrongly off pixels. The training set consists of 21 txt files, and the test set includes 21 txt files.

The first step in the project was to preprocess the data and convert the pixels to a bipolar input for the network. Each class (letter) was then encoded as a 7-length vector, with one of the elements being 1 and the rest being -1 to indicate which neuron should be on in the output layer. The preprocessed data was then converted to CSV files for easy downloading and use.

To run the preprocessing code, download the rar files containing the data and extract them. The Python code can be executed to preprocess the data and generate the CSV files.

The main code includes implementations of Perceptron and Adaline networks, which were trained on the preprocessed data to classify the letters from different fonts. The accuracy of the networks was evaluated using the test set.

If you're interested in using this code for your own project, feel free to download the repository and modify the code as needed.
