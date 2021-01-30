## CS234 - Data, Analytics, and Visualization

## Final Project - Women's Work - A closer look at Wellesley alums

### By Briana Vigil, Panya Tang and Andrea Mock

This Github repository contains all the code used to investigate the paths Wellesley alums took after graduation, with a focus on Computer Science 
majors and alumns currently working in the tech field. 

For data transparency purposes we have shared our code here. Some lines may be commented out to protect the privacy of the individuals we collected data on.

The corresponding blog post that describes our findings can be found here: 
https://bvigil-28946.medium.com/wellesley-at-work-an-analytical-overview-of-wellesleys-alums-after-wellesley-67061aa63bbb 

## This GitHub repository contains the following files: 

1.	Linkedin Scraper: contains the code used to scrape the information for Wellesley CS alums

2.	Hive scraper: Code to scrape information from Wellesley alums on the Hive

3.	Linkedin_Data_Cleaning: This notebook, using the data collected from Linkedin on Wellesley CS alums does some preliminary cleaning of the data. It creates a pickle objects titled education and another one titled jobs.csv. One containing education information and the other just entries from our dataset pertaining to job information. 

4.	jobs_exploration: preliminary exploration of how long and what titles Wellesley alums hold 

5.	Education Data Cleaning: This notebook is dedicated to cleaning the data that is relevant to each alums education (using the data in the education pickle)

6.	merging_datasets: merges the data from Linkedin and the Wellesley Hive. Also includes the cleaning of the Wellesley Hive data.

7.	Alum_skills: Explores the skills and words Wellesley alums use in their Linkedin profiles and analyzes the distribution of these. 

8.	Alum_Locations: Explores and visualizes the current location of all alums in our dataset.

9.	Alum_majors: Analyzes the majors Wellesley alums choose and the combination of majors.

10. Alum positions: Investigates the positions that Wellesley alums hold at their current workplace

11. Top 50 Companies: Determines what the 50 top companies Wellesley alums worked at 

12. Final Glassdoor: Notebook that contains code to scrape data from glassdoor for relevant companies Wellesley alums worked at

13. Parsing the Wellesley Hive: Notebook containing code to scrape data from the Wellesley Hive, a copy of Linkedin for Wellesley students and alums

14. Cleaning_Wellesley_Hive: Cleans data collected from the Wellesley Hive

