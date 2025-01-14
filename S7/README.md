# S7 Assignment

Task: Your assignment 6 is:

    Run this network.  
    Fix the network above:
        change the code such that it uses GPU
        change the architecture to C1C2C3C40 (basically 3 MPs)
        total RF must be more than 44
        one of the layers must use Depthwise Separable Convolution
        one of the layers must use Dilated Convolution
        use GAP (compulsory):- add FC after GAP to target #of classes (optional)
        achieve 80% accuracy, as many epochs as you want. Total Params to be less than 1M. 
        upload to Github
        Attempt S7-Assignment Solution
        
        
Assignment Solution: ![CIFAR-10 Model](https://github.com/Gilf641/EVA4/blob/master/S7/S7_AssignmentSolution.ipynb)
        
        
* **Model Features:**

1. Used GPU
2. Receptive Field = 62
3. Total Params = 315,312
3. Used Depthwise Separable Convolution
4. Used Dilated Convolution
5. Since the model was overfitting, I used Dropout of 10% with L1 & L2.
6. Ran the model for 15 Epochs
7. Got more than 80% accuracy after 9th epoch.
8. Implemented model checkpoint to save best model and also to save model.
9. Built a Image Classifier similar to ResNet Architecture(maintaining same number of channels for each convolution block).


* **Library Documentation:**

1.![image_transformations.py](https://github.com/Gilf641/EVA4/blob/master/S7/evaLibrary/image_transformations.py) : Applies required image transformation to both Test & Train dataset aka Image PreProcessing.

2.![cifar10_models.py](https://github.com/Gilf641/EVA4/blob/master/S7/evaLibrary/cifar10_models.py): Consists of 2 models i.e seafarNet & cfarResNet(don't mind the names...)

3.![execute.py](https://github.com/Gilf641/EVA4/blob/master/S7/evaLibrary/execute.py): Scripts to Test & Train the model.

4.![DataLoaders.py](https://github.com/Gilf641/EVA4/blob/master/S7/evaLibrary/DataLoaders.py): Scripts to load the dataloaders.

5.![visualizeData.py](https://github.com/Gilf641/EVA4/blob/master/S7/evaLibrary/visualizeData.py): Consists of helper functions to plot images from dataset & misclassified images



* **Misclassfied Images**


![](https://github.com/Gilf641/EVA4/blob/master/S7/CIFAR10(2).png)


