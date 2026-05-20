# Global Layoffs-Data-Cleaning-and-EDA

# Executive Summary:

Using MySQL, I cleaned Global Layoffs Dataset by Removing Duplicates, Standardizing the Data, converting Blank Values to Null values and Removing unwanted Columns. I also performed Exploratory Data Analysis to pull out trends or insights from the cleaned dataset. Since the major aim is to maximize profit and expand the business by reducing or preventing future layoffs, I recommend that the strategy team for each company especially the companies with the most layoffs in the United States implement the following:

1. These Companies can stop hiring new employees early so they do not overextend before cuts are necessary.
2. They should move talented workforce to growing parts of the business if possible to reduce or prevent layoffs.

# Business Problem:

The general dream of any business is to maximize profit and expand as much as possible. Several columns of data about layoffs of employees in different companies globally have been provided for us. How do we make the most of that information to find gaps that can be corrected to maximize the profit and also expand the business?

# Methodology:

1. Data Cleaning and Exploratory Data Analysis with Windows Function, Common Table Expression(CTEs), Rolling Total and Self Join to improve dataset consistency and extract patterns and insights from the dataset.

# Skills/Tools Used:

MySQL: Row_number(), Trim(), Str_to_date(), CTEs, self-join, Over(partition by...), min(), max(), sum(), group by, order by, substring(), year(), dense_rank()

# Results/Key Insights:

The United States had the highest total layoffs of 256,559 globally. This was followed by India with a total layoffs of 35,993.

The data range for all layoffs was from 2020-03-11 to 2023-03-06. The highest total layoffs fell mostly between 2022-10 to 2023-02.

2022 had the highest layoffs of 160,661 followed by 2023 with 125,677 and then 2020 with 80,998. 2021 had the lowest layoffs with 15,823.

1 is the maximum percentage_laid_off which means 100 percent of company layoff. Google from the United States had the highest layoffs of 12000, it happened in one day on 2023-01-20 with a percentage layoff of 0.06 and 26 million funds raised. 

Companies at the stage called post-IPO had the highest layoffs of 204,132.

Consumer companies such as Google and Twitter had the highest layoffs of 45,182 followed by Retail companies such as Amazon and E-bay with total layoffs of 43,613.

The first month of the layoffs according to the dataset which was 2020-03 had total layoffs of 9,628. The final month which was 2023-03 had a total layoffs of 383,159. 

The top five companies with the highest layoffs globally were Amazon with a total layoffs of 18,150, Google with 12,000 layoffs, Meta with 11,000, Salesforce with 10,090 and then Microsoft with 10,000. All these companies were based in the United State, they were all at the post-IPO stage, and they all had layoffs in 2022 0r 2023.

# Business Recommendations:

To maximize profit and expand the business by reducing or preventing future layoffs, I recommend that the strategy team for each company especially the companies with the most layoffs in the United States implement the following:

1. These Companies can stop hiring new employees early so they do not overextend before cuts are necessary.
2. They should move talented workforce to growing parts of the business if possible to reduce or prevent layoffs.


# Next Steps:

1. More data should be provided such as specific reason for each company layoff in order to be able to give more specific recommendations.
2. These companies can offer money and benefits to the employees that were laid off.
3. Also, these companies can offer career coaching or job search resources to support the employees in finding a new job.
