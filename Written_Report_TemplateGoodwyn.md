# Kickstarting with Excel : Theater & Kickstarter Analyses

## Overview of Project
1. Visualization of Theater Projects Based by Launch Date
   * Table Counts of Successful, Failed, and Canceled Kickstarters by Month
   * Chart of Theater Outcomes vs. Launch Dates
2. Visualization of Plays' Kickstarters Based on Funding Goals
   * Table Counts of Successful, Failed, and Canceled Kickstarters by Funding Range
   * Chart of Play Outcomes vs. Goal

### Purpose
	Kickstarters are a common way to generate funding for numerous types of events. Our client wants to generate funding for a play. Using data from around the world, this analysis provides insight into several statistics related to theater and its subcategory, plays, kickstarters. With this analysis, the data can help the client get a clearer picture of the outcomes and necessary funding goals to mount a successful kickstarter campaign for their play. 

## Analysis and Challenges
	This analysis looked at every type of kickstarter categorized under the category theater, which encompasses plays and other kickstarters under the realm of theater, and compared the outcomes of successful, failed, and canceled theater kickstarters based on their counts versus the month the kickstarter was initiated. Additionally, this analysis contains info regarding funding goals for plays specifically, and whether or not their outcomes were successful, failed, or canceled. 

[Theater Outcomes Based on Launch Date](https://github.com/lawrencegoodwyn/kickstarter-analysis/blob/33ab026d7bdfafa9725b58a31429d666c74fbc50/Screen%20Shot%202021-09-01%20at%203.05.08%20PM.png)

[Outcomes Based on Goal](https://github.com/lawrencegoodwyn/kickstarter-analysis/blob/33ab026d7bdfafa9725b58a31429d666c74fbc50/Screen%20Shot%202021-09-01%20at%203.05.22%20PM.png)


	Some of the challenges that occurred when dealing with the data were an awareness of what filters were in place while analyzing the dat, using the necessary and correct amount of criteria for the "countifs" function, and an awareness as to the spelling of words contained in the data. 
	To overcome these challenges, I simply kept tweaking the data until I was able to get an end result that looked similar to the information provided to me for reference. I think that the formula used, prudent filtering, and spelling are all super important for me and will be quite necessary for me to be cognizant of in the future and to stay aware of for future projects. Especially because I was not necessarily encountering syntax errors, but mainly the data was not returning the analysis I I was looking for.

### Analysis of Outcomes Based on Launch Date

	May contained the most successful theater kickstarters with June following closely behind. So, it would be wise for Louise to launch her kickstarter sometime around those two months. Additionally, it seems as though December has a nearly equal amount of successful and failed kickstarters. Following in line with that trend, overall, there is about a 50/50 chance that a kickstarter in the theater category will be successful. 

### Analysis of Outcomes Based on Goals

	Most plays seem to do fairly well if their funding goals are below $5k, as these two categories have the most kickstarters and also the highest percentage of successful outcomes. Very few ki4ckstarts go above $20,000, so it would be best to keep her kickstarted below that goal. Additionally, very few kickstarts have a success rate above 50% past $20,000; besides kickstarters that are between $35k-45k. Given that the plays in that goal range only account for 6 plays out of over a 1,000; Those plays could simply be outliers and achieved such a funding goal due to numerous outside reasons. 

### Challenges and Difficulties Encountered
	The largest challenge presented from this challenge, for me, stemmed from being aware of what exactly I was aiming to analyze. For example, my chart for "Outcomes Based on Goals" went through a lot of tweaking before it looked like the one provided. The first time, I was analyzing the amount pledged, then I was not using "less than or equal to" in my "countifs" functions--so realizing and changing all of that took some time. However, it did provide a learning opportunity for me to simultaneously edit multiple functions. Even though I was able to get the analysis correct eventually, it just shows me that I would not be able to complete the challenge without the guidelines in place so I should always aim to make sure that I am using my functions thoroughly and accurately when performing an analysis. 

## Results

	My two main conclusions about the outcomes based on launch date sheet is that May contains the most successful theater kickstarters and that there is a roughly 50/50 chance that a kickstarter in the theater category will be successful. For the outcomes based on goals sheet, most kickstarters achieve their funding goals if their goal is below $5k, as those have the highest percentage of successful outcomes--moreover, not many kickstarters go above $20k. 
	It would be nice to see outcomes _and_ percentages of plays _by_ month, because counts and percentages overall don't give you a good enough picture. Looking at just theater overall by month versus their outcomes and their percentages doesn't exactly help the creator line up their kickstarter goal by months. 
	A graph of the percentages and outcomes of plays by month would be a great start. Additionally, we could create more graphs based in the US to get a more solid picture of the way kickstarters pan out in the United States. 

