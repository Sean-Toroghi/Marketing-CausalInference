<h1>Summary and notes: Machine learning and generative AI for marketing</h1>

# Introduction
The field of marketing has been changed, or perhaps better to say evolutionalized, by the emerge of data science and machine learning methods. This transformation has fundamentally changed both the tools and methodologicies in the merketing field. It effects marketing strategies, from targeted advertizing to personalization of customer experience.  

## Evolution of marketing by machine learning :)
The use of machine learning in the field of marketing results in transition from traditional marketing methods to data-driven and machine learning enhanced methods. These new techniques improve the efficiency, effectiveness, and engagement in marketing, while providing more personalized marketing products to the audience. Such a transformation can be ssen as a shift from mass advertisement prints and radio commercial to email marketing, use of social media and machine learning to personalize and target customers.

Digital marketing creates targeted advertisement and measureable campaigns, by collecting information from search engines, social media, customer accounts, and employs new advertisement methods such as email marketing. Furthermore, the integration of machine learning leverage collected data for insights and personalization. This makes marketing capable of moving beyound demographic targeting to create highly personalized experiences and predict customer needs and behaviors. Machine learning provide can be used in the following ways in the field of meketing:
- predictive analysis and customer insights by making prediction about customer behaviors based on historical data. This leads to develop a proactive marketing strategies, from anticipating customer needs and preferences to identifying potential churn risks. Furthermroe, explanatory analysis such as clustering helps marketers to identify distinct market segments and inform about targeted marketing strategies. It enables marketers to make informed decisions, optimize marketing efforts, and foster stronger customer relationships.
- personalization at scale, by segmenting audience and sending tailored masseges, offers,a dn contents to match the interests and needs of each group of customers.
- Generative AI can be used for content creation, customer engagement, and analytics. Generative AI models can generate text, images, videos, and offer new possibilities for dynamic and personalized marketing materials.

## Data scinece in marketing 
To understand complex customer data, optimizing marketing strategies, and enhancing customer experience, knowledge of a data scientist becomes handy in marketing. The outcome of a data scientist model provides a deep understanding about how customer data and predictive analythics could be combined, and the result then be used for a highly effective marketing strategy. An end-to-end approach could be as following:
- step 1: data collection (first party and third party)
- step 2: ETL
- step 3: data analysis and preprocessing
- step 4: develop model
- step 5: customized targeted marketing

## Predictive analysis
Perhaps the most well-known application of machine learning is predictive analysis. The use of predictive analysis in marketing range from predicting which customers are likely to make a purchase to identify those with the risk of churn. Marketing strategies can also be more effective, if taken into account seasonality and trend (time series forecasting). Predictive models can be used in different capacities, including:
- email opening likelihood
- purchase likelihood
- churn prediction
- website login frequency modeling
- contact frequency modeling


For develoing a good predictive models, data scientist can leverage data including:
- demographic features about customers
- purchase history
- online behavior pattern
- social media inteactions
- search history

However, one challenge in this process is to collect the data, and also analyze and interpret the results, and translate them into actionable insights. For example, sentiment analysis helps to gain customer insights, a better understanding of customer emotions and opinions, that leads to more efficient merketing efforts. PErsonalized product recommendation is another approach to improve merketing by analyzing and interpreting customer data.

## A/B testing

A/B testing is an essential technique among other methods in the new approach to marketing. To make comparison of two version of a marketing asset, such as email or ads, A/B testing provides is a data-driven approach to optimizing marketing materials and strategies based on actual customer behavior rather than intuition. 

## Segmentation and targeting
One of the fundamental applications of data science in marketing is segmentation. This process involves dividing a broad customer base into smaller subgroups based on shared characteristics or behaviors. Techniques such as cluster analysis enable marketers to identify distinct segments within their audience, allowing more targeted and personalized marketing efforts. 

## Customer lifetime value modeling
Customer lifetime value (CLV) provides insights into how much revenue a customer is expected to generate over their relationship with the brand. CLV modeling is a key aspect of maximizing marketing effort profitability.

## integrating AI and marketing
Employ techniques such as zero-shot learning, few-shot learning, and micro-targeting with RAG, illustrates the use of AI in marketing. 


---
# Key performance indicators (KPIs)
Key performance indicators (KPIs) are great at capturing the current status or results of marketing initiatives.
A KPI is a key performance indicator that measures and quantifies the progress toward a certain goal or objective. KPIs help organizations identify strengths and weaknesses and make data-driven decisions in every aspect of business, such as marketing, finance, sales, and operation. KPIs help to track the performance of a marketing campaign and define sucess criteria. In each stage of the marketing funnel, there are KPIs associated with it. For example, siome of the KPIs during the marketing funnel could be as following:
1. awareness stage: Number of Page Views, Number of Ad Clicks, Number of Visitors, and SEO Rankings. 
2. engagement stage: Number of Opens, Number of Clicks, Number of Likes, Number of Qualified Leads, and cost per leads ($\frac{\text{cost of marketing}}{\text{number of leads}}$)
3. conversion stage: Number of Purchases, Amount of Purchases, Number of Subscriptions, or Number of Items in Cart.
4. retention stage: customer retention rate (CRR), customer churn rate (CCR), customer lifetime value (CLV), and cost per acquisition (CPA).
5. loyalty stage: number of clicks, retention and churn rates, amount of purchase, net promoter score (NPS), and number of referrals 

