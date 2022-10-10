# Cricket Shots Deep learning model

This project is part of HELLO FOSS 2022 by WnCC.
</br>
We have build a Deep learning model to perform an image classification task
</br>
## Guidelines

The pre - equisites for you to understand and contribute in this project are Machine learning, understanding of Neural networks, Python and PyTorch library.
</br>

Don't worry, if you dont know the above tech stack, you can learn them with the resources we'll link down and still contribute!

## The Model

We have used ResNet9 architecture for our model, about which you can read more [here](https://towardsdatascience.com/an-overview-of-resnet-and-its-variants-5281e2f56035). 
</br>
We have imported the dataset from Kaggle, it's divided into 4 classes having almost 5k images and also it's fairly balanced as almost equal number of images for all the 4 classes of batting shots.
</br>
Try exploring the dataset on your own to gain insights which eventually help you to tune the model to achieve higher accuracy.

## Good - First Issues

Good First Issue is an initiative to artifically create easy to fix issues in projects, so developers who've never contributed to open-source can get started quickly.

</br>

- Try changing number of epochs, you might be able to see accuracy isn't saturated yet.
- Correct the values of normalisation transformation. Calculate mean and standard - deviation for each channel and fill in the correct values.
- It's always better to visualize results graphically, plot graps for various paramters like loss vs no. of epochs, related to accuracy etc.
- Try finding the ideal batch-loader size by changing it's value and running the model.

## Relevant Sources and documentation
https://drive.google.com/drive/folders/1mTojuq6HrYSX01Dif6-3WePFKAflkaoQ?usp=sharing





