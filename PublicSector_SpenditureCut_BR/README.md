## **Description**

This project aims to estimate potential savings from cutting public sector wages in Brazil. The study focuses on marginal rates to protect lower-income employees. The analysis is based on data from Brazil in 2019 and uses metrics from IPEA's Atlas do Estado Brasileiro as the primary data source. The data segregates employees into three groups representing the Executive, Judiciary, and Legislative branches.

## **Methodology**

The notebook follows these key steps:

- *Data Filtering and Cleaning:* columns were renamed, and some types changed.

- *Feature Engineering*:
	- Population is calculated from percentage column.
	- Mean Wage is calculated based on range column.
	- Marginal Rate Calculations: Marginal rates are applied to each wage group to estimate the potential savings.

- *Visualizing Findings*: Graphical representations are used to better understand the potential impact of the proposed cuts.

- *Summary and Conclusion:* The final section summarizes the key findings and discusses the limitations of the analysis.

## **Key Takeaways**

- *Potential Savings:* This project provides an estimated value for the potential savings from wage cuts in the public sector.

- *Impact on Different Groups:* The analysis offers insights into how the cuts would affect employees in the Executive, Judiciary, and Legislative branches differently.

- *Data-Driven Approach:* By using real-world data, we're offered a more grounded estimation compared to hypothetical scenarios, albeit using a simplified approach.

- *Limitations and Future Work:* It is acknowledged that the study is a rough estimation and I suggest that a more detailed Probability Density Function could provide more accurate results.

Please note that this analysis serves as a rough guide and should not be considered as financial advice or a policy recommendation.


### **Appendix:**

Data Source, Atlas do Estado Brasileiro v.2.6.4:

https://www.ipea.gov.br/atlasestado/consulta/175