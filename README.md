# Online Retail

1. Introduction

E-commerce businesses generate large volumes of transactional data every day. Hidden within this data are patterns that reveal which customers are likely to stop purchasing (churn) and which customers are the most valuable. Identifying these patterns early allows a business to act — with targeted retention offers, loyalty programs, or personalised marketing — before revenue is lost.

This project applies the complete data science lifecycle (business understanding → data understanding → data preparation → modelling → evaluation → business insight) to a real transactional dataset from a UK-based online retailer, in order to:

    Understand purchasing behaviour through exploratory data analysis (EDA).
    Engineer customer-level features (RFM: Recency, Frequency, Monetary) from raw invoice-level data.
    Build and compare machine learning models that predict customer churn.
    Segment customers using unsupervised clustering to support targeted business strategy.
    Translate the technical results into actionable business recommendations.

2. Business Understanding

Business problem: The retailer wants to reduce revenue loss caused by customers who quietly stop purchasing. Acquiring a new customer is far more expensive than retaining an existing one, so the marketing team needs a way to (a) flag customers who are at risk of churning, and (b) understand which customer segments deserve the most retention investment.

Business questions this project answers:

    Which customers are likely to churn in the near future, based on their historical purchase behaviour?
    What distinguishes loyal, high-value customers from at-risk or low-value ones?
    How much revenue is currently concentrated in at-risk customers?
    What retention actions should the business prioritise, and for whom?

Success criteria: A churn classification model with strong recall (catching most true churners, since a missed churner costs more than a false alarm) and clear, explainable customer segments that the marketing team can act on directly.
