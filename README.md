# **📊 Delivery Performance Dashboard - Power BI**  

## 📌 **Overview**  

This project features a Power BI dashboard designed to provide a comprehensive overview of key performance indicators (KPIs) for a parcel delivery company operating in Paris and its surrounding areas. It offers insights into the punctuality of delivery operations, success rates, and other critical metrics. These insights help the company track operations and make data-driven decisions to improve efficiency, such as courier allocation, volume shifting between hubs, and identifying trends on high-volume days.  

The company provides a VIP delivery service where customers can select a specific time window on a particular date for parcel delivery. Parcels are received from four large logistics platforms (e.g., DHL) and dispatched to three hubs. Each hub serves designated sections of Paris and its suburbs.  

---

## **🎯 Goal:**  
Track and visualize delivery performance across multiple hubs.  

### **📄 Pages: Relevant Insights for Multiple Stakeholders**  
- **Logistics Director Page:** Provides a high-level overview of key metrics with filters by HUB and client to highlight trends requiring corrective or preventive actions, aswell as an overview of the health of the supply chain & insights on profitability.
  ![image](https://github.com/user-attachments/assets/506b7aaa-5a76-4e9f-ace1-b55a95f2264c)

- **HUB Managers Page:** Allows a deeper dive into operational data, evaluating individual couriers' performance, optimizing courier allocation, and displaying key KPIs with month-over-month comparisons.  
  ![image](https://github.com/user-attachments/assets/7f249056-af13-406a-9198-d6f05a62a5b7)

---

## **📊 Key Metrics**  
- 📦 **Total Orders Received - Change from Last Month** → Since the company’s profitability depends on parcel volume, monitoring month-over-month changes is crucial.  
- ✅ **Successful Deliveries** → Tracks the number of successfully delivered parcels.  
- 📊 **Delivery Punctuality Index (%)** → Measures the percentage of parcels delivered within the client’s requested date and time window.  
- ⏳ **Late Deliveries (%)** → Parcels delivered outside the requested date and time window.  
- ❌ **Undelivered Orders** → Parcels received at the HUBs but not delivered (e.g., lost parcels, client refusals, or returns to sender).  

---

## **🛠 Tools Used**  
- **Python (Pandas)** → Data Cleaning, Type Casting, Feature Engineering  
- **Power BI** → Data Visualization & Analysis  
- **Copilot AutoMeasures** → Data Modeling & Calculations  
- **Simulated Dataset with Columns:**  
  `["ID_Commande", "Date_Réception", "Client", "Destination", "Plateforme", "Date_Livraison_Souhaitée", "Créneau", "Courrier", "Date_Livraison"]`  

---

## **📊 Dashboard Features**  

### **1️⃣ KPI Cards - Key Business Insights**  
- **Total Parcels Received**  
- **% Change in Total Parcels Received from Last Month**  
- **Delivery Success Rate (%)**  
- **Delivery Punctuality Index (%)**  

### **2️⃣ Horizontal Bar Chart: Number of Parcels Received from Clients per Logistics Hub**  
- **X-axis** → Count of Orders  
- **Y-axis** → HUB  

### **3️⃣ Pie Chart: Delivery Performance Breakdown**  
- ✅ **On Time**  
- ⏳ **Late**  
- ❌ **Not Delivered**  

### **4️⃣ Map: Number of Parcels per HUB Destination**  
- **Location** → Parcel Destination  
- **Bubbles** → Number of Parcels  
- **Legend** → Logistics Hub  

The dashboard includes filters by HUB and Client for easy access to relevant insights.  

---

## **🛠 How to Use the Dashboard**  
1️⃣ **Download & Install** [Power BI Desktop](https://powerbi.microsoft.com/).  
2️⃣ Download & Open the `.pbix` file in Power BI.  
3️⃣ Explore the insights and interact with the data visuals!  

---

## **📩 Contact & Connect**  
📧 **Email:** hossamelmorabity@gmail.com  
🔗 **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/hossam-el-morabity-a90316227/)  
🖥 **GitHub:** [GitHub](https://github.com/hossam-elm)  

Feel free to reach out with any questions or feedback! 🚀  
