---
layout: default
title: Your Project Title
---
# Instacart Basket Analysis

### [Github Repository](https://github.com/kirstencurrie/cf_instacart)

<br>

## Intro

This was a theoretical Instacart project meant to analyze product sales via Products, Orders, and Customer datasets. 

Original data was accessed by Instacart and actual customer names & other variables such as prices had been imputed to protect information.

Leveraging Python using Jupyter Lab Notebooks, the Instacart data was cleaned, wrangled, and prepared for analysis. One of the datasets contained over 32 million rows of data, which in turn required troubleshooting techniques in order to run the study smoothly. In the end, sampling 20% of the data was selected in order to conduct the analysis.


![Frequency of purchases made by age group](assets/img/ic_age-income.png)
***FIG. A:***  *A frequency chart illustrates which age groups spend the most money; a clear increase is seen at the age 40 mark*

<br>

## Data Aggregation

With millions of data insights at hand, you can imagine the challenge of being able to glean insights without the ability to group the variables into more meaningful categories.

With the help of data aggregation (calculating average, min, max, etc) and column flag creation (creating new data variables that consolidated age groups, customer loyalty, shoppers by time of day, etc), capturing a sense of which products customers were drawn to became much easier, and a narrative was much simpler to form.

![Screenshot of Jupyter notebook showing creation of customer flags](assets/img/ic_customer-flags.png)
***FIG. B:***  *Screenshot of a Jupyter Notebook script detaling the creation of age group by customer loyalty crosstabs*

<br>

![Distribution of shoppers by time of day in custom created customer profile types](assets/img/ic_shopping-times.png)
***FIG. C:***  *Here shoppers are arranged to groups by time of day they shop; though a small portion of the populous, Insomniac shoppers still must be accounted for.*

<br>

![Pie chart of customer age group distrobution](assets/img/ic_age-distro.png)
***FIG. D:***  *Customer ages were grouped into broader categories by creating new data variable columns in Python*

<br>

![Bar char showing breakdown of shoppers by parent age group](assets/img/ic_parent-ages.png)
***FIG. E:***  *Older parents surpass the other parent age groups the customer pool in terms of customer loyalty*

<br>

## Conclusion

The ability to create groups and join data within Python provides an infinite possiblity for exploring relationships within the data. Insights from this study was able to highlight how categories like bulk food, pet products, and alcohol were struggling and require new marketing strategies to bring them back to life. Frequency checks showed stakeholders how timeliness matters and how weekends were essential for their consumer.


Further studies could provide analysis into regional sales and how exactly timeliness and customer profile types could impact sales there.

![Grouped bar chart comparing customer loyalty shopping habits by product type](assets/img/ic_customer-segments.png)
***FIG. F:***  *Customers are divided into loyalty segments (New, Regular, and Loyal) then categorized by their shopping preferences. Produce is a clear winner.*

<br>

---

### [See Next Project](project1.md)
