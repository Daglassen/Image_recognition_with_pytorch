# Image_Recognition_with_PyTorch <br>

**Machine Learning Project on South African coronary heart disease dataset** <br>

**From Abstract** <br>

In this project, we use a Bayesian Neural Network to classify
the body part present in an X-ray image, and use different
methods to explain how our network made this classification.
We will analyze our network’s decision making process by
obtaining posterior distributions for the network’s last layer
of weights, identifying the regions of the X-ray our network
considers relevant in making this classification, and evaluating
the certainty of the model weights. A convolutional neural
network will be built and Class Activation Maps will be used
to attribute relevance to features of the X-ray images. Uncertainty
analysis will be incorporated via Bayesian Neural
Network translation using Laplace Approximation. We find
that the Class Activation Maps successfully aid in the interpretation
of the networks decision making process. We also
find how evaluating the uncertainty of a network’s weights is
significant in increase its explainability.

**Results** <br>
We utilised the class activation map technique to attribute relevance
to the final layer of weights of our CNN. Once generated,
the maps are combined with the original images, in
order to understand which aspects of the image activate the
neural network the most. In figure 3, we see two sample images
from the dataset, one of a shoulder and one of a hand. In
the hand’s heatmap, we can see that the most instructive areas
are the ones around the wrist and the thumb. The latter is also
what discriminates it from the ’wrist’ class. One thing worth
mentioning is the fact that after seeing a few images, that the
model is trained to focus more in the center of the image. For
example, a wrist image might contain a finger close to the
edge of the picture. However, this will not have a big impact
in the model’s decision and this is what provides the capability
to the model to achieve high scores in those classes. These
images tell us how the model identifies particular bones and
joints in the X-ray images in order to identify the extremity
present.


