# [Subreddit Clustering](https://github.com/Data-Science-for-Linguists-2024/subreddit-clustering)
by: Madeline Powers

## Teresa's comments

- Your data is in a very clean format. It seemed like the web scraping turned out really well so you have a ton of data to work with! I also think it was very clever to include the username of the person who wrote the comment, in case they've written multiple comments.

- This isn't really an avenue for improvement, but I just wonder if the fact that some subreddits may be more picture-based might mess with your analysis a bit, since you're only able to analyze the descriptions of the photos included. This might just mean narrowing down the choice of subreddits for analysis.

- I personally found web scraping a little difficult so it was impressive to see it done so well. I definitely learned from the way you did it. I also think the data-sharing idea was a very good one and think I might approach my data sharing in a similar manner.

### Response from author
Thanks! The web scraping aspect is definitely something I'm proud of. For the picture thing, I scrapped comments instead of post content.

## Dastan's comments

- I really liked how you split the scripts that you used for scraping from the analysis notebook. So much so in fact that I am considering stealing this method later on for my project. Also you use tqdm to keep track of progression which is good practice especially for more time consuming tasks, such as collecting subbreddit data in your case

- In terms of the data analysis, I think you could've added more visualizations and more examniation of the data, I am not sure if the analysis of the "text" property was left out of progress report 1 intentionally or not, but doing some preliminary analysis on the "text" property would definitiely be a good direction to go in.

- One thing that I learned was that python had it's own library wrapper for the reddit API which is conveient as you don't have to explicitly scrape the subreddits themselves.

### Response from author
Thank you! PRAW definitely made it easier than it would have been. I hope to add more visualizations soon.

## Riley's Comments

- I think your project idea in general is really cool! Your notebook is super clean, and I think you structured your exploration of the scraped data very well.

- Overall I think your project looks great. Something I'm curious about is that you deleted any comments that were deleted or removed. I would wonder, since you're looking for similarities across subreddits, if some subreddits have comments removed more than others and if that could be indicative of language used in those subreddits.

- I didn't know much about webscraping, so looking through your scripts was very informantional

### Response from author
I hadn't thought of analyzing which subreddits have the most deleted/removed comments! I'll have to give that a shot.

## Maya's Comments
- I think your concept is very cool and I think your project is at a really good stage! When looking through your jupyter notebook, I really appreciated the amount of markdown cells you added to explain what was going on, and I enjoyed the conversational tone you used.  
- Though you document your actions well in your progress report, I think it would be beneficial to add a quick summary at the beginning or end of your jupyter notebook so that viewers can get a quick sense of what you have accomplished. I also think some visualizations would be a great addition!
- From reading your project plan, I learned how long webscraping can take, as you said your scripts could take a few hours to scrape all the data.

### Response from author
Thank you! Adding more summary information is definitely a good idea.