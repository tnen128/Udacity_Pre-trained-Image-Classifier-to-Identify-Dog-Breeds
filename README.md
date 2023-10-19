## Dog Breed Image Classifier
This project is an image classification task that focuses on identifying images as either "dogs" or "not dogs" using Python and deep learning models, specifically convolutional neural networks (CNNs). Additionally, it aims to determine the best CNN architecture among AlexNet, VGG, and ResNet for this application.

## Project Overview
Image classification involves determining the content of an image, in this case, whether it's a dog or not. The project also extends to identifying the breed of a dog if it's indeed a dog. To clarify, an image classifier can be seen as a tool with an input (an image) and an output (a classification label), such as "dog." Keep in mind that image classifiers may not always classify images accurately.

The project has the following key objectives:

Determine the "best" image classification algorithm for distinguishing between "dogs" and "not dogs."
Assess how well the "best" classification algorithm identifies a dog's breed.
Measure the time each algorithm takes to perform the classification. There's often a trade-off between accuracy and runtime in computational tasks.
Prerequisites
Python Version: 3.6.3 is required for this project.
Getting Started
Clone this repository to your local machine.
Ensure you have Python 3.6.3 installed.
You will be using a deep learning model, a convolutional neural network (CNN), pre-trained on a vast dataset known as ImageNet. This model can detect features in images and identify objects.
The project provides a classifier function in classifier.py for using different CNN architectures.
Refer to the test_classifier.py file for an example program on how to utilize the classifier function.

## Architecture Exploration
This project explores three different CNN architectures:

AlexNet
VGG
ResNet
You will evaluate the performance of each architecture to determine which one is most suitable for this image classification task.

## Important Notes
Be aware that certain dog breeds look very similar. The more the algorithm learns from images of similar-looking dog breeds, the better it can distinguish between them. Some breeds known to be similar include Great Pyrenees and Kuvasz, German Shepherd and Malinois, Beagle and Walker Hound, among others.
## Conclusion
This project challenges your Python skills in image classification and algorithm evaluation. By the end, you'll have a better understanding of which CNN architecture works "best" for classifying dogs and potentially their breeds.

For any questions or clarifications, refer to the FAQs or reach out for support.

Enjoy working on this fascinating image classification project!
