# AI-Final-Project
Final project for `Artificial Intelligence` course.

### 🎲 How does the process look like? 

<img src="https://user-images.githubusercontent.com/70984049/206620090-21725a95-dae7-4e43-be04-12db2cd86ad8.png" width="300" height="500"/>
<br> 

### 🧩 Implementation flow of the algorithm:
 1. `🗂️ Data Collection` -> 50 videos that come from the <a href="https://www.tiktok.com/"> <button>TikTok</button></a> app
 2. `📊 Preprocessing Data` -> convert raw data obtained through the Data Collection process into data/information that will be used as parameters or information
 3. `📚 Feature Learning` -> the program learns the features contained in each data frame that has been obtained in the previous process
    1. `Convolution` -> make use of 'filter' using 'random' way
    2. `ReLU (Rectivfied Linear Unit)` -> transform data in the Convolution process with a zero value to the pixel value
    3. `Pooling` -> reduce the spatial size of a feature in the convolution process to speed up the computational process by using a down-sampling operation
 4. `📦 Classification` -> classify the results of the Pooling on the Feature Learning process based on several parameters
    1. `Flattening` -> changing the frames generated from Feature Learning to be collected into one linear vector
    2. `Fully Connecting` -> reshaping the activation map into a vector so that it can be used as input
    3. `Softmax` -> the activation stage used for output
    4. `Model` -> classify each frame

 
### 🎯 Project brief: Detecting potential `mental health disorder` from video using the `CNN Method`

### 🔗 Dataset Link: https://drive.google.com/drive/folders/13zLVvmE-xPBcHoTx6AU8pcguBednRUAL?hl=id

### 🔧 Tech stack: Python

![code](https://user-images.githubusercontent.com/70984049/206621790-3ab86da0-d70b-4d90-9d16-d823b8540ef3.png)
 See the code <a href="https://github.com/Lilemanalu/AI-final-project/blob/main/Mental_Health_Indication_Recognition_based_on_Video.ipynb"> <button>here</button></a>!
 
 <br> 
 
 ```
 🧞‍♂️ Team 14
 
 1. 12S20017 - Lile Manalu
 2. 12S20034 - Daniel Limbong
 3. 12S20048 - Jevania
 
 ```
