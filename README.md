# 🛒 E-Commerce Operations & Process Improvement  
**Data Analytics | OMS | WMS | Power BI**

## 📌 Project Overview
This project simulates and analyzes the end-to-end order fulfillment and customer support operations of an e-commerce company using an Order Management System (OMS) and Warehouse Management System (WMS).  
The objective is to identify operational bottlenecks, optimize inventory, and improve customer experience using data-driven insights.

---

## 📊 Business Problem
E-commerce companies struggle with:
- Late deliveries
- Inventory stockouts
- Inefficient warehouses
- High customer support workload

This project answers:
- Which warehouses are causing delays?
- Which SKUs are at risk of stockout?
- Where are customers experiencing the most pain?
- How can support resolution time be reduced?

---

## 🗂 Data Model
The project uses four simulated enterprise-grade datasets:

### Orders (OMS)
- order_id  
- order_date  
- customer_id  
- order_value  
- payment_type  
- warehouse  
- order_status  

### Fulfillment (WMS)
- order_id  
- pick_time  
- pack_time  
- ship_time  
- delivery_time  
- carrier  

### Inventory (WMS)
- sku  
- warehouse  
- stock  
- reorder_level  
- lead_time_days  

### Support Tickets
- ticket_id  
- order_id  
- issue_type  
- created_time  
- resolved_time  
- status  

---

## 🛠 Tools & Technologies
| Tool | Usage |
|------|------|
| Python (Pandas, NumPy) | Data simulation, cleaning, KPI calculation |
| SQL | Operational analysis & bottleneck detection |
| Power BI | Interactive operations dashboard |
| CSV | Data exchange format |

---

## 🔄 Data Pipeline
