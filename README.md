# Kickstarter Funding for "Theater Projects" & "Play Projects" Analysis

## Overview 
1. Visualization of Theater Projects Based by Launch Date
   * Table Counts of Successful, Failed, and Canceled Kickstarters by Month
   * Chart of Theater Outcomes vs. Launch Dates
2. Visualization of Plays' Kickstarters Based on Funding Goals
   * Table Counts of Successful, Failed, and Canceled Kickstarters by Funding Range
   * Chart of Play Outcomes vs. Goal

### Purpose
Kickstarters are a common way to generate funding for numerous types of events. The client wants to generate funding for a play. Using data from around the world, this analysis provides insight into several statistics related to theater and its subcategory, plays, kickstarters. With this analysis, the client can get a clearer picture of the necessary funding goals and achieve the desired outcome to mount a successful kickstarter campaign for their play.

## Analysis and Challenges
The analysis loooks at every type of kickstarter categorized under the category "theater", which encompasses "plays" and other kickstarters in the realm of "theater", and compared the outcomes of successful, failed, and canceled "theater" kickstarters based on the counts of each versus the month the kickstarter was initiated. Additionally, this analysis contains info regarding funding goals for plays specifically, and whether or not their outcomes were successful, failed, or canceled. 

<b>"Theater" Outcomes Based on Launch Date</b> <p>
<img src = "https://user-images.githubusercontent.com/89168119/157936378-925dbeb4-b31f-4981-b0f6-60bd92cc0443.png" width = "450"></p>


<b>"Plays" Outcomes Based on Goal</b> 
<p>
<img src = "https://user-images.githubusercontent.com/89168119/157950017-4f70b767-4950-43f3-ac5e-5344d44a0853.png" width = "600"> </p>

-	The "countifs" function provided much of the work here to divy up the data amongst the 150+ theater kickstarter types.
	

## Analysis of Outcomes Based on Launch Date
The month of May contained the most successful theater kickstarters with June following second. So, it would be wise for them to launch their kickstarter sometime around those two months. Additionally, it seems as though December has a nearly equal amount of successful and failed kickstarters. Following in line with that trend, overall, there is about a 50/50 chance that a kickstarter in the theater category will be successful. 

### Analysis of Outcomes Based on Goals

Most plays seem to do fairly well if their funding goals are below $5k, as these two categories have the <b>most</b> kickstarters and <i>also</i> the <b><i>highest</b></i> percentage of successful outcomes. Very few ki4ckstarts go above $20,000, so it would be best to keep the kickstarter below that goal. Additionally, very few kickstarters have a success rate above 50% past $20,000; besides kickstarters that are between $35k-45k. Given that the plays in that goal range only account for 6 plays out of over a 1,000; Those plays could simply be outliers and achieved such a funding goal due to numerous outside reasons. 

### Results

My two main conclusions about the outcomes based on launch date sheet is that May contains the most successful theater kickstarters and that there is a roughly 50/50 chance that a kickstarter in the theater category will be successful. For the outcomes based on goals sheet, most kickstarters achieve their funding goals if their goal is below $5k, as those have the highest percentage of successful outcomes--moreover, not many kickstarters go above $20k. 
	It would be nice to see outcomes _and_ percentages of plays_by_ month, because counts and percentages overall don't give you a good enough picture. Looking at just theater overall by month versus their outcomes and their percentages doesn't exactly help the creator line up their kickstarter goal by months. 
	A graph of the percentages and outcomes of plays by month would be a great start. Additionally, we could create more graphs based in the US to get a more solid picture of the way kickstarters pan out in the United States. 
