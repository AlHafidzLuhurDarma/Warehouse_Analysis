# Warehouse Storage Analysis

## Table of Contents:
* Executive Summary
* Objectives
* Data Description
* Sales Performance Report
    * Overall Performance
    * Product Sales
    * Best Performing Period
    * Customer Demographics
    * Regional Performance
* Growth Rate
    * Most Stable Products
    * Countries with the Most Consistent Growth
* Recommendations
* Limitations and Warnings


## **Executive Summary**

The data presents sales performance over the years 2011–2013 and the first month of 2014. The total revenue generated amounts to **$29.3 million**. The **fourth quarter** consistently stands out as the most stable period, with a total profit of **$9 million.**

Sales of **Bicycles** increased each year, reaching their peak in **2013 with $16 million** in revenue. Among all bicycle products, **Road Bikes** were the most popular, contributing **$14.5 million** in total revenue.

The United States emerged as the most profitable region for the company, with **U.S.** customers contributing **$9.1 million** (or **30.8% of total regional revenue**). Additionally, the **VIP customer segment** showed significant growth, expanding from just **7% in 2010** to **76% in 2013**, indicating a strong shift in the company’s customer demographics.

<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/bi_1.png" width=700 height=600>
</p>

Objectives

This analysis aims to provide a comprehensive overview of the business performance of **Gold Bike Store**, a company engaged in the sales of bicycles and related accessories, based on sales data from **2011–2013** and **January 2014**.
Specifically, this report has several key objectives:

* **Identify annual and seasonal sales trends** to determine the best-performing periods and the factors influencing sales fluctuations.
* **Analyze product performance by category** (Bikes, Components, Clothing, Accessories) and subcategory to identify the most profitable and most stable products.
* **Examine customer characteristics** based on age, customer class (VIP, Regular, New), and country region to identify potential customer segments and their purchasing behavior.
* **Evaluate each region’s contribution** to the company’s total revenue and identify opportunities for expansion in markets with stable growth.
* **Provide strategic recommendations** to improve sales performance, customer loyalty, and operational efficiency based on the data findings.


## **Data Description**

The data used in this analysis consists of historical sales records from **Gold Bike Store’s** sales system, covering the period **2011–2013** and part of **January 2014**. This dataset includes several key dimensions representing the company’s business activities, as follows:

<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/ERD.png" width=400 height=300>
</p>

* **Customer Dimension:** Contains information about the customers’ country of origin, customer class (VIP, Regular, New Customer), and age group. These variables are used to understand customer characteristics and purchasing behavior.
* **Product Dimension:** Includes product categories and subcategories such as **Bikes, Components, Clothing, and Accessories**, along with Product Line details like Road, Mountain, and Touring. These variables serve as the basis for measuring product performance and each product’s contribution to total sales.
* **Time Dimension:** Records transactions by **year, quarter, and month**, enabling the analysis of seasonal trends and performance comparisons across different periods.
* **Sales Fact:** Contains information on **revenue, units sold**, and **profit margin** for each combination of product and customer.

## Sales Performance Report

* **Overall Performance**: Sales reached their peak in **2013**, generating a total revenue of **$16 million**, with the **fourth quarter** contributing **$9 million**. **Bicycle products** remained the most in-demand category, producing a total profit of **$28 million**, which accounted for **96%** of total sales from **2011 to 2014**.

<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/pertumbuhan_perbulan.png" width=700 height=600>
</p>

* **Product Sales**:
    * **Product Profitability**: **The Road Bike** consistently dominated sales each year, contributing **$14.5 million** in total revenue. Meanwhile, **Tires and Tubes** were the most frequently purchased items, with **17,000** units sold. Although they generated only $244,000 in revenue, Tires and Tubes proved to be one of the most stable and reliable products in terms of sales volume.
    * **Weakest Performance**: The **Socks category** (under Clothing) recorded the weakest performance in terms of sales, generating only **$5,100** in revenue with 586 units sold. Although it ranked fourth in total quantity sold, it performed the worst in terms of revenue among all products.
    * **Units Sold**: The Accessories category dominated in total units sold, with 36.1K units purchased overall. Within this category, Tires and Tubes had the highest sales volume at 17.3K units. In contrast, Bikes had the lowest quantity sold with only 249 units, despite contributing the largest share of total revenue.

## Best Performing Period

* **Quarterly Analysis:** The **first quarter (Q1)** of each year showed **inconsistent performance**. In **2011**, Q1 dominated the year’s sales; however, in **2012** and **2013**, Q1 became the **weakest quarter** in each respective year. Although **Q1 of 2014** only includes data for **January**, historical patterns suggest that this period requires closer attention and further improvement.

<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/pertumbuhan_perkualtal.PNG" width=500 height=500>
</p>

