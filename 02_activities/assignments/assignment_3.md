# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

Data: Intimate Partner and Family Violence.csv

Visualization 1 (viz: assignment_3_viz_1.png, jupyternotebook: assignment_3_vis_1.ipynb)

    > What software did you use to create your data visualization?
    Python Jupyter notebook.

    > Who is your intended audience? 
    City of Toronto public social services staff who need a clear overview of trends in parent–child relationship violence reports over time.

    > What information or message are you trying to convey with your visualization? 
    How parent–child relationship violence has changed over the past years, both in the absolute number of reports and in its proportion relative to all intimate partner and family violence cases.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I focused on three key design aspects: accessibility, substance, and perception.
    Accessibility — I included descriptive alt-text for the plot and selected a colorblind-friendly palette to ensure inclusivity.
    Substance — I made sure the visualization meaningfully represents changes in both the total number and the proportion of parent–child relationship violence reports, providing context within overall cases. I also provided the source of the data together with the accessed time.
    Perception — I used clear, well-labeled axes, increased font sizes for readability, and maintained an uncluttered 2D layout to ensure that important trends are easily and accurately understood.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I ensured reproducibility by including fully commented, step-by-step code that enables anyone to recreate the visualization from the raw dataset. All code, explanations, and instructions are provided.

    > How did you ensure that your data visualization is accessible?  
    1. I included descriptive alt-text to improve accessibility for screen reader users.
    2. The visualization uses a colorblind-friendly palette to ensure information is visible to all viewers.
    3. Font sizes are larger for readability, and the layout is clean with clear, uncluttered axis labels and titles.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Individuals and communities who might be impacted by this visualization include:
    - Policymakers who may rely on this information for preventive strategies.
    - Researchers and advocates focused on violence prevention
    - The broader Toronto community, as understanding the prevalence and changes in parent–child violence can inform collective action

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    To highlight trends in both the total number of parent–child violence cases and their proportion within all family violence incidents, I focused exclusively on family violence data—excluding intimate partner violence cases and omitting geographic information. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Several forms of underwater labour were essential:
    - City of Toronto staff who collected, cleaned, and organized the data
    - Developers and maintainers of the open-source tools I used (pandas, matplotlib, seaborn, Jupyter) 
    - Course instructors and teaching assistants who developed the course materials, slides, and provided guidance design principles

Visualization 2 (viz: assignment_3_viz_2.png, excel: assignment_3_viz_2.xlsx)

    > What software did you use to create your data visualization?
    Excel.

    > Who is your intended audience? 
    City of Toronto public social services staff who need a clear overview of proportions of parent–child relationship violence cases reported in different incident locations in 2024.

    > What information or message are you trying to convey with your visualization? 
    The visualization highlights which types of premises (locations) have the highest proportion of reported parent–child relationship violence cases in 2024.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I focused on three key design aspects: accessibility, substance, and perception.
    Accessibility — I included descriptive alt-text for the plot and selected a colorblind-friendly palette to ensure inclusivity.
    Substance — I made sure the visualization meaningfully represents the proportions of parent–child relationship violence cases across different incident locations in 2024, highlighting which types of premises have the highest rates. I also provided the source of the data together with the accessed time.
    Perception — I used clear, well-labeled axes, increased font sizes for readability, and maintained an uncluttered bar chart layout to ensure that the proportions by location are easily compared and accurately understood.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I ensured reproducibility by using pivot tables generated directly from the original dataset and creating the bar chart from those pivot tables.

    > How did you ensure that your data visualization is accessible?  
    1. I included descriptive alt-text to improve accessibility for screen reader users.
    2. The visualization uses a colorblind-friendly palette to ensure information is visible to all viewers.
    3. Font sizes are larger for readability, and the layout is clean with clear, uncluttered axis labels and titles.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Individuals and communities who might be impacted by this visualization include:
    - Policymakers who may use this information to shape effective prevention strategies—for example, determining which settings should be prioritized to reduce parent–child relationship violence.
    - Researchers and advocates focused on violence prevention
    - The broader Toronto community. We need to raise people's awareness of where the violence cases are more likely to occur.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    To ensure the visualization is relevant for current policy decisions, I focused exclusively on data from 2024, omitting all previous years. I further narrowed the dataset to include only incidents involving parent–child relationships, excluding other types of family or intimate partner violence. Additionally, I chose not to incorporate geographical information, concentrating instead on the type of premises where these incidents occurred.
    
    > What 'underwater labour' contributed to your final data visualization product?
    Several forms of underwater labour were essential:
    - City of Toronto staff who collected, cleaned, and organized the data
    - Microsoft Excel developers and maintainers who created and maintain the spreadsheet software
    - Course instructors and teaching assistants who developed the course materials, slides, and provided guidance on design principles

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
* Submission Due Date: `23:59 - 02/02/2026`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
