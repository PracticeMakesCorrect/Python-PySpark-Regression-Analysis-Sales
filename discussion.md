## Discussion

Predictive power is modest:

- Linear Regression explained about 3% of the variance in ASV. This confirms that a strictly linear relationship between ASV and the chosen fields (industry, revenue, employee count) is weak. 

- Gradient Boosted Trees (GBT) performed better, roughly four times stronger than linear regression. Therefore, nonlinear interactions between fields capture more of the variation in ASV.

- Which variables are most predictive of higher ASV?  
  - Employee count (34%) and annual revenue (43%) together dominate the model.  
  - Industry categories contribute under ~13%, which is comparatively minor.
  - This means that company size is by far the biggest driver of ASV, while industry classification plays a small role.

**Takeaway:** Larger companies (by revenue and headcount) tend to sign bigger deals, regardless of industry. Industry adds some nuance, but not enough to be a major predictor on its own. From a business perspective, targeting accounts based on size metrics yield more reliable expectations of deal value than relying on industry.

## Next Steps

This analysis shows some meaningful patterns, but also highlights the limits of the current dataset. I would try a Pareto analysis in case that shows stronger trends. 
