## Amazon Vine Review Analysis
The purpose of the analysis was to determine if paid amazon reviews show bias versus unpaid reviews. 

The analysis was run on a dataset of reviews on kitchen items which initially included 4,880,466 reviews. The reviews were filtered to only include items with greater than 20 votes. It was determined that items with less than 20 votes could potentially skew the analysis. 

The filtered review dataframe included 101,229 items. These reviews were further filtered for Vine reviews and non-Vine reviews to determine if Vine reviewers show bias for products they are paid to review. 


## Are paid reviews better?
### The Results
* The analyzed dataset included 1,172 Vine reviews and 100,057 non-Vine reviews. 
* 490 of the Vine reviewers gave the product a 5-star rating. 
* 43,888 of the non-Vine reviewers gave the product a 5-star rating. 
* Overall, 44,378 of the reviews were 5-stars. 
* The total percent of Vine 5-star reviews was 1.10%.
* The total percent of non-Vine 5-star reviews was 98.90%.

## Summary
Based on the analysis there is absolutely no bias in 5-star reviews for the Vine program. If anything, there is a questionable lack of 5-star reviews from the Vine program.

Non-Vine members were much more likely to give a 5-star review to Kitchen products sold on Amazon. This may be due to individuals wanting to provide the best feedback for products they use and like, or there may be a bias in 5-star reviews from non-Vine members.

From the dataset it is difficult to determine if Vine reviews are more beneficial for a product than non-Vine reviews. Success may be defined in many different ways for an e-commerce business. Simply having more reviews over a certain threshold may provide the most benefit, or increasing the number of reviews overall regardless of score may be beneficial. So, while no bias was show in Vine reviews it is difficult to determine if paying for Vine reviews is beneficial. 

Further analysis could look into the percentage split in reviews between Vine members and non-Vine members at each star rating level. Digging deeper into each available rating could provide insight into why Vine members are less likely to give a 5-star rating to a Kitchen product. 

One theory is that Vine reviewers are cautious of giving 5-star reviews if they are paid for reviewing a product because giving the best rating may seem untrustworthy to a potential customer who knows the review is a paid review. Customers who read paid reviews which fall closer to the median may be more likely to accept the review as confirmation bias rather than rejecting the review as coming from an untrustworthy source. 