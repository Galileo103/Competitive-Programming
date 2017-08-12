# The-Journey-To-The-Center-Of-The-Data-Science
Maybe it was a dream to study Data Science but it happened, A month ago I started internship at IBM in Machine Learning and Data Science.

We started learn <a href="https://www.ibm.com/us-en/marketplace/spss-modeler">IBM SPSS Modeler</a> from "Introduction to IBM SPSS Modeler And Data Mining (v16)" then "Advanced Data Preparation Using IMB SPSS Modeler (v16)"
I took 3 weeks to finish it, then my instructor decide to solve in <a href="https://www.kaggle.com/">Kaggle</a> Instantly I was happy
but when he showed the problem that we will try to solve it and apply the principles we have learned, I terrified because it not problem 
to train it is business have $1,200,000 Prize Money <a href="https://www.kaggle.com/c/zillow-prize-1"> Zillow’s Home</a>

I finished my day then back to my home and I dreamed of a million.

## Zillow’s Home
I begin read data dictionary of the problem features and do data visualization to know what is the best or complete features, so start to run 3 million records and observed them it take along time and all of processor, after day and half I found that 
<ul>
  <li>bathroomcnt</li>
  <li>bedroomcnt</li>
  <li>Milk</li>
  <li>buildingclasstypeid</li>
  <li>calculatedbathnbr</li>
  <li>finishedsquarefeet12</li>
  <li>fips</li>
  <li>fireplacecnt</li>
  <li>fireplaceflag</li>
  <li>fullbathcnt</li>
  <li>latitude</li>
  <li>longitude</li>
  <li>lotsizesquarefeet</li>
  <li>poolcnt</li>
  <li>pooltypeid7</li>
  <li>propertycountylandusecode</li>
  <li>propertyzoningdesc</li>
  <li>rawcensustractandblock</li>
  <li>regionidcounty</li>
  <li>regionidzip</li>
  <li>roomcnt</li>
  <li>unitcnt</li>
  <li>yearbuilt</li>
  <li>taxvaluedollarcnt</li>
  <li>structuretaxvaluedollarcnt</li>
  <li>landtaxvaluedollarcnt</li>
  <li>taxamount</li>
</ul>
is very important to achieve the target of predict log error, I solved random without anything of thinking only put nodes next to 
other until I reach to complete the missing data with (mean - median - my eye vision) I cant understand anything only put node again and
say I will go to the million.
when we meet in IBM and describe what we do, I understand that I go in the wrong way and never use the target as feature in the module and should build dummy model to measure the improvement must split the data between training and testing (70-30 or 50-50) after the day I back to home and delete my save stream and start with new job

## Zillow’s Home with Dummy Model
I start with dummy and calc the Mean Absolute Error <a href="https://en.wikipedia.org/wiki/Mean_absolute_error">(MAE)</a> and write it as a comment in my stream and start to improve my model by discard so records complete some fields by relations between some feature such as fireplacecnt, fireplaceflag and poolcnt, pooltypeid7 or complete fields by median such as bathroomcnt, bedroomcnt and untcnt
and when I calc the MAE I say "WOW the million will come it's 0.048326036" and make the file submission Go to kaggle  uplode the file wait for the ranking

Surprise "Evaluation Excption Submission must have 3 Millions Records"

I start search and view my file and tables etc after 9 hours I discovered that I must delete all select nodes in my stream it use only when I build my model then I fixed it and make file submit again and upload it and get "0.0651445" MAE and reach to the 1580 in leaderboard it was a great moment in July 
In IBM I told my instructor about where did I get and learn from him some things about data preparation when I back to my home I found new fields such as garagecarcnt, garagetotalsqft and see the garagecarcnt = 0 and garagetotalsqft = 350.000 so here I make garagetotalsqft = 0 and detect that assessmentyear has one value and 99.8% of his value is missing so I ignore it etc.

In my second submit I got "0.0650009" MAE and go to 1361 in leaderboard in the last day in the trial and hope to improve it

## What is the purpose of all those words above?
First motivate you, motivate you and motivate you Its my First Problem in machine learning
Second I work randomly but you should be organize and follow the STAGES Process
<dl>
  <ol>
    <li>
    	<dt>Business Understanding: </dt>
  		<dd>Understand the project objectives and requirements from a business perspective, and then convert this knowledge into a data mining problem definition and a preliminary plan designed to achieve the objectives.</dd>
    </li>
    <li>
    	<dt>Data Understanding: </dt>
  		<dd>Start by collecting data, then get familiar with the data, to identify data quality problems, to discover first insights into the data, or to detect interesting subsets to form hypotheses about hidden information.</dd>
    </li>
    <li>
    	<dt>Data Preparation: </dt>
  		<dd>Includes all activities required to construct the final data set (data that will be fed into the modeling tool) from the initial raw data. Tasks include table, case, and attribute selection as well as transformation and cleaning of data for modeling tools.</dd>
    </li>
    <li>
    	<dt>Modeling: </dt>
  		<dd>Select and apply a variety of modelling techniques, and calibrate tool parameters to optimal values. Typically, there are several techniques for the same data mining problem type. Some techniques have specific requirements on the form of data. Therefore, stepping back to the data preparation phase is often needed.</dd>
    </li>
    <li>
    	<dt>Evaluation: </dt>
  		<dd>Thoroughly evaluate the model, and review the steps executed to construct the model, to be certain it properly achieves the business objectives. Determine if there is some important business issue that has not been sufficiently considered. At the end of this phase, a decision on the use of the data mining results is reached.</dd>
    </li>
    <li>
    	<dt>Deployment: </dt>
  		<dd>Organize and present the results of data mining. Deployment can be as simple as generating a report or as complex as implementing a repeatable data mining process.</dd>
    </li>
  </ol>
  
  
  ## Learn-Data-Science-In-30-Days
  if you follow this I think you will learn the concept of Data Sciences and Machine Learning in only 30 Days by IBM SPSS Modeler
  
