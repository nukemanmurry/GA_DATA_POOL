# GA_DATA_POOL
Attempt to pool GA statistical data for open source COVID analysis

Hello there!

Disclaimers up front: I did this on my own personal time, none of this reflects the opinion or position of my employer and should not be interpreted as anything other than a personal project that I did for my own anxiety coping. 

This spreadsheet is intended to serve as a tool for anyone to analyze the developing COVID situation in Georgia at a county level and analyze relative to demographic, political, and economic data. 

Georgia, quite honestly, and without intending to offend anyone, is garbage at compiling said data in one place, so I’ve tried my best to do it for them as a way of dealing with my anxiety over the situation. I’ve published all this in the hope that someone else may find a use for it as well. 

Some notes on sourcing:

The case count data for 4/20/2020 comes from the invaluable JHU GitHub repository available at https://github.com/CSSEGISandData/COVID-19

 - note, Glascock and Taliaferro counties numbers are not reported and I have not included those two counties in the rest of the sheet, but I would like to at some point

The 2018 vote numbers for Brian Kemp and Stacy Abrams comes from https://sos.ga.gov/index.php/Elections/current_and_past_elections_results 

Demographic/race/age data comes form https://opb.georgia.gov/census-data/population-estimates

GDP and per capita personal income come from https://www.bea.gov/data/economic-accounts/regional 

I will add and update as I think of other ways to analyze it, any comments or contributions are welcome and may be directed at nukemanmurry@gmail.com

I have tried to make column headers self explanatory, nonetheless:


FIPS	-> FIPS number for that county
County -> County Name
Total_Population_2019_est -> 2019 population estimate
Kemp_Votes	-> Votes received by Brian Kemp in the 2018 election
Abrams_Votes -> Votes received by Stacy Abrams in the 2018 election
Total_Population_2016 -> 2016 population estimate for use with other 2016 data

—
| White
| Black_or_African_American
| American_Indian_or_Alaskan_Native
| Asian	Native_Hawaiian_Other_Pacific_Islander
| Two_or_more_races
| POC_sum_non_white - (sum of all non-white residents)
|—
|-> Number of people in that demographic


[ 0_to_4_2016	5_to_9_2016	10_to_14_2016	15_to_19_2016	20_to_24_2016	25_to_29_2016	30_to_34_2016	35_to_39_2016	40_to_44_2016	45_to_49_2016	50_to_54_2016	55_to_59_2016	60_to_64_2016	65_to_69_2016	70_to_74_2016	75_to_79_2016	80_to_84_2016	85_or_older_2016 ] -> Number of people in that age group for 2016

Median_Age	-> Median age for that county

Cases_4.20 -> Number of confirmed cases in that county
Deaths_4.20	-> Number of COVID related deaths in that county
Recovered_4.20 -> Number of Recovered cases in that county
Active_4.20 -> Number of active COVID cases in that county

2018_GDP_1000s_Chained_Dollars -> GDP for that county in 1000s of chained dollars in 2018

Per_Capita_Personal_Income_2018 -> per capita income in that county for 2018

If you’ve made it this far congratulations I guess. God bless and stay safe in these trying times. 

Best,

Murry Dan Smith III
Oh yeah, Go Jackets!
