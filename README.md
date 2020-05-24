# Movies-ETL
##Hackathon ETL
### Assumptions
We are making some assumptions with this code. One assumptions is that the location this data has been placed will stay the same. If the information is moved our of the direct file path it will break the code and ti will not be uploaded properly.

A second assumption is that that any new code that will be added to the code will stay with in line with the regulare expressions we have written to deal with the code. If we do have some code written that will drop it if doesn't comply but it could lead to data that needs to be cleaned again.

Another assumption we are making is that the column names will not change. We would have to amend some of the transform steps to deal with that change.

A forth assumption is that these data bases are still going to be able to be merged. If kaggle or wiki remove the imdb id we would have to find another way to merge the data. 

The fifth assumption is that when we merged the kaggle and wiki columns is that the columns we chose to take the information from, will still be the best information moving forward. Wiki could  updat their release dates to a more accurate and easy to use format. We are assuming that Kaggle will still be superior moving forward.
