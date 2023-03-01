# Efficientnetv2-Pytorch

A notebook that can train a efficientnetv2 for customized dataset with 1000 classes.

Here is the dataset structure you need to prepare:

```
dataset
├── train
      ├── class0
             ├── image 0
├── test
      ├── image 0
├── val
      ├── class0
             ├── image 0
```
Here we use train and val file for our training.

In the test file, you can put all the image you want to inference or evaluate, the ouput would be a csv file.
