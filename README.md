# handwritten-to-latex
The goal of the project is to build the model which would be able to convert handwritten mathematical formula in the form of an image to a LaTeX expressions.
Current stage: CNN for single symbol recognition is in development.
The accuracy of CNN tested on MNIST and EMNIST datasets is approximately 98 and 87 percent consequently.
CNN architecture for EMNIST consists of 3 conv layers with 3x3 kernels, each followed by maxpool layers with 2x2 kernels, and 3 fully connected layers. Architecture varies based on the dimentionality of datasets being tested. The script proposing the possible model architecture based on the size of the image in the dataset was written.
