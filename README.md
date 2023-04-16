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
- To train or validate the code use the 3 ipynb files mentioned in the first point of Source Code Package.
- Before running any of those 3 files please change the directory path in cell 4. [Link to cell 4 of UTKFaceipynb file](./Code/UTKFace/AllUTKFace/AllModelsOnUTKFaceDataset.ipynb#cell-4)
## **Instructions on how to run the pre-trained model on the provided sample test dataset**
- [Random Test Sample of 100 images from each dataset](https://drive.google.com/file/d/1Lsw0U2c2BQMXjaWgyLWOQG9oaGjfiTPm/view?usp=sharing)
- Use the [TestSampleOnPreTrainedModel file](./Code/TestSampleOnPreTrainedModel.ipynb) to run the pretrained models.
## **Source Code Package in PyTorch**
- There are 3 ipynb files of eaach dataset containing the initial 9 models which can be found here with their saved model files. [Dataset-1 UTKFace](./Code/UTKFace/AllUTKFace/) | [Dataset-2 Adience](./Code/Adience/AdienceAllModels/) | [Dataset-3 Appa-Real](./Code/AppaReal/AllModelsAppa-Real/)
- The 2 Transfer Learning models can be found here with their respective saved model files. [Transfer Learning Files](./Code/TransferLearning/)
- Preprocessing steps can be found [here](./Code/Preprocessing/).
- Dataset Study can be found [here](./Code/DatasetStudy.ipynb).
- **Note**- Other ipynb files and Saved models which are available in the code are mentioned under the Ablative Study section in results.
## **Description on how to obtain the Dataset from an available download link**
### *Original Dataset Link*
- [Dataset 1 (Punctuations)](https://www.kaggle.com/datasets/abhikjha/appa-real-face-cropped)
- [Dataset 2 (Numbers)](https://www.kaggle.com/datasets/jangedoo/utkface-new) 
- [Dataset 3 (Alphabets)](https://www.kaggle.com/datasets/arcarcarc/adience-dataset-preprocessed)

