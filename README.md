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

