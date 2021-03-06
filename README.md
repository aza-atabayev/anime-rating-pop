# Anime score prediction (Regressinon)

# Problem statement
## Context
With the introduction of 3D animation, 2D animation started to be considered as obsolete in the western market. However, japanese animation (anime) is still prevalent with 2D hand-drawn animation, which is still evolving with introduciton of new genres and recent animation studios appearing there in Japan. To legally broadcast anime outside of Japan the licensors have to buy rights for the specific anime. Since their business is strongly dependant on the popularity of the anime they bought rights on, it is useful to predict the popularity or score of it.

## Goal
Identify factors that might help predict popularity of the anime (without considering synopsis).

# Data Collection
## Data Source
I used "Anime data" dataset from Kaggle provided by user [Canggih P Wibowo](https://www.kaggle.com/canggih/anime-data-score-staff-synopsis-and-genre).

# Visuals
![alt text](https://github.com/aza-atabayev/anime-rating-pop/blob/master/images/1.png?raw=true)

![alt text](https://github.com/aza-atabayev/anime-rating-pop/blob/master/images/2.png?raw=true)

![alt text](https://github.com/aza-atabayev/anime-rating-pop/blob/master/images/3.png?raw=true)

![alt text](https://github.com/aza-atabayev/anime-rating-pop/blob/master/images/4.png?raw=true)

![alt text](https://github.com/aza-atabayev/anime-rating-pop/blob/master/images/5.png?raw=true)

# Conclusion
## Insights TV anime
*   Anime with the higher number of episodes per season has higher score. 12 episodes negatively affect the score and 24 positively affect the score.
*   The fact that anime has more than 6 genres listed positively affects the score.
*   If the second producer was 'Shueisha', for some reason anime might have recieved a higher score than producers with the similar number of projects.
*   The more projects producer participate in, the higher score its projects get (possibly because failing producers go bankrupt before participating in good anime production).
*   The more projects studio make, the higher score its project gets (possibly because failing studios fall before making good anime).
*   Licensors don't affect the score / There aren't licensors that preferably license good anime.
*   Rating doesn't affect the score, meaning either watchers don't care about rating or things that are being age rated does not increase the score.
*   Comedy as the most frequent genre and more rare genres like Psychological have higher scores. That means that comedy is always well recieved and less frequently appearing genres have set of attributes that are expected, leading to higher score.

## Insights movie anime
*   Movies that have duration within 100 and 120 minutes have boost in score.
*   Unlike the TV anime data licensors play a bigger role in predicting the score. It might mean that experience in licensing anime movies is more valuable than licensing TV anime.
*   The more projects producer participate in, the higher score its projects get (possibly because failing producers go bankrupt before participating in good anime production).
*   For some peculiar reason the more anime studio makes, the less score movie will get. My assumption is that studios that create popular TV anime series sometimes create shortened movie versions of the TV series. Audience might not like abridged versions of the stories and thus give a smaller score.
*   Rating doesn't affect the score, meaning either watchers don't care about rating or things that are being age rated does not increase the score.
*   Genre has little importance in score of the movie anime.


## Produced value
*   If one wants to build anime licensing business, it is better to do that in TV anime industry because in the movie industry experience of the licensor strongly affects the score.
*   It is better to keep movie duration within 100 and 120 minutes.
*   It is better to create TV seasons with at least 24 episodes.
*   Saying "original anime has more risks because it doesn't have established fanbase" is a myth, because source doesn't affect the score.