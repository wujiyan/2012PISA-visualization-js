# 2012PISA-visualization-js

##Summary
The Programme for International Student Assessment (PISA) is a triennial international survey which aims to evaluate education systems worldwide by testing the skills and knowledge of 15-year-old students. The data I used was assessed in 2012, having investigated around 510000 students in 65 economies, regarding reading, science and math ability. In this project, I made several web pages to find out some features from the math ranking and further investigated the possible reasons that resulted in the feature. 

##Design
###Logic and charts
1. I am curious about the math ranking across countries. So I decided to draw a bar chart to show each economy's average math scores and sort them.After cleaning the data, I made the bar chart and the sort function. I found out that of the 7 countries with the highest math scores, 6 are in Chinese cultural circle, Shanghai, Singapore, Hong Kong, Taiwan, Korea, Macao and Japan. 
2. I wonder why economies in Chinese cultural did far better than any others in math so that they took up 6 seats of the highest 7 ones. I looked through the variable dictionary, and guess that student's difference in math behavior should be a possible reason. So I picked up four factors that seemed more likely to explain the feature from the math behavior group and cleaned the data again into the second dataset. Drawing pie charts showing percentage is a good way to observe their math performance. So I write the function to draw pie charts and linked the bar chart to the pie chart so that we can deeply study students from one economy's math performance by clicking the bar representing the country. 
3. Besides students' subjectivity, I think more objective factors should be helpful to improve math performance in those countries. Since the PISA data includes reading and science performance, I assumed that reading and science ability could have positive influences on math performance. So I created the second web page trying to show reading, math and science ranking of each country and the comparisons among them. A line chart could better show changes among data, so I drew the line chart which could clearly displayed that economies with higher math ranking also enjoy higher reading and science rankings. 
4. In order to study more deeply, I tried to observe gender differences of performances in math, reading and science in the six economies, respectively. Drawing bar charts for each economy was enough to display the feature. I found out that generally in the 6 eonomies, male students did better in both math and science and female students did better in reading. So I think science ability positively influences math performance more than reading ability does. Plus, I added two buttons that could be used to click through by users to see ranking difference and gender difference. 

###Elements
1. Tooltip. I created tooltips in order to pop up information box when hovering the mouse over lines, bars and pies.
2. Highlight. I made the bar chart on first page and line chart on the second page highlighted by changing their colors when hovering your mouse, so that we could clearly know what bars or lines or texts are we selecting. 
3. Description words. The description words are on the top of each page so that users could read them firstly and better observe the data. 
4. Buttons. Buttons are placed in the middle of the page in order to catch user's eyes so as to induce users to click them.

###Aesthetics
1. I selected orange and blue as the basic colors for pages since they contrast strongly to each other. 
2. In order to find a country that we are interested in, bar charts on the first page have been grouped by continent and colored by blue of different level. 
3. All buttons will change their color if we hovor mouse over them so that we could know the mouse is over this button.
4. Cursor will shift into a pointer when hovering over a element if it can be clicked.

##Feedbacks
Yan Yu: You would better add some pie charts to show outcomes of questionary. That would be better for us to learn more from students behaviors on math. 

As a response to his suggestion, I picked up four factors and cleaned the dataset again. I drew pie charts and linked the pie charts to bar chart. 

Teng Zhongwei: First of all, I do not understand what the science and reading ranking showed in the formation box on the second page mean. Secondly, the content is too disperse. You would better merge the second and third page into one page. 

As a response to his suggestions, I add more descriptive words to explain what the values mean. Meanwhile, I merged the second and third pages into one. 

Tomkaka: It is hard for me observe countries in the bar chart. Maybe you should colored bars by country's continent so that I can observe them without hovering mouse. Then,if you clearly represent the selected bar with a different contrasting color than the blue which is for all the bars then it will be much clear. Next, I don't know that I could click bars to show pie charts. Besides, some color selections should be adjusted in order to make it genderer, and the axis tick marks are merging in between each other and hence it's not clear.

As a response to his suggestion, I colored each economy on the first page by different colors so that we could clearly see Asian ecocnomies ranked the highest. I changed a different contrasting color than the blue. I add a text "Click me to find more" with red in the information box to notify users to click bars. I also changed tick numbers and made some adjustments to color selection to make it look better.

##Resource
http://bl.ocks.org/mbostock/3885705
http://www.d3noob.org/2013/02/update-d3js-data-dynamically-button.html
http://stackoverflow.com/questions/18057917/adding-label-on-a-d3-bar-chart
http://plnkr.co/edit/JpVkqaZ1AmFdBbOMwMup?p=preview
http://www.oxxostudio.tw/articles/201411/svg-d3-04-axis.html
http://canvasjs.com/html5-javascript-pie-chart/
https://bl.ocks.org/mbostock/3883245
http://zeroviscosity.com/d3-js-step-by-step/step-1-a-basic-pie-chart
http://www.d3noob.org/2013/01/adding-title-to-your-d3js-graph.html
https://chartio.com/resources/tutorials/how-to-show-data-on-mouseover-in-d3js
http://c3js.org/examples.html

