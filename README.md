# Picture_segmentation
<br>
This is an AI project meant to find cats and dogs in pictures and segment them from the rest of the picture.<br>
Three approaches were provided, first one inspired by ParseNet(the papper is provided in the repository), second<br>
approach is a pretrained MobileNet to which I added a couple of layers to adjust it for the segmentation purposes,<br>
and the third is a Fully Convolutional neural network. The three approaches have been compared in this project, and<br>
also the metrics have been showed. The paper on Fully Convolutional neural network is also provided in the repository<br>
along with other popular segmentation strategies.

## Data
<br>
The data I used for training is the COCO dataset available at: https://cocodataset.org/#home<br>
All the analyzation, preprocessing etc. has been thoroughly described in the .ipynb file.<br>

## Our Goal
<br>
These are some of the results of the overfitted models, and these are the results we want our model to generalize well.<br>
We can see the model recognized a cat on the picture(blue color) and segmented it well. This is the result of a Fully Convolutional neural network.

### FCN

![pic1](pictures/Immagine.jpg)

Here is a result of the adjusted MobileNet which successfully segmented and recognized a dog(yellow color).

### MobileNetV2

![pic2](pictures/Immagine1.jpg)

Another example of a dog segmentation by a neural network inspired by the ParseNet arhitecture

### ParseNet

![pic3](pictures/Immagine2.jpg)
