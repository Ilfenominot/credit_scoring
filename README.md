# ML model for predicting the probability of a customer default
Machine learning model for predicting credit default

Task:
Predict the probability of a customer default based on historical data. Select one or several suitable
learning algorithms and a suitable metric for assessing quality model. The data for learning the model is
contained in the train.csv, the description of the fields is given below.
Prediction should be done on the test.csv part of the data. The analysis is carried out using Python and,
the result is presented as a .ipynb (jupyter notebook) file.
Criteria for evaluation: Correctness of the analysis, compliance algorithms and metrics with the task,
adequacy of visualizations, code quality and common style.

Description of fields:
● id - an anonymous identifier of the applicant
● application_dt - application submission date
● sample_cd - sample category
● education_cd - education
● gender_cd - gender
● age - age of the applicant
● car_own_flg - vehicle presence flag
● car_type_flg - the foreign car presence flag
● appl_rej_cnt - the number of denied past claims
● good_work_flg - flag for "good" work
● Score_bki - a quick score based on data from the credit bureau
● out_request_cnt - number of requests in the bureau
● region_rating - rating of the region
● home_address_cd - home address categorizer
● work_address_cd - work address categorizer
● income - the income of the applicant
● SNA - the applicant's relationship with customers
● first_time_cd - prescription of information about the applicant
● air_flg - presence of the passport passport
● default_flg - default credit flag - target variable
