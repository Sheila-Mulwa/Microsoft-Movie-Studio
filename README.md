# Microsoft-Movie-Studio (Sheila Mulwa)

This project is a part of the Data Science (DSF-FT) Course at Moringa School. The full project description can be found here.


## Project Overview 

Following the creation of the new Microsoft Movie Studio, I have been charged with exploring 
what types of films are currently performing best at the box office. After utilizing the EDA process ,
the analysis identified the following:
  * The best month to release a movie is February.
  * The most-selling genre is Animation followed closely by Sci-Fi.
  * The best three directors are John Andreas Andersen , Robin Pront, David Delhoffen.


  ## 1. Business Problem

Microsoft has decided to venture in to the film industry by launching a new movie studio: *Microsoft Movie Studio*.
However, they are not sure where to start , because they don't have enough knowledge about the film industry.
I have been tasked with aiding the new head of Microsoft to study which films  are showing the best results at the box office, and translate my findings into actionable insights. There are many aspects that affect profitability of such an industry. 

I based my analysis on the following factors:
 * Total gross earnings
 * Genre
 * Release Date
 * Rating
 * Runtime
 * Directors
 * Studios(Competitors)


## 2. Data Understanding

I used three datasets from renowned film database websites: Box Mojo, IMBD and TMBD
 
Such data primarily comes from the years 2010-2019.
From the  first dataset which is in .csv format, we have the movie titles, year, studio and revenue information of films that have been released and those that are yet to be released. With gross earnings being the target variable, the monetary data (domestic gross and foreign gross) columns are the main reason this dataset was selected. 

From the second dataset which is in .db format, we have a database with 8 tables containing different types of non-monetary information about films such as their genres, directors, writers, movie ratings and more. This information will be used to understand the characteristics of the films that are currently performing the best at the box office.

From the third dataset which is in .csv format, we have the popularity, original titles, votecount and release_date. The popularity column will be used to determine the films that are currently performing the best at the box office.



## 3. Methods

This project uses descriptive analytics to describe trends in the features of successful movies.

For all the datasets, I removed unnecessary columns, cleaned, and filtered all of the tables used. To make sure that the data we used was relevant to Microsoft's business question, we limited the data to only include movies released between 2010 - 2019 .

Data Preparation: I combined all the datasets and dropped the columns that I was not going to use for my analysis.
I focused on six perfomance metrics :
* Genre
* Release_Date
* Film/Movie
* Studio
* Rating
* Runtime

I finally decided to analyze some more data. I got the directors data loaded and determined the 20 best directors.
The above data was analyzed to produce this project's recommendations.


## Results
 
What Genres are the most profitable?
* Animation ,SciFi,Fantasy, Comedy and Family are the top five most profitable genres

<img
  src="images\Genres.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 500px">


Which are the best months to release a movie?
* February seemed to leading with most gross earnings
* July was second, November was third

<img
  src="images\release_date.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 500px">




### Who are the best directors in the game?
* John Andreas Anderson, Robin Pront, David Delhoffen, Scott Armstrong and Brian Peter Falk.

<img
  src="images\directors.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 400px">


### Which competitor studios is leading in the industry?
* PW/D,BV, Sony,WB(NL) are the leading movie studios in terms of numbers and revenue.

<img
  src="images\studio.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 400px">


### Does the ratings of a movie really determine the gross earnings?
* Rating does not affect the gross earnings

<img
  src="images\ratings.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 400px">


### Does the runtime of a movie detemine its' popularity?
* The runtime of a movie can influence its popularity with some audiences preferring shorter films for convinience while others may
prefer longer films for depth and complexity.

<img
  src="images\runtime.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 400px">



## Conclusion

* 'SciFi' ,'Animation' and 'Comedy' genres are more likely to have a higher returns.

* Success of a film is not determinant on the films rating

* The length of a film (Runtime) of a film has impact on its box office performance. The ideal-time is between 90minutes-120 minutes.

* The best month to release a movie is November as it was the second most grossing and the second most in terms of number of releases. However, February seemed to have highest returns.

* Films directed by John Andreas Anderson, Robin Pront, David Delhoffen, Scott Armstrong and Brian Peter Falk produce the highest gross earnings.

* The best competitor studios in the business  are  P/DW , BV, Sony, WB(NL) and Fox respectively.


## Future Considerations
Further analyses could yield additional insights to improve recommendations for Microsoft's studio debut:
* Thorough financial analysis(P&Ls).
* Determine the impact of all crew members.
* Determine the impacts of different combination genres.


## For More Information
Please review the full analysis in the Jupyter Notebook 
For any additional questions, please contact : sheilamulwa22@gmail.com or via linkedin: www.linkedin.com/in/sheila-mulwa
