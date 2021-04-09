![](images/exmaple_result.png)
#### Visualizing Convolutional Neural Network features based on method purposed by [Erhan et al. (2009)](https://www.researchgate.net/publication/265022827_Visualizing_Higher-Layer_Features_of_a_Deep_Network).

This repository is visualizing the deep layer feature. Feature Maps are constructed randomly initialized noise image by computing the activation maximization. In the first stage, a feature map for different layers has been constructed. Then, we later fit the selected picture to the model to compute the forward propagation. The features seem more complicated at higher layers. Based on the result of n most activated filters, then we constructed the feature maps again for these filters at higher layers using the premonition method, to see how the activation of the feature corresponds to the image.

For the experiment, we used pre-trained torchvision.modelsresnet34. However, it can easily be extended to the other models.

For more detail check out the code and the paper.
