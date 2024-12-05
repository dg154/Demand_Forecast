Demand Forecasting Model

Overview

This repository contains a Demand Forecasting Model built using Random Forest Regressor to predict product demand based on historical data. The model uses various features such as price, store details, promotional activity, and time-based features (e.g., date, month, year) to predict the units sold for a given product in a store during a specific time period.

Key Features

Time-Series Forecasting: Forecast demand for products considering seasonal trends.

Random Forest Regressor: Uses Random Forest to predict demand based on various input features.

Date-based Features: Incorporates date, month, and year as important features for predicting demand.

Store-Specific & SKU-Specific Predictions: Customizes predictions for individual stores and SKUs.

User Input: Allows for dynamic user input to predict demand for any given scenario.



The dataset used for training the model contains historical product demand data and includes the following columns:


week: Date of the sale (Week-based format).

store_id: Identifier for the store.

sku_id: Identifier for the SKU (product).

total_price: Total price of the product.

base_price: Base price of the product.

is_featured_sku: Whether the SKU was featured in promotional activities.

is_display_sku: Whether the SKU was displayed in-store for promotion.

units_sold: Target variable representing the number of units sold (demand).
