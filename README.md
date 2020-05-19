# Yelp-Analysis
Analyzed the Yelp dataset to predict if a business will be closed based on its business attributes.

# Motivation
Yelp very recently refreshed its board of directors and is currently transforming its business model from CPM to CPC. (impression-based internet advertising to cost-per-click performance-based model) With the new management team onboard, Yelp is now committed to mid-teen CAGRs(Compound Annual Growth Rate) from 2019 - 2023. In Yelp’s most recent earnings presentations, they state that revenues from subscription software and new partnerships are growing at 30%. However, these account for only 5% of Yelp’s total business. This means that for the short term, Yelp will drive its growth rate by pushing its sales team to growth their advertising accounts in a consistent way, while at the same time cutting operating budgets aggressively. We anticipate that the following 1-2 years will be a painful period for Yelp’s current sales representatives. We hope our model can help Yelp’s sales representatives in the following ways:

1. Filter out dying local businesses so they don’t have to call everyone on their cold call number lists

2. Utilize the time they free up to building relationships and improve client retention & explore multi-location and national accounts

3. Decide whether to onboard a business on its platform looking at its attributes and predicting if they’ll survive or not

# Data 
We worked on the Yelp data set on Kaggle
https://www.kaggle.com/yelp-dataset/yelp-dataset

# Approach
1) Started with exploratory data analysis
2) Feature selection based on data analysis
3) Model Building

# Insights and Recommendations
1) Top features of shopping malls are highly correlated than restaurants (it is easier to come up with a winning formula to make money in retail). However, it also means that non-parametric models are better suited for predicting shopping mall success.
2) Yelp’s overall strategy shifting their focus away from local restaurants seems to be a step in the right direction, because it is harder to build long-lasting relationships with customers in an industry where business life cycles are shorter

a) Restaurants:
BYOB - The restaurants that do not allow BYOB are worse off, because the decreased revenue due to lost customers are more than the additional income from selling beverages. Giving customers the freedom of choice (Yes with cork fee) gives us the best performance.

Delivery - Working with delivery options seems to be a double-edged sword, offering this service creates additional workload on the cooks and servers without additional tips. For most restaurants this seems to negatively affect the service and food quality that dine-in customers are receiving.

b) Shopping:
Happy hour- This one is self-explanatory because setting up special discounts during special holidays both attracts customers and entices them to buy more stuff than normal.

Wheelchair access- What’s worth noting here is that shopping malls that have wheelchair access as NA outperform both malls with and without wheelchair access, by a large margin too. Our hypothesis is that the former malls are in buildings or areas that are so well designed that disabled people could move around at will, and the idea of searching for handicapped-accessible pathways doesn’t even cross their minds.
