# Customer Personality Segmentation

Unsupervised machine learning project that groups the customers of a retail company into segments so marketing can target each group.

**Tools:** Python · pandas · scikit-learn (K-Means) · Yellowbrick · Matplotlib · Seaborn


## Key achievements

- **Cleaned a dataset of 2,240 customers and 29 features:** filled 24 missing income values with the median (income was heavily skewed) and removed 182 duplicate records.
- **Chose the number of clusters with two methods.** The elbow method and silhouette scores both pointed to **2 segments**.
- **Found two clearly different customer groups:**

| Segment | Customers | Avg. income | Profile |
|---|---|---|---|
| **High-value** | 809 | ~$72K | Spend about 5x more on wine and 10x more on meat, buy in store and by catalog, and respond best to campaigns (24% took the last offer) |
| **Budget-conscious families** | 1,249 | ~$39K | More children at home, visit the website often but buy less, and use more discounts (10% took the last offer) |

## Business recommendations

- Keep running campaigns like #1 and #5 for high-value customers, since those worked best for that group.
- Turn the budget segment's frequent website visits into sales with online deals and products for kids and teens.
- Offer lower-priced options in every category to keep the budget segment buying.

---

*Completed as part Certificate for AI and Data Science through MIT Data, Systems, Society (IDSS)
