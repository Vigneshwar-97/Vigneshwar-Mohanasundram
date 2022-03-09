# Lending Club Case Study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 


## Table of Contents
* Problem statement
* Analysis approach
* Insights

<!-- You can include any other section that is pertinent to your problem -->

## Problem statement
- The finance association which provides various types of loans to different clients When the party 
accepts a loan application
- the party has to resolve for loan authorization established the # 
claimant’s profile
- Two types of risks are guide the bank’s conclusion
◦ If the seeker is inclined compensate the loan, before not approving the loan results in a misfortune of 
trade to the association
◦ If the candidate is with difficulty to restore the loan, i.e. he/she is inclined default, before authorizing the 
loan concede possibility bring about a financial misfortune for the guest.
◦ The applicant likely beneath holds the information about past loan claimants and either they ‘defaulted’ a 
suggestion of correction.
◦ The aim search out recognize patterns which display if one is inclined default, that grant permission be 
secondhand for taking # conduct to a degree declining the loan, lowering the amount of loan, loaning (to 
dangerous applicants) at a bigger interest, etc
- loan.csv is the dataset which we used in this case study.

## Analysis approach.

- Examine the values to check whether the type assigned is suitable for analysis, if not convert it accordingly 
based on input criteria.
- Analyse the whole data check for null value rows and look for any deprecation in actual data.
- Filter out null or invalid column which are not much helpful for analysis.
- Remove inappropriate columns and rows which diverts the analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Insights
- Using univarient analysis, Annual income is plotted using box plot, It has been identified with outliers.These values can 
tilt our analysis and often provide us with a biased perspective of the data available.
- In bivarient analysis, Using linechart with variables purpose and charge off ratio we could clearly see 
small_business takes up high chargedoff ratio. It is highly risk to provide loan to 
small_business.
- In multivarient analysis, on seeing heat map it is clear that whenever the loan amount is higher then number of installment is also in propotion.
•pub_rec is directly propotional to pub_rec_bankruptcies with corr value of 0.84, if public record is higher then risk of 
defaulters will also be higher.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@Vigneshwar-97] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
