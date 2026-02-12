# Sydney Airbnb Price Prediction using Machine Learning

## Overview

This project explores how well structured listing features can predict Airbnb prices in Sydney using machine learning models. 

The goal is to compare a simple linear regression baseline with a gradient boosted tree model (XGBoost) and evaluate whether model complexity meaningfully improves predictive performance.

---

## Problem Statement

Accurate pricing is critical for short-term rental hosts. Underpricing results in lost revenue, while overpricing reduces occupancy rates.

This project aims to:

- Predict nightly listing price (AUD)
- Identify the most influential features driving price
- Compare linear models vs gradient boosted trees
- Evaluate trade-offs between interpretability and performance

---

## Dataset

Source: Inside Airbnb – Sydney Listings Data  
Website: https://insideairbnb.com/get-the-data/

The dataset contains publicly available scraped Airbnb listing data, including:

- Property type
- Room type
- Location (neighbourhood)
- Host characteristics
- Availability
- Reviews
- Amenities
- Price (target variable)

---

## Project Structure

