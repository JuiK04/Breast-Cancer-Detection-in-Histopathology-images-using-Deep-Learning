### Project Description
#### Invasive Ductal carcinoma detection using Breast histpathology images
<div style="text-align: justify"> Invasive Ductal Carcinoma (IDC), also known as infiltrating ductal carcinoma, is the most frequent subtype of breast cancer.The main goal of this work is to present a simple deep learning method for detecting IDC.
</div>

### Getting Started
<div style="text-align: justify">

- Open the [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index, "Google Colab").
- Upload the project file **20200315PMM.ipynb** by following the steps below  :
- File -> Upload Notebook -> choose file -> select the project notebook **20200315PMM.ipynb**
- Since the project uses deep learning technique, it is recommended to use GPU. Hence, follow the below steps to activate GPU in Google Colab.
- GoTo Edit -> Notebook Settings -> Select GPU -> Save.
- To run the notebook follow the below instruction :
- GoTo Runtime option -> select Run all option
- Once the notebook is run, it will ask for a 'choose files' option i.e it will ask for a file to  upload(This is the kaggle authentication json file uploaded on git with the name   **kaggle.json**).
- select 'choose files' option -> select the **kaggle.json** file. Then the remaining code will run automatically.
- Please make sure not to run the project file in **incognito mode**of browser.
</div>

### Dataset used
<div style="text-align: justify">

The dataset used in this project is an open dataset: [Breast Histopathology Images](https://www.kaggle.com/paultimothymooney/breast-histopathology-images, "Breast Histopathology Images") by [Paul Mooney](https://www.kaggle.com/paultimothymooney, "Paul Mooney") on [Kaggle](https://www.kaggle.com/, "Kaggle").
The original dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) specimens scanned at 40x. From that, 277,524 patches of size 50 x 50 were extracted (198,738 IDC negative and 78,786 IDC positive). Each patch's file name is of the format: uxXyYclassC.png — > example 10253idx5x1351y1101class0.png . Where u is the patient ID (10253idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC</div>.


### Methodolgy
- Installation of required packages
- Import the data from Kaggle
- Read and understand the data
- Data analysis and Exploration
- Data Preprocessing
- Data Train and Test split
- Data Augmentation
- Build and train the model
- Performance analysis

### Result
#### Evaluation Metric Analysis
![](Images/EvalMetric_final.png)
#### ROC Curve Analysis
![](Images/ROCCurveAnalysis_final.png)

### Conclusion
<div style="text-align: justify">
According to a comparison study published in this project, some of the proposed CNN architectures can achieve outstanding results in breast cancer identification from images.We learned that one issue in applying deep learning to any specific sector is selecting an appropriate model configuration from a large number of network designs by examining the effectiveness of a variety of different CNN architectures.We believe that a composite model that incorporates multiple architectures will be able to achieve more accuracy than a single design.
