# Customer-Forecasting
## __Problem Statement__
The company is tryng to decide whether to focus their efforts on their mobile app experience or their website

## __About Dataset__
* `Avatar`: This column represent a Avatar Color chosen by the customer.¶
* `Avg. Session Length`: the average duration of sessions (in Minutes) of Mobile and Website.
* `Time on App`: the total amount of time (in Minutes) that a customer spends using the mobile App application.
* `Time on Website`: the total amount of time (in minutes) that a customer spends on the website.
* `Length of Membership`: the duration of membership or loyalty of each customer (in Months)
* `Yearly Amount Spent`:the total amount of money spent by each customer on the company's products Via an year.

### __Correlation Between Data__

![corr between data](https://github.com/arduinto/Customer-Forecasting/assets/142419799/df0f6ab3-00a9-4fe0-834c-fe57c3de725d)

### __Relationship Between Numerical Data__

![relationships between num data](https://github.com/arduinto/Customer-Forecasting/assets/142419799/538de0da-ff16-44e6-92cb-5dfc9446a276)

### __Predicted vs. Actual__

![predicted vs actual](https://github.com/arduinto/Customer-Forecasting/assets/142419799/80e49201-5366-4d64-847d-274e93f3d29c)

### **Conclusion**

* __Cross Validation Score: 98.25%__
* __Train Score: 98.46%__
* __Test Score: 98.27%__

| __Independent Feature__     |  __Coefficient__ |
| ----------------------- | ------------ |
| Avg_Session_Length      | 25.45        |
| App_Usage               | 38.79        |
| Website_Usage           | 0.22         |
| Membership_Length       | 61.49        |


### **Insights based on Output**

1. **High Model Accuracy:**
   - The model used for predicting customer spending is highly accurate. With cross-validation, training, and testing scores all above 98%, we can be confident that the model reliably predicts how much customers are likely to spend annually.

2. **Key Influencers on Customer Spending:**
   - **Average Session Length (Coefficient: 25.45):** This feature has a significant positive impact on customer spending. Longer average session lengths suggest that customers who spend more time on the platform tend to spend more money. This could imply that improving user engagement can directly boost sales.
   - **App Usage (Coefficient: 38.79):** App usage is a crucial factor. Customers who spend more time on the app tend to spend significantly more. This highlights the importance of enhancing the app experience to encourage higher usage and, consequently, higher spending.
   - **Website Usage (Coefficient: 0.22):** Website usage has a minimal impact on spending compared to other features. This suggests that while website presence is necessary, it does not drive customer spending as much as app usage or session length.
   - **Length of Membership (Coefficient: 61.49):** The length of membership is the most influential factor. Longer membership durations lead to higher spending, indicating that customer loyalty programs and retention strategies are highly effective. Encouraging long-term membership can significantly boost revenue.

### **Actionable Recommendations:**

1. **Enhance User Engagement:**
   - Invest in features and content that encourage users to spend more time on the platform, especially focusing on the app. Interactive features, personalized content, and seamless user experience can help increase session length and app usage.

2. **Focus on Mobile App Development:**
   - Given the high impact of app usage on spending, prioritize improvements and innovations in the mobile app. This could include new functionalities, better user interface design, and regular updates to keep the app engaging and user-friendly.

3. **Strengthen Loyalty Programs:**
   - Develop and enhance loyalty programs that reward long-term membership. Offer exclusive benefits, discounts, and rewards to encourage customers to stay longer with the platform, as this has the highest impact on spending.

4. **Monitor and Adapt Website Strategy:**
   - While website usage has a lower impact, it should not be neglected. Ensure the website is user-friendly and complements the app experience. Use the website to drive users to the app where possible, as it is the primary driver of spending.

By understanding these insights and implementing the recommendations, we can effectively leverage the data to drive customer spending and improve overall business performance.
