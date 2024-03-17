# All the analysis

**Cash Loans Dominance:** Most customers have opted for cash loans, which seem to be associated with a lower default rate.

**Gender Distribution:**
- A majority of loans were taken by females, who exhibit a lower default rate (around 7%) compared to males.

**Accompaniment Status:**
- Unaccompanied individuals are the primary recipients of loans, with a default rate of approximately 8.5%.

**Income Type:**
- Safer loan segments include working individuals, commercial associates, and pensioners.

**Education Level:**
- Applicants with higher education levels display a notably lower default rate, at less than 5%.

**Family Status:**
- Married individuals represent a safer demographic to target, with a default rate of 8%.

**Housing Situation:**
- Applicants owning or residing in a house/apartment demonstrate a safer profile, with a default rate of around 8%.

**Occupation Type:**
- Certain occupations, such as Low-Skill Laborers and drivers, are associated with higher default rates. Conversely, accountants exhibit lower default rates, while Core staff, Managers, and Laborers present default rates ranging from 7.5% to 10%.

**Organization Type:**
- Certain organization types, such as Transport type 3, show higher default rates, while others like Others, Business Entity Type 3, and Self-Employed individuals have default rates around 10%.

**Univariate Numeric Variables Analysis:**
- Loans predominantly fall within the price and credit amount ranges of 0 to 1 million. Additionally, annuities and customer incomes typically range from 0 to 50,000 and 0 to 1 million, respectively.

**Bivariate Analysis:**
- Positive correlations are observed between the credit amount (AMT_CREDIT) and goods price (AMT_GOODS_PRICE), with higher credit amounts linked to lower default rates. Customers with incomes below 1 million, especially those taking loans of less than 1.5 million, may exhibit higher default rates. Families with 1 to fewer than 5 children are safer loan candidates. Annuities of 100,000 are associated with higher loan acceptance rates, particularly for amounts below 2 million.

**Analysis on Merged Data:**
- Previous loan applications for repair purposes experience the highest number of cancellations. Moreover, 80-90% of previously canceled or refused applications are repaid in the current dataset. Conversely, unused offers from previous applications now have the highest number of defaulters despite targeting high-income customers.

# Final Conclusion/Insights

**Target Demographics:**
- Low-income individuals (below 1 million) working in specific organization types (Others, Business Entity Type 3, Self-Employed) and occupations (Accountants, Core staff, Managers, Laborers) are prime candidates for loans. Married individuals with housing stability and a moderate number of children are preferred. Higher education and female applicants are also favorable.

**Loan Amount Recommendations:**
- Credit amounts should generally not exceed 1 million, while annuities up to 50,000 are advisable. Additionally, targeting customers with incomes below 1 million is recommended.

**Strategy Adjustments:**
- Banks may reconsider previously refused or canceled applications, as a significant portion (80-90%) of these applicants repay loans successfully.

# Precautions

- Organizations classified as Transport type 3 and occupations such as Low-Skill Laborers and drivers should be approached with caution due to their higher default rates. Unused offers from previous applications targeting high-income customers should also be handled carefully.

- Dataset: https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter
- Acknowledgments: Learnerea
