# Credit_Risk_Analysis

<b>Overview</b><br>
The purpose of this analysis is to determine the levels of credit card risk by calculating and evaluating unbalanced classes.  By using Python and resampling to look at several machine models we can note the performance and determine whether the models are appropriate for use in analyzing credit card risk.

<b>Results</b><br>

<b> - RandomOverSampler </b><br>

The balanced accuracy score from RandomOverSampler is 63%. The overall average precision is 99%, with 69% recall. 

<img width="472" alt="Screen Shot 2022-06-26 at 12 52 26 PM" src="https://user-images.githubusercontent.com/100445222/175825164-f7ac52ff-6052-45a0-8f43-255f070e7e87.png">

<img width="766" alt="Screen Shot 2022-06-26 at 12 52 34 PM" src="https://user-images.githubusercontent.com/100445222/175825166-8b5c02ec-af34-4ac0-92bd-811526f55a14.png">


<b> - SMOTE </b><br>

The balanced accuracy score from SMOTE is 63%. The overall average precision is 99%, with 64% recall. 

<img width="419" alt="Screen Shot 2022-06-26 at 12 55 34 PM" src="https://user-images.githubusercontent.com/100445222/175825258-1d9139ae-be4d-48bb-b584-64ff9f76a16a.png">

<img width="808" alt="Screen Shot 2022-06-26 at 12 55 40 PM" src="https://user-images.githubusercontent.com/100445222/175825262-abe3bac4-5d21-4e22-a8fd-68ded56ef595.png">


<b> - ClusterCentroids </b><br>

The balanced accuracy score from ClusterCentroids is 63%. The overall average precision is 99%, with 45% recall. 

<img width="536" alt="Screen Shot 2022-06-26 at 12 56 43 PM" src="https://user-images.githubusercontent.com/100445222/175825297-01622686-890a-4418-a8db-79971160ed76.png">

<img width="789" alt="Screen Shot 2022-06-26 at 12 56 49 PM" src="https://user-images.githubusercontent.com/100445222/175825303-83314a6e-a218-49ec-9132-d41be8d08727.png">


<b> - SMOTEENN </b><br>

The balanced accuracy score from SMOTEENN is 53%. The overall average precision is 99%, with 58% recall. 

<img width="585" alt="Screen Shot 2022-06-26 at 12 59 16 PM" src="https://user-images.githubusercontent.com/100445222/175825393-a31864ae-758e-46ff-b8e9-054715463805.png">

<img width="826" alt="Screen Shot 2022-06-26 at 12 59 23 PM" src="https://user-images.githubusercontent.com/100445222/175825395-d8876972-28e1-4e00-a709-23859f8d56e5.png">


<b> - BalancedRandomForestClassifier </b><br>

The balanced accuracy score from BalancedRandomForestClassifier is 79%. The overall average precision is 99%, with 91% recall. 

<img width="510" alt="Screen Shot 2022-06-26 at 1 00 19 PM" src="https://user-images.githubusercontent.com/100445222/175825422-56f9ad06-16f5-47eb-b99e-b2d24ba23885.png">

<img width="772" alt="Screen Shot 2022-06-26 at 1 00 26 PM" src="https://user-images.githubusercontent.com/100445222/175825426-e1c3bd2a-2bac-40a0-a096-f76c04e11bf8.png">

<b> - EasyEnsembleClassifier </b><br>

The balanced accuracy score from EasyEnsembleClassifier is 93%. The overall average precision is 99%, with 94% recall. 

<img width="595" alt="Screen Shot 2022-06-26 at 1 01 29 PM" src="https://user-images.githubusercontent.com/100445222/175825460-ecc78ffe-9768-4c15-8dce-d5bb1a334a68.png">

<img width="802" alt="Screen Shot 2022-06-26 at 1 01 33 PM" src="https://user-images.githubusercontent.com/100445222/175825465-824a43de-cc0a-4db7-8f55-e151ae5ed5c4.png">


<b>Summary</b><br>

Of the many models used in this project to note credit card risk, the most likely candidate to determine levels of risk is the EasyEnsembleClassifier due to its high recall percentage.  With 94% recall, it is more capable of detecting high risks. 
