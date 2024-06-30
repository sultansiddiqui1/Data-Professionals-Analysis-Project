# Data-Professionals Analysis Project
A Project fully made in PowerBI,which means even the data cleaning and standardizing is done in Power BI.This is a real world project, where the raw data is taken from the instagram survey done by Alex the Analyst via his instagram stories, where he asks the data professions questions about their professions like Job Title, pay range etc and also personal questions like preffered programming language and age and country of origin.

**Loading and Transforming the data in PowerBI:**
  - Rather than simply loading the data we put it in the Power Query Editor so that we can transform and clean      some of the columns that need some work. It is better to do this in excel or sql, but since we want to          really see what all we can do in PowerBI we do it here for this project.The points below do not cover         all the steps done but gives you a breif idea of what all we implemented.
  - Next, i delete a few columns that i am sure i will not be using. PowerBI tracks the changes that i do and       also gives me the option of undoing them, so worst case if i need the columns again, i can get them back.
  - Next, i look at the Job Title Column.The columns contains a  lot of diffrent options like data analyst,         data enggineer, data architect etc which might break our visulizations. Therefore we take 6 most popular        titles and replace the other titles with others tag.
  - Next we look at the salary column. We first remove the 'K' from the salary ranges and rather than having       ranges we replace it with an average value.
  - we also standardize the country column, by using a similar apporach of only keeping the most popular ones       and replacing all other entries with a generic value:'others'.

**Building the Dashboard:**
- After transforming the data now we go towards building our interactive dashboard to get insights and build a    report.
- We utlize multiple charts to present insights from our data to help make business decisions and to draw         conclusions (nothing really to suggest to stake holders in this case) about the data science job Family.
- The dashboard is ofcourse better to look at and play around by yourself rather than reading about it, so       please feel free to either open the pdf or powerbi file and hopefully you gain some insights about this         field.
