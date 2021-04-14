# Binge-watch 🍿
The data set contains data till 2020. Major chunck of data was taken from kaggle and then web scrapped from wikipedia. The data which was scrapped from wikipedia didnot conatained genres which was then taken from TMDB. The data cleaning and separation was done in 3 level. Ultimately every movie is judged on the basis of directors , 3 main actos and genres. 

User reviews was collected from social media and sentiment analysis was done on the reviews. The binge watch engine was feed with the parameters of genres , cast and directors. The data was first converted to a matrix of token counts and cosine similarity was used to generate the movie score. On the basis of cosine similarity we generate a list of enumerations. According to the movie title binge watch engine gives top 10 movies on the basis of score.

<img src='https://www.designmantic.com/blog/wp-content/uploads/2016/02/Movie-poster-design-trends.jpg' >
