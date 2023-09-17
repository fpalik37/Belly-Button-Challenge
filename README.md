# Belly-Button-Challenge

## Overview
My foray into Java was one big biodiverse belly button bug bash (as in ‘party’, not scripting 😉).  In particular, for the Belly-Button-Challenge (Module 14), I built an interactive dashboard to explore a given “Belly Button Biodiversity” dataset. Yep, you heard/read me right– the data is literally a catalog of microbes that colonize human navels :o!, which can be found on the following site (in case you want to see for yourself):
	http://robdunnlab.com/projects/belly-button-biodiversity/
The contents of this repository include the following artifacts (i.e., the fruits of my belly-button-challenge labor):
1)	app.js – the main java script.
2)	index.html –  the html page itself 😊.
3)	samples.json – the data for which the analytic charts were built.
4)	GUI_Image_Belly_Button_Biodiversity_Dashboard.png – a lovely png image of the colorful dashboard itself, included here specifically for the reader/grader’s convenience 😊.
   
## Programmatic Highlights
I offer a few newly-learned programmatic elements.  These are significant to me, especially since I do not recall any of them from the Java class of my Computer Science curriculum -  25 years back :o.  Indeed, this stuff ain’t your mamma’s ‘cup o’ joe’ :

•	The D3 JSON library is essential.  This is a powerful visualization library used to create interactive data dashboards within a browser environment, and can be found via the following URL: https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json .

•	Specifically, I used D3 for basic document object model (DOM) manipulation and event handling.  The DOM is dynamically manipulated through events, such as chart interaction, dropdown and click events.

•	An “event” is an action triggered by the user or the browser.  JavaScript listens for the “event” to then execute the code (i.e., interact with the HTML).

•	I implemented JavaScript control flow in the form of functions and loops.

•	I created Javescript objects. Note ‘objects’ are collections of properties.  ‘Properties’ are key-value relationships (or ‘pairs’).

•	I used plotly’s layout objects to customize the appearance of charts and menus, adding labels and hover text.

•	I employed the arrow function (=>).  The arrow function provides an alternative way to write functions, allowing for shorter, more concise, syntax.

•	I utilized the filter method. Note, the filter method creates an array with elements that pass a test provided as a function.

## Dynamic Dashboard Design Details
My colorful, and dynamically interactive dashboard includes:

•	Sample metadata of individual demographic information in the form of a display box, showing the bacterium OTU ID, the individual’s ethnicity, gender, age, location, belly button type :o, and wash frequency (yikes!).  There’s a selector window which allows the user to change the ID, upon which the corresponding demographic details will change.  _Thought- considering that we are looking at their belly-button bugs, dare I say this could be a breach of PII ?, or in the least, clearly TMI_ :p.

•	A bar chart showing the top 10 cultures (OTUs).

•	A colorful bubble chart, my personal favorite– the bubbles representing individual samples, the colors for distinct OTU IDs.  As a data analyst, I appreciate the layered dimensionality of this chart in that the bubble size shows the proportionality of 
population size relative to the other samples – cool!

•	Both bubble and bar charts have a ‘hover-over’ capacity – giving the full scientific nomenclature and ID of each OTU displayed.

## Conclusion
In all, the finished dashboard illustrates the fact that surprisingly, only a small handful of microbial species (also called operational taxonomic units ( now say that five times fast 😉), or more concisely OTUs), were present in more than 70% of people, while the rest were rare – who knew!!!
Time did not allow for the ‘advanced challenge’ – yet, I am planning to go back and put in that nifty ‘Belly Button Wash Frequency’ dial.  Since java is in my professional near-future, I plan to do so when things ‘dial back down’.  _And, hey, what could be more intriguing than analytics focused specifically on ‘belly button hygiene’??_ ☹. 

## Acknowledgments
This effort would not be possible without the guidance of esteemed professor Alexandria Kalika and the infinite encouragement, patience, and expertise of data analytics tutor Bethany Lindberg 😊.
