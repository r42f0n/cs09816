java c
Problem Set One Notes
Hello! As promised, I am forwarding a few pointers and notes to you. By now, you
should have read and reread the chapter from given to you and posted in the E-Reserve section of the courses Blackboard. It can be difficult to follow however it is super important that you read
and reread. Noteworthy is that time series forecasting is perhaps one of the most basic and yet compatible forms of forecasting (or predicting) future needs. Noteworthy is that we can
differentiate forecasting software from systems that are utilized in forecasting. If you are interested in learning more, please visit: https://ibf.org/ .
Time Series Forecasting
Keeping in mind that forecasting is defined as a process of predicting future events based on past and present data, time series forecasting uses time stamped or “ordinal” data points.
These may include years, months, quarters, weeks, days etc. This method utilizes several factors to produce a forecast. These might include trend or data set trend. Seasonal effect, seasonality or a pattern that occurs regularly and is repeatable in some way. In addition, random error is
included and must be accounted for in some way. This is also known as data noise that effects the forecasts accuracy. Multiple types of models are utilized in time series forecasting.
Among these models include autoregressive, moving average, autoregressive moving
average, autoregressive integrated moving average, seasonal autoregressive models, vector
autoregression and vector error correction models. While these models differ you can learn more about each by visiting: https://vitalflux.com/different-types-of-time-series-forecasting-models/ .  However, for the purposes of this problem set, we only need to understand that we will use a
trend and seasonality corrected model (see page 202 of the posted chapter). It is highly important that you understand the role of forecasting given, be able to identify the components of a demand
forecast, the use of historical data and analyze the demand forecast to estimate forecast error (see page 204 of the posted chapter). To begin any forecast such as the plastic bead issue at Specialty  Packaging Corporation (Starting on Page 207 of the posted chapter) we must understand the
steps.
In this problem set, you must estimate the demand for the Black Plastic Containers.
Recommended steps include the notion that you should review the data presented. This includes the year, the quarter and the demand (in thousands) for the Black Plastic Containers. The
assignment is: “Consider the information and data presented in the e-reserve case study (located on the left-hand side navigation on Blackboard under e-Reserve Items) “Specialty Packaging
Corporation” (pages 207-208 in scanned document).  In the case study, “Julie” is asked to select the appropriate forecasting method for the two types of containers and use that method to
forecast demand for years 6-8.  代 写Problem Set One Notes Time Series ForecastingHaskell
代做程序编程语言 For this assignment, assume that Julie chooses to implement a time series model with level, trend, and seasonal components.” You must … .
“Create an Excel spreadsheet that fits a time series model (with level, trend, and seasonal components) for the black plastic containers. Include calculations necessary to determine
forecast margin of uncertainty.   Use your models to forecast future demand (for Years 6-8) for the black plastic container, including a margin of uncertainty.   Assume that forecast errors are  normally distributed.  The assessment of your work will include the accuracy as well as the clarity of the spreadsheet (e.g., clear labels, good alignment, easy to understand, etc.).”Based on this you as a seasoned and educated business forecaster must produce a clear forecast that also recommends in written text what you have done and how many of the black  plastic things must be produced for years 6, 7 and 8.
Steps Needed
1 - Review the data. Is it ordinal? Is it ordered?
2- Create a spread sheet by column. Column A Year, B quarter, C demand (black plastic, in thousands of pounds).
3- You will need to create an entry record number (index number) it is suggested that you insert this between column C and D. See figure 1.

Year

Quarter

IndexBlack Plastic Demand ('000 lbs)
1
I
1
2250

II
2
1737

III
3
2412

IV
4
7269
2
I
5
3514

II
6
2143

III
7
3459

IV
8
7056
3
I
9
4120

II
10
2766

III
11
2556

IV
12
8253
4
I
13
5491

II
14
4382

III
15
4315

IV
16
12035
5
I
17
5648

II
18
3696

III
19
4843

IV
20
13097




Figure 1
4- You will need to create a column to DE-seasonalize the data. In order to accomplish    this, we take the demand for Year 1 Quarter 1 + 2 TIMES the SUM of Year 1 Quarter 2, Year 1  Quarter 3 and Year 1 Quarter 4 AND ADD to Year 2 Quarter 1 THEN divide by 8. Excel would be something like =(D2+2*SUM(D3:D5)+D6)/8 all depending on the cell relationships. See
figure 2. This could be correct! Is It?

IndexBlack Plastic Demand ('000 lbs)

De-seasonalize
1
2250

2
1737

3
2412
3575
4
7269
3784
5
3514
3965
6
2143
4070
7
3459
4119
8
7056
4272
9
4120
4237
10
2766
4274
11
2556
4595
12
8253
4969
13
5491
5390
14
4382
6083
15
4315
6575
16
12035
6509
17
5648
6490
18
3696
6688
19
4843

20
13097

Figure 25 - USE REGRESSION TO FIND D-BAR. HINT YOU WILL NEED THE INTERCEPT AND THE X VARIABLE.  HINT DATA ANALYSIS TOOL PAK REGRESSION (OR ANOTHER  FUNCTION IF KNOWN). The OUTPUT will look something similar to figure 3.
Figure 3

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
