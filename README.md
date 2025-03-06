# 📊 Side Project: Company2 Business Database Analysis

## 📌 Introduction
This side project focuses on analyzing **Company2's internal business database**, hosted on **Azure MySQL**. The project includes various SQL queries to perform business intelligence tasks such as employee performance analysis, product sales trends, and customer segmentation. The results are visualized using **Tableau** for better insights.

## 🔗 Database Connection
We use **Python & pymysql** to connect to the **Company2** database on Azure MySQL:
```python
import pymysql
conn = pymysql.connect(
      host="ccw-mysql.mysql.database.azure.com",
      user="user1",
      password="123@Ntut",
      database="company2")
