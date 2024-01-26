# Facial_Emotion_Recognition
# Work Description
Emotion recognition is the ability to interpret and process human emotions. Facial Emotion Recognition(FER) is a technique of identifying and analyzing these human emotions based on their facial expressions. Through this presentaion, we aim to analyze the best possible approach or model that could recognize the seven basic human emotions and provide the best accuracy in terms of training and testing datasets. The models used in this for this purpose are ResNet50, VGG 16, and EfficientNet. Our motive is to draw a clear comparison between the models in terms of their accuracy using confusion matrix, loss, and accuracy curves, comparison tables, and accuracy comparison bar graph to identify the best model or models for the purpose of recognising emotions using Facial Emotion Recognition (FER) techniques.

# Software Requirements:

1) Deep Learning Framework ‘PyTorch’ as my deep learning framework. Required specific version of the framework that includes pre-trained VGG16 and ResNet-18 models. I used ‘torchvision.models’ module.
2) I used ‘google colab’ for implementing all my models.
3) Additional Python Libraries: torch.utils.data, dataset , dataloader , transforms , pandas , numpy , matplotlib , Image , splitfolders , Imagefolder, zipfile, EfficientNet, tqdm, mlextend, seaborn, etc.

# Hardware Requirements:
Required RAM: For running inference on pre-trained models, I need A modern computer with 8 GB or more of 
RAM and needed a few gigabytes of storage space for storing model weights, input data of 3500+ images, 
and output results. Training deep learning sequential model, I needed 16 GB of RAM, but more RAM (32 GB or higher) is suggested for handling larger datasets and more complex models. Training deep learning models generates substantial 
amounts of data, including model checkpoints and log files. I needed a considerable amount of 
storage space, typically several hundred gigabytes to terabytes, depending on the size of my dataset (3500+) 
and the number of training iterations.

# Research Paper Description
This paper explores Facial Emotion Recognition (FER) using deep learning models (ResNet50, EfficientNet, VGG16) through transfer learning on the CK+ dataset. EfficientNet outperforms with 98.31% accuracy, surpassing ResNet50 (91.14%) and VGG16 (82.42%). The study emphasizes FER's significance in identifying human emotions and highlights EfficientNet's superior convergence.
