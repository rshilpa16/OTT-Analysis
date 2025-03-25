# OTT-Analysis-Dashboard

## Problem Statement

This dashboard contains files which helps the OTT of different platforms to understand their customers better. It helps them to know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, and thus they can improve their services by identifying these area. It also lets them to compare the OTT of different platform.

Here, Netflix(584) have least number of show while Amazon prime making highest number of movies (7814) and series(1854)

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file. There are total three csv files with name "Amazon Prime" , "Disney plus" and "Netflix Originals". 
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Button used to navigate the page from one Dashboard to another using "cltr + click" 
- Step 6 : In the report view, under the view tab, theme was selected. 

## Netflix

- Step 7 : Visual filters (Slicers) were added for two fields named "Genre" and "List of shows"
- Step 8 : Four card visuals were added to the canvas, it represents total shows, runtime, IMDB score and English language. 
- Step 9 : Bar chart was also added to the report design area representing the yearly release of the shows
- Step 10: In the report view, under the insert tab, one text box was added to the canvas, mentioning the OTT name
- Step 11: Calculated column was created for show duration by keeping the runtime in four durations as follow- 
           < 30 minutes 
             30-60 minutes (excluded 60 minutes)
             1-2 hour(included 60 minutes)
           > 2 hours 
- Step 12: Using New measures, three measures were created which used in report named as "Total Language", "English" and "%English".


## Amazon Prime

- Step 13: Slicers were added for six fields named "Genre", "List of shows", "About Shows", "List of Director", "Duration" and "View Rating" 
- Step 14: Four card visuals were added to the canvas, first one representing total shows, second and third representing for Movies and series and fourth representing the country.
- Step 15: Pie chart was also added to the report design area representing the rating of the shows.
- Step 16: In the report view, under the insert tab, one text box was added to the canvas, mentioning the OTT name.
- Step 17: Using New measures, five measures were created which used in report named as "Total(type)", "TV Show","%TV Show", "Movies" and "%Movies"


## Disney Hotstar

- Step 18: Visual filters (Slicers) were added for six fields named "Genre", "List of shows", "About Shows", "List of Director"and "Duration". 
- Step 19: Four card visuals were added to the canvas, first one representing total shows, second and third representing for Movies and series and fourth representing the country.
- Step 20: Bar chart was also added to the report design area representing the yearly release of the shows. While creating this visual, field named "type" was also added to the Legends                   
           bucket, thus number of shows are also segregated according the type.
- Step 21: In the report view, under the insert tab, one text box was added to the canvas, mentioning the OTT name.
- Step 22: Using New measures, five measures were created which used in report named as "Disney(TotalType)", "DisneyTV Show","%DTV Show", "DisneyMovie" and "%DMovie"


# Report Snapshot (Power BI DESKTOP)

 ![Screenshot 2025-01-08 193938](https://github.com/user-attachments/assets/91720774-40b7-4888-884b-a66473084caf)
 ![Screenshot 2025-01-08 193956](https://github.com/user-attachments/assets/78fa231d-7b15-4db2-a69c-947f5c8f2dde)
![Screenshot 2025-01-08 194016](https://github.com/user-attachments/assets/3c905ad7-39c8-4e87-87a9-78d29c4e8a3e)

# Insights


A three pages report was created on Power BI Desktop.


Following inferences can be drawn from the dashboard;

### Netflix
 
IMDB Score = 6.27
Highest number of shows release in the year of 2020, i.e. = 183
Total number of shows = 584
English Language shows = 68.66 %

They need to work on there number of shows and languages. If they want more viewers, they need to release more shows in other languages as well. 


### Amazon Prime 

Total Shows = 9684
Movies = 7814 (81%)
Series = 1854(19%)
Total Country = 87
Rating of "13+" is highest in percentage which is about 21.85% which shows that maximum shows are familiar to kids and teenagers. 


### Disney Hotstar

Total Shows = 1450
Movies = 1052(73%)
Series = 398(27%)
Total Country = 90
Highest number of Movies was released in the year of 2019 i.e. 630. But in 2021, it decreases to 192 only. It seems they need to work on it to get more viewers.
Rating of "TV-G" is highest in percentage which is about 21.93% which informs that most of the shows are for all ages.  
