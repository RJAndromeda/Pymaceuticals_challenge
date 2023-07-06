# Pymaceuticals_challenge

This was a challenging one for me, and I did not complete all sections.
I have referred to the course materials, as per usual, and also stackoverflow for troubleshooting, and the documentation for python, etc. In addition, I reviewed some points from 
- TylerJames' subsets solution within duplicated from Stackoverflow:https://stackoverflow.com/questions/71957360/using-pandas-to-drop-duplicates-for-subsets-of-rows) to ensure that "Duplicate_mice = merged_mouse_data_df[merged_mouse_data_df[['Mouse ID' , 'Timepoint']].duplicated() == True]" actually worked
- (referred to: https://sparkbyexamples.com/pandas/pandas-get-list-of-all-duplicate-rows/?expand_article=1), specifically: # df = df.drop(df[df.score < 50].index
- # referred to  - https://stackoverflow.com/questions/21487329/add-x-and-y-labels-to-a-pandas-plot - for plt.ylabel addition to chart
- For assistance with merging each of the different drug regimens, I used the idea to separate each individual drug this way from https://github.com/dmilestone/matplotlib-challenge-cancer-drug-analysis/blob/master/Pymaceuticals_Final.ipynb)
