# Mental Health in the Tech Industry

**Authors**: Ignacio Ruiz, Justin Williams

## Overview

A one-paragraph overview of the project, including the business problem, data, methods, results and recommendations.

Open Sourcing Mental Illness (OSMI) is a non-profit, 501(c)(3) corporation dedicated to raising awareness and educating others about mental illness. They provide resources to support mental wellness in the tech and open source communitees. A dataset from a OSMI survey conducted primariliy in 2014, was procured via kaggle and utilized for our analysis. Our research question was:

_"Do you believe discussing mental health illness with your employer could have negative consequences?"_

Essentially, we wanted to know what variables would lead to folks answering _Yes_ or _No_ to the aforementioned. We utilized binary classification to train several machine learning models on the dataset. Our main takeaways were respondents knowledge of _benefits_ package, comfortability with _supervisor_ and _interference_ of mental illness with work, were the primary indicators of an answer of _Yes_ to the target variable. Our reccomendations are:

## Business Problem

Summary of the business problem you are trying to solve, and the data questions that you plan to answer in order to solve them.

With tech jobs exponentially increasing, mental health within the tech industry continious to be a salient topic. According to [OSMI](https://osmihelp.org/about/about-osmi), the environment and the way we talk about mental illness in general, needs to change. This was our rationale behind choosing _"Do you believe discussing mental health illness with your employer could have negative consequences_" as our target variable. We hypothesized that if an employee felt discussing a mental health issue with their employer could lead to negative consequences, this would indicate a poor environment for those suffering to recover. Therefore, tech employers looking to improve their workplace environments for those with mental health illness, could take the reccomendations provided from this analysis to make long term sustainable changes.


***
Questions to consider:
* What are the business's pain points related to this project?
* How did you pick the data analysis question(s) that you did?
* Why are these questions important from a business perspective?
***

## Data

Describe the data being used for this project.

The dataset utilized was from a 2014-2016 tech industry mental illness survey by non-profit OSMI procured through kaggle. The survey consisted of a series of questions with multiple choice answers that varied depedning upon the question asked. For instance, for question:

_"If you have a mental health condition, do you feel that it interferes with your work?"_

The answers were:
- Sometimes
- Never
- Rarely
- Often

Whereas the answers for our target were _Yes_, _No_ and _Maybe_.

As a result, besides an age, and timestamp column, the data was all categorical. Our target itself actually had three answers:

_"Do you believe discussing mental health illness with your employer could have negative consequences?"_
- Yes
- No
- Maybe

We ended up combining _Yes/Mabye_, to make it a strict binary classification. We did this because we felt if respondents were unsure (answered maybe) to the question, then it was evident there was somem degree of uncomfortabiliy in broaching the subject of mental illness with their employer. 

Here is a list of all the questions utilized in the survey:

| #  | Question                                                                                                               |
|----|------------------------------------------------------------------------------------------------------------------------|
| 1  | If you live in the United States, which state or territory do you live   in?                                           |
| 2  | Are you self-employed?                                                                                                 |
| 3  | Do you have a family history of mental illness?                                                                        |
| 4  | Have you sought treatment for a mental health condition?                                                               |
| 5  | If you have a mental health condition, do you feel that it interferes   with your work?                                |
| 6  | How many employees does your company or organization have?                                                             |
| 7  | Do you work remotely (outside of an office) at least 50% of the time?                                                  |
| 8  | Is your employer primarily a tech company/organization?                                                                |
| 9  | Does your employer provide mental health benefits?                                                                     |
| 10 | Do you know the options for mental health care your employer provides?                                                 |
| 11 | Has your employer ever discussed mental health as part of an employee   wellness program?                              |
| 12 | Does your employer provide resources to learn more about mental health   issues and how to seek help?                  |
| 13 | Is your anonymity protected if you choose to take advantage of mental   health or substance abuse treatment resources? |
| 14 | How easy is it for you to take medical leave for a mental health   condition?                                          |
| 15 | Do you think that discussing a mental health issue with your employer   would have negative consequences?              |
| 16 | Do you think that discussing a physical health issue with your employer   would have negative consequences?            |
| 17 | Would you be willing to discuss a mental health issue with your   coworkers?                                           |
| 18 | Would you be willing to discuss a mental health issue with your direct   supervisor(s)?                                |
| 19 | Would you bring up a mental health issue with a potential employer in an   interview?                                  |
| 20 | Would you bring up a physical health issue with a potential employer in   an interview?                                |
| 21 | Do you feel that your employer takes mental health as seriously as   physical health?                                  |
| 22 | Have you heard of or observed negative consequences for coworkers with   mental health conditions in your workplace?   |
| 23 | Any additional notes or comments                                                                                       |
***
Questions to consider:
* Where did the data come from, and how do they relate to the data analysis questions?
* What do the data represent? Who is in the sample and what variables are included?
* What is the target variable?
* What are the properties of the variables you intend to use?
***

## Methods

Describe the process for analyzing or modeling the data. For Phase 1, this will be descriptive analysis.

***
Questions to consider:
* How did you prepare, analyze or model the data?
* Why is this approach appropriate given the data and the business problem?
***

## Results

Present your key results. For Phase 1, this will be findings from your descriptive analysis.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
