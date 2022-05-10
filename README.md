# insurance-claims-forecast-project

Pre Read:
● I chose my own data set. I am utilizing two data sets that I received as part of a recent case study I had to do
○ Weather Data: weather.csv
■ This data comes from the NOAA Storm Prediction Center: ■ https://www.spc.noaa.gov/climo/reports/
○ Jobs Data: jobs.csv
■ Dummy data provided from a contractor tech company
● Resources:
○ Facebook prophet: I used this tool to analyze the data and come up with
my forecast
■ https://facebook.github.io/prophet/
Questions I Am Trying to Answer:
● What is the overall # of jobs we can expect in 2019?
● What is the demand of roof vs. complete models we can expect?
● How much of the expected volume might come from weather events?
Main findings from the exploratory data analysis, and how you chose the results to put in your explanatory analysis:
● I limited some of the outputs in the presentation to the findings that were most significant (i.e. lowest error rate). My main findings were I was able to forecast job demand for a couple of subgroups and total jobs, and the number of weather
 
 related jobs. My findings also concluded that weather events did have a noticeable impact on jobs but was somewhat limited.
Data Fields:
● Weather data
○ COMMENTS A description of the weather event.
○ COUNTY The county of the weather event.
○ STATE The state of the weather event.
○ LOCATION The address of the weather event.
○ LON The longitude of the weather event.
○ LAT The latitude of the weather event.
○ DATETIME The datetime of the weather event.
○ COMPOSITE_KEY A unique key for the weather event.
● Jobs data
○ Job Identifier: Unique job id
○ Organization ID: User who did the job purchased the job
○ Job Location City: The city where the job was located.
○ Job Location Region Code: The state where the job was located.
○ Job First Upload: JOb complete
○ Types of Jobs:
■ Job Deliverable Complete: Complete remodel
■ Roof: Company completely re doing the customer’s roof ■ Roof Estimate: Company providing a roof estimate
■ Total Living Area: Estimate of house’s total living area

■ Total Living Area Plus: Estimate of house’s total living area plus a 3D model of the house
