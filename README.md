## L120 - Driving Business Impact with Data Science: Customer Journey Analytics Lab Materials

Welcome to the repository for **L120 - Driving Business Impact with Data Science: Customer Journey Analytics Lab** at Adobe Summit 2024. This resource is meticulously designed to showcase how Customer Journey Analytics (CJA) serves as an invaluable component of modern data science workflows. Through this lab, participants will gain hands-on experience with CJA's capabilities in data formatting, feature selection, and the on-the-fly pre-aggregation and preparation of data. We'll explore how to maintain consistency with analyst teams' data interactions, and importantly, how to bring enriched data back into CJA for further analysis. This cycle not only democratizes data access across teams but also facilitates its activation through audience creation and other impactful strategies.

## Introduction

The materials contained within this repository, presented at Adobe Summit 2024, are crafted to provide you with an end-to-end understanding of analyzing and leveraging customer journey data. You'll learn how CJA integrates into data science workflows, enhancing your ability to perform sophisticated data manipulation, visualization, and predictive modeling. From data formatting and feature selection to pre-aggregation and data preparation, these resources will guide you through working with data in ways that align with your analyst teams' operations. Moreover, you'll discover how to bring your data findings back into CJA for further exploration, democratization, and activation, empowering you to make data-driven decisions that drive real business impact.

## Notebooks Overview

Here's what you'll find in this repository:

- [**Notebook 1: Querying CJA Data**](query_data.ipynb) - Introduction to data retrieval from CJA for analysis.
- [**Notebook 2: Clustering & Propensity Modeling**](clustering.ipynb) - Advanced analytics for customer segmentation and behavior prediction.
- [**Notebook 3: Visualizing CJA Data**](visualize_data.ipynb) - Techniques for creating insightful data visualizations.
- [**Notebook 4: Ingesting Data Back into AEP > CJA**](ingesting_data.ipynb) - Strategies for feeding processed data back into Adobe Experience Platform.
- [**BONUS NOTEBOOK: CJA Data View Solution Design Reference Generator**](cja_dataview_solution_design_reference_generator.ipynb) - A tool to assist in the design of CJA Data Views.

## Getting Started

To explore these materials, ensure you have Jupyter Notebook installed. Clone this repository and open the notebooks in Jupyter to interact with the pre-configured code cells and conduct your analyses.

## Dependencies

Ensure the following Python libraries are installed to fully utilize the notebooks:

- `pandas`
- `requests`
- `json`
- `PyJWT` (include `PyJWT[crypto]` for security features)
- `pathlib`
- `pytest` (for testing purposes)

## Reference Links

- **cjapy GitHub Repository**: [https://github.com/pitchmuc/cjapy](https://github.com/pitchmuc/cjapy?tab=readme-ov-file)
- **CJA API Documentation**: [Adobe CJA APIs](https://www.adobe.io/cja-apis/docs/api/) | [Use Cases](https://www.adobe.io/cja-apis/docs/use-cases/)
- **Adobe Developer Console Guide**: [Getting Started](https://developer.adobe.com/developer-console/docs/guides/getting-started/)

## License

This collection of lab materials is made available under the [MIT License](LICENSE). Feel free to explore, modify, and distribute these resources as you navigate the intricacies of Customer Journey Analytics.
