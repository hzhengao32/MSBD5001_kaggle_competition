# MSBD5001_kaggle_competition
Use random forest model to make this prediction. The code and the model is quite simple.As for the data preprocessing, I use sklearn.preprocessing package and fill the Nan values. Then use random forest with max_depth 10 and got the result. The final score for public score is 0.96551.

## The MSBD5001_original_code.ipynb file 
is the process of I training and get scores on public leaderboard.

## generate_result_on_private_leaderboard.ipynb file
is to save your time and generate the private leaderboard scores. To achieve it, all you need to do is to change the test file in the corresponding line. Then run this .ipynb file all over. The "sub.csv" is the target file.

## model.pkl
is the pre_trained_model to save your time and simply test.

## sub_public.csv file is NOT the target file you want for private leaderboard
It is just the result file in public board in which I got the scores higher than the baseline. 
## *If the generate_result.ipynb is not working(with slight chance),you may need to run the original_code.ipynb all over.
