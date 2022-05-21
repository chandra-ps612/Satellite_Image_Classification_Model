# Satellite_Image_Classification_Model
For this particular project, I used ```efficientnet-b0 pre-trained model```.


What is ```EfficientNet```?

It was introduced by ```GoogleAI``` in 2019. It is a CNN architecture and scaling method
that uniformly scales all dimensions of CNN such as depth, width, and resolution using 
a compound co-efficient.

It provides a way to scale up CNNs in a more structured manner while also balancing
all dimensions of the network at once, leading to a significant improvement in both
accuracy and efficiency.

```EfficientNet``` has 8 models from ```b0``` to ```b7```. Each model has 4 components
given below-

1. Stem layer
2. Final Layer
3. Sub-blocks (Each block has sub-blocks.)
4. Modules (Each sub-blocks has modules.)

Layer details:



Models' details:

|   Base Model    | Resolution (Input shapes)|
| --------------- | ------------------------ |
| `EfficientNetB0`|          224             |
| `EfficientNetB1`|          240             |
| `EfficientNetB2`|          260             |
| `EfficientNetB3`|          300             |
| `EfficientNetB4`|          380             |
| `EfficientNetB5`|          456             |
| `EfficientNetB6`|          528             |
| `EfficientNetB7`|          600             |



# Reference:
1. Dataset link: https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification
2. For this notebook, I used this particular ```Repo``` https://github.com/rohan-paul/EfficientNet_Pretrained_Pytorch_Covid_19_X_Rays  
   as a tutorial.