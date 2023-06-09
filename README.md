          UCI Machine Learning provided survey data to describe driving scenarios where participating 
     drivers were offered a coupon.  We can analyze relationships within the data to infer conditions 
     and cohort attributes that drive engagement, i.e. the acceptance of a coupon.  In this exercise, 
     we will strategically design a new coupon campaign to drive participation rates well above the 
     broader group mean of 56%.
     
         For context, the data includes over 12 thousand survey results, which each include details 
     on the whether a coupon was accepted, weather during each engagement, the target destination, time 
     of day, and various driver attributes including income, occupation and dining habits.  All of the 
     data was reviewed to eliminate incomplete surveys and to ensure sensible distributions of 
     the results. Specifically, null values were removed, and two variables were converted to numeric 
     value types to simplify analysis. More detail on the data preparation can be found in the 
     accompanying Jupyter notebook, located at 

     https://github.com/JOSHUAGITBERG/Customer_Coupon/blob/main/Coupon_Engagement_Analysis.ipynb   
    
     A quick survey of the data reveals some simple trends within each cohort of responders.  
     For example, the following charts show that people with friends were more likely to 
     accept a coupon relative to drivers with children, and that drivers were more likely to
     accept a coupon on sunny days.  

![alt text](https://github.com/JOSHUAGITBERG/Customer_Coupon/blob/main/images/weather_passenger.png))

     The most popular coupon type is “Carry Out and Take Away”, which were accepted at a rate of 73%.

![alt text](https://github.com/JOSHUAGITBERG/Customer_Coupon/blob/main/images/coupon.png)

     Coupons distributed between 2PM and 6PM are the mostly likely to be accepted:

![alt text](https://github.com/JOSHUAGITBERG/Customer_Coupon/blob/main/images/time.png)

     What other attributes can we leverage to drive up acceptance? 

     If we isolate acceptance by occupation, we can see that healthcare workers represent 
     two of the top three cohorts.  Combined, they accepted 70% of their coupons.  

![alt text](https://github.com/JOSHUAGITBERG/Customer_Coupon/blob/main/images/occupation.png)

     We already showed that drivers with a Friend are more likely to engage, and that the peak 
     time for coupon acceptance is 2-6PM.  If we isolate healthcare workers traveling with a friend 
     between 2-6PM, the engagement shoots to 93%. See the chart below to see the effect of this 
     stacking strategy.  

![alt text](https://github.com/JOSHUAGITBERG/Customer_Coupon/blob/main/images/summary.png)

    The above chart shows that we can strategically stack cohorts to generate highly engaged coupon 
    campaigns.  In this example, we might create an ad campaign that texts healthcare workers likely 
    to have friends during the afternoon. We can extend this methodology to other cohorts that 
    demonstrate engagement based on available targeting capabilities and relevant 
    business goals.     



