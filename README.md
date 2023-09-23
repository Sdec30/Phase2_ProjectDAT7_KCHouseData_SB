# Phase2_ProjectDAT7_KCHouseData_SB

![image](https://github.com/Sdec30/Phase2_ProjectDAT7_KCHouseData_SB/assets/140704907/0acc6c9d-98e1-40a2-ba54-638367625113)

Author: **Sneha Bhaskar**

Date: 24 September 2023

# Overview

This project analyzes the King County House Sales Dataset to answer the business case question of what type of housing features to focus when building a house and selling in King County Washington, United States. Utilizing the OSEMN framework for data science, the most valuable feature for a Pro Home Builder Company would be living area square footage and zip code. Zip codes provide contextual information about property values, local demand, and building regulations, allowing builders to choose locations and tailor their designs to specific demographics strategically. On the other hand, square footage directly influences construction costs, selling price, design considerations, building grade improvements, and the house price rises as well.

# Business Problem 

The Pro Home Builder Company aims to construct residences in King County Washington, and wants to identify which housing features/areas to focus on for maximum profitability. By understanding which amenities significantly influence home prices, the company can make data-driven choices on the types of houses to build in order to optimize profits

# Key Findings 

# Top 10 Zip Codes By Average Price

![image](https://github.com/Sdec30/Phase2_ProjectDAT7_KCHouseData_SB/assets/140704907/049847b8-440a-4892-b6bd-ac21dbb76bb0)

- **Property Value**: Zip codes are often indicators of property value. More affluent areas usually have higher selling prices, which can result in greater profit margins for builders.
- **Demographics**: Knowing the demographics of a zip code can help builders design homes that appeal to the people most likely to live there, whether they are families, young professionals, retirees, etc.
- **Regulations and Zoning**: Different zip codes may have different building regulations and zoning laws, which can affect the cost and scope of a building project.
- **Market Demand**: Certain zip codes may be more desirable due to factors like school districts, proximity to amenities, or lower crime rates, affecting how quickly homes sell.
- **Comparative Analysis**: Builders can compare construction costs, potential sale prices, and profitability more accurately between different zip codes.
- **Local Partnerships**: Builders may establish connections with local suppliers and subcontractors who are familiar with the requirements and nuances of working in a particular zip code.

According to this dataset the most popular suburbs to build is:

- West Bellevue 
- Kirkland 
- Medina 
- Mercer Island
- Sammamish
- Seattle 
- Overlake 
- Education Hill 

# Square Foot Living Vs Price 

![image](https://github.com/Sdec30/Phase2_ProjectDAT7_KCHouseData_SB/assets/140704907/c4c966cd-9ffe-424d-849a-65d1258a89ba)

This visualization shows there seems to be a relatively strong linear relationship between square feet of living space and the price of a house.

1500 - 2500 sqft_living is the most observed footage of the house in this dataset

# The square footage of interior housing living space for the nearest 15 neighbors Vs Price 

![image](https://github.com/Sdec30/Phase2_ProjectDAT7_KCHouseData_SB/assets/140704907/c7cb9b45-5968-4160-9f23-f5b740baf73d)

The square footage of interior housing living space for the nearest 15 neighbours was positively correlated with house price suggests that as the size of the living space inside houses increases, the price of those houses also tends to increase, at least for a specific group of 15 neighbouring houses.

In simpler terms, bigger houses (in terms of living space) among these 15 neighbors are generally more expensive. This is a positive correlation, meaning both variables move in the same direction. When one increases, the other tends to also increase.

Understanding that larger homes tend to command higher prices in a specific area can help a builder make informed decisions on project investments and pricing strategies. This knowledge can optimize resource allocation and potentially increase profitability by catering to market demand for larger living spaces. However, this insight should be balanced with other market factors for a comprehensive approach such as grading.  

# House Grade by Price

![image](https://github.com/Sdec30/Phase2_ProjectDAT7_KCHouseData_SB/assets/140704907/19663a35-8bb5-4bd2-aa34-8bd5092e8ab3)

The visualization above shows that when the building grade improves, the house price rises as well. We can see in the bar plot that the mean house price for a home with a grade of 11 is far above other grades. While the building grade of 4 falls short of minimum building standards based on the King County grading system.

# Regression analysis 

![image](https://github.com/Sdec30/Phase2_ProjectDAT7_KCHouseData_SB/assets/140704907/e387960c-428e-4626-9910-373478ea5036)

The results of the analysis were as follows:
- The model above with an  R-squared value of 0.775, telling us that the model fits the data with an accuracy of 78%, We can confidently say that zip code is one of the strongest influencers on the value of homes in King County.
Other features that were positively correlated with price included:
- Square footage of living space, which was positively correlated with house prices.
- Building grade, which was positively correlated with house prices
- The square footage of interior housing living space for the nearest 15 neighbors which was also positively correlated with house price.

# Strategic Recommendations for a Pro Home Builder Company

To optimize the profitability and marketability of residential properties in King County, the following strategies are recommended:
- Strategic Location Selection: Prioritize property acquisition in high-value zip codes to benefit from the area's intrinsically higher property valuations.
- Optimize Living Space: Expand the square footage of the living area to align with the positive correlation observed between living space and property value.
- Quality of Construction: Employ premium-quality building materials and construction techniques to secure the highest possible building grade according to the King County Grading System. This will not only enhance the property's intrinsic value but also its appeal to potential buyers.
- Neighbourhood Composition: Opt for land parcels where the surrounding 15 residences have a higher average interior square footage. This is indicative of a neighborhood's overall property value and can positively influence the value of the new development.
By implementing these targeted strategies, housing development firms can substantially increase the likelihood of marketing higher-priced homes in King County

# Future Work 

In the future, the next steps would be reducing noise in the data to improve the accuracy of our model. Additionally, i would like to investigate certain features like proximity to good schools, other facilities like hospital, gyms, restaurants and play grounds that could eventually boost the pricing of that suburbs. 
