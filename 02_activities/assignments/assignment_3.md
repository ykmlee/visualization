# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    > ANSWER (for both plots): Python (using pandas for data processing and matplotlib for visualization)

    > Who is your intended audience? 
    > ANSWER (for both plots): University dministrators, education policymakers, and academic researchers who are interested in understanding gender distribution and enrollment trends over time. It may also be of interest to current and former students.

    > What information or message are you trying to convey with your visualization? 
    > ANSWER (for plot 1): The visualization shows the gender composition of graduate students, highlighting how enrollment is distributed between genders and whether that balance changes over time. It helps reveal patterns of representation or imbalance in graduate-level education. From the plot we can see that enrollment is increasing in all gender categories. Most graduate students identify as female regardless of fisical year.
    > ANSWER (for plot 2): The visualization shows how the proportion of undergraduate versus graduate enrollment changes over time. It is showing how one group is growing or shrinking relative to the total student population each fiscal year, rather than focusing on raw enrollment numbers. From the plot, we can see that undergraduate students have made up the majority of the student body, but the proportion of gradaute student have been increasing in recent years.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    > ANSWER (for plot 1): I focused on clarity, comparability, and accessibility. A line plot was used to make gender proportions easy to visualize across years. Consistent color mapping was applied to each gender category to avoid confusion. Axis labels, a descriptive title, and a legend were included to ensure the visualization is self-explanatory.
    > ANSWER (for plot 2): I considered clarity, comparability, and simplicity. I used a 100% stacked bar chart so each year is normalized to the same total, making proportions easy to compare. Consistent colors for undergraduate and graduate categories improve readability. Labels, a legend, and axis titles were included to ensure the chart is interpretable without additional context. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    > ANSWER (for both plots): The visualization is reproducible because it is built using a Python script (which I have included in my submission) with pandas and matplotlib, which can be rerun on any machine with the same dataset. The data processing steps (e.g. cleaning, grouping) are fully coded rather than manually done. If reproducibility were not ensured, others would not be able to verify results or update the visualization when new data becomes available, reducing trust and usability.

    > How did you ensure that your data visualization is accessible?  
    > ANSWER (for both): Accessibility was considered by using clear axis labels, a descriptive title, and a legend instead of relying on color alone. The chart uses high-contrast default matplotlib colors and avoids overly subtle design elements. 

    > Who are the individuals and communities who might be impacted by your visualization?  
    > ANSWER (for both): Students, university administrators, education planners, and policymakers are directly impacted. Changes in undergraduate and graduate enrollment can influence funding allocation, program development, staffing decisions, and institutional priorities. Prospective students and researchers studying higher education trends may also use this information.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    > ANSWER (for plot 1): I included only graduate-level data and gender categories because the goal was to specifically analyze gender distribution within graduate enrollment. Other variables such as Study level = undergradaute were excluded to maintain clarity and avoid overcomplicating the visualization. Aggregating data at the graduate level ensures a focused comparison of gender proportions.
    > ANSWER (for plot 2): I only included "Insitute = Toronto", “Fiscal Year,” “Study Level,” and “HEADCOUNT” because they directly support the comparison of enrollment proportions over time. I excluded other variables such as gender, institution, and other breakdowns to avoid overcomplicating the visualization and to keep the focus on undergraduate vs graduate trends. Aggregating across those excluded categories helps present a clearer high-level trend.

    > What ‘underwater labour’ contributed to your final data visualization product?
    > ANSWER: I had to understand the dataset, decide on what story I wanted to tell with the data, and determine the best way to present the data. 

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
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
