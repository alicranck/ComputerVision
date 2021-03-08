# ComputerVision
This repository only contains implementations for Neural styel transfer.

## Neural Style Transfer

**To use the Neural Style transfer implementation:**

[Run in Google Colab](https://colab.research.google.com/github/ldfrancis/ComputerVision/blob/master/NeuralStyleTransfer/easyNST%20on%20google%20colab.ipynb)

```python
from NeuralStyleTransfer import implementNTS as NST
```

set the image dimension and train and generate an image
```python
NST.setImageDim(400,300)
NST.run(num_iteration=1000)
```
the `setImageDim` function in the module implementNTS takes 2 arguments: <br/>
<br/>
width: the width of the images used<br/>
height: the height of the images<br/>


the `run` function in the module implementNTS takes 3 arguments: <br/>
<br/>
num_iteration: number of iterations to train for<br/>
content_image: the path to the content image of size: (WIDTH=400, HEIGHT=300)<br/>
style_image: the path to the style image of size: (WIDTH=400, HEIGHT=300)<br/>



### Requirement
* Tensorflow
* numpy
* scipy
