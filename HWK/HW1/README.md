STEPS

Using the requests module, I scraped the text from the link provided.

I then created a script that assigns each liine of text to a list within a list and loaded this main list into a pandas dataframe after checking that each inner list was 14 elements long.
Question 1 involved counting the length of the dataframe.

To answer question 2, I returned a dataframe devoid of 'N/A' values by invoking the code dropna(axis=0) and counted the length of this new dataframe.

For question 3, I used the value-counts().idxmax() method to return the most frequent education level.

I used a filter condition, [data['education'] == 6] to retrieve the rows where education level is 6 and then counted the highest occuring income level.
