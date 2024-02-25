# L120 - Driving Business Impact with Data Science: Customer Journey Analytics Lab Materials

Welcome to the repository for **L120 - Driving Business Impact with Data Science: Customer Journey Analytics Lab** at Adobe Summit 2024. These materials are designed to showcase how Customer Journey Analytics (CJA) can be integrated into modern data science workflows. Through hands-on exercises, participants will learn how to leverage CJA's capabilities in data formatting, feature selection, pre-aggregation, and data preparation, all while maintaining consistency with analyst teams' data interactions. Furthermore, we'll explore how to enrich data analysis and bring findings back into CJA for further exploration and activation.

## Introduction

The materials contained in this repository, presented at Adobe Summit 2024, aim to provide an end-to-end understanding of analyzing and leveraging customer journey data. You will gain practical experience with CJA's integration into data science workflows, enhancing your skills in sophisticated data manipulation, visualization, and predictive modeling.

## Notebooks Overview

- [**01 Querying CJA Data.ipynb**](01 query_data.ipynb): Introduction to querying data from CJA for analysis. This notebook covers setting up credentials, exploring Data Views, and discovering Metrics and Dimensions within CJA.

- [**02 Visualizing CJA Data.ipynb**](02 visualize_data.ipynb): Techniques for creating insightful data visualizations. This includes retrieving and processing CJA data, visualizing trended orders, and forecasting future orders using SARIMAX.

- [**03 Clustering & Propensity Modeling.ipynb**](03 clustering_and_propensity.ipynb): Advanced analytics techniques for customer segmentation and behavior prediction. This notebook delves into clustering using t-SNE and DBSCAN, building a propensity model to predict future customer actions, and exporting data for further analysis.

- [**04 Writing Data to AEP > CJA.ipynb**](04 writing_data_to_aep.ipynb): Strategies for feeding processed data back into Adobe Experience Platform and CJA. It outlines creating a schema and dataset in AEP, ingesting data, and reviewing results in Analysis Workspace.

- [**05 CJA DataView Solution Design Reference Generator.ipynb**](05 cja_dataview_solution_design_reference_generator.ipynb): A tool to assist in the design of CJA Solution Design Reference Documentation. It automates the generation of a comprehensive spreadsheet detailing all metrics and dimensions available in a selected CJA Data View.

## Getting Started

To explore these materials, ensure you have Jupyter Notebook installed. Clone this repository and open the notebooks in Jupyter to interact with the pre-configured code cells and conduct your analyses.

## Dependencies

Ensure the following Python libraries are installed to fully utilize the notebooks:

- `cjapy`
- `pandas`
- `plotly`
- `json`
- `jwt`
- `requests`
- `sqlalchemy`
- `datetime`
- `sklearn`
- `numpy`
- `statsmodels`
- `warnings`

These can be installed using pip:

```sh
pip install cjapy pandas plotly json jwt requests sqlalchemy datetime sklearn numpy statsmodels warnings
```

Note: cjapy might require additional setup as it is a custom library for Adobe's Customer Journey Analytics.

## Reference Links

- **cjapy GitHub Repository**: [https://github.com/pitchmuc/cjapy](https://github.com/pitchmuc/cjapy?tab=readme-ov-file)
- **CJA API Documentation**: [Adobe CJA APIs](https://www.adobe.io/cja-apis/docs/api/) | [Use Cases](https://www.adobe.io/cja-apis/docs/use-cases/)
- **Adobe Developer Console Guide**: [Getting Started](https://developer.adobe.com/developer-console/docs/guides/getting-started/)

## License

This collection of lab materials is made available under the [MIT License](LICENSE). Feel free to explore, modify, and distribute these resources as you navigate the intricacies of Customer Journey Analytics.
