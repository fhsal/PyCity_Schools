# PyCity_Schools

CWRU Data Analytics Module Four Challenge

# PyCity Schools

## Overview of Project

The project involved learning about using pandas, including data frames and capabilities such as loc, mean, and formatting with a  data set that included math and reading scores for in 15 school systems.  A variety of segmentations and views of the student populations along dimensions such as per-school spending, school size, high and low overall passing rates and aggregations for size and spending groups.   Additionally, we were asked to remove the reading and math scores from the data for 9th grade students at Thomas High School due to concerns around cheating and re-run the analysis - and then provide observations as to the impact. 


### Purpose

The purpose of the challenge was to exercise our skills with using pandas in a variety of ways to summarize, aggregate, sort, filter, format and replace data to facilitate summary-level views of the student and school populations.  

## Analysis and Results

The analysis of re-running the school district analysis had two components:

(1) replacing the scores of the 9th grade Thomas High School students with 'nan' - which effectively impacted all the aggregate stats in which these scores had previously been included;  and

(2) Removing the 9th grade Thomas High School students from the population totals - which effectively impacted all the aggregate population related stats in which these students had previously been included (e.g., total students, per-student stats, etc.)

### Analysis of Outcomes Based on Launch Date

![img](https://github.com/fhsal/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

![img](https://github.com/fhsal/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

A bit tricky with "COUNTIFS" rather than "COUNTIF", but otherwise straightforward. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?   Success rates are much higher in late spring and early summer whereas failure rates are relatively flat 

- What can you conclude about the Outcomes based on Goals?  Unsure - the success rates seem higher at lower cas rates than higher but ther eis a bump around #5k-$40k

- What are some limitations of this dataset?  It doesn't include causal factors 

- What are some other possible tables and/or graphs that we could create?  variations due to currency and country, for example 