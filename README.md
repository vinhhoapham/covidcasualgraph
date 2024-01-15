# Analysis of COVID-19 Time Series Dynamics: A Causal Graph Approach

This project delves into the intricate relationships among countries' COVID-19 case trends. Utilizing the Temporal Causal Discovery Framework (TCDF), available at [this GitHub repository](https://github.com/M-Nauta/TCDF), we employ a Convolutional Neural Network and Attention Mechanism to uncover causal connections. Subsequently, network analysis is used to identify key characteristics of these relationships.

The core of the analysis is contained in `main.ipynb`, which includes the steps for data processing, exploratory analysis, and the application of the TCDF framework. The `TCDF` folder holds the necessary code and instructions for implementing the TCDF framework.

## Key Insights

Our analysis reveals significant findings regarding the spread and influence of COVID-19 cases across countries:

1. **Cyprus and Senegal as Central Influencers**: These two countries emerge as pivotal in influencing COVID-19 trends in other nations.
2. **Interconnectivity within the African Region**: A well-connected causal graph in this region indicates that new cases in one African country significantly impact others.
3. **Europe's Influence on Other Regions**: Europe stands out as a primary influencer of COVID-19 case trends in other regions, with the African region being notably central.
4. **Sparse Graph with Limited Connected Components**: Reflecting the impact of international travel restrictions, the causal graph is sparsely connected, with few clusters encompassing more than a couple of countries.
5. **Existence of a Global Cluster**: Despite restrictions, we observe an international cluster of countries that are interconnected in terms of COVID-19 case trends.

This study provides a novel perspective on the global dynamics of COVID-19, highlighting the importance of regional influences and international connections in the spread of the virus.
