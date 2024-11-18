# NLP-Project- Finding music recommendations using Reddit API
In this project, I set up a Reddit API access  using PRAW where I targeted the 'MusicRecommendations' subreddit. I then collected the top 200 posts from the past year which includes the post titles, the post scores, the number of comments and the content of each comment. 
I then implemented a genre detection system for 20 predefined genres which could always be expanded. I then created a function to identidy the mentions of these music genres within the comment text and generated the frequency distribution. With the gathered data, I then visualized the results using bar charts. 
I applied the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization which I limited to only a thousand features and implemented K-Means clustering to group similar recommendations. 
Then I implemented a sentiment analysis of each comments by using TextBlob. I then calculated the polarity where -1 would be negative and 1 being positive. 

In the cluster visualization, it shows how recommendations group together based on similarity and frequency. In the music genre graph, it gives us insight on the most recommended music genres in the top 200 posts of the year. From the data gathered, we see that Rock is the most popular, followed by rap, metal, house and soul.  
And finally, the sentiment distribution histogram, it provides an understanding on the overall tone of each recommendations. The sentiment score gravitate on being neutral to positive. 
