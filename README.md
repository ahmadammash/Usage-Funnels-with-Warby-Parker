# Usage-Funnels-with-Warby-Parker
This project uses SQL queries to analyse Warby Parker's marketing funnel and the effectiveness of a controlled experiment. Warby Parker Inc. is a major retailer of prescription glasses based in New York City. The analysis is formed of two parts: 

## Quiz Funnel
This part of the analysis uses SQL queries to answer questions around the responses to Warby Parker's 5-question survey which enables customers to efficiently and conveniently find the frame that exactly matches their preferences.

The survey is formed of five questions:
- What are you looking for?
- What's your fit?
- Which shapes do you like?
- Which colors do you like?
- When was your last eye exam?

The SQL queries pull data from the responses of 500 customers to the survey in order to answer the questions:
- What is the number of responses for each question?
- Which question(s) of the quiz have a lower completion rate?

## Home Try-On Funnel
The Purchase Funnel at Warby Parker consists of three stages:
- Take the Style Quiz (in the section above)
- Home Try-On
- Purchase the Perfect Pair of Glasses

Warby Parker conducted an experiment to determine whether giving customers 3 versus 5 pairs of glasses to try on made a significant difference to their purchase rate. Half of the 500 respondents to the Style Quiz were given 3 pairs to try at home while the other half was given 5 pairs.

After creating the funnel table (showing whether the customer took glasses to try on at home, the number of pairs taken, and whether they made a purchase) using a CTE query, SQL queries were used to answer the following questions:
- What are the overall conversion rates?
- How do the conversion rates between the different stages of the funnel compare?
- How do the purchase rates differ between customers who had 3 versus 5 pairs to try at home?
- What are the most common results of the style quiz?
- What are the most common types of purchase made?
