# Delivery Performance Dashboard  - Power BI

## 📌 Overview  

This project features a Power BI dashboard designed to give a general overview on the KPIs & performance for a parcel delivering company operating in Paris & its surrounding. It provides insights on the punctuality of the delivery operations, the success rate & other metrics that would help the company keep track of its operations & make data-driven decisions to improve efficiency (like courrier allocation, volume shifting between HUBs, find trends on high volume days...)

The company provides a VIP delivery service where clients can select between 4 specific time window on a certain date when they want their parcel to be delivered at their address, parcels are received from 4 large logistics platforms (think DHL) and dispatched between HUBs, each of the 3 hubs operated by the company delivers to certain sections of the city of Paris & its surrounding.

**🎯 Goal:** Track and visualize delivery performance across multiple hubs.  

### Key Metrics:  
- 📦 **Total Orders Received - Change from Last Month** : Seeing that the company's profitability is directly linked to the volume of parcels received from clients, monitoring change becomes crucial.
- ✅ **Successful Deliveries** - As its name suggests, this metric tracks how many parcels were successfully delivered. 
- 📊 **Delivery Punctuality Index**  - Or Delivery Precision, this metric tracks the perentage of parcels that were delivered within the date & time window specified by the customer.
- ⏳ **Late Deliveries (%)**  - Parcels that were delivered outside of the date & time requested by the client.
- ❌ **Undelivered Orders**  - Parcels that have been received by the HUBs but weren't delivered, in many cases such parcels are lost or the end client have refused them & they will be returned to the sender.

### 🛠 Tools Used:  
- **Python: Pandas** → Data Cleaning - Type Casting - Features Engeneering
- **Power BI** → Data visualization & analysis  
- **Copilot AutoMeasures** → Data modeling & calculations  
- **Simulated Dataset With the Following Columns** → ["ID_Commande", "Date_Réception", "Client", "Destination", "Plateforme","Date_Livraison_Souhaitée", "Créneau", "Courrier", "Date_Livraison"]7

## 📊 Dashboard Features  

### **1️⃣ KPI Cards - Key Business Insights**  
- **Total Parces Received**
- **% Change of Total Parcels Received From Last Month**
- **Delivery Success Rate (%)**  
- **Delivery Punctuality Index (%)**

### **2️⃣ Horizontal Bar Chart: Number of Parcels Received from Clients per Logistics Hub**  
- **X-axis** → Count of Orders
- **Y-axis** → Hub

### **3️⃣ Pie Chart: Delivery Performance Breakdown**  
- ✅ **On Time**  
- ⏳ **Late**  
- ❌ **Not Delivered**  

### **4️⃣ Map: Number of Parcels in each Hub per Destination**  
- **Location** → The Destination of the Parcel  
- **Bubbles** → Number of Parcels
- **Legend** → Logistics Hub

The dashboard also provides filters by HUB & by Client for easy access to relevant informations.

## 🛠 How to Use the Dashboard  
- 1️⃣ **Download & Install** [Power BI Desktop](https://powerbi.microsoft.com/).  
- 2️⃣ Download & Open the .pbix file in Power BI.
- 3️⃣ Explore the insights and interact with the data visuals!

## 📩 Contact & Connect
- 📧 Email: hossamelmorabity@gmail.com
- 🔗 LinkedIn: [LinkedIn](https://www.linkedin.com/in/hossam-el-morabity-a90316227/)
- 🖥 GitHub: [Github](https://github.com/hossam-elm)
Feel free to reach out with any questions or feedback!



