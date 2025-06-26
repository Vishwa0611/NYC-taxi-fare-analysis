
# 🚖 NYC Taxi Fare Analysis Based on Payment Methods

## 📌 Objective
The goal of this project is to **analyze the relationship between total fare amount and payment method** in NYC taxi trips.  
By using **descriptive statistics**, **A/B testing**, and **linear regression**, we aim to uncover whether the way a customer pays (credit card vs. cash) has a measurable impact on the fare amount and trip patterns.

---

## 📊 Problem Statement
In today’s fast-paced taxi booking industry, **maximizing revenue is essential** for both long-term success and driver satisfaction. While many factors influence fare amounts, **payment methods** are often overlooked.

This project explores:
- Whether customers who pay by **card** tend to take **longer and higher-fare trips** than cash users.
- How taxi services can **leverage this insight** to optimize pricing and encourage more profitable behaviors through **digital payments**.

---

## 🧠 What We Did

| Step                 | Description                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Descriptive Analysis | Analyzed key variables such as fare amount, trip duration, distance, and payment types. |
| Hypothesis Testing   | Performed a T-test to compare fare amounts between credit card and cash users. |
| Regression Analysis  | Implemented linear regression to examine how trip duration affects fare amount. |

---

## 📈 Key Insights

- 💳 **Card-paying customers** tend to take longer trips and pay **higher fares** on average than cash-paying customers.
- 🧍‍♂️ **Single-passenger rides** dominate both payment types but are **more common in card payments (40.08%)** than cash (20.04%).
- 📉 The **regression model** shows that for each additional minute of trip duration, the fare increases by **₹0.69**, with a base fare of **₹2.53**.
- 📊 The model has an **R² score of 0.76**, indicating a strong relationship between trip duration and fare amount.

---

## 💡 Recommendations

- Encourage **card payments** by offering **small discounts or loyalty rewards** to boost average revenue.
- Promote **cashless options** as they are linked to **higher fare values** and **customer convenience**.
- Provide **secure and seamless card payment options** to enhance adoption.
- Use **passenger count and payment method** together to understand behavior and design better pricing strategies.

---

## 🛠️ Tools & Libraries Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Linear Regression, Metrics)
- Statistical Testing (T-test)

---

## 📁 Folder Structure

