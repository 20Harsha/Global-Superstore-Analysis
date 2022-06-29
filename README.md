# Global Superstore Analysis
Using Tableau, Story has been created to solve the global superstore case study

* **Problem Statement :** Global Superstore has been going through loss in the products sold. Identify Market as well as country wise loss & find products in which sub-category are in loss in those countries.

* The Global Superstore dataset consist of 20 columns and 51,281 rows. 
* Before analyzing the data the quality of the data has been checked using python.
* Using Business Intelligence tool Tableau the Global Superstore Story has been created. The story consist of relevant worksheets and an interactive dashboard to solve the case study where user can interact with the story created to find answers to the business questions.

**View the tableau story here :** https://public.tableau.com/views/Globalsuperstoreanalysis_16545405841970/Story?:language=en-US&:display_count=n&:origin=viz_share_link

**Youtube link for case study explanation :** https://youtu.be/oQTkR9xP4ps

## **Finding answers to the following questions**: 

**Q.1) Market wise analyze the profit for subcategories?**

Ans.

![Q1](https://user-images.githubusercontent.com/87359806/172657420-27ae67a0-86c4-4f31-a732-5a1b4962fda0.PNG)

When we look at the above heat map we observe that sub category book cases has recorded loss in market region USCA , tables has recorded loss in market region Europe, Asia Pacific, USCA & LATAM & supplies has recorded loss in USCA. Basically tables are the one in which maximum loss has recorded. When we observe grand total we could see most profitable region was Europe although tables in European market are in loss.



**Q.2) Observe the quarterly profit recorded for the subcategory which is occurring huge loss?**

Ans.

![Q2](https://user-images.githubusercontent.com/87359806/172657799-942537fb-e4e1-4a1b-8eb0-3e3a4069d112.PNG)

As from the above business question we got to know that tables are in huge loss so we select category as furniture than subcategory as tables so that we could observe the quarterly profit for tables. The average line indicates the average profit made as well color indicates the loss higher the loss dark red color will be there. For 4 years that is 2012 to 2015 this quarterly analysis has been done. We could observe that in 2012 in quarter one the loss was high in second quarter also it raised then it was decreasing. In 2013 again loss has been occurred but in quarter two, three there is an decrease in loss where as in quarter four it again raised up. Similarly in 2014 the loss has increased but in 2015 there was a drastic increase in loss for tables in quarter four the loss recorded is -$11.5K. So in 2015 tables are in huge loss compare to 2012 to 2014.



**Q.3) Market wise is their any relation between discount given v/s profit recorded?**

Ans.

![Q3](https://user-images.githubusercontent.com/87359806/172658140-b8986dd7-b618-49f5-947c-6ee0c675cf13.PNG)

When look at the above heat map we could see that there is a relation between discount & profit for the market region. When the discount percentage increases above 27% then products are occurring loss. Means when the products are sold with the discount of 27% or more than that then then rather than gaining profit loss is occurring.



**Q.4) Observe the discount given market wise for tables?**

Ans.

![Q4](https://user-images.githubusercontent.com/87359806/172658540-36b612af-e5b5-4099-9991-86a9acca26d3.PNG)

As we have seen that tables were the sub-category where maximum loss has been occurred so we can select furniture from category & tables from sub-category to observe the discount percentage for the same. So from the above heat map we could observe that beyond 20% if discount is given then rather than gaining profit loss is occurring.



**Q.5) In 2015 which are the top 5 countries with the minimum profit are recorded & which are the top 5 common subcategories which are in loss in those countries?** 

Ans.

![Q5i](https://user-images.githubusercontent.com/87359806/172658964-ba254b19-2215-46e1-a200-52bb30ca5b22.PNG)
![Q5ii](https://user-images.githubusercontent.com/87359806/172659810-4985722e-9588-4e36-a89e-62e3b8583d63.PNG)

In 2015 top 5 countries with maximum loss are turkey(-$30K), Nigeria(-$23K),
Netherlands(-$12K), Pakistan(-$9K) & Honduras(-$9K). To observe the common products we could simply hover over those place to observe the sub category wise profit analysis and we can note down the common sub categories. The top 5 common sub categories with maximum loss are Tables, Phones, Book cases, Copiers & Chairs.


**Q.6) In which subcategory maximum loss has occurred also find the average discount and profit respectively?**

Ans.

![Q6](https://user-images.githubusercontent.com/87359806/172660012-db9b7348-cc9d-46b4-8299-9c4a0692dfe7.PNG)

In the above dashboard we could observe that in the sub-category tables are the ones where maximum loss has occurred so we simply select tables from sub-category and we could now observe that average discount was gives as 29% & average profit recorded is -$74.43.

**Q.7) Identify the market region where tables sold are causing huge loss?**

Ans.

![Q7](https://user-images.githubusercontent.com/87359806/172660378-f01e2db9-6362-49fe-a108-4c664f9a89a7.PNG)

In the above dashboard when we select tables in sub-category section we could observe that Market Asia Pacific is the one where tables has recorded maximum loss and also the discount is 29%.

**Q.8) In 2015 for Market (Asia Pacific) what is the average discount given for tables?**

Ans.

![Q8](https://user-images.githubusercontent.com/87359806/172660544-d9bdf432-4e4f-4675-b061-48dffc8e0d2f.PNG)

In the above dashboard we first filter the year as 2015 then in market region we select Asia pacific then finally we select tables and now we can observe the average discount for Asia Pacific is 36%. 

**Q.9) Which country has maximum loss find out which products are causing huge loss as well find the average discount, profit & sales?**

Ans.

![9iiiii](https://user-images.githubusercontent.com/87359806/172661549-93d9c151-2206-442b-b6dc-6c7f8c1f3da7.PNG)

![Q9](https://user-images.githubusercontent.com/87359806/172666155-ffed6605-73e5-42c0-9bce-55533a348c5d.PNG)

We could basically select top 1 country with in the slider so we get to know that turkey was going through maximum loss with negative profit of -$98K .So in the dashboard when we click on turkey we could see all information regarding that country. Phones, Storage, Chairs, Book cases are in huge loss. The average discount recorded for turkey is 60% which is huge so that might be the reason for loss that has occurred as well average profit is -$71.44 & Sales are $2.19.

# **Tableau dashboard** 
![dashboard](https://user-images.githubusercontent.com/87359806/172662060-87590db6-780c-4f90-80be-5930a4d66b1e.PNG)

**View the tableau story here :** https://public.tableau.com/views/Globalsuperstoreanalysis_16545405841970/Story?:language=en-US&:display_count=n&:origin=viz_share_link 