* **Year-to-Year Comparison:** The year **2013** was the most profitable, generating **$16 million** in revenue with a total of **56,000 units sold**. Despite a weaker performance in 2012, this fluctuation provides valuable insights that can be used to develop more effective strategies for future periods.

<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/penjualan_berdasarkan_tahun.png" width=500 height=300>
</p>

## **Customer Demographics**

* **Age Distribution:** The **50–59 age group** represents the **largest customer segment by revenue**, contributing **$10 million**. Meanwhile, the **30–39 age group** dominates in terms of **customer count** (data not specified). This indicates that customers aged **50–59** generally possess **stronger financial stability** compared to other age groups.

* **Customer Class Distribution:** In terms of customer class, the majority fall under the **Regular** category—customers with a **subscription period longer than 12 months** and **total spending below $5,000**. Although the **VIP customer group** is relatively smaller, it shows a **steady year-over-year increase**, indicating the company’s success in **building loyalty among high-value customers**.

* **Demographic–Product Correlation:**

  * Customers aged **60 and above** preferred the **Mountain-200 Silver-38**, generating **$504K** in sales.
  * Customers aged **50–59** favored the **Mountain-200 Black-42**, with total sales of **$480K**, while the **40–49** group preferred the **Mountain-200 Black-46**, contributing **$464K** in sales.
  * The **30–39** age group showed a preference for the **Road-150 Red-48**, generating **$28K** in total sales.

<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/jumlah_pelanggan_setiap_grup_umur.png" width=200 height=200>
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/jumlah_pelanggan_setiap_kelas.png" width=300 height=300>
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/demografi_pelanggan_pertahun.png" width=800 height=700>
</p>


## **Regional Performance**

* **Top-Performing Countries:** Based on the product sales chart by country, the **United States (U.S.)** stands out as the **largest contributor** to Gold Bike Store’s total revenue, with total sales reaching **$9.1 million**, or approximately **31% of global sales**. Other strong contributors include **Australia**, with around **$5 million** in revenue, followed by **Germany** and **Canada**, both showing **steady sales performance** year over year.

* **Lowest-Performing Country:** In contrast, **France** recorded the **lowest sales**, generating **less than $2 million** during the observation period. Despite its relatively small volume, sales in France have shown a **consistent positive growth trend**, suggesting the emergence of a **potentially developing market**.

* **Country-Based Insights:** Overall, **English-speaking regions**—the **U.S., Australia, and the U.K.**—remain the **main backbone** of the company’s sales performance. This dominance can be attributed to factors such as **higher purchasing power**, **well-developed sports infrastructure**, and a **strong cycling culture** in these countries.


<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/kontribusi_setiap_negara_terhadap_penjualan.png" width=300 height=200>
</p>
<p align="center">
   <img src="https://github.com/AlHafidzLuhurDarma/Analisa-Gudang-Penyimpanan/blob/main/gambar/penjualan_perbulan_berdasarkan_negara.png" width=600 height=500>
</p>

## **Key Considerations**

* **Gender Information:** The difference between male and female customers is relatively small, indicating that **gender is not a primary focus area**, especially for the **marketing team**. Promotional strategies that emphasize one gender over the other could potentially **alienate the opposite gender**, reducing overall market effectiveness.

* **Customer Class:** A **deeper analysis** is required to understand the **increasing dominance of VIP customers** in terms of percentage share each year, even though their **absolute number remains the smallest** among all customer classes.


# **Recommendations**

* **Develop exclusive loyalty programs** for VIP customers, such as free service bonuses or discounts for future purchases.
* **Create strategies to attract younger customers** (under 20 years old), for example by introducing more affordable **entry-level products** or launching **digital marketing campaigns** on relevant social media platforms.
* **Expand into potential European markets** such as **France**, which shows growth potential. This can be supported through **localized strategies**, including partnerships with local bike shops or promotions during **annual cycling events**.
* **Utilize regional product preferences** to implement **segmented marketing strategies** — for instance, promoting **Mountain Bikes** in mountainous regions and **Road Bikes** in urban areas.

# **Limitations and Warnings**

* The dataset covers a **relatively short time period** with **highly detailed variables**. Since the data only spans **2011–2013 (plus early 2014)**, it does not fully represent **long-term trends**. It is therefore **too early to determine** which dimensions or variables truly dominate overall sales trends — this is evident, for example, in the **yearly growth percentage of VIP customers**, even though their **total count remains relatively small**.
* There are **seven products with incomplete information**, specifically product IDs **252, 253, 254, 255, 256, 257, and 258**.


Visit the SQL queries used for the analysis: **[SQL]**

Download the Power BI presentation created for this analysis: **[Power BI]**

View the various data visualizations generated during the analysis: **[Images]**

Access the Python program used for machine learning: **[Python]**

Visit my personal website for other projects: **[Website]**

