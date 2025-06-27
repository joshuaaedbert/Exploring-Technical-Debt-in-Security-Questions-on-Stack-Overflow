# Exploring-Technical-Debt-in-Security-Questions-on-Stack-Overflow
Full paper on: https://www.computer.org/csdl/proceedings-article/esem/2023/10304868/1SBGHz9cSYg

The repository includes all materials required for conducting the study again, including all scripts and data utilized.

## Repository Structure
The directory is structured as follows:

    .
    ├── data                                            
    │   ├───── quantitative analysis 
    │   │	      ├───────────────────── final_dataset_combined_sanitized_sentimentQuestionLength.csv  (the results generated for sentiment score, post score, question length)
    │   │       ├───────────────────── final_dataset_combined_sanitized_answertime.csv 		     (the results generated for time to answer)
    │   │       ├───────────────────── final_dataset_combined_sanitized_usersinfo.csv		     (the results generated for user profile age, reputation score, profile views)
    │   │       ├───────────────────── final_dataset_combined_sanitized_badgeinfo.csv                (the results generated for user badges)
    │   │            
    │   ├───── qualitative analysis
    │	  │       ├───────────────────── td_manualcoding.csv 	(the results of our manual coding for TD questions)
    │	  │       ├───────────────────── ntd_manualcoding.csv	(the results of our manual coding for non-TD questions)
    │   │
    │   ├───── sampling verification
    │   |       ├───────────────────── model_verification_merged_final.csv 	(the results of our sampling verification for binary classification model)
    │		|       ├───────────────────── security_verification.csv 		(the results of our sampling verification for extracted security questions)
    │
    │
    └── src
    ├───── main.ipynb (the script for conducting this study)
