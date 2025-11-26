Team Kaggle: Matthew Huang, Justin Koida, and Joenna Yaya
Instructor: Cal Poly CSC 480 Rodrigo Canaan


Libraries Used: 
        - PyTorch
        - Sckit-learn
        - pandas 
        - numpy
        - pathlib
        - PIL
        - seaborn


Credits - Inspiration
    Domingo, E. (2023). ISIC 24 SCD PyTorch Simple CNN Submission. Kaggle. https://www.kaggle.com/code/edomingo/isic-24-scd-pytorch-simple-cnn-submission

    
Instructions:
    For our final, we submitted 2 .ipynb files. These files have all the code segments ran so you can see what we did. However, in order to actually run these, use this link to google drive https://drive.google.com/drive/folders/1pIa5TZWWHNQZiT38_CmOapU5mxdiTjGz?usp=sharing
    People who have this link have access to view mode of the drive. In order for the notebook to work, you need to first move this drive into your my drives folder, instructions are as follows:
        1) Open link
        2) In left menu bar press 'shared with me'
        3) Find the CSC480-Project folder and right click
        4) Press 'organize'
        5) Press 'add shortcut'
        6) Press 'all locations' tab
        7) Hover over My Drive and press 'Add'

    Once you have moved this folder into MyDrive, then everything is set up. You can Open the folder and navigate to the 

    CNN_Kaggle_Skin_Cancer_Comp to view our CNN models 

    OR navigate to Final_Code_Kaggle_Skin_Cancer_Comp to view our other final models

    Furthermore, for the CNN models, you will need to have a kaggle account to download a kaggle api token. Instructions to do this are in the CNN_Kaggle_Skin_Cancer_Comp colab in the appropriate place.


    Validation Scenarios:

    For the validation scenarios, the results are already shown in the .ipynb files in this folder. Since running the CNN models are computationally expensive and overall pretty complicated, we've simplified the process by submitting the .ipynb with everything ran. However if you do need to run it, everything up until the scratch section should work if run sequentially. Everything after Scratch was mostly used for visual creation and that sort, and may not necessarily run due to how you need to run the cells in order for it to work. The stuff after Scratch is not necessarily required for the CNN models just something we experimented with. 

    For the other models used such as Logistic Regression, Random Forest, and XGBoost, all the models are pretty simple to run. The Random Forest Classifier models take longer, the one with SMOTE takes about 50 minutes to run, so we recommend just viewing our results in the Final_Code_Kaggle_Skin_Cancer_Comp file. To run this fill, just run it sequentially, and skip over the section that has Random Forest Classifier in order to not have to wait an hour. Within the code, there are comments provided on what you can change for parameters. The main parameter that was changed was in the BCELossWithLogitLoss loss function which you could change the pos_weight parameter to weight classes.
    # Kaggle-ISIC-2024
