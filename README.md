![image](https://user-images.githubusercontent.com/126204698/231929627-f8a08d40-0e06-4805-b8a6-47f4758c3f03.png)


[image source](https://th.bing.com/th/id/R.df84bb876dae8f0c2e035ed069391cb0?rik=VbQoStOUeMjxyw&riu=http%3a%2f%2fwww.allmobileza.co.za%2fwp-content%2fuploads%2f2014%2f03%2ffltw-logo.png&ehk=sH3VMMPkQvZz9boGAVcfEewZn6oChBIH22Irhv0mRNI%3d&risl=&pid=ImgRaw&r=0)
# Maching-Learning-Mock-Regression
I grew up on a island surrounded by oceans and am always fascinated with seafood. One major factor on determing a good quality of fish is on its weight and dimension. In this project, I am demonstrating skills to predict the weight of fish on a machine learning regression question.

##Data Cleaning
Inconsistent values (species) and impossible values (weight = 0) was found and addressed.

##Exploratory Data
On correlation heat map. it is observed that weight has the highest corr with Lengths.

![image](https://user-images.githubusercontent.com/126204698/231928233-f320c3ea-1f64-48cd-89cd-0ccfb6e88f35.png)

##Machine Learning Preprocess
A preprocessor was implemented with scaler and OneHotEncoder since there are nominal datas.

##Mahcine Learning Prediction Models

1. model selection: 
- 4 models, default and tuned Decision Tree and default and tuned Bagging tree, are used to predict the weight of fish.
- Bagging tree default and tuned have similiar testing results with MAPE=.107, RMSE=77.789 and R2=.954. All metrics are the highest among 4 models

2. Bagging tree results suggest within 10.6% of the true weight.

3. Consider to use other tree models for future studies.

Therefore, Bagging tree model model is my choice.
