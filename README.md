# Introduction
## Main Research Question: 
How do customer demographic factors influence their purchasing behaviors? 
## Background Information: 
Walmart is one of the largest retailers globally, serving a diverse customer base, with a network of physical stores and an e-commerce platform. Walmart serves millions of customers, providing customers with a wide variety of products ranging from everyday household items to groceries, electronics and apparel at an affordable cost which aligns with their motto of offering “Everyday Low Prices.” Walmart’s vast customer base also spans across different demographics, including geographies and income levels. As the company expands its e-commerce operations, understanding customer behavior becomes essential for optimizing sales strategies and enhancing customer experience. Walmart’s significant collection of online and in-store transactions can provide valuable data and customer insights in purchasing behavior. By analyzing how demographics such as gender, age, and city category affect purchasing behavior, Walmart can develop targeted marketing campaigns and optimize inventory for popular products. For example, this analysis can help determine whether younger customers are more likely to purchase a certain product or if customers in different cities show higher spending habits. Studying this walmart dataset provides valuable insights not only for understanding the purchasing behaviors specific to walmart customers but also for drawing parallels to other real-world scenarios. These insights can guide businesses in optimizing marketing strategies, tailoring product offerings, and improving customer satisfaction across various industries.
## Goal
In this project, we will hypothesize that demographic factors influence purchasing behaviors. Specifically, we aim to explore the relationship between variables such as gender, age, occupation, marital status, and city category, and their impact on the total purchase amounts as well as product preference. By using exploratory data analysis (eda), we will identify correlations and trends (using box plots and bar plots), and we plan to employ both two–sample t-testing and ANOVA testing to further understand and break down these relationships. The indicators selected, such as demographic attributes (gender, age, marital status), provide a comprehensive view of customer preferences. These variables are theoretically relevant because they directly influence the customers’ purchasing behaviors. 
## Data: 
The dataset was from Kaggle. It represents anonymized Walmart e-commerce transaction data.
The dataset contains the following columns:
User_id: user id
Product_id: product id
Gender: sex of user
Age: age in bins
Occupation: occupation (masked)
City_category: category of the city (a,b,c)
Stayincurrentcityyears: number of years stay in current city
Marital_status: marital status
Productcategory: product category
The data set contains 550,068 records, representing a wide range of customer transactions. Its variables include both categorical and numerical types, allowing for diverse analytical methods. Hypothetically, we assume that some of the variables are going to showcase a correlation with purchasing behaviors and some do not. Here is a breakdown of how each variable is going to contribute to answering the business question:
Age: A categorical variable that provides a clear segmentation of customers into age groups. This helps in identifying distinct spending patterns and preferences across life stages, which directly answers questions about how age influences purchasing behaviors.
City Category: A categorical variable that categorizes regions into A (metropolitan), B (smaller cities), and C (towns). This segmentation helps identify urban-rural purchasing differences, addressing regional influence on customer behavior.
Gender: A binary variable that provides insights into whether male or female customers have distinct purchasing trends.
Marital Status: Another binary variable that helps explore how personal circumstances (married vs. unmarried) correlate with shopping habits and spending priorities.
Product Category: A categorical variable that represents the type of product purchased. This variable is essential for analyzing customer preferences across demographics and identifying the most popular product types for each segment.
Purchase Amount: A continuous variable that directly measures customer expenditure. It allows for comparisons between demographic segments, making it pivotal for identifying high-value groups.
Stay In Current City Years: A continuous variable that provides insights into customer loyalty and stability. Long-term residents might exhibit different spending patterns compared to new movers.

