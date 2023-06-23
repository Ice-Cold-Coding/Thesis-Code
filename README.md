# How to run the code

First download the datasets and the self-supervised model:

  CheXpert: https://stanfordaimi.azurewebsites.net/datasets/8cbd9ed4-2eb9-4565-affc-111cf4f7ebe2
  
  Chest X-ray14: https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/37178474737
  
  cxr-50x1-remedis-m: https://physionet.org/content/medical-ai-research-foundation/1.0.0/

Secondly run notebooks stored in the Data Filterting and Exploration folder, starting with the Chest X-ray14 and CheXpert Filterting notebooks.
These will generate csv files that will be used in the Chest X-ray14 and CheXpert data exploration notebooks

After these notebooks have been run, the images will be fed to the self-supervised feature encoders. 
The notebooks containing that code are stored in the self-supervised feature representation folders,
these notebooks will generate npz files that will be used to train the classifiers.

Finally run the models stored in the Models folder, the hyper-parameter tuning folder is attached in case others want to test out other values for the hyper parameters. 

That's all :)
