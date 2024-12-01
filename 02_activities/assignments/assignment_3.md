# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Your answer...
        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Your answer...
        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

Bad Visualization: Internet Access Across the World. 2003 to 2022 
URL: https://public.tableau.com/app/profile/chimdi.nwosu/viz/MakeoverMondayWk45-InternetAccessAcrosstheWorld_2003to2022/Dashboard1

- Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
As mentioned in the initial analysis in Assignment 2, this visualization is quite dense, presenting the audience with 180 from the start which can be overwhelming and exclude some viewers, particularly those unfamiliar with the data or with cognitive impairments. High cognitive load due to excessive inital detail will make extracting insights that much more difficult.
The subtle gradients in the color choices can be problemating for those with colorblindness or low vision, which is at times compounded by the small size of text labels, thus making it doubly difficult for those with visual impairments.
As far as reproducibility, whilst the data source is mentioned, there is no documentation on how some of the values were calculated (the percentages), nor is there documentation on how this visualization was created. The visualization is hosted on Tableau which makes it not reproducible outright, and some of the choices and methods of design are unintuitive which would make it difficult to recreate this visualization.
In terms of equity, the grouping into regions hides regional inequalities which may result in an incomplete understanding of the presented situation.

- How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)? 
This visualization can be improved in number of ways but the first would be to reduce the cognitive load required to understand the visualization by grouping up the countries under regions (and additionally refining the groupings/regions) and letting viewers "drill down" to the details they are interested in.
Increased font sizes, and a clearer differentiation between the different shades of gray could aid in readability and access for those with visual impairments.
Standardizing country tiles and additional filters from the top down could allow readers to get better access to the insights they are seeking.


Good Visualization: NBA Shot Chart 2018-2019
URL: https://public.tableau.com/app/profile/daniel.teo/viz/NBAShotCharts_15795208182820/ShotChart

- Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
When it comes to accessibility, this visualization does a great job of being accessible and intuitive in terms of presenting the available information using a blue-red gradient. This however could be problematic for colour blind individuals so using textures as well as colours could aid in reducing this barrier.
Whilst the visualization is hosted on Tableau which means that it is not directly reproducible, the public nature of the available base data as well as the intutitive design to other standard shot chart formats would aid in recreating the visualization. The visualization, however, does not say much about it's methodology on data treatment/processing so there's a bit of opacity on that step of the process.
In terms of equity, it isn't clear why these 25 specific players were chosen and others omitted (Lebron), which could lead the audience to infer that the author is presenting inforamtion with certain biases. The comparison to league average gives some context but can misrepresent information as basketball is still a positionally-dominant sport which means that players ought to be compared to those who have a similar playstyle or play the same position.

- How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)? 
Accessibility can be improved by incorporating patterns or symbols in the shot chart to aid colorblind readers. Adding text descriptions as overlays can help those with screen readers.
The data is presumably from NBA.com or a secondary source of the NBA but citing the raw data sources would be helpful in determining the veracity of the data. An explanation of how shooting zones and efficiency was calculated would help in recreating the chart.
In terms of equity, things can be made better by incoroprating more players as well as other leagues including the WNBA. Providing comparative context to positions can highlight key player differences that woudl otherwise be lost if we're comparing to all players in the league.

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:
| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
