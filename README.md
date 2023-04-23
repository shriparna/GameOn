# Project 1 : Group 9

### Details of the Project 
#### Date: 4/18/2023
#### Presentation: 4/20/2023
<hr>

## Package Contents:

1. [Gaming Sales Data.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/Gaming%20Sales%20Data.ipynb) Gaming Sales Data to be evaluated. Author: Gagan
2. [MI_PBP.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/MI_PBP.ipynb) Effect of hours of gaming on mental health. Author: Portia
3. [Sales_2019_2020.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/Sales_2019_2020.ipynb) Sales data between years of 2019 and 2020. Author: Jesus
4. [games_by_rating_votes_MM.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/games_by_rating_votes_MM.ipynb). Top 20 Games and Ratings. Author: Marina 
5. [genre_sm.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/genre_sm.ipynb) Analysis of video game genre. Author: Sherry
6. [healthSK.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/healthSK.ipynb) Does gaming affects mental health  differently for Male or Female gamers. Author: Shridhar
7. [InputData](https://github.com/shriparna/GameOn/tree/main/InputData) All input data files are in this directory
8. [Visuals](https://github.com/shriparna/GameOn/tree/main/Visuals) The visuals can be found in this directory
9. [Presentation](https://docs.google.com/presentation/d/1JX_ZKHol0w1bfFU_Oh2WrBeBSIxb3f4f1kslOJ8TsjU/edit?usp=sharing)

<hr>

## Instructions:

- Activate PythonData using conda activate PythonData
- Download the above files 
- Open Jupyter Notebook using command jupyter notebook
- Open above files one after the other
- Execute from top to bottom   
- The Analysis is part of the files using markdown or given below:

<hr>

## Analyses/Conclusions:


## Gaming Sales Data

[Gaming Sales Data.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/Gaming%20Sales%20Data.ipynb) Gaming Sales Data to be evaluated. Author: Gagan
<br>
[Sales_2019_2020.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/Sales_2019_2020.ipynb) Sales data between years of 2019 and 2020. Author: Jesus

<img width="582" alt="Screenshot 2023-04-22 at 23 37 32" src="https://user-images.githubusercontent.com/120141110/233818605-b2ef29b1-c813-4716-b790-93e59ae682ed.png">


#### Conclusions
In this data exercise our hypothesis was to see if gaming sales had increased during Covid. We utilized sales data from 2019 and 2020 for this comparison. We compared the sales data across regions and grouped by the genre to see which games performed the best for their respective years. Lastly, we merged the data from both years in order to get an illustration of changes between the year 2019 and 2020 in sales.
The results showed that genres that were dominating the sales in 2019 carried over into 2020. While the total sales for each of the top 5 genres did decrease in 2020. That change was not enough to remove them from their 2019 spots. As for our question that we set out to answer. The conclusion was that during covid increase in sales did not occur.

Going by the sales data of console games between the year of 2019 to 2020, we can see that that there was almost no noticeable change in the sales between years due to Covid-19. If anything, sales dropped by 0.77$ having a maximum profit of 7096.24M in the year 2019 and 6988.05M in the year 2020. We can infer that the drop in sales is due to consumers being unable to purchase games in stores, but further studies are needed in order to have more concrete evidence.


## Gaming and Mental Health Data

[MI_PBP.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/MI_PBP.ipynb) Effect of hours of gaming on mental health. Author: Portia <br>
[healthSK.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/healthSK.ipynb) Does gaming affects mental health  differently for Male or Female gamers. Author: Shridhar

<img width="616" alt="Screenshot 2023-04-18 at 19 37 24" src="https://user-images.githubusercontent.com/120141110/233818362-5becdc6b-91ac-446e-bacb-b5108f9394a5.png">
<img width="838" alt="Screenshot 2023-04-22 at 23 38 52" src="https://user-images.githubusercontent.com/120141110/233818657-bb441386-1c0a-4cbf-ba40-48d38651a70f.png">


#### Conclusions:
We hypothesized that gaming would have a detrimental effect on mental health. Analysis conducted found there was no relationship between hours spent gaming and mental health and therefore the null hypothesis was supported. In this data, people were asked using a reddit forum to respond to this survey and the researchers collected 13,464 responses across 108 countries. Generalized anxiety was measured using the General Anxiety Disorder-7 (GAD-7), narcissism was measured using a 5-scale narcissism rating, life satisfaction was measured using the Satisfaction with Life Scale (SWL), and social phobia was measured using the Social Phobia Inventory. Several outliers were found and data was analyzed with outliers included and removed. Pearsons R correlations were conducted and found no relationship between hours spent gaming and any of the measures given as all r-values were minimal. The level at which people found difficulty playing games and doing work was also measured and most answered "Not difficult at all" and secondmost people answered "Somewhat difficult" indication that while game-life balance may be a concern for some, for most it is not detrimental to their life.

- There is no special distinction in Male vs Female in terms of Mental Illness due to gaming. They both showed the same pattern
- Hence it is concluded that the gaming affects Male and Female equally
- Based on this data we cannot conclude definitely if the mental illness is more prominent in Male or Female.


## Gaming and Genre
[games_by_rating_votes_MM.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/games_by_rating_votes_MM.ipynb). Top 20 Games and Ratings. Author: Marina  <br>
[genre_sm.ipynb](https://github.com/shriparna/GameOn/blob/main/Code/genre_sm.ipynb) Analysis of video game genre. Author: Sherry

<img width="672" alt="Screenshot 2023-04-22 at 23 39 23" src="https://user-images.githubusercontent.com/120141110/233818652-82183820-ba5d-4b78-a4df-590befa47e41.png">




#### Conclusions
In general, top 20 games that have ratings 8.1 - 9.7 are in a range of 46903 - 181778 votes. There is no direct relationship between rating and votes for a game. A game that has a high rating doesn’t have the same position in high votes, except one game that has the highest rating and highest votes that match. It’s The Last of Us. For example, The Witcher 3: Wil Hunt and Red Dead Redemtion 2 have high ratings of 9.7 but they only rank 11th and 17th place out of 20 top games by votes. If a game developer wants to build a successful game, Last of Us is a good example for deep analysis from a game plot/characters/graphics point of view

- The most popular video game genre? <br>
`Action` genre, refer to: [The Distribution of Genre](###The-Distribution-of-Genre)
There were a great amount of video games which been identified as `Action` genre also been recogized as `Adventure` genre. We can tell by looking at the Genre vs Year line plot. The two lines that represented `Action` and `Adventure` has similar pattern, refer to: [Genre v.s. Year](###Genre-v.s.-Year) 
- Which genre has the overall highest rating?<br>
`Mystery` genre has the overall highest rating.  `Adventure`, `Crime`, `Fantasy`, `Sci-Fi`, and `Thriller` have a few outliers of ratings, refer to: [Genre v.s. Rating](###Genre-v.s.-Rating)
- Which genre has the most votes? (Suppost that more votes means more users)
`Action` genre got the most votes, which align to the answer of the first question, refer to: [Genre v.s. Votes](###Genre-v.s.-Votes)
- We can say `Action` is the most popular genre based on previous analysis. Which genre will be the best to combine with `Action` if we would like to have a high rating?<br>
The average rating for video games that only been identified as `Action` genre is 6.66. When we calculate the average rating of the combination of `Action` and the other genre, all the combinations got a higher rating than only `Action` genre itself, espicially `Action & Mystery`, which got 7.38 as the overall rating, refer to: [Action with other Genre Rating](###Action-with-other-Genre-Rating)
- According to the Heatmap above, we can tell that the variables in this dataset are independent to each other, with the highest correlation of 0.22 between `rating` and `votes`, and the lowest of -0.22 between `Action` and `Mystery`.


<hr>
