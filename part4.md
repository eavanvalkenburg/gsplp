# Day 21-25
## Synapse & Purview Architecture Design

There are many valid architectures that use Synapse, alone or in combination with other data services like Databricks or Azure Analysis Services. In this part of the learning path, you will design your own architecture based on a fictional customer case. The customer case has many elements, thus feel free to divide your architecture in multiple parts.

### Assignment
> Review several architectures, including, but not limited to, the links below and create and be prepared to discuss your own  standard architecture, include at least Synapse and Purview.

---
- [Azure Data platform end-to-end](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/dataplate2e/data-platform-end-to-end)
- [DataOps for the Modern Datawarehouse](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/data-warehouse/dataops-mdw)
- [Modern Data Warehouse Architecture](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/modern-data-warehouse)
- [Browse Azure Architecture](https://docs.microsoft.com/en-us/azure/architecture/browse/?filter-products=synapse&products=azure-synapse-analytics)
- [Google: azure synapse architecture](https://www.google.com/search?q=azure%20synapse%20architecture)

## Customer case

Contoso is a leading Dutch retailer with 500 stores across 20 countries (Europe and the US). They are in business for over 10 years and did grow to 20 million orders in 2020! Especially in 2020, most of their sales come via their online retail channel which is using Azure Cosmos DB to store their order data for global distribution, with multi-region writes. Data for the in-store sales are stored in a SQL database, divided over a datacenter per country. Stores in the bigger countries in Europe already moved to Azure SQL, however some countries still have their data in a private cloud.

2020 wasn't a great year for their in-store sales due to some obvious reasons and due to the pandemic, Contoso understands that their online business is here to stay. They want to leverage their (historical data) for multiple use-case:

- Understand more about customer behaviour for product planning
- Improve their loyalty program with personalization
- Operational reporting
- Improve their supply chain with forecasting

Contoso works regularly with vendors like Northwind Traders, who like to have insights in detailed sales figures for their brands. Some of these companies even want to have a copy of this data, for their own reporting/analytical needs, but Contoso is still hesitant to share this information. They are looking for advice on this topic.

**This customer case doesn't contain all the information you would have in a real-world scenario, thus feel free to add your own creativity. If you want to have your architecture reviewed, you can post it in the Teams community.**

## How to draw a diagram?

There are many options to draw a nice architectural diagram, hereby some of the options that are widely used.

- [Draw.io](https://app.diagrams.net/), which has many Azure icons included via search
- [Diagrams (Python)](https://github.com/mingrammer/diagrams), diagram as code
- Microsoft Visio
- Microsoft PowerPoint with the [Azure icon pack](https://docs.microsoft.com/en-us/azure/architecture/icons/)
- Whiteboard or paper

---

[previous-link]: part3.md
[next-link]: part5.md
[home-link]: README.md
[<img src="assets/previous.png" width="50" height="50" rotate="180" style="float:left">][previous-link]
[<img src="assets/home_button.png" style="vertical-align:middle">][home-link]
[<img src="assets/next.png" width="50" height="50" style="float:right">][next-link]
