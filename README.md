![WhatsApp Image 2026-03-22 at 21 31 04](https://github.com/user-attachments/assets/0c2ac22d-c3e1-4478-ba53-e10ab15eae18)

## Food-Demand-Forecasting-Hackathon
## Overview

The Genpact Machine Learning Hackathon is aimed at assisting a meal delivery firm to enhance operational planning by means of demand forecasting. The company has several fulfilment centres spread across a number of cities, which deliver meals to the customers every week. The weekly demand data, features of the meal that include category, cuisine, and price, and fulfilment centre data of the location, type, and operational area are available to the participants. It is now a problem of knowing the future demand in order to ensure that the centres are able to efficiently manage the stocks and resources.

## Problem Statement

Management of perishable raw materials and employees within the fulfilment centres is a problem that the meal delivery company is struggling with. Failing to make a correct prediction of demand may cause a shortage of stock, hence customer dissatisfaction, or overstocking, hence wastage. The company needs an effective forecasting tool that would help it forecast the quantity of orders per meal at a particular centre per week so that it can better plan and allocate resources to its operations.

## Objective
To make a reasonable prediction of the quantity of orders per week in each meal-centre combination in the upcoming ten weeks (Weeks 146 through 155).

To utilise the historical demand data, meal attributes, and fulfilment centre data to develop a predictive model that is reliable.

To ensure the effective acquisition of perishable raw materials by anticipating demand before it is too late.

To plan staffing at fulfilment centres with workforce planning and the desired order volume.

To minimise wastage and ensure improved efficiency in operations and delivery of products to customers on time

## Data Analysis
<img width="975" height="516" alt="image" src="https://github.com/user-attachments/assets/025cb02f-7d1c-491d-b317-1575caf59d2c" />
<img width="975" height="582" alt="image" src="https://github.com/user-attachments/assets/49480cc1-b805-473a-85b6-bc63f905ae6e" />

The pattern of distribution and boxplot of weekly demand (num_orders) indicates a highly skewed right distribution, such that most of the cases are drawn to the low value, with a few cases yielding very high orders. The small value of the compressed interquartile range and a large number of outliers support the fact that the common demand is low and stable, and, at times, the spikes are large contributors to the total distribution. This imbalance implies that several combinations of meal centres contribute to the excessive proportion of demand.


<img width="975" height="501" alt="image" src="https://github.com/user-attachments/assets/7770475c-2ae1-4bed-b45d-43bd6d8ac28e" />

Meal distribution is very skewed, with Beverages taking the lead with approximately 127,000 orders, many times higher than all other groups and may be a result of being bundled together or included with other items also. The rest of the categories (Rice Bowl, Sandwich, Pizza, Starters, etc.) are a comparatively balanced range of mid-tier (between 26,000-34,000) demand, and several categories, such as Fish and Soup, are low-demand products. This skewness indicates that a few categories contribute to a disproportionate volume, which is consistent with the Pareto Principle, and it is necessary to avoid combining the dominant categories, such as Beverages, to prevent the distortion of analysis and forecasting models.

