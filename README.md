# 📊 PEM Power BI Dashboard  

## 📌 Project Overview  
This project is an interactive **Power BI Dashboard** designed to provide actionable insights into **Sales, Customers, and Regional Performance**.  

The solution enables businesses to:  
- Track **sales performance** by product, channel, and warehouse  
- Analyze **customer behavior** and profitability  
- Evaluate **regional performance** with city/suburb-level details and geospatial mapping  
- Compare **current vs. previous year trends** using advanced time intelligence with DAX  
- Support **data-driven decision-making** through interactive, drill-through reports  

---

## 🗂️ Data Model & Structure  
The data model follows a **star schema** with a central **fact table (Sales_Data)** connected to multiple dimension tables for efficient reporting and scalability.  

**Tables Used:**  
- **Sales_Data (Fact Table):** Order details including Sales, Profit, Cost, Channel, Dates, and Product references  
- **Customer_Data:** Customer Index and Customer Names  
- **Regions_Table:** City, Suburb, Latitude/Longitude, Postal Codes for geo-analysis  
- **Products_Data:** Product details (ID & Name)  
- **DAX DateTable:** Custom date table for time intelligence (Day, Month, Year, Sorting columns)  

📌 **Data Model Screenshot:**  
![Data Model](https://github.com/Amaan838/Power-BI-Sales-Analytics-Dashboard/blob/main/Screenshot%202025-09-03%20132132.png)

---

## 📊 Dashboards  

### 🌍 Regional Dashboard  
- Sales and Previous Year Sales by City  
- Profit Contribution by City  
- Count of Cities & Suburbs  
- Map visualization of sales distribution  

![Regional Dashboard](screenshots/Screenshot-Regional.png)  

---

### 👥 Customer Dashboard  
- Total Customers & Average Revenue per Customer  
- Top 10 Customers by Sales  
- Cost, Profit, and Profit Margin by Customer Names  
- Color-coded Tree Map for quick customer analysis  

![Customer Dashboard](screenshots/Screenshot-Customer.png)  

---

### 🛒 Sales Dashboard  
- Sales, Profit, Total Cost, and Products Sold KPIs  
- Sales & Previous Year Sales by Product Name  
- Monthly Sales Trends  
- Sales by Channel (Wholesale, Distributor, Export)  
- Warehouse Code-wise performance  

![Sales Dashboard](screenshots/Screenshot-Sales.png)  

---

## 📈 Key Insights  
- The business operates across **45 cities and 87 suburbs**, with **Christchurch, Hamilton, and Waitakere** contributing the most sales.  
- There are **50 active customers**, where **Medline, Pure Group, and OUR Ltd** lead in revenue generation.  
- The company achieved **154.57M Sales**, **57.79M Profit**, and sold **68K Products**, with the **Export channel** contributing over **53% of sales**.  
- Year-over-year analysis highlights growth trends and key areas for cost optimization.  

---

