### HealthTVizer: Exploring Health Awareness in Twitter Data through Coordinated Multiple Views
<!-- Please click to watch the overview video. -->

<!-- [![ScreenShot](https://github.com/iDataVisualizationLab/DycomDetector/blob/master/images/play-btn.png)](http://www.myweb.ttu.edu/mdykabir/DycomDetectorIntro.mp4) -->
Online demo:  https://idatavisualizationlab.github.io/HealthTvizer/

Micro-blogging and social media data can help in predicting a variety of events and also able to detect the flow and evolution of the events and incidents like presidential elections and flu spread. Analyzing public user posts and shared information in social media can assist us in measuring various population characteristics, patterns, movements, and as well as the public health conditions. In this paper, we introduce HealthTVizer - a social media analytics tool, for exploring health awareness using Twitter data through interactive and interconnected multiple views. The tools assist a user in achieving a quick summary about the current diseases along with the geographical location on the United States map. 

We processed and analyzed over 57 million tweets and pick the tweets related to the diseases using topic modeling. After that, we categorized the tweets in 21 most frequent and discussed diseases on that time frame. We plot the diseases cloud and stream graph to show the change in the discussion about those diseases. Further, we added several visualization methods to find out valuable insights from the data. 

### HealthTVizer Visualization

HealthTVizer contains coordinated multiple views which highlight different tweet attributes: User ID, geolocation, keywords, time stamp, and the related disease. The following image shows the key features of the HealthTVizer. 

![ScreenShot](https://raw.githubusercontent.com/iDataVisualizationLab/HealthTvizer/master/images/teaser1.png)

The key features of HealthTVizer are:

**Box A: Top user list** 
The top user list represents the users based on the number of tweets about any particular disease type. After clicking on diseases cloud, the list will automatically update with respect to the corresponding disease. On hovering on the user ID or user tweets count bar, a table will pop up displaying the 20 tweets of that particular user.

**Box B: Diseases map** 

The distribution of top 20 users tweets related to all 21 different diseases is depicted in the United States map represent in Box B.  On loading of the application the map shows the user tweets related all the diseases. However, if a viewer clicks on the particular disease from disease cloud the map and user list bar chart will be updated automatically and visualize the related disease tweets locations.  

**Box C: Network of Diseases and Keywords**
Box C, shows the overview network of 20 diseases and top 50 popular keywords from January 6 to January 31, 2017, on Twitter. The thickness of a link indicates the relationships frequency between the diseases and keywords based on the co-location in the same tweets.  

**Box D:** 

**Box E:**

User Stories: 
Cancer: 
![ScreenShot](https://raw.githubusercontent.com/iDataVisualizationLab/HealthTvizer/master/images/cancer.png)

![ScreenShot](https://raw.githubusercontent.com/iDataVisualizationLab/HealthTvizer/master/images/cancerHover.png)

Autism:
![ScreenShot](https://raw.githubusercontent.com/iDataVisualizationLab/HealthTvizer/master/images/autism.png)

AutismSocietySD, Jan 10, San Marcos, CA
7th annual swimming with autism conference. 
@autismparentmag 7th annual swimming with autism conference march 4-5! info registration @Ì¢ï¿½ï¿½ï¿½_ https://t.co/htmiww1aw3


### References
Previous work:  https://github.com/iDataVisualizationLab/RumorViz



