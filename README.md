# WhichProperty
# PASSAR TUDO PRA INGLES

# 1. Business Problem.

House Rocket, located in seattle, is a company specialized in buying and selling real estate, with its profit on it

Currently, real estate choices are made manually by a team of company specialists, however, due to the complexity and cost of evaluating the profit potential of a property with so many options in the portfolio, the company has an extremely unpredictable cash flow, driving investors away. 

# 2. Business Assumptions.

The assumptions about the business problem is as follows:

- The National Realtors Association forecasts that sales prices of existing homes will average $ 218,500 this year, 5% higher than the $ 208,000 of 2014, and that new and existing home sales might reach 5.83 million in 2015, higher than in any year since the recession.
- The national Case-Schiller index tracks repeat-sales home prices across the country. It reflected national price growth of 1.3% in 2012, 9.6% in 2013 and 6.6% in 2014.

![_2015_04_housing_market_2_case_schiller](https://user-images.githubusercontent.com/72039442/117127180-2430ff80-ad72-11eb-8f31-7acb474cc8f2.png)

- [Reference](https://smartasset.com/mortgage/housing-market-2015#:~:text=2015%20Forecast&text=The%20National%20Realtors%20Association%20forecasts,any%20year%20since%20the%20recession. )


   
# 3. Solution Strategy

My strategy to solve this challenge was:

**Step 01. Data Description:** My goal is to use statistics metrics to identify data outside the scope of business.

**Step 02. Feature Engineering:** Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

**Step 03. Data Filtering:** Filter rows and select columns that do not contain information for modeling or that do not match the scope of the business.

**Step 04. Exploratory Data Analysis:** Explore the data to find insights and better understand the business

**Step 05. Convert Analysis to Business Values:** Convert the analysis that i´ve do into a business result.

**Step 6. Deploy Modelo to Production:** Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

# 4. Top 3 Data Insights

**Hypothesis 01:** Does the season that you sell influence price?

**True.** As observed, on average, properties sold in the summer are 22,000 more expensive

**Hypothesis 02:**  The valuation of the zipcode influences the price of the property?

**True.** As observed, the cheapest zip code is, on average, 230k the price of the property, while the most expensive is 1.4m

**Hypothesis 03:** If the condition of the property is bad, is it more than 30% devalued, in the mean?

**True.** As observed, if the condition of the house is "bad" it is, on average, ≅40% cheaper than the condition of good condition


# 5. Business Results

Let's recap how many properties the House Rocket business team must analyze in this data set provided and how long they would take a decision, on average 
   - let's consider that a professional can say in 1,5 min if that property can pass for a more refined analysis

|Before-After   | Dataset size  | Analysis time  |        
|:--------------|:--------------|:---------------|
|Before         | 21613         | 22 days        |           
|After          | 5629          | 6 days         |           


Our full original dataset contains records for 21,000 properties. Suppose we are going to analyze all of them and decide which ones to buy, our result achieved a profit of 23% in relation to the properties purchased, which is higher than the 10% to 15% that is usually obtained in a property sale. Thus, translating to commercial numbers.

|                        | Profit             | Worst             |
|:-----------------------|------------------:|------------------:|
| WhichProperty          | \$186,164,981.89  | \$171,777,607.99  |
| Today (AS IS)          | \$105,000,000.00  | \$35,000,000.00   |


This means that having a portfolio of 70k patients that would go through the clinical procedure to check whether they have or not a cardiovascular disease, in the **worst business scenario** the portfolio would generate a profit of **\$171.7 million** and in the **best scenario \$186.2 million**, in contrast to today's procedure that at its best has an accuracy of 65% and would generate a total of \$105 million, that's **a difference of \$81.2 million!**


# 8. Conclusions

# 9. Lessons Learned

# 10. Next Steps to Improve

**1.** **Develop an app** that intakes a portfolio of patients and assigns for each patient its respective probability of presenting a cardiovascular disease.

**2.** **Run a Design Discovery** to uncover facts that could be missing in our analysis in order to enrich the data that we have and improve the model performance.

**3.** Build a **model retraining pipeline**.



4. Os 5 principais insights de negocio:
    - Insights comprovados e acionaveis a aprtir da analise dos dados
5. Resultados financeiros para o negocio:
    - O lucro mais o menos que a empresa vai ter se cumprir com nossa analise e aplica-la
6. Conclusao:
    - Seu objetivo inicial foi alcançado?
7. Proximos passos;
    - O que pode ser melhorado no meu projeto?
    - Que coisas o implementariam?



