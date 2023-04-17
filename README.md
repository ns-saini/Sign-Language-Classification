# **COMP6721_Winter2023_GroupG**
> *Project: ASL Classification Using CNNs*

## **Team Details**
1. Nishant Saini (40195801)
2. Vikram Singh Brahm (40241024)
3. Simran Sohal (40226103)
4. Shalvi Saxena (40220846)

## **High level description/presentation of the project**
 - In Canada alone, there more than 357,000 people who're part of the Deaf Community and American Sign Language is the most tool for them for communication. In this study, we approach the problem of recognizing static hand gestures using Convolutional Neural Networks and recognize and help in interpretation of these hand gestures. 

 - Proposed a systematic approach using ResNet18, MobileNetV3, and ShuffleNetV2 models trained on different facets of ASL i.e. punctuations, numbers and alphabets. We study, how different architecutres approach the problem and how we train these networks from scratch or pretrained weights and study the precisions, accuracy and f1 score and what makes networks better for training. 
## **Requirements**
- PIL                 9.2.0
- cv2                 4.7.0
- matplotlib          3.5.2
- numpy               1.21.5
- sklearn             1.0.2
- torch               1.8.1+cu111
- torchvision         0.9.1+cu101
- cuda                V11.1
- shutil              11.0.0
## **Instruction on how to train/validate the model**
- To train and validate the model, we have created multiple .ipynb files for each dataset and each model. The models are saved in the respective folders.
- To train the model, change the location of the dataset in the code or link the kaggle account in your .ipynb files. The dataset can be downloaded automatically from the kaggle. Run all the blocks under the training section. The models weigh would be saved in the current directory.

## **Instructions on how to run the test sample on the pretrained model**
- User can also run the validation models by running the blocks under validation section in the .ipynb files. Dataloader should be preloaded with the test dataset. The validation accuracy, precision, recall and f1 score would be printed and T-SNE plots would be generated.

## **Description on how to obtain the Dataset from an available download link**
- [Dataset 1 (Punctuations)](https://www.kaggle.com/grassknoted/asl-alphabet)
- [Dataset 2 (Numbers)](https://www.kaggle.com/datasets/muhammadkhalid/sign-language-for-numbers) 
- [Dataset 3 (Alphabets)](https://www.kaggle.com/datasets/mrgeislinger/asl-rgb-depth-fingerspelling-spelling-it-out)


### Link to presentation
- [Presentation](https://drive.google.com/file/d/1vGqgibZ4QIUM7ejvfBvLR5X2ueZ7FxHy/view?usp=sharing)
