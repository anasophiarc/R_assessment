# R_assessment

## Team Name: GIT 'ER DONE 

## Experience working in a research team: 
- Ella: Worked with postdocs, wrote her own reports 
- Simona: Wet lab w phds, postdocs, PI and undergrads (diverse); would work on sub aspects of projects
- Sophie: Reproducible coding 

## PLAN: 
Divided up tasks for analysis: 
- Import + Process (cleaning, encoding): Sophie 
- Analyse (1 script): Collab editing
- Generate plots/tables: Ella (R markdown) 
- Report: Simona 

## Reflective Notes: 
- Workflow split up less individually because we are working on it together - would be different if we were working remotely/at different times
- Importance of clearly commenting code for reproducibility between project teams
- Must make sure the report contains a step-by-step plan so other teams can replicate our code and analysis 

## Obstacles + Challenges 
- using the "here()" command in read.csv(here("data", "myfile.csv")) to ensure that the differing working directories of the team members are aligned and do not need to be changed during each edit
- Some of the data set was given verbally during the first session and we needed to type it down; all three of us used Shiny/excel to record the data and then we compared the observations afterward
- The time limit added a lot of pressure, similar to an upcoming deadline
- Due to the time limit, we were unable to produce impactful figures, such as tables or graphs, that could have added to our analysis. 

# Peer Review 
- 45 minutes of reconstructing and replicating the other's team's work + giving constructive feedback
- 15 minutes of reflecting on our own feedback

PROS:
- Good cleaning practices + well commented cleaning
- Good making all other values of gender NA
- Advanced use of dplyr package
- Completeness
- Code is reproducible when running in chunks
- Efficient prevalence calculations 

CONS: 
- Data shouldn't be on Git
- Title of script should be more informative (shouldn't have to come over and explain it) 
- Shouldn't use fields that are not in all datasets OR include a justification
- Try not to include unrelated files
- R markdown/discussion is missing and file doesn't knit => having interpretation of resulsts is really important 
- Would be good to have even more detailed and comments (especially validating the representativeness)
- Model adjusted prevalence not well explained
- *Understanding that there was a lack of time :) 


# Our Work's Peer Feedback 
- Group did a really good job presenting a clear and well-structured analysis. The use of headings, justification, and detailed comments made the work easy to follow.
- The group also clarified the report's aims at the beginning and provided a thorough descriptive summary of the results at the end. There are proper reasons stated to support each analysis step.

The things that can be better are:  
1. During the data-wrangling process, we found that several variables had inconsistent category labels. For example, the gender variable contained multiple forms such as "f", "female", "m", and "male".
2. The outcome variable Belief was not converted to a factor and remained in numeric form. We recommend converting all categorical variables into factors to ensure they are correctly treated in the analysis.

  
4. Regarding the prevalence, you might want to adjust for confounders using a regression model before computing the prevalence of health issues. The group solely used the age stratification and calculated the distribution in each subgroup for different variables.
5. You might want to keep exploring the sample validation and generalisation section.

Nice work overall!

