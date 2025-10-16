# Credit Card Churn Analysis and Data Cleaning

**Credit Card Customer Churn Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The Credit Card dataset contains just over 10,000 customers' data like Age, Gender, Income category, card category, etc. This dataset can be accessed from the following link: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data


## Business Requirements
A bank manager is concerned about increasing customer churn in their credit card services. The goal is to assess which customers are likely to churn using customer data and develop strategies to improve retention.


## Hypothesis and how to validate?
## Hypothesis 1:
Old customers with higher credit limits are less likely to attrite compared to younger customers with lower credit limits.

### Result:

Attrition is more common among younger customers with lower credit limits.
Older customers with higher limits tend to remain active.

# Hypothesis 2:
Customers with higher credit limits tend to be older, reflecting a possible correlation between age and financial trustworthiness or creditworthiness.

### Result:

Older customers are more likely to have higher credit limits
Younger customers are clustered around lower credit limits, suggesting that there is a limited financial history.

# Hypothesis 3:
Lower-income customers exhibit higher total transaction amounts, suggesting greater reliance on credit card usage.

### Result: 

The customers earning less than $40k have the highest total transaction amount, even more than higher-income groups. This could mean that lower-income groups may use their credit cards more often as they may rely on them for everyday expenses. 

# Hypothesis 4:
Customers with Blue credit cards are more likely to be retained than those with Silver, Gold, or Platinum cards.

### Result:

Blue cardholders are more likely to stay with the bank than customers with Silver, Gold, or Platinum cards. The Blue card category has teh highest number of existing customers and the lowest number of attrited.

# Hypothesis 5: 
Card category affects customer retention, with Blue and Silver cards showing loyality than Platinum and Gold. 

### Result: 

Blue and Silver cardholders have the highest retention rates, while Platinum has the lowerst. This supports the idea that card types affect customer loyalty, with Blue and Silver cards being more effective at keeping customers.

## Project Plan
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.