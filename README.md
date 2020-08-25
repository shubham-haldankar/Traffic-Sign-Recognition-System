# Traffic-Sign-Recognition-System
Project on an AI to identify which traffic sign appears in a photograph

# Experimentation Process
I tried different numbers of convolutional and pooling layers keeping all other parameters the same. When I tried with one each of convolutional and pooling layers, I got 0.2960 loss and 0.9261 accuracy, while when I tried with two each of convolutional and pooling layers, I got 0.1987 loss and 0.9546 accuracy. This suggests an increasing number of convolutional and pooling layers keeping all other parameters the same decreases loss with an increase in accuracy.

I also tried different numbers and sizes of filters for convolutional layers. I observed that by increasing the number of filters the loss is generally decreasing and accuracy increasing. But by increasing or decreasing the size of the filter from (3×3) the loss increases while accuracy decreases for single convolutional and pooling layers.

I also tried different pool sizes for pooling layers. I observed by increasing pool size from (2×2) to (3×3) the loss is increasing while the accuracy is decreasing.

When I removed one of the hidden layers out of two, the loss decreases, and accuracy increases.

Finally, when I increased dropout from 0.25 to 0.5, the loss decreases while accuracy increases.
