# Project 1: Standardized Testing, Statistical Summaries and Inference

## Problem Statement

The SAT is a college admissions test in competition with the ACT. The new format for the SAT was released in March 2016. This project examines participation rates and total scores for the 2017 and 2018 SAT and ACT, and makes recommendations on how the College Board can improve future SAT participation and scores in the state of West Virginia, which has low SAT scores and low SAT participation.

## Executive Summary

This project begins by processing, exploring, and analyzing 2017 and 2018 score and participation data by state for the SAT and ACT. The provided data is combined with outside research to develop recommendations for improving future SAT participation and scores in the state of West Virginia, which has low SAT scores and low SAT participation. Suggestions of additional data to gather are offered.

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Data Dictionary:
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|string|ACT 2017 and 2018 and SAT 2017 and 2018|state of the USA where we are looking at test scores|
|**act_2017_participation_%**|integer|ACT 2017|ACT 2017 participation, percentage of high school students|
|**act_2017_english**|float|ACT 2017|ACT 2017 English test scores, from 1 to 36|
|**act_2017_math**|float|ACT 2017|ACT 2017 math test scores, from 1 to 36|
|**act_2017_reading**|float|ACT 2017|ACT 2017 reading test scores, from 1 to 36|
|**act_2017_science**|float|ACT 2017|ACT 2017 science test scores, from 1 to 36|
|**act_2017_composite**|float|ACT 2017|ACT 2017 composite test scores, from 1 to 36|
|**sat_2017_participation_%**|integer|SAT 2017|SAT 2017 participation, percentage of high school students| 
|**sat_2017_evidence-based_reading_and_writing**|integer|SAT 2017|SAT 2017 English test scores, from 200 to 800|
|**sat_2017_math**|integer|SAT 2017|SAT 2017 math test scores, from 200 to 800|
|**sat_2017_total**|integer|SAT 2017|SAT 2017 reading test scores, from 200 to 800|
|**act_2018_participation_%**|integer|ACT 2018|ACT 2018 participation, percentage of high school students|
|**act_2018_composite**|float|ACT 2018|ACT 2018 composite test scores, from 1 to 36|
|**sat_2018_participation_%**|integer|SAT 2018|SAT 2018 participation, percentage of high school students|
|**sat_2018_evidence-based_reading_and_writing**|integer|SAT 2018|SAT 2018 English test scores, from 200 to 800|
|**sat_2018_math**|integer|SAT 2018|SAT 2018 math test scores, from 200 to 800|
|**sat_2018_total**|integer|SAT 2018|SAT 2018 reading test scores, from 200 to 800|

## Recommendations:
* Mandating the completion of the SAT for all high school students
* Fee waivers from the College Board cover 100% of test registration costs
* “SAT School Day” generally includes a free SAT exam offered during the school day to make student participation as convenient as possible
* Increasing student and family awareness of college accessibility, especially among racial and ethnic minorities, English language learners, and economically disadvantaged students
* Increasing access to the PSAT
* Have school district offer for-credit SAT preparation course
* Free test preparation available from the College Board and the schools
* SAT question of the day contest<br><br>

## Additional Data to Explore:
* Have any of these programs been implemented?
* What are the participation rates by income and race?
* How do West Virginia schools fare in participation and scores for other standardized tests that people take in addition to the SAT?
  * AP
  * SAT 2
