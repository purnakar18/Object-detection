# Object-detection


Abstract:

The aim of the project is to identify images of people who are wearing masks. 

Methods:

The function count_masks(dataset)  counts the number of faces correctly wearing mask (with_mask class), without mask (without_mask class) and incorrectly wearing mask (mask_weared_incorrect class) in the list of images dataset which is an instantiation of the MaskedFaceTestDataset class. The aim is to implement a 3 class (4 class with background) masked face detector which can detect the aforementioned categories of objects in a given image. 


Inputs

•	dataset is an object of the MaskedFaceTestDataset class shown in the cell below.

Outputs

•	This function should return a 2 dimensional numpy array of shape 𝑁×3N×3 of data type int64 whose values should respectively indicate the number of faces wearing mask, without mask and incorrectly wearing mask.

