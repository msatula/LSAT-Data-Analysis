# Law School Admissions Test - Statistical Analysis 
This project is a data analysis report of LSAT (Law School Admission Test) multiple-choice questions, conducted for my final project in my Data Modeling II class at UW-Madison. For the project, we analyzed whether there was a strategy for guessing the answer to a multiple-choice question that is more likely to be correct than randomly guessing. This was a partner project with my classmate, Ben Kizaric.

## Tech 
- `R (programming language)`
- `Posit (formerly RStudio)`
- `Python`

## How we did it
We first acquired LSAT answer sheets from an official LSAT prep source. But since we couldn't get them as usable data files, we had to manually output the questions and answers ourselves into text files. 
After cleaning the data, we then used a self-written Python script to convert the text files into CSV files. 

With CSV files, we analyzed the data in Posit, using R. We used analysis methods like monte-carlo simulations to verify our hypothesis about the data. We also visualized the data using various charts and graphs.

Unfortunately, we didn't discover any statistically significant answer-guessing strategies, but we did discover that the LSAT multiple-choice tests are much less likely to have the same letter answer be correct in a row, compared to a randomly-generated answer sheet. 

## How it could be improved
- More recent data - The available answer sheets were several years old.
- Explore further answer-guessing strategies.

## To open
- Download and open the PDF version: <a href="https://github.com/msatula/LSAT-Data-Analysis/blob/main/LSAT_Data_Analysis.pdf">`LSAT_Data_Analysis.pdf`</a>

Or view the HTML (with no page breaks):
1. Download <a href="https://github.com/msatula/LSAT-Data-Analysis/blob/main/LSAT_Data_Analysis.html">`LSAT_Data_Analysis.html`</a>
2. Open the file in your web browser
    

## Sample Screenshot
![Screenshot of one of our confidence interval graphs](https://github.com/msatula/LSAT-Data-Analysis/blob/main/95%20Confidence%20Interval.png)
