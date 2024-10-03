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

Then based on the assumptions made, we can form the following expectation formula as the expected customer churn due to change in the variable multiple products. Furthermore, the expectation, according to the assumptions made, can be extended to cover more priors: $E\[\text{custoemr churn}|\text{multiple products}\] = E\[\text{custoemr churn}|\text{multiple products}, \text{previous purchases (product count}, \text{age}, ...\]$. The next step is building a causal model. 

A causal model takes target variable, treatment, common causes, and instruments. Common causes are the features that effect target variable and treatment. Instrument has effect on treatment, but not directly the target variable. In the above example, salary is a common cause, while age is an instument.

__To validate__ the causal effect of the treatment on outcome, we can employ __refutation technique.__ This technique can be perfromed by intorducing a ranmly generated variable to the model and test if the causal estimate significantly change. Other approaches are: repalcing treatment with placebo, replacing the outcome with a dummy (unrelated) variable, or refute with bootstrapped random sample (generate multiple bootstrapped samples from the data and estimate the causal effect on each sample). 


# Time series analysis for strategic marketing planning

Time component in most cases effects marketing strategy outcome. Identify overal trends, seasonality, and anomalies helps to identify the temporal effects on marketing campaign. While analyzing impact of time series components provides a valuable insight for an efficient and timely marketing campaign, time series forecasting helps marketers to optimize marketing goals. Some examples of such uses are:
- to increase off-season sales, forecasting the types of off-season promotions that may result in the highest sales helps to improve marketing performance.
- in case marketing goal be to sale items in inventory, a time-series forcasting model cna help to identify demands in different regions or demographics and help marketers to focus their strategy on selling items according to demand in different regions.
- a marketing strategy for promoting a new product/service, with the help of a time-series forecasting model can identify the best time to start a promotion campagin based on the expected demand rises or falls of similar product categories.

__Time series algorithms__
- statistical based models: ARIMA, SARIMA, Exponential smooting (EST), and Gerenalized autoregressive conditional heteroskedasticity (GARCH).
- machine-learning based models: regression, tree-based ensemble models, and SVM.
- deep learning based models: RNN, LSTM, MLP, CNN, combination of LSTM and CNN, and time-series specific architectures such as N-Beat and NHiTs.
- transformers based models: Temporal fusion transformers (TFT) 


# Semantic analysis in marketing

__References__
- [Berger etal., Uniting the Tribes: Using Text for Marketing Insight - 2019](https://journals.sagepub.com/doi/10.1177/0022242919873106)

The emerge of new approaches with the invent of transformers architectures creates new era in the field of NLP. In the field of marketing, nlp helps to uderstand csutomer sentiment for shaping a marketing strategy, or refine a brand massesing. It also can improve customer experience by means such as creating an automeated chat system and AI enhanced assistant system. Furthermore, it enables marketers to sort through unstructured text data such as customer feeback, soclial media, and product reviews. Bedide monitoring brand reputation, nlp can be used to tailor marketing massages based on customer preferences.

Nowadays, sentiment analysis plays an important role in marketing. It acts as a guide for merketers to understant how people feel. Applications of sentiment analysis in marketing can be summarized into following buckets.
- __brand monitoring__: real time monitoring of brand perception across different platforms by tracking shift in sentiment provides marketers ability to anticipate and mitigate potential PR crises.
- __campaign analysis__: examnine emotional response to a marketing campaign allows for agile strategy adjustments. It reveals to marketer whether a campaign resonates positivel y with the tarrget audience, or there is a need to make some modifications.
- __product feedback__: apply sentiment analysis can pinpoint specific aspects of products or services that delight or disappoint customers. This aids to understand customers needs and address them in the next product/service update.
- __market search__: employ sentiment analysis creates a competitive edge by uncovering trends, competitor standings, and gaps in the market. For example, YouTube uses viewer preferences and trend in its recommendation algorithms. 

## methods
Transformers based algorithms, LLMs, and Generatve aI (GenAI) all transformed sentiment analysis. However, some of the techniques have downsides such as computational expense and massive processing power requirement, generating unforeseen inaccurate results or biased responses, and requirement for additional infrastructure to run them. 

Beside more advance techniques, still there is a room for traditional ruled-based method to be used for sentiment analysis. Specially when the task in hand does not require more sophsticated approaches, or the gain vs cost can not justify the use of methods such as LLMs. 

Some of the packages for text processing are
- [NLTK](https://www.nltk.org/)
- [TextBlob](https://textblob.readthedocs.io/)
- [Gensim](https://radimrehurek.com/gensim/)



# A/B testing and marketing
One application of A/B testing in the field of marketing is to help tailor marketing massage to target customers instead of mass marketing to the entire otential customer base. A/B testing can help to decide which predictive model is more suitable for a given marketing effort. In this capacity, results of differnet models addressing the same problem are compared and A/B testiing is used to pick the best model.

# Application of recommendation models in marketing

Personalizing recommendation for a product/service has become a norm with the advancement of technologyu and availablity of data. In the field of marketing, personalized marketng campaign is a proven approach to work much better for dricing customer engagements and conversions compare to conventional maxx marketing campaign. One example of the tasks that recommendation model can be utilized for is market basket analysis that helps marketer better uunderstand which items/services are frequently bought together.

Market basket analysis answers to questions such as which product/s shoud be recommendded to customers who are buying product i, or what product needs to be close to another group of products so customers can easily fin them. 

A conventional approach to market basket analysis is _associationn rule_ method. It computes the significance of itemset occurance in a transaction, by using a set of rule-based machine leearning methods. Associattion rule has two parts: antecedent and consequence. Antededent defines condition of a rule and consequent shows the result of a rule. Association rule uses 5 metrics to compute the strength of association rules:
1. support: the frequency an itemset occurs in the dataset
2. confidence: the conditional probability of itemset (X,Y) occuring given that the antecedent X has occurred: P(X,Y | X). The confidence value will be 1 if the consequent always occurs with the antecedent.
3. lift: measures how much more often itemset (X,Y) occurs together than if the antecedent and consequent were independent events. It is the ratio of confidence over support. If the antecedent and the consequent are independent, the lift score will be 1.
4. leverage measures the difference between the frequency of the antecedent and the consequent occuring together and the frequency of the antecedent and consequent if they were independent. $leverage = support(X,Y) - Support(X) support(Y)$. Leverage values range between –1 and 1 and if the antecedent and the consequent were independent, the leverage value will be 0.
5. conviction measures how much the consequent depends on the antecedent. $conviction = \frac{1-support(Y)}{1- confidence (X->Y)}$. If the antecedent and the consequent are independent, then the conviction will be 1. On the other hand, if the confidence of the antecedent and consequent is 1 or if the consequent always occurs together with the antecedent, then the denominator becomes 0 and the conviction value becomes infinite.

## Modern algorithms

Among various approaches in building recommendation systems, some of the methods more frequently are used are as follow:

- __Collaborative filtering__ in two flavors user-based and item-based
- __Content-based filtering__
- ___Predictive models__
- __Hybrid models__

### Collaborative filtering: user-based and item-based
This method uses previous user behaviors, such as pages they viewed, products they purchased, or ratings they have given previously to find similar products or content to those that the users have shown interest in previously. The collaborative filtering algorithms are often built based on the similarities between users or items:
- User-based collaborative filtering uses data to find similar users based on the pages viewed or products purchased previously.
- Item-based collaborative filtering uses data to find items that are often bought or viewed together.

The key to the collaborative filtering algorithms is to find similar users or items. There can be various metrics that can be used to measure the similarities between users or items, such as Euclidean distance, Manhattan distance, or Jaccard distance. However, cosine similarity is one of the most frequently used similarity metrics in collaborative filtering, as it focuses more on the directional similarity over the magnitude of the distance.

### Content-based filtering
Content-based filtering method uses the characteristics of products, contents, or users to recommend those that match a user’s preferences.
### Predictive modeling
Predictive models can also be used to build a recommendation model. A predictive model can identify the items that the users are highly likely to be interested in seeing or purchasing, based on the existing data. Furthermore, the probability output of its predictions can be used to rank the items so that more likely items are shown to the users before other less likely items.

### Hybrid models
Blending different approaches for recommendations can help improve the recommendation accuracy that single-approach recommendation systems may miss. This is to some extend, similar to ensemble models, in which the results of multiple models is more accurate that a single model.

## Other approaches to build a recommendation models

- Bestsellers or top views
- Trending
- New arrivals
- Promotions



---
# Clustering analysis for customer segmentation
It is a proven fact that targeted marketing is more effective that conventional mass marketing approach. One important toolbox for data scientist is the unsupervised methods that can be used to segment customers prior to lunching a marketing campaign. Futhermore, targeted strategy based on customer segment such as geography, demographic, or interest can be used to segment customers. 

One of the basic customer segmentation method is to divide customers into repat and one-time customers. Repeat customers are more reliable, and retiaining them requires less investment. Furthermore, allocating resources to retain repeat-customers can lead to building brand loyalty.

__Clustering algrorithms__

Beyound clustering customer based on repeat vs one-time customer identifier, segmenting customers when we have more than one factor requires unsupervised machine learning method. In most cases, there are an infinite number of ways and values you can segment the customers by. Even with limitd number of features, finding an appropriate cut-ff for each factor to break down the customer base is a challenging task. Finally, deciding about how many segment to create requires robust analysis. The clsutering algorithms (such as k-mean, k-mode, and k-prototypes) is one of the most frequently used machine learning algorithms for segmentation task. 

Customer segmentation methods is not limited to clustering algorithms. Although, still clustering is the go to approach for segmentation, the new algorithms such as LLMs can be used for customer segmentatation.

__Evaluate a clustering model__: to evaluate a clustering model, the following factors are needed to be considered:
- Model performance: employ metrics such as Silhouette scores and Calinski-Harabasz Index can be used to determine model performance. This comes handy when we ant to decide about number of cluster. We can perform experiment with a range of number of cluster, and pick the one with highest score.
- Distribution of points in a cluster: beyound evaluating model performance, it is important to check if the data points in each cluster are evenly distributed. 



# Employ zero-shot, few-shot, and retrieval-augmented generation (RAG) in marketing











