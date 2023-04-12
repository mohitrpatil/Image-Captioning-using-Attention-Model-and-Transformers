# Image Captioning using Different Neural Networks
## CSE 598: Introduction to Deep Learning
<br>

### Introduction
The code is responsible for conducting experiments of end-to-end image captioning and obtaining results using different Neural Networks. Each approach or experiment conducted is a form of different ipynb file (Jupyter Notebook Python code). The dataset used in all the experiments is *Flickr8k* 

### How to Run
1. Download the Flickr8k dataset from https://forms.illinois.edu/sec/1713398 <br>
It can also be easily downloaded from https://www.kaggle.com/datasets/adityajn105/flickr8k
2. The code makes use of google drive for getting the dataset as well as storing metadata like extracted features, model pickle files etc.
3. The base directory used by the code everywhere is: '/content/gdrive/Shareddrives/DLSD/'<br>
Once the dataset is downloaded, please unzip and place in google drive and replace the directory in the variables - 'BASE_DIR' and 'WORKING_DIR' with the one you have used in the google drive.<br>
The hierarchy of the dataset is as follows:<br>
```
BASE_DIR
│
├── Images
│   ├── 1000268201_693b08cb0e.jpg
│   └── 1001773457_577c3a7d70.jpg
│   ...
│   ...
└── captions.txt
```
4. The code runs end-to-end to find out results and the metrics.
<br>4.1 Baseline Model - Baseline_Image_Captioning.ipynb
<br>4.2 CNN Variations Model - CNNVariations.ipynb
<br>4.3 Attention Model - ImageCaptioningAttention.ipynb
<br>4.4 Transformer Model - Image_Captioning_Transformer_model.ipynb
5. Once it has run once, you can use the already formed feature files or pkl files to quickly run the subsequent code to save time.
6. The dataset and the formed features and pkl files are available here and can be given access to immediately if and for the reference : https://drive.google.com/drive/u/1/folders/0AFEGUAQMbf56Uk9PVA

