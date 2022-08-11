# IEEE-Big-Data-2022

In this experiment, we have applied  the  pre-trained zero-shot model (https://joeddav.github.io/blog/2020/05/29/ZSL.html), and the supervised alogorithms such as Support Vector Machine, Naive Bayes, Random Forest, and Decision trees in the context of topic prediction for the digital forensic data. We have applied cluster based approach to preprocess the input data in order to improve the performance of the zero-shot model. The zero-shot is robust against the unseen class and the unseen text because it can predict the topics in unseen data without any training.  The API of the zero-shot is publicly avaible at : https://huggingface.co/zero-shot/ 

The outcomes of the zero-shot API as follows: 


<img width="455" alt="zrshot" src="https://user-images.githubusercontent.com/25291998/184075549-69a1572c-467d-4dcf-bfdc-290eeae44b97.PNG">




# Packages need to be installed![Uploading zero-shot_model_outcomes.PNG…]()

!pip install -U sentence-transformers![Uploading zrshot.PNG…]()


!pip install sentence_transformers

!pip install transformers

!pip install datasets

!pip install stop_words

!pip install scipy 

!pip install https://github.com/scikit-learn-contrib/scikit-learn-extra/archive/master.zip


# Data 

1. Reuters News Group Data is available in https://huggingface.co/datasets/reuters21578 

2. Yahoo-Answers-Topic Data is available in  https://huggingface.co/datasets/yahoo_answers_topics

# Code:

Reuter Data Application: To execute the code using Reuters in Code folder please run the notebook named Zero_Shot_Reuters_Data_Appliccation_.ipynb

Yahoo-Answers-Topic Data Application: To execute the code using Yahoo-Answers-Topic in Code folder please run the notebook named Zero_Shot_yahoo_answers_topic_Data_Appliccation_.ipynb

Small Warrant Data Application: To execute the code using Warrant texts in Code folder please run the notebook named Zero_Shot_Warrant_Data_Application.ipynb

Supervised Algorithm Comparison: To exceute for Reuter data in Code folder please run the notebook named Zero-Shot_vs_Supervised_Reuters_Data.ipynb, and to exceute for Yahoo-Answers-Topic data in Code folder please run the notebook named Zer-Shot_vs_Supervised_Yahoo_Data.ipynbnb


