# 🎬 Exploratory Data Analysis: Supermarket Sales

This project aims to explore supermarket customer data and find patterns or insights related to the behavior of customers who subscribe or not.
---

## 🧠 Background

- Is it effective if we create members for customers?
- Is the transaction time (hour or day) different between member and non-member customers?
- Of all the existing branches, which branch customers have the least to register as members?
---

## 📁 Dataset

- Source: dummy dataset
- Number of rows and columns: 1000 rows, 17 columns
- Important features:
  - Invoice ID: Column that contains a unique number that distinguishes each transaction
  - Branch: Column that contains the branch from which
  - City: Column that contains the city name
  - Customer Type: Column that contains whether the transaction comes from a member customer or a non-member customer
  - Gender: Column that contains the gender of the customer
  - Product Line: Column that contains information about the product category
  - Unit price: Column that contains the price per unit.
  - Quantity: Column that contains the number of product purchases
  - Tax 5%: Column that contains the tax value of 5% of the unit price.
  - Total: Column that contains the price (unit price * quantity) + tax
  - Date: Column that contains the transaction date
  - Time: Column that shows the transaction time
  - Payment: Column that shows the type of payment method for each transaction by the customer
  - Cogs: Total costs incurred by the company to produce or obtain goods or services sold
  - Gross margin percentage: Percentage metric that measures the efficiency of the company in generating profits from operational activities.
  - gross income: total income received by a person or company in a certain period, before deducting taxes, operating costs, or other deductions.
  - rating: an assessment or ranking that indicates the level of quality, capability, or popularity of a product.

---

## 🧰 Tools & Library

- Python (Google Colab)
- Pandas
- Seaborn & Matplotlib


## 🧪 Analysis Steps

1. **Import & Cleaning Data**
   - Mengecek outlier tiap kolomnya
2. **Exploratory Data Analysis (EDA)**
   - Distribution of Number of Member vs Normal Customers
   - Average Purchase: Total and Number of Items
   - Average Rating per Customer Type
   - Total Income (Gross Income) from Each Customer Type
   - Product Type Distribution between Member vs Normal
   - Are transaction times (hours or days) different between member and non-member customers?
   - Of all the existing branches, which branch has the fewest customers registering as members?
3. **Visualisation**
   - box plot, histogram, barplot

---

## 📌 Insight Utama

1. Customer members have been proven to contribute significantly to revenue.
    This shows that the member program is quite effective financially.

2. There are different behavioral patterns between members and non-members in terms of transaction time.
    This can be used to develop a more targeted time-based promotion strategy.

3. The distribution of members is not evenly distributed across all branches.
    Some branches still have the potential for growth in the number of members if a more intensive approach is taken (eg: local referral programs or special member events).

###The membership program has been proven to contribute significantly to revenue, and shows unique transaction patterns that can be further utilized. It is recommended to increase member participation in branches with low participation through local loyalty programs, as well as conduct further analysis of repeat purchase behavior to form a long-term retention strategy.
---

## 📎 Link Project

- 💻 Google Colab: [Klik untuk melihat notebook]( https://colab.research.google.com/drive/1lQyG6daFYydwfX3ux7i_-gcjGy-oESyt?usp=sharing)
