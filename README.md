java c
Credit Risk Group Project
As part of this project,you will need to analyse a portfolio of loans with CreditMetrics.Portfolio details are given at the end of this note.You should assume that the analysis is conducted on 21st November 2023.All the data you need to collect (see below)will have to be consistent with such date.
Tasks: 
1.Find model inputs. These are:
1.1.Daily prices of relevant stocks,adjusted for dividends and splits.These can be found in Yahoo Finance,DataStream or Eikon(help  line 0800442000 for both)and  Bloomberg.If you are unfamiliar with these data services,please contact the data providers for help.
1.2.Corporate yields.You can estimate the term structure of corporate bond yields across different ratings with the Nelson and Siegel(NS)method.The data to apply the NS method on corporate bonds can be found in the Excel file“US Bond data 2024 Datastream   -Students"in the“Group Project"folder in“Course Documents"on Blackboard.
1.3.US Treasury zero coupon yield curve.This can be sourced from Bloomberg,Reuters or Datastream.
1.4.A  transition matrix.Transition matrices can be found in Moody's“Annual default study …xlsx"(Excel  Data)Published on 14 April  2023.Also,familiarise yourselves with the "Annual default study:Corporate default rate will rise in 2023 and peak in early 2024" published on 13 March 2023,which provides insightful comments on the data in the excel file.You will need to register with Moody's at www.moodys.com to have access to these documents.Registration is free.
1.5.Credit ratings for each loan in your portfolio.These can be found in the Moody's website( www.moodys.com ).Simply type the name of the company of interest in the search bar on top of the landing page to find the company's rating.You may need to  register with Moody's to have access to the rating information.Registration is free.
1.6.LGD data.Aggregate LGD data can be sourced from the excel file in point 1.4.Issue  specific LGDs for a given company can often be obtained directly from the Moody's website under the"Ratings and Assessments"menu available from the company'代 写Credit Risk Group ProjectPython
代做程序编程语言s credit profile page.
2.[50%weight-Sub-questions are equally weighted] Model applications.
2.1.With CreditMetrics,full implementation and variable recovery rates,compute Absolute VaR and Absolute Expected Shortfall.Time horizon:1 year.Use two confidence intervals:95%and 99%.
2.2.Redo the calculations in point 2.1 when the time horizon is 3 years.
2.3.VaR stability:
Show with your own calculations that your VaR and Expected Shortfall in question 2.1 are sufficiently stable given the number of simulations you have used in 2.1.The stability analysis in this question should be done by writing your own Python code.Please include the code in your submission.
2.4.Stress testing:compute the absolute VaR and ES (time horizon:1 year;confidence levels:95%and 99%)under the following stress scenarios:
a.Assume stressed PDs computed as the maximum PD for each rating observed over the 1920-2022 period in the 2023 Moody's"Annual default study",Exhibit 36.
b.Assume that the zero-government bond yield curve is a linear interpolation of the 2000-2021 average 3-month US treasury rate and the 2000-2022 average 10-year US treasury yield that can be computed from“Table 2.A.Historical data:
Domestic variables,Q1:2000-Q4:2021"in the Federal Reserve Board"2023 StressTest Scenarios".
c.Assume credit spreads increase,for each rating,by the same percentage as the increase in PDsfrom the value used in 2.1 and that obtained in 2.4.a.For instance,if the PD goes up from 1%to 2.2%then the credit spread should be increased by 1.2%.
d.Compute moving average correlations of stock returns for the borrowers in your   portfolio from 2007.The time window of the moving average should be one year. Correlations should be computed with daily frequency.In CreditMetrics,assume the maximum moving average correlations for each pair of borrowers over the observation period.
e.Consider a scenario when you combine all of the above scenarios.
2.5.Do a reality check on all the above calculations.Are your results as you expect them to be?Why or why not?




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
