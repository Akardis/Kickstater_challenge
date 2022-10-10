# Kickstater_challenge
challenge work for Kickstarter data


# Kickstarting with Excel

## Overview of Project
  Analyis the data and show cases skills learned during the modules. Help Louise find the best campaign strategies for rasing money for her play. 
### Purpose
  Utilize skills learned during the week in the course and on our own through the modules. Utilize the tools within excel to analyis the dat about kickstarting campaigns. Practice making table and graphs for data sets the were filtered out using tools and skills learned form classs. 

## Analysis and Challenges
  Had some trouble with picking the right fields and placements for PivotTables. Had to try a couple times to get the right columns and rows. Once the correct ones were picjed and placed correctly using the PivotTables were a great help to see the data. Being able to change the table to produce different graphs really helped me see what was going on in the data. It was helpful to changes filters and other perammeters to see how those impacted campaigns successfulness or not. 

### Analysis of Outcomes Based on Launch Date
  The best time to lauch a theater play is at the end of April and the start of May. That is where the biggest gap between failed and successful plays were launched. Outside of that window the launch date had a negative affect. After May the sucess rate drops and finishes the year almost the same as those that failed. Launching at the end of the year has almost the same chance of failed as it does to succeed. 

### Analysis of Outcomes Based on Goals
  The percentage of successful campaigns went down as the goal went up. When goal was under $15,000 more campaigns for successful than not. There was small bump between $35,000 and $40,000 were campaigns were once agian more succesful than they were not. As the goal for donations gets higher more campaigns struggled causeing more to fail than succeed. Running a campaign and using this as a model shows that hitting your goal for donations does not factor into being a succesful campaign. It is important to have donations, but as the chart shows outcomes do not favor those who focus on high donation goals. 

### Challenges and Difficulties Encountered
  I had some trouble with the COUNTIFS() function. I was having trouble writing the code in the right order for the ranges. At first it was also a litte unclear which coloumn from the orginal data set should go first. The intrustions made it seem that I should use the outcomes column first. I was able to firgure out that I needed the goal column first for the number values. =COUNTIFS(Kickstarter!$D:$D,">=5000",Kickstarter!$F:$F,"successful",Kickstarter!$D:$D,"<=9999",Kickstarter!$R:$R,"plays")
  
  One other minor issue I ran into a few times was not clearing filters before comtinuing on to the step/part. There were a few times that not clearing the filters set me back a few steps and I had to find my error. Which was usaually not clearing filters. 
  
  Not a difficulty, but could have been was knowing short keys on the keyboard. Going ovber a few in class helped save tons of times and engery when copying code and large columns. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  The best time to launch a theater play is late April begining of May. That is when the most successful theater plays launch. The worst time to launch is at the end of the year. Theater launches then for succesful and failed are nearly the same, with successful ones barely beating out failed. 

- What can you conclude about the Outcomes based on Goals?
  Donation goals is not the best metric to use as the base for your campaign. More campigns that reached goal failed than succeeded. Campaigns should focus on other areas like launch date over donation goals. 

- What are some limitations of this dataset?
  The data set only goes back to 2009. That gives only one decade of data. Being able to ago back further may give better insight into what helps campaigns succeed versus fail. 

- What are some other possible tables and/or graphs that we could create?
  Create a line graph to showcase how donations are given throughout the year. This mioght give insight into when its best to push hard on donations and when not to. Since the goals outcome shows that reaching donation goal doesnt mean you succeed it might be helpful to seen when donation koostly come in. A graph to show how much is being donated could help restructure the goals so that they are more reasonable. 
