# predict_youtube_likes
* I found an interesting competition on Kaggle: https://www.kaggle.com/c/kaggle-pog-series-s01e01/overview, where one is expected to provide prediction model for likes vs views ratio, based on some image information (thumbnail), text information (description, title, tags) and other quantity (date, seconds duration, etc...).
* Data type:
 <img src="images/data.jpeg" alt="MarineGEO circle logo" style="height: 300px"/>
 
* Image data as thumbnail: 
 <img src="images/img.jpeg" alt="MarineGEO circle logo" style="height: 200px"/>
 
* Text data as description and tags:
 <img src="images/text1.jpeg" alt="MarineGEO circle logo" style="height: 100px"/>
 <img src="images/text2.jpeg" alt="MarineGEO circle logo" style="height: 100px"/>
 
* This question looks interesting to me as we have to deal with some feature engineering and also have to handle image information as well as text information. We will basically practice our machine learning and deep learning techniques with this hands on project.
* I record my solution and comparisons in "results comparison".
* Currently, the notebook in "results comparision" do some feature engineering work, and then use boosting methods (XGB+LGB) to do the regression job. However, this method doesn't take the "thumbnail" information into account. My next improvement is to extract useful features from the image-based "thumbnail" and then add the features into the gradient boosting algorithms. We will see how the additional feature can improve the resutls.
