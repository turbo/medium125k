# medium125k

This is a data set of more than 125,000 titles and subtitles of articles published at [medium.com](https://medium.com). The data is formatted as CSV and the columns are: 
<br>
<br>

![](/explain.svg)

<br>

The data set should only contain english posts, but sometimes a foreign title slipped through the Medium language detector (e.g. chinese) when the input is ambiguous, like in `> 我等香港人：海外研究生就法院有關雨傘佔領者判決之聲明 We Hong Kongers: Statement by Overseas Graduate Students on the`. However, not many of these are present in the set and manual cleanup shouldn't take too long (if you did this, please open a PR).

Available [on Kaggle](https://www.kaggle.com/nulldata/medium-post-titles).
