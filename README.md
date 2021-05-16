# Deep-CNN-for-Image-Classification

	As part of an academic course project in the module of Deep Learning for Computer vision. I was tasked with researching fundamental CNN architectures which had made significant breakthrough in the field of computer vision influencing how models are crafted and trained today. 
Following the groundbreaking success of AlexNet (2012) most model architecture that subsequently followed focused on increasing the Depth and with of their neural network models. This put a huge strain on the level of compute required for training making it difficult to implement with small computation resources 


I experimented with two model architectures VGGNet with 16 layers and GoogLeNet with 22 layers using MNIST dataset. Experimental results are shown and discussed in the PDF file named “Experimental Results Deeper Networks for Image Classification”

VGGNet - The VGGNet paper focused on simplicity using a “deep and narrow” approach. It utilised small convolutional filters and depth of its network to improve performance. In the original paper 5 variations of the network was proposed with each respective variation increasing in depth and width.

GoogLeNet - Also referred to as inception net, it introduced the concept of inception in CNN, using a “deep and wide” approach. It employed multiscale transformation within layers, lowered parameters numbers adding a bottle neck layer, sparse connections and a global average pooling at the final layer. In addition it used auxiliary classifiers to speed up convergence
