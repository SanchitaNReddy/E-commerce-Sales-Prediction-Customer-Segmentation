# Sales Prediction and Customer Segmentation
This project focuses on developing machine learning models to predict future e-commerce sales for a fashion retailer and segment customers based on their behavior. The project is divided into two parts:

1. Building predictive models using PySpark MLlib for offline analysis.
2. Implementing a streaming application with Apache Kafka and Spark Structured Streaming for real-time predictions and visualizations.

## Features
### Part A: Predictive Modeling
1. Purchase Prediction and Revenue Forecasting:
1.1 Use customer data and browsing behaviors to predict:
1.1.1 Whether a customer will make a purchase.
1.1.2 The potential revenue from the purchase.
1.2 Techniques: Classification models and regression models.
2. Customer Segmentation:
2.1 Use K-Means clustering to group customers based on their behavior and attributes.
2.2 Gain insights into customer preferences and tailor marketing strategies accordingly.

### Part B: Real-Time Streaming Application
1. Streaming Sales Prediction:
1.1 Integrate predictive models into a real-time platform using Apache Kafka and Spark Structured Streaming.
1.2 Process incoming data streams to make live predictions.
2. Visualization:
2.1 Consume and visualize streaming data to monitor predictions and sales metrics dynamically.

## Technologies

1. Programming Language: Python 3+
2. Big Data Framework: Apache Spark (PySpark, MLlib, Spark SQL, Structured Streaming)
3. Messaging System: Apache Kafka
4. Visualization: Matplotlib, Seaborn, and real-time dashboards
5. Environment: Jupyter Notebook, Docker
