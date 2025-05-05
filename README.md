# 🚕 Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

This project explores how taxi drivers can **optimize revenue** by analyzing the impact of **payment types (cash vs card)** on fare amounts. Using real-world **NYC Taxi Trip data**, we identify patterns that can inform strategies to increase driver earnings.

---

## 📌 Problem Statement

In a fast-paced taxi industry, drivers' profitability is tightly linked to operational choices. This project investigates:

> **Does the payment method affect the fare amount?**  
> And can we gently influence customer behavior to prefer more profitable payment types?

---

## 📊 Data Overview

We used a refined subset of the NYC Taxi Trip records, focusing on:

- `passenger_count` (1 to 5)
- `payment_type` (`card` or `cash`)
- `fare_amount`
- `trip_distance` (miles)
- `duration` (minutes, derived from pickup and dropoff timestamps)

---

## 🧠 Methodology

### 1. Descriptive Analysis  
Basic statistical summaries across fare amount and payment type.

### 2. Hypothesis Testing  
Used a **T-test** to check if average fare differs significantly between card and cash payments.

### 3. Regression Analysis  
Explored linear relationships between trip duration and fare amount.

---

## 🔍 Key Findings

- **Card payments** make up **67.5%** of transactions and are **linked with higher average fares and longer trips**.
- **Single-passenger rides** are the most common for both payment types, especially cards (40.08% of card transactions).
- T-test results (T = 165.5, p-value < 0.05) allow us to reject the null hypothesis, confirming **payment method significantly impacts fare**.

---

## 💡 Recommendations

- Offer **discounts or rewards** for card payments to drive adoption.
- Ensure **secure and smooth card payment experience** to boost user satisfaction.
- Target **long-distance riders or single-passenger trips** for payment-based nudging strategies.

---

