| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


> Important note: this template includes major elements of Part I, but the instructions on Canvas are the authoritative source.  Make sure to read through the assignment page and review the rubric to confirm you have everything you need before submitting.  When done, delete these instructions before submitting.

## Outline 

As someone who has played football for 16 years, concussions and awareness of their effects have always been at the forefront of my mind. Playing offensive and defensive line throughout my career, I experienced—and witnessed—numerous brutal blows to the head, some days worse than others, with Advil often feeling like a necessity. As awareness of chronic traumatic encephalopathy (CTE) grew, particularly around the time the movie Concussion brought the issue to public attention, the importance of understanding concussions and their potentially devastating long-term outcomes became even more personal and urgent for me, especially during my senior year, when I ended up in the hospital after a game due to a concussion I suffered.

Building on this personal experience, this project explores concussion rates and totals across youth, collegiate, and professional football, focusing on trends, risk factors, and long-term implications such as CTE. Using publicly available datasets and journal data, the project will visually convey football’s high concussion rates relative to other sports at the high school and NCAA levels, while examining how these rates vary geographically, over time, and across levels of play.

Next, the scope expands to the NFL. Since concussions and CTE gained widespread attention, the NFL has implemented rule changes aimed at reducing head injuries and making the game safer overall. This project will explore these changes and analyze their impact on concussion totals over the years, highlighting patterns before and after key policy interventions.

Finally, the project examines CTE data, showing the real-life consequences that repeated concussions can have on players’ long-term health. Through visualizations, the goal is to highlight the connection between football and elevated CTE risk, emphasizing that these issues deserve serious attention at every level of play. While the project does not seek to dissuade anyone from playing football, it provides insight into the hidden risks of concussions and encourages awareness and informed decision-making for athletes, coaches, and the broader sports community.



> A project structure that outlines the major elements of your story.  Your Good Charts text talks about story structure in Chapter 8 - you should describe what you hope to achieve.  Make sure the outline is detailed enough that we can see how you anticipate your story unfolding.  You can incorporate your Story Arc from the in-class exercise, along with your user stories and one sentence summary, to make the topic even clearer. 

# Project Structure
One Sentence Summary: This project visually explores concussion trends across youth, collegiate, and professional football, highlighting the risk, long-term consequences, and the impact of rule changes over time.  
1. Personal Connection
   -I want to open similarly to how I opened this. I want to focus on my experience playing football for 16 years, go deep with my experiences, including headaches during practice, and my own concussion story.
   -This will allow for immediate ethos, as I have played football and understand how brutal concussions can be. 
2. Youth and High School Trends
   -Present concussion rates by sport, highlighting how dominant football is in this regard.
   -Use map visualizations to convey concussion rates by state, and if anything jumps out, I hope to do further research towards rules as to why this may be the case
   -This will establish football as a leader in concussions, and possibly highlight rules that have worked for youth sports in this regard.
   -Also, highlight how we do focus on football in this project, but this can happen to anybody playing any sport. 
   3. NCAA Data and Trends
      -Show NCAA concussion rates by sport, and compare these trends to high school data.
      -Show patterns seen in youth sports carrying over to college, and highlighting any potential risk escalations.
      4. NFL Trends and Rule Changes
         -Present NFL concussion totals per season, noting game and practice trends, along with rule changes throughout the years
         -Normalize this data to compare concussion rates to the NCAA and high school data
         -This will establish the continued high concussion rate in football, but also how rule changes have caused these concussion rates and totals to decline
5. CTE and long-term implications
   -Introduce
         

## Initial sketches
> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  

Text here...

# The data
> A couple of paragraphs that document your data source(s), and an explanation of how you plan on using your data. 

Text here...
For this project, I am using multiple datasets to explore concussion rates across high school, NCAA, and NFL football, along with additional data examining CTE and its significance. I have a goal of identifying trends in sports with the highest concussion rates and exploring further through the NCAA and NFL concussion data. 

Starting with high school concussion data, this data comes from the Youth Risk Behavior Surveillance System (YRBSS) and related CDC/NSC reports. This dataset provides concussion rates by state, sport, and gender/demographic. I will use this data to create a map visualization showing how concussion rates vary geographically across U.S. states for youth sports. I will additionally display the highest concussion rates across sports in ages 10-18 using data provided by a scholarly article called "Concussion in high school sports: findings from injury
surveillance".

After establishing football as the leading cause of concussions through the data, I will be looking at NCAA data to see if the trends fall similarly. First, I will start by examining concussion trends by collegiate sport, similar to what we did with youth/high school sports. For this part, I have two data sets, both from the Journal of Athletic Training. The first one, titled "Epidemiology of Concussions in National Collegiate Athletic Association (NCAA) Sports", examines data from 2011-2015, examining concussion rates by sports. The second article is called "Epidemiology of Concussions in National Collegiate Athletic Association (NCAA) Sports", so the same title and a continuation of the same study, but from 2015 to 2019. I hope to pull the data from these two journals and see how trends across sports have changed in terms of concussion rates trhoughout the years. 

One limitation of NCAA concussion data is that the data is collected by a private organization, and therefore, public data is not accessible. In order to account for this, I decided to put an extra focus on the NFL. 

For the NFL, the data is provided by the NFL, from 2015 to 2024, as 2015 is when the NFL started collecting Data. In trying to find earlier data, it is nearly impossible, as earlier data is usually heavily undercounted. This data includes concussions per season for each year. An additional dataset provided via GitHub by scraping data from pro-football-reference allows for further breakdown by Team, players, and position. 

CTE DATA



> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your GitHub repository, Box account, or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available, please talk to me first. 

| Name | URL | Description |
CDC Youth Concussion Date |  https://yrbs-explorer.services.cdc.gov/#/graphs?questionCode=H79&topicCode=C06&location=XX&year=2023   | Includes data that we can pull into CVS files through an easy click for the entire US and further broken down by US States|

|Sport,Overall_Cases,Overall_Exposur  |  Provided in this Github Repository   |   Breakdown of Conussion rates by High School|

|   NCAA Sports Data  2011-2015 |  https://pmc.ncbi.nlm.nih.gov/articles/PMC5384815/   |   The link provides the article, from which data will be easily pulled from the table and pushed into CSV format using AI tools for easier conversion |

|NCAA Sports Data 2015-2019| https://pubmed.ncbi.nlm.nih.gov/34280281/| The link, just like the above data set, is provided in the article via a table, and data will be pulled using AI tools|

|NFL Concussion Data| Data is provided by the NFL, https://www.nfl.com/playerhealthandsafety/health-and-wellness/injury-data/injury-data, but a Kaggle dataset has already converted this into a CSV, https://www.kaggle.com/datasets/ajvazquez/nfl-concussions-from-2015-2023|. This data examines concussion rates throughout the NFL season, breaking it down by Preseason, Regular season, games, and practice|

|NFL Concussion Data via scrapping| Guthub link, https://github.com/jchernak96/NFL-Injury-Data-PFR-/tree/master/Data| Guthub provides data sets of concussion data through scrapping of Pro-football-refernce|


# Method and medium
> In a few sentences, you should document how you plan on completing your final project. 

Text here...

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._
