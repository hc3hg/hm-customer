# Team-72
 Team 72's group project GitHub repository for MGT 6203 (Canvas) Spring of 2023 semester.

# Predicting H&M Customer Value


<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> :cloud: About The Project</h2>

<p align="justify"> 
  Retailers spend huge amounts of time and effort to figure out how to get maximum value out of their customers. From loyalty programs to diverse product lines and more, there are many factors that affect how much customers spend and how often they shop at stores like H&M. 

</p> <p align="justify"> 
The purpose of this analysis is to understand the future value of a H&M customer (as measured in $s spent OR quantity purchased with H&M). Our objective is to predict how much (in $s OR quantity) a current customer will purchase with H&M in the future based on their current attributes, such as demographic information and current purchasing behavior.
</p>
<p align="justify"> 
To do so, we built several linear regression model to analyze the relationship between customer attributes and their future purchasing amounts, followed by a supplementary logistic regression to predict high-volume and non-high-volume purchasers.
</p>
<p align="justify"> 
The results of our analysis can be used by companies like H&M to focus their advertising, identify high-value customers, decide product offerings and ultimately increase their ROI.


</p>


<!-- OVERVIEW -->
<h2 id="overview"> 📁 The Data</h2>

<p align="justify"> 
  The H&M data, sourced from Kaggle, consists of multiple tables relating to H&M customers. There is a “customers” data table with demographic information, an “ articles” table detailing which articles of clothing are purchased by each customer, and a “transactions” table with information about customers’ purchases. These tables have been merged for use in this analysis. 
</p> <p align="justify"> 
We chose to segment the data into two time periods of equal length, Sep 2018 - Feb 2019 (t1) and Sep 2019 - Feb 2020 (t2), for the purposes of prediction.

</p>


<!-- DIRECTORY INFORMATION -->
<h2 id="project-files-description"> :floppy_disk: Directory Information </h2>
The organization of this repository is quite simple. Our code is stored in a single R markdown file called “Group72.rmd” in the Final Code folder. Links to our dataset are stored in a pdf file called "Team72_data_links.pdf" in the Data folder. The other assets of our project are stored in their respective directories. 


<!-- GETTING STARTED -->
<h2 id="getting-started"> :pencil: Getting Started</h2>

<p>
This project requires the following packages to be installed: 
</p><p>
[tidyverse]
 </p><p>
[dplyr]
 </p><p>
[lubridate]
 </p><p>
[digest]
 </p><p>
[zoo]
 </p><p>
[Metrics]
 </p><p>
[caret]

</p>


<!-- CONTRIBUTORS -->
<h2 id="credits"> :hand: Contributors</h2>


<p>Natania Christopher </p>
<p> Roopam Chakrabarty </p>
<p>Helen Cunningham </p>
<p>Janine Mis </p>

