Retail Data Sales Analysis


# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
I will be using a dataset from kaggle which is linked below. https://www.kaggle.com/datasets/manjeetsingh/retaildataset/data



## Hypothesis and how to validate?
My hypothesis is how are the markdown promotions impacting the weekly sales? I will model the effects of the markdowns between 2010-2012, and provide recommended actions based on insights drawn and how to improve the retail sales. I will be validating this by cleaning the datasets, merging them and analysing them to prove my hypothesis right and to take further action to support this data. 

## Project Plan
First, I downloaded and applied the dataset from kaggle into jupyter notebook, I then began checking each dataset for any cluttered, missing data. Once I found if there was any missing data, I then filled this in using the mean and created an additional dataset called 'cleaned_features' dataset. I began basic visualisation in order to meet my objectives and analysed my findings. I used more advanced visualisation such as Plotly to get more insight into the data, specfically when were the promotional markdowns the most effective. Once I found my findings, I wrote in detail about them underneath and then gave a conclusion and next steps, if this project was either to be recreated or to be continued.
The data was collected fine, and the processing was not time consuming at all. With the missing values in one of the datasets, I chose to fill the missing values. The data was managed fine when analsying the findings and interpretating the graphs.


## The rationale to map the business requirements to the Data Visualisations
* To meet the business requirements, I employed time-series line charts to visualize sales trends, particularly focusing on the seasonal impact during holidays. The line chart of weekly sales with holiday highlights revealed that sales peaked during the Christmas period. To evaluate the effectiveness of markdowns, I plotted sales with and without markdowns over time, providing clear insight into the markdown’s impact on sales. For store performance comparison, a time-series plot was used to show sales performance across different stores. Lastly, external factors like temperature, fuel prices, and CPI were visualized through time-series plots to observe their influence on sales.

## Analysis techniques used
Correlation Analysis: Checked the relationship between markdowns and sales to see if markdowns affect sales.
Time-Series Analysis: Analyzed sales trends over time, focusing on holidays like Christmas.
Comparative Analysis: Compared sales during holidays versus non-holidays to assess markdown effectiveness.
Correlation Analysis: Doesn't prove cause and effect, just shows relationships.
Time-Series Analysis: Can be affected by outliers and might not predict future trends accurately.
Comparative Analysis: May not account for other factors influencing sales, like weather or local events.

The data analysis was structured starting with Exploratory Data Analysis (EDA) to clean and understand the dataset, identifying key variables like sales and markdowns. Next, Correlation Analysis was used to explore potential relationships between markdowns and sales. Time-Series Analysis followed to examine sales trends over time, particularly focusing on seasonal effects like holidays. Finally, Comparative Analysis was performed to compare sales during holidays versus non-holidays, helping evaluate the effectiveness of markdown promotions. This structure ensured a logical flow, from understanding the data to identifying relationships, observing trends, and comparing key events for actionable insights.

The data had some limitations, particularly the limited time range, as it only goes up to 2013, which restricted long-term trend analysis and forecasting. To address this, I focused on seasonal trends and holiday impacts within the available period. Additionally, missing data and inconsistencies were handled during the data cleaning process to ensure accuracy in the analysis. This allowed me to make meaningful conclusions despite the constraints.

I used generative AI tools such as ChatGPT to assist with ideas by brainstorming potential analysis methods and visualizations, helping me explore different angles for analyzing the data. For design thinking, AI helped refine the flow of analysis and suggested ways to present findings effectively, ensuring clarity and relevance to the business objectives. When it came to code optimization, AI provided guidance on improving efficiency, suggesting alternative code structures, and identifying potential improvements in data handling and visualization techniques. This allowed me to streamline the analysis process and focus on delivering actionable insights.

## Ethical considerations
Based on the dataset and the analysis performed, there were no immediate data privacy issues since the data appears to be aggregated and does not contain any personal identifiers or sensitive customer information. However, there could be bias or fairness issues, particularly if certain store types, regions, or demographics were overrepresented or underrepresented in the data, potentially skewing insights.
* How did you overcome any legal or societal issues?



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
* I used Pandas, Numpy, Madplotlib, Seaborn; and I used these libraries to complete this project by being able to plot data into graphs, calculate information and fill in missing values, and I also used Pandas for data manipulation so that the data was easier to interpret.


## Credits 

* My sources were https://www.kaggle.com/code/aremoto/retail-sales-forecast, https://www.kaggle.com/code/shubhamsinghgharsele/retail-data-analysis#Analysis-Datewise, and small helps from ChatGPT

## Acknowledgements 
I would like to thank everyone who provided support with this project which is the whole group.