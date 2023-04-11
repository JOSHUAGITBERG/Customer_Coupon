# Customer_Coupon


     UCI Machine Learning provided survey data to describe driving scenarios where participating drivers were offered a coupon.  We can analyze relationships within the data to infer conditions and cohort attributes that drive engagement, i.e. the acceptance of a coupon.  In this exercise, we will strategically design new coupon campaign to drive participation rates well above the broader group mean of 56%.
     For context, the data includes just over 12 thousand survey results, which each include details on the whether a coupon was accepted, weather during each engagement, the target destination, time of day, and various driver attributes including income, occupation and dining habits.  All of the data was reviewed to weed out incomplete survey results and to ensure distributions of the results are sensibly distributed.  Null values were removed, and two variables were converted to numeric value types to simplify analysis. More detail on the data preparation can be found in the accompanying Jupyter notebook.   
    A quick survey of the data reveals some simple trends within each cohort of responders.  For example, the following charts show that people with friends were more likely to participate, and that participation was greater on sunny days.

https://github.com/JOSHUAGITBERG/Customer_Coupon/blob/main/images/passenger.png

The most popular coupon type is “Carry Out and Take Away”, which were accepted at a rate of 73%.

<pic>

Coupons distributed between 2PM and 6PM are the mostly likely to be accepted:

<pic>

<pic>

What other attributes can we leverage to drive up acceptance?

If we isolate acceptance by occupation, we can see that healthcare workers represent two of the top three cohorts.  Combined, they accepted 70% of their coupons.  

<pic>

We already showed that drivers with a Friend are more likely to engage, and the the peak time for coupon acceptance is 2-6PM.  The chart below shows that if we isolate healthcare workers traveling with a friend between 2-6PM, the engagement shoots to 93%.   


\