Some of the frequently used KPIs in digital and data-driven marketing are __conversion rate, cost per acquisition (CPA), customer lifetime value (CLV), and return on investment (ROI).__  A proper usage and definition of KPIs ahead of embarking on any marketing campaign is crucial for the effective measurement of marketing successes and failures.

Some of the visualization tools for KPIs:
- Bar charts: Ideal for comparing quantities across distinct categories, such as sales performance across different regions or products.
- Pie charts: For illustrating a composition or proportion of a whole, like market share distribution.
- Scatter plots: Use these to explore relationships between two variables, such as ad spend versus sales revenue.
- Line charts: Suitable for showing trends over time, such as website traffic growth or sales trends.
- Area charts: Typically used for comparing one or more series over time, or numeric values, such as website traffic across different channels.
- Heat maps: Effective for showcasing correlations or patterns within large datasets, such as the relationship between various marketing KPIs.
- Funnel charts: Perfect for visualizing stages in a process, particularly useful for conversion rates across a marketing or sales funnel.
- Waterfall charts: Often used for showing additions and subtractions that sum up to the total, such as cash flows.





# Examine factors affecting customer engagement, conversion, and churn

While KPIs are great to detect current status, they lack the ability to show drivers, make prediction, or identify affecting factors. This is where the data scientitst skills comes handy. An example is evaluting factors influencing customer engagement, or answer to question what are the factors actually effect customer conversion or response to an ads. Furthermore, analysing customer churn requires employing methods that go beyound simple corerlation, but get deeper into the cause and effect analysis. 

__Customer engagement__

In marketing, one of the frst factors to measure is whether an marketing strategy results in increasing the engagement rate. Potential customers need to engage with service or product a company has to offer, before convert and make purchase. Such an engagement can be measured by number of clicks or visit to a website after sending a merketing ads. To improve a marketing campaign performance, identify and predict which factors, such as socio-economic background or people from a specific region, are more likely to reposnd positive to an ads helps to target each ads to customers with higher potential to engage. As the result, understanding how potential customers interact with different components is the key to achieving higher engagement rates and the start of targeted or personalized marketing. To achive this, methods such as regression analysis is an effective approach to understand interactions among various components that affect higher or lower engagement among target customers. Regression method can be implemented with a range of algorithms, including linear regression and its variants (Ridge/LASSO) (continous target variable), logistic regression (categorical/binary target), or an ensemble tree method such as LightGBM regressor/classifier (continous or categorical target). 

__Customer conversion__

Method for analyzing customer conversion, requires to have a high capability of handling complex interactiona mong variables. This is where a linear regression model lacks and methods such as decision trees are more suitable. There can be nuemerous factors affecting a customer conversion, such as socio-econmic, age, region, gneder, seasons, and other factors. Not only single factors but also combinations of various factors may have significant influences on who may convert. A small retailor with an online store has a higher likelihood to look for a promotional shipping rate on high volume shipments than a business that provides services. 


__Customer churn__

Analyzing cause of churn helps companies to identify/optimize/change factors to reduce the customer churn rate. Machine learning methods such as regression and classification, while reveal relashioships or interacton among variables, lack in identifying causes and effects of certain outcomes. Causal analysis is typically done through various experiments with control groups and treatment or experimental groups. No treatment is given to control group, while the treatment group receives the treatment. This requires to setup an experiments prior to running a marketing campaign, and restricts the after-the-fact analysis. ]However, with the existance of data, we can run a causal analysis even after lunching a marketing campaign. 

To run a causal inference model, we __first require to make an assumption__ and form the causal effect of our interest based on the assumption made. For example, in a marketing campaign, to find potential cause for customer churn we can build the following assumptions:
- having multiple products may affect the churn rate, as customers may find it difficult to pick among similar products.
- count of products in past purchases of a customer can affect the possibility of a customer to pick more than one product, as it can be used to determine whether a customer is willing to buy more than one product.
- age, salary, purchase frequency are also can be seen as factors that affect whether a customer purchase more products.

Then based on the assumptions made, we can form the following expectation formula: $E\[\text{custoemr churn}|\text{multiple products}\] = E\[\text{custoemr churn}|\text{multiple products}\]$.












