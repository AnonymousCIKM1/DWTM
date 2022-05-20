# DWTM

Dynamically weighted Tabular method

#Instructions
Before application please make sure that the Dataset is viable for DWTM application.
1.   Ensure that there are no missing values
2.   Ensure that the independent variable (Class) is the final column in the dataset

Open the Notebook titled 'DWTM_Implement_Image_Creation.ipynb'
The rest of the instructions are mentioned at the top of the Notebook. 
It is suggested to follow the steps mentioned there.

Follow these steps for successful implementation of the DWTM. For applying Steps 2-5, 
run the cells mentioned below. The notebook is numbered to make it easier to follow:
1.   Upload the following python files from the Google 
Drive Link to working directory and import the classes within them:

    *   1.1 Data_Processing_Numerical.py
    *   1.2 Data_Processing_Categorical.py
    *   2.1 Image_Canvas_Creation.py
    *   3.1 Image_Generate.py

2.   Process your input Dataset to create a Processed Dataset. Save the Processed Dataset in the working 
directory.
    *   For datasets with only **Numerical Data** - Use ***1.1 Data_Processing_Numerical.py***
    *   For datasets containing **Categorical Data** - Use ***1.2 Data_Processing_Categorical.py***

3.   Use the Proccessed Dataset to successfully divide the Canvas Space. Use 2.1 Image_Canvas_Creation.py 
for Canvas Space Creation
4.   Create the Image Dataset using the Processed Dataset and Canvas Space information. Use 
3.1 Image_Generate.py for creating image dataset

5.   Zip and Download the Image Dataset

6.   Use an image classification codebase to obtain your results on the Image Dataset. If required 
you can use the ***Image_Classification_Pytorch.ipnyb*** from Drive Link to classify the Image 
dataset and obtain your results. 
