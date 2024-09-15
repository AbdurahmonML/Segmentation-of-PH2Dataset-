
# Segmentation of PH2Dataset
The PH2 dataset is real dermoscopy images; it was used to evaluate performances of the proposed system for the classification of skin diseases. In this dataset, you can see two types of skin lesions: melanoma and moles. The goal of this project is to train the model to segment the images and find which model performs better.


You can find all my models and results in the notebook above. If my notebook isn't visible to you, don't fret. Simply download and open it, and you'll be able to see all y results. Or you can find the notebook by the link: https://drive.google.com/file/d/1yRLa5Gkg589FzDy2rkgCkRroqD3WM_Uu/view?usp=sharing



#### Datasets: 
You can find dataset by this link: https://www.kaggle.com/datasets/kanametov/ph2dataset/data

#### Models:
- SegNet
- U-Net
#### A little of explanation:
- Whenever I train my model, I consistently conduct predictions on test data and then compare the predicted results with the actual answers through visualization to see how much my prediction is close to the actual answer.
- I am experimenting with training SegNet and U-Net models using various loss functions to determine which combination yields superior performance.
#### Result:
Best model is: Unet + SSIM, IoU score is: 0.9130123853683472
