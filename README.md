# T20_2022_players_analysis

## Problem statement 

We are going to have a Cricket match with folks from other planet so we want to Find top 11 cricket players from earth for that we analysed players based on T20 World Cup 2022.

This project so good with a lot of learning

### 1. Web Scrapping

1. Learned web scrapping, used beautiful soup and a selenium
2. wrote code for scrapping all matches
3. wrote code for scrapping all batting summary and bowling summary from all matches
4. wrote code for fetching players profiles this a bit challenging as all data wasn't in a single table, also need to scrap image and there is a problem in image scrapping there some websites who uses lazy loading that means while whole website is laoding they put random image with very small size so if you scrap data using beautifulsoup you will get those lazy images so i used selenium is like browser in terminal, so i opend that website through it, and waited for laoding (10 sec) then scrapped data and images from it took near 2hr time to run whole program and scarp data although in between code breaks many times and i have to debug it.
5. finally all data scrapped got all 4 csv files (matches, batting summary, bowling summary, profile ).

### 2. Data Transformation and cleaning

1. Removed depulicates row from all files
2. Removed extra charcaters from coloumns
3. Trimmed the columns
4. Found out that there are some duplicates row in profiles csv due to lazy images so have to delete them also there were some columns got wrong data due to change in profile section of website which i missed while writing the scrapping code for profile
5. so used profile file provided by codebasics to correct mine.

### 3. Dashboarding

1. Dashboarding of this project was beautiful and functional which taught me alot, I used buttons, tooltip, learned how to navigate through pages using buttons, it is like my intro to so many things that powerBI can do still there is lot to know and lot to learn which i will learn by doing such projects slowly.
2. Below is Final Dashboard, created button to navigate through different pages, this page is for power hitters showing some metrices of power hitters

   ![1705089779916](image/README/1705089779916.png)
4. In image below i have shown that if you hower over any player name a window will appear showing player's profile

![1705089721071](image/README/1705089721071.png)


4. Below it Final 11 page where final players are selected in left side there is list of all players so can change Final 11 if you want

![1705089562532](image/README/1705089562532.png)
