## Udacity-Capstone-Sparkiy-Project

### Introduction

This  is the final project to be submitted as a part of the Udacity Data Scientist Nanodegree program. I am predicting customer churn for Sparkify using Pyspark here.

### Content
_Sparkify.ipynb_ includes the preprocessing, feature engineering and modelling.

### Packages Used
Numpy <br>
Pandas <br>
Matplotlib <br>
Seaborn <br>
PySpark <br>
Datetime <br>

### Results

I built 9 features to train the model which are as follows:
  - total_songs             
  - total_thumbs_up         
  - total_thumbs_down       
  - add_to_playlist         
  - add_friend              
  - lifetime                
  - total_listening_time    
  - gender                  
  - total_artist_played     

I used two models to predict customers churn : 
- Random Forest and,
- Gradient Boost

Finally, selecting Random Forest for customer churn prediction. The RF model had an 80% accuracy with 0.826 F1 score. Also, investigating feature importance- Lifetime of the customer looks to be an important determinent in the data.

For a more detailed analysis, please check this blog post link.
