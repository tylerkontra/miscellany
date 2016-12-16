# miscellany

## Vanishing Recession
This ia a nanoproject in R. I was reading about SEI's (seic.com) assets under management, sitting at $707bn as of June, was curious how much it might've been if the recession never happened.

I simply took the real GDP from FRED, cut it off at January 2008 and regressed that (ARIMA). Then predicted the next 30 quarters (approximately where we are now) and plotted it against the *actual* real GDP. For those curious, the pct difference is about 5.7%. So all other things constant (read: unlikely) $707bn could be almost $750bn today. A lot of money, but it was a lot to begin with.

## titanic-kaggle
Kaggle Titanic Data Beginner Machine Learning Competition

My first foray into Kaggle. I primarily used Trevor Stephens' 
  'Getting Started with R' tutorial @ http://trevorstephens.com/post/72916401642/titanic-getting-started-with-r

My final submission was a conditional forest model (cforest_model_1.R). It provided a public score of 0.81340, a score I am satisfied with.
At time of submission, that score afforded a leaderboard position of 395.
I am not planning on continuing with this data set, but maintain this repository as a documentation of my learning process.
