# comic
This idea has taken up space both on the back and front burners of my mind since the Marvel/Netflix cancellation (#SaveDaredevil).

Does appearance influence how long a comic book character will live? 

Data are taken from Kaggle (https://www.kaggle.com/fivethirtyeight/fivethirtyeight-comic-characters-dataset)

This is a WIP. 

Results (so far...)

1. I did a linear regression and a LASSO to determine which physical features predicts a comic character's longevity. I'll be reporting the LASSO regression results. From the LASSO regression, only five features had non-zero regression coefficients. From eye colour, characters with blue eyes (coefficient: 27.67) are more likely to stick around compared to brown eyes (regression coefficient 6.17). Good characters last longer (14.6) compared to bad characters (regression coefficient -0.8). Finally, individuals with a public identity are more likely to survive longer than individuals with a secret identity (regression coefficient 0.71). 

2. Are there any differences? To assess this, I did some prelimary plots. It appears that "good" characters are equally likely to have a secret or public identitiy while a majority of "evil" characters are likely to have a secret identity. For "neutral" characters, there are slightly more characters with a secret ID than a public ID. The two dominant eye colours are brown and blue - where good characters are more likely to have blue eyes. Hair colour distribution is similar between good, evil, and neutral characters - where black and brown are the most common hair colours. Good characters are more likely to make more appearances than evil or neutral characters. 
