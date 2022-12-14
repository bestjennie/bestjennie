## INF1340 Final Project 

### Project description:
#### Background
Can we say that a film is a success before it is released?
Given that films costing more than $100 million to make still fail, this question is more important than ever.
Suppose an investor is considering entering the film industry and wants to use current film data analytics to drive better decisions and innovation.
This project is to analyze the characteristics that affect the box office and ratings of movies.

#### Data Context
The dataset is sourced from Kaggle: the Movies Daily Update Dataset. It contains more than 700,000 movies listed in the TMDB Dataset, mainly from three decades of global cinema (1990-2022/10).
We conducted data cleansing to enhance analytic accuracy.

#### Data analysis
Through data analysis and visualization of TMDB movie data, we can discover popular trends, find investment directions, and provide specific reference suggestions for new entrants in this industry.  We will analyze:
The top 5 movies that make the most revenues 
The top 5 movie production companies
The top 5 movie genres
Analysis of the most popular movie keywords
The average movie rating in relation to the length of the movie
The relationship between movie box office and movie duration
Correlation of box office with other factors.

### Execution instruction:

#### Installation requirement
Python 3 installation is required in your system for the execution of this program. If you don't have it installed, check this installation [guidline](https://realpython.com/installing-python/).

Install.package("pandas")

Install.package("matplotlib")

Install.package("numpy")

Install.package("matplotlib.pyplot")

Install.package("wordcloud")

Install.package("imageio")


### How to run this program:
#### For the analysis #1:
##### The first step is running the imported CSV file. After running it, this program will show the top 5 movies which have the most revenue in a decreasing order. The example of running this program is:
<img width="549" alt="image" src="https://user-images.githubusercontent.com/116989271/207637860-ad9611da-c035-454e-9707-bc6d80e15a26.png">

#### For the analysis #2:
##### The CSV file can be run once. After doing that, the results of all analysis will appear. For this analysis, it will display the five most popular genres in the dataset. The result may help investors to make more wise decisions when they are deciding which genre to invest. The example of running this program is:
<img width="304" alt="image" src="https://user-images.githubusercontent.com/116989271/207641186-c5d6da68-f8a7-4d89-9de1-81a762254f63.png">

#### For the analysis #3:
##### For this analysis, it shows the top 5 movie production companies that make most movies in the imported dataset. The example of running this program is:
<img width="461" alt="image" src="https://user-images.githubusercontent.com/116989271/207640252-014b3307-54eb-45d8-8a30-ccfa2118cf76.png">

#### For the analysis #4:
##### For this analysis, it displays the average movie rating in relation to the length of the movie. The length of movie is divided into five intervals, including less than 60 mins, bewteen 60 mins to 90 mins, bewteen 90 mins to 120 mins, bewteen 120 mins to 150 mins, and equal to and longer than 150 mins. The average vote scores for different movie duration are shown respectively. The result shows that there is as negative relationship between the average vote scores of movies and their duration. As the movies' duration increases, the average vote score will decrease. Movies equal to or longer than 150 minutes have the highest average vote score, while movies less than 60 minutes have the lowest average vote score. The example of running this program is:
<img width="795" alt="image" src="https://user-images.githubusercontent.com/116989271/207644052-823e2619-a0bd-440c-a75f-658afe94d428.png">

#### For the analysis #5:
##### For this analysis, it shows the five most popular keywords in the dataset. The basis for determining whether it is popular is to analyze the frequency of this keyword. The five most frequently occurring words and their corresponding occurrences are shown respectively. The example of running this program is:
<img width="681" alt="image" src="https://user-images.githubusercontent.com/116989271/207647240-78877e2d-174b-4766-8f0a-c01e9543c6fc.png">

#### For the analysis #6:
##### For this analysis, it shows the trends in the number of movies by genre over time (from 1903 to 2022). The result is shown in pandas.Dataframe. A corresponding plot is displayed as well. This result informs investors which genres are becoming more and more popular. The example of running this program is:
<img width="694" alt="image" src="https://user-images.githubusercontent.com/116989271/207651728-e0f652ac-ff98-44d5-b00b-a99ca194e676.png">
<img width="719" alt="image" src="https://user-images.githubusercontent.com/116989271/207652975-ac1e7b22-8098-4f8e-a472-16bb5bb90b77.png">

#### For the analysis #7:
##### For this analysis, the relationship between movie box office and movie duration is shown in a plot.
<img width="1334" alt="image" src="https://user-images.githubusercontent.com/116989271/207673324-baa3cf8e-ea14-4b2b-9939-9da67498e8dd.png">

#### For the analysis #8:
##### For this analysis, it shows the correlation of box office with other factors, including runtime, popularity, vote count, and budget. 
<img width="696" alt="image" src="https://user-images.githubusercontent.com/116989271/207652572-12f27f11-a061-4e8d-8868-cc034f8491d9.png">

## License
 University of Toronto
