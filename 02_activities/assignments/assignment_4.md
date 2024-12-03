# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

https://data.ontario.ca/dataset/university-enrolment/resource/59b71ef5-e837-4dc7-a7f4-e4921815871c

Visualization 1: Excel
![UofT Graduate Enrollment by Gender](02_activities/assignments/IMG_DataVis_in_Excel-1.png)
![UofT Graduate Enrollment by Gender Detailed](02_activities/assignments/IMG_DataVis_in_Excel.png)

•	What software did you use to create your data visualization?
o	I used Microsoft Excel for visualization.
•	Who is your intended audience?
o	My intended audience in this case are those interested in seeing gender trends in graduate students at the University of Toronto.
•	What information or message are you trying to convey with your visualization?
o	There’s no specific message that I’m trying to convey but rather to show trends in gender enrollment for graduate students at the University of Toronto. Given the output of the visualization, the message could be that whilst the overall # of students is increasing, the number of female students is far outpacing the number of male students, and there’s an increased education gap.
•	What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
o	The substantiative principle was to focus on graduate students at UofT only, and to clearly label and clear up any confusing information. For perceptual, I made sure to use distinct colours and clear legends for each gender group, organizing the years on the horizontal axis to show the passage of time. The aesthetic choice was to use a simple, clean palette that maintained consistent formatting.
•	How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
o	The software I use does not allow 1:1 reproducibility. That being said, the range for the chart itself could be loaded with new data to allow those following our footsteps to recreate the work. Given that the data is not 1:1 reproducible via code, someone checking on my work would have to recreate the steps that I went to and make assumptions based on the work presented.
•	How did you ensure that your data visualization is accessible?
o	I’ve ensured that the color palette for the visualization uses blue & orange for male and female to allow colorblind users greater access. There are also clear, legible labels, as well as a legend that will allow our users to read the information quickly.
•	Who are the individuals and communities who might be impacted by your visualization?
o	Some who may be impacted by visualization are those studying gender gaps in higher education, sociologists, potential students, and University administrators.
•	How did you choose which features of your chosen dataset to include or exclude from your visualization?
o	I chose to focus on a bite-sized, clearly defined visualization as there was quite a bit of information available. I chose to include the N/A or another gender despite the comparably low number of students to the other genders to allow for posterity and visibility. I also chose to focus on the University of Toronto and graduate students as those are more relevant to my experience.
•	What ‘underwater labour’ contributed to your final data visualization product?
o	There was quite a bit of labour that went into this task prior to producing the visualization. The first was determining what set I wanted to base the visualization of, and then what subset. Once that was done, I needed to clean and parse the data, which I pared down to UofT and filled in ‘*’ data with ‘0’ to aid visualization. Once that was done, the visualization itself had trouble coming into fruition despite built in graphing features which previously seemed straightforward, but this time required me to create a pivot summary table before allowing me to present the final version of the table that told the information I was interested in seeing.

Visualization #2: Python
![UWO Graduate Enrollment by Gender](02_activities/assignments/IMG_DataVis_in_Python.png)

•	What software did you use to create your data visualization?
o	I used Python in a Jupyter notebook, the Python libraries used were matplotlib and pandas. 
•	Who is your intended audience?
o	The intended audience is similar to the previous ones interested in seeing gender trends in graduate students at the University of Toronto, but this time it’s those interested in the same trends at the University of Western Ontario.
•	What information or message are you trying to convey with your visualization?
o	The image is meant to convey gender differences in graduate enrollment at the UWO as they have evolved over the 10-year period presented in the data. In contrast to UofT above, the number of male graduate students is larger than female graduate students and the gap is widening.
•	What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
o	The substantiative principle was to focus on graduate students at UWO only, and to clearly label and clear up any confusing information. For perceptual, I made sure to use distinct colours and clear legends for each gender group, organizing the years on the horizontal axis to show the passage of time. The aesthetic choice was to use a simple, clean palette that maintained consistent formatting. These decisions were similar to the previous plot and aided my understanding of a similar task using different methods.
•	How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
o	I ensured the data visualizations are reproducible by providing my code in a notebook and commenting that code where appropriate to show decisions made.
•	How did you ensure that your data visualization is accessible?
o	I’ve ensured that the color palette for the visualization uses blue & orange for male and female to allow colorblind users greater access. There are also clear, legible labels, as well as a legend that will allow our users to read the information quickly.
•	Who are the individuals and communities who might be impacted by your visualization?
o	Some who may be impacted by visualization are those studying gender gaps in higher education, sociologists, potential students, and University administrators
•	How did you choose which features of your chosen dataset to include or exclude from your visualization?
o	I chose to focus on clearly defined question of what the gender trends among graduate students at UWO are, I excluded all information that was not relevant then pivoted the information to get it in an appropriate format. One interesting piece of information here was the ‘Other’ gender group as at times the information wasn’t present at all (not reported) which resulted in a discontinuous graphs, at other times the information was given but with an asterisk value which I chose to replace with a ‘0’.
•	What ‘underwater labour’ contributed to your final data visualization product?
o	See above for my summary but the graphing wasn’t the bulk of the work. The bulk of the work was identifying an appropriate data set that I could work with, then within that set finding an appropriate, sizeable enough question to ask ourselves and get an insight on. Once I knew what I wanted to do then it was a matter of simply putting the code together and make decisions with my aim in mind.


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
