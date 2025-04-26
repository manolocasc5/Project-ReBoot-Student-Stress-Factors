# Project-ReBoot-Student-Stress-Factors
![image](https://github.com/user-attachments/assets/e93ec221-4c0f-43fd-8466-357b5f57b725)

## About Dataset
Have you ever wondered which factors truly influence student stress? The dataset "ReBoot – Student Stress Factors" compiles responses from dozens of fellow students about their habits, emotions, and academic environment. It is your personal laboratory to turn numbers into stories and detect hidden relationships: Do students who sleep poorly report higher anxiety? Does neighbourhood noise impact academic performance?

Put on your data‑scientist lab coat and find out!

## 🗂️ Quick Guide to Variables

|       Factor        |         Variable     	|        What it represents    		|   Scale overview*	|
|---------------------|-------------------------|---------------------------------------|-----------------------|
|Psychological	      |anxiety_level	    	|Perceived anxiety intensity		|1–20            	|
|              	      |self_esteem  	 	|Student self‑esteem        	        |1–30            	|
|              	      |depression  		|Depressive symptoms        	     	|1–20                 	|



		
		
mental_health_history	Previous mental‑health diagnosis	0 = No / 1 = Yes
Physiological	headache	Headache frequency	0–5
blood_pressure	1 = Low, 2 = Normal, 3 = High	
sleep_quality	Perceived sleep quality	1 = Very poor … 5 = Excellent
breathing_problem	Breathing issues	0–5
Environmental	noise_level	Household noise	1–5
living_conditions	Overall home comfort	1–5
safety	Feeling of safety	1–5
basic_needs	Access to water, food, etc.	1 = Never … 5 = Always
Academic	academic_performance	Self‑rated performance	1 = Very low … 5 = Excellent
study_load	Study hours per week	Integer
teacher_student_relationship	Relationship quality	1–5
future_career_concerns	Worries about future career	1–5
Social	social_support	Sense of social support	1–5
peer_pressure	Peer pressure	1–5
extracurricular_activities	Participation in activities	0–5
bullying	Bullying experiences	0–5
Outcome	stress_level or str_level	Overall stress (duplicate)	1 = Low … 3 = High
🔎 What Can You Investigate?
Below you will find graded challenges to guide you step by step.

## 🐣 Task for the beginners
Time to rise and shine. Best of luck! Add your notebook link if you solve them.

1) Descriptive Statistics

How many students are in the dataset?
What is the average anxiety_level?
How many students report mental_health_history = 1?
2) Psychological Factors

How many students have self_esteem below the average?
What percentage experience depression beyond a clinical threshold?
3) Physiological Factors

How many suffer frequent headache (≥ 4)?
What is the mean blood_pressure rating?
How many rate their sleep_quality as 1 or 2?
4) Environmental Factors

How many live with noise_level ≥ 4?
What percentage feel unsafe (safety ≤ 2)?
How many have basic_needs ≤ 2?
5) Academic Factors

How many rate academic_performance below 3?
Average study_load.
How many express future_career_concerns ≥ 4?
6) Social Factors

How many report social_support ≥ 4?
Percentage experiencing bullying ≥ 3.
How many join ≥ 1 extracurricular_activities?
7) Comparative Analysis

Is there a correlation between anxiety_level and academic_performance?
Do students with poor sleep_quality (≤ 2) also show higher depression?
Are students who experience bullying more likely to have a mental‑health history?
8) General Exploration

Which factor (Psychological, Physiological, Environmental, Academic, Social) gathers the most negative experiences?
Any visible trends when comparing factors?
Within each factor, which variable most strongly impacts stress_level?
🚀 Suggested Next Steps
**Load the CSV in a notebook and run df.info(),describe,etc to inspect dtypes and missing values.
Explore and Clean.
Visualise: histograms, boxplots, correlation heat‑maps.
Tell your story: conclude with practical insights (and share them!).
