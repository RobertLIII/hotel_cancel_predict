# 📊 Hotel Booking Cancellation Prediction

## 📝 Project Overview
This project uses **XGBoost** to predict hotel booking cancellations based on various features such as lead time, special requests, and price per room. The model provides both **binary predictions** and **cancellation probabilities**, allowing for **dynamic pricing and deposit policies** to reduce financial losses from cancellations.

## ⚡ Features
- **Predicts hotel cancellations** using structured data.
- **Outputs both binary predictions & probabilities** for dynamic decision-making.
- **Implements business rules** (e.g., deposits for high-risk bookings).
- **Evaluates model performance** with ROC-AUC, Precision-Recall, and Confusion Matrix.
- **Feature importance analysis** to identify key cancellation factors.

## 📂 Dataset
The dataset contains features such as:
- `lead_time`: Days between booking and stay.
- `market_segment_type`: Type of booking channel.
- `no_of_special_requests`: Customer’s special requests.
- `avg_price_per_room`: Price per night.
- `no_of_adults`, `no_of_week_nights`, `no_of_weekend_nights`, etc.
- `booking_status`: Whether the booking was canceled.


## 📊 Model Performance
- **ROC-AUC Score**: ~0.94
- **Precision & Recall Analysis**: High recall for cancellations
- **Feature Importance**:
  - `lead_time` and `avg_price_per_room` are top predictors.
  - Special requests & segment type have moderate influence.

## 🎯 Business Impact
- Implement **dynamic deposit requirements** for high-risk bookings.
- Offer **discounts on non-refundable bookings** for medium-risk customers.
- Optimize **pricing strategies** based on cancellation likelihood.

## 📜 License
MIT License.

