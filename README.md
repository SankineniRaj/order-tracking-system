 Order Tracking System Dashboard

An interactive Excel-based dashboard for monitoring e-commerce logistics performance across delivery partners and cities.

Show Image  [Dashboard Preview](order_tracking_sytsem_dashboard.png)

📌 Problem Statement
Organizations managing large volumes of orders across multiple cities and delivery partners face significant challenges in monitoring real-time order status, identifying performance bottlenecks, and ensuring timely deliveries.
With 50 total orders distributed across 5 delivery partners and 8 cities, the business had no centralized visibility into:

Which delivery partners are underperforming or causing delays
Which cities have high order volumes but low fulfillment rates
The root cause of failed and pending orders — representing a 26% non-delivery rate


🎯 Objective
To build a robust, data-driven order tracking dashboard in Microsoft Excel that provides actionable insights into delivery performance, reduces pending/failed order rates, and enables faster decision-making across partners and cities.

📊 Dashboard Features
KPIValue🟦 Total Orders50✅
            Delivered Orders37 (74%)
            ❌ Failed Orders3 (6%)
            ⏳ Pending Orders10 (20%)
Visuals Included

🥧 Delivery Status Pie Chart — Breakdown of Delivered, Failed, and Pending orders
📊 Delivery Partner Performance Bar Chart — Orders handled per partner with status breakdown
📈 Average Delay Days Line Chart — Avg delay per delivery partner
🏙️ City-Wise Orders Bar Chart — Order distribution across 8 cities (Ahmedabad, Bengaluru, Chennai, Delhi, Hyderabad, Kolkata, Mumbai, Pune)


🛠️ Built With
Microsoft Excel only — No external tools or plugins used.
Excel Functions & Features Used
FeaturePurpose COUNTIFSCount orders by status, partner, and city
SUMIFAggregate delay days per delivery partnerAVERAGECalculate average delay per partnerPivot TablesSummarize data dynamically by partner, city, and 
statusPivot ChartsVisualize pivot table data as interactive chartsSlicers / FiltersDynamic filtering by date, status, and delivery partner
All charts update dynamically when data is filtered — no manual refresh needed.

📁 File Structure
📂 Order-Tracking-Dashboard/
├── 📊 MyDashboard_Starter.xlsx     # Main Excel dashboard file
├── 🖼️ order_tracking_dashboard.png # Dashboard screenshot
└── 📄 README.md                    # Project documentation

🚀 How to Use

Download MyDashboard_Starter.xlsx
Open in Microsoft Excel (2016 or later recommended)
Use the date filter on the left panel to filter by specific dates
Use the Status and Delivery Partner slicers to drill down
All charts and KPI cards update automatically


📈 Key Insights from the Dashboard

DTDC handles the most orders (11 delivered) but also has the highest failure count
Ecom Express has the highest average delay of 2.18 days — nearly 3× that of BlueDart (0.71 days)
Bengaluru leads city-wise with 11 orders; Chennai has the lowest at just 1
10 orders are still pending, signaling a need for better fulfillment tracking


👤 Author
Raj Sankineni

📝 License
This project is for educational and portfolio purposes.
