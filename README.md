# Predictive Analytics for Customer Churn

## Overview

This project focuses on predicting customer churn for a subscription-based service using machine learning techniques. Customer churn is a critical metric for subscription businesses, and accurately predicting which customers are likely to cancel allows for proactive retention efforts.

## Dataset

The dataset contains anonymized customer subscription and interaction data. Key features include:

*   `CustomerID`: Unique identifier for each customer
*   `SubscriptionType`: Type of subscription plan (e.g., Basic, Premium)
*   `PaymentMethod`: Payment method used (e.g., Credit Card, PayPal)
*   `PaperlessBilling`: Whether the customer uses paperless billing
*   `ContentType`: Type of content accessed (e.g., Movies, TV Shows)
*   `MultiDeviceAccess`: Whether the customer has access on multiple devices
*   `DeviceRegistered`: Device registered by the customer
*   `GenrePreference`: Customer's preferred content genre
*   `Gender`: Gender of the customer
*   `ParentalControl`: Whether parental control is enabled
*   `SubtitlesEnabled`: Whether subtitles are enabled
*   `AccountAge`: Age of the customer's subscription account (in months)
*   `MonthlyCharges`: Monthly subscription charges
*   `TotalCharges`: Total charges incurred by the customer
*   `ViewingHoursPerWeek`: Average viewing hours per week
*   `SupportTicketsPerMonth`: Number of customer support tickets raised per month
*   `AverageViewingDuration`: Average duration of each viewing session
*   `ContentDownloadsPerMonth`: Number of content downloads per month
*   `UserRating`: Customer satisfaction rating (1 to 5)
*   `WatchlistSize`: Size of the customer's content watchlist
*   `Churn`: Target variable indicating whether the customer churned (0 or 1)

The dataset consists of three files (`train.csv`, `test.csv`, and `data_descriptions.csv`).

## Libraries Used

*   pandas
*   numpy
*   matplotlib
*   seaborn

## Goal

The primary goal of this project is to build a predictive model that accurately identifies customers at high risk of churn, enabling the business to implement targeted retention strategies.

