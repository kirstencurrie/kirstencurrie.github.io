---
layout: default
title: Your Project Title
---
# Instacart Basket Analysis

[Github Repository](https://github.com/kirstencurrie/cf_instacart)

## Intro

This was a theoretical Instacart project meant to analyze product sales via Products, Orders, and Customer datasets. 

Original data was accessed by Instacart and actual customer names & other variables such as prices had been imputed to protect information.

Leveraging Python using Jupyter Lab Notebooks, the Instacart data was cleaned, wrangled, and prepared for analysis. One of the datasets contained over 32 million rows of data, which in turn required troubleshooting techniques in order to run the study smoothly. In the end, sampling 20% of the data was selected in order to conduct the analysis.


![Frequency of purchases made by age group](assets/img/ic_age-income.png)

## Data Aggregation

With millions of data insights at hand, you can imagine the challenge of being able to glean insights without the ability to group the variables into more meaningful categories.

With the help of data aggregation (calculating average, min, max, etc) and column flag creation (creating new data variables that consolidated age groups, customer loyalty, shoppers by time of day, etc), capturing a sense of which products customers were drawn to became much easier, and a narrative was much simpler to form.

![Distribution of shoppers by time of day in custom created customer profile types](assets/img/ic_shopping-times.png)


![Screenshot of Jupyter notebook showing creation of customer flags](assets/img/ic_customer-flags.png)


![Pie chart of customer age group distrobution](assets/img/ic_age-distro.png)


## Conclusion

The ability to create groups and join data within Python provides an infinite possiblity for exploring relationships within the data. Insights from this study was able to highlight how categories like bulk food, pet products, and alcohol were struggling and require new marketing strategies to bring them back to life. Frequency checks showed stakeholders how timeliness matters and how weekends were essential for their consumer.

Further studies could provide analysis into regional sales and how exactly timeliness and customer profile types could impact sales there.

![Grouped bar chart comparing customer loyalty shopping habits by product type](assets/img/ic_customer-segments.png)

