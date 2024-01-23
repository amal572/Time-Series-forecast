# Sales Forecasting Project

This project focuses on predicting the future sales quantities based on historical data of products. Leveraging real data, which includes detailed information on products and their respective quantities, the goal is to provide the company with accurate sell-out quantity forecasts. This information is crucial for informed decision-making and enables the company to effectively manage its inventory and optimize supply chain processes.

## Key Components:

### Time Series Model:

A sophisticated time series forecasting model has been developed to analyze historical sales patterns and predict future sell-out quantities. This model is essential for anticipating demand trends and making data-driven decisions.

### Workflow Management with Prefect:

The project utilizes Prefect, a workflow management system, to orchestrate Extract, Transform, Load (ETL) processes seamlessly. Data is collected from multiple sources, cleaned, and transformed, ensuring the quality and consistency of the input data for the forecasting model.

### MLflow Deployment with Flask:

For deployment, the project employs MLflow in conjunction with Flask. MLflow provides a unified platform for managing the end-to-end machine learning lifecycle, while Flask facilitates the creation of a web API for accessing the predictive model. This deployment architecture ensures accessibility and scalability.

## Performance Metrics:

The model's performance is evaluated using a mean score of absolute error, achieving an impressive accuracy rate of 92%. This accuracy metric underscores the reliability of the forecasting model, making it a valuable asset for strategic planning and operational decision-making.
