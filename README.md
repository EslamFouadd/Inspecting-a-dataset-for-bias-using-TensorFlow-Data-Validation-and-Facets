# Inspecting-a-dataset-for-bias-using-TensorFlow-Data-Validation-and-Facets
In this lab, we use TFDV to compute descriptive statistics that provide a quick overview of the data in terms of the features that are present and the shapes of their value distributions. We use Facets Overview to visualize these statistics using the Civil Comments dataset.

![img](https://www.tensorflow.org/static/site-assets/images/project-logos/tensorflow-extended-tfx-logo-social.png)

# Overview

Bias can manifest in any part of a typical machine learning pipeline, from an unrepresentative dataset, to learned model representations, to the way in which the results are presented to the user. Errors that result from this bias can disproportionately impact some users more than others.

TensorFlow Data Validation (TFDV) is one tool you can use to analyze your data to find potential problems in your data, such as missing values and data imbalances - that can lead to Fairness disparities. The TFDV tool analyzes training and serving data to compute descriptive statistics, infer a schema, and detect data anomalies. Facets Overview provides a succinct visualization of these statistics for easy browsing. Both the TFDV and Facets are tools that are part of the Fairness Indicators.

In this lab, you use TFDV to compute descriptive statistics that provide a quick overview of the data in terms of the features that are present and the shapes of their value distributions. You use Facets Overview to visualize these statistics using the Civil Comments dataset.

# Objectives
In this lab, you learn how to perform the following tasks:

Use TFRecords to load record-oriented binary format data

Use TFDV to generate statistics, and Facets to visualize the data

Use the TFDV widget to answer questions

Analyze label distribution for subset groups
