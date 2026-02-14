# Ola Ride Analytics Dashboard
An end-to-end data analytics dynamic project analyzing ride bookings, cancellations, revenue patterns, vehicle performance, and customer behavior using SQL, Excel, and Power BI to uncover operational inefficiencies and improve ride-service decision making.

📸 Dashboard Preview
<img src="Images/Ola 1 Overall Page.png" width="1000"/>

<img src="Images/Ola 2 VehicleType Page.png" width="1000"/>

<img src="Images/Ola 3 Revenue Page.png" width="1000"/>

<img src="Images/Ola 4 Cancellation Page.png" width="1000"/>

<img src="Images/Ola 5 Ratings Page.png" width="1000"/>


---

## 🎯 Project Objective

The objective of this project is to analyze ride-hailing service data to:

* Monitor booking volume and revenue trends
* Understand ride success vs cancellation behavior
* Analyze payment method preferences
* Measure customer and driver satisfaction through ratings

---

## 🧠 Business Problem

Ride-hailing platforms operate with multiple vehicle types, drivers, and customers simultaneously.
Operational teams struggle to answer questions such as:

* Why are rides getting cancelled?
* Which vehicle types generate the most revenue?
* What payment methods do customers prefer?
* Are drivers or customers responsible for more cancellations?
* Do ratings vary across vehicle categories?
* How does daily booking demand fluctuate?

Raw booking records alone cannot provide clear answers.
This dashboard transforms transactional ride data into actionable operational insights.

---

## 🛠 Tech Stack

**SQL** – Data extraction and transformation
**Excel** – Initial cleaning and preprocessing
**Power BI Desktop** – Dashboard development
**Power Query** – Data shaping and preparation
**DAX (Data Analysis Expressions)** – KPI calculations and measures

**File Formats:**
.pbix (dashboard)
.xlsx / .csv (dataset)

---

## 📂 Data Source

Source: Practice ride-booking dataset (OLA-style service data)

The dataset includes:

* Booking status (success, cancelled by driver/customer, no driver found)
* Vehicle type
* Booking value and ride distance
* Payment method
* Ride timestamps
* Cancellation reasons
* Customer and driver ratings

---

## 📊 Key Metrics

* **Total Bookings:** 103K+
* **Total Booking Value:** 35M
* **Successful Rides:** ~58K
* **Cancelled Rides:** ~35K
* **Cancellation Rate:** ~28%

---

## 📈 Dashboard Walkthrough

### 🔹 Overall Performance

* Displays total bookings and booking value
* Shows booking status distribution (Success vs Cancelled vs No Driver)
* Ride demand trend across dates

**Insight:** Majority of rides are successful, but a significant portion fails due to operational issues.

---

### 🔹 Vehicle Type Analysis

Compares performance across:

* Prime Sedan
* Prime SUV
* Prime Plus
* Mini
* Auto
* Bike
* E-Bike

Metrics analyzed:

* Total booking value
* Successful booking value
* Average distance travelled
* Total ride distance

**Insight:** Higher category vehicles generate more revenue while low-cost rides drive booking volume.

---

### 🔹 Revenue Analysis

* Revenue by payment method (Cash, UPI, Credit Card, Debit Card)
* Daily ride distance trend
* Top customers by spending

**Insight:** Digital payments dominate ride revenue contribution.

---

### 🔹 Cancellation Analysis

Two major perspectives:

**Customer Cancellations**

* Driver not moving
* Driver asked to cancel
* Change of plans
* Wrong address
* AC not working

**Driver Cancellations**

* Customer related issues
* Personal & car related issues
* More passengers than allowed

**Insight:** Most cancellations are operational rather than demand-based, indicating service coordination issues.

---

### 🔹 Ratings Analysis

Compares ratings across vehicle types:

* Driver Ratings
* Customer Ratings

**Insight:** Ratings remain consistent across categories, meaning cancellations affect operations more than satisfaction.

---

## 💡 Business Insights

* Nearly **1 in 3 rides gets cancelled**, highlighting operational inefficiency
* Mid-range vehicles balance revenue and demand best
* UPI & Cash dominate payment usage
* Driver behavior contributes heavily to failed rides
* Ratings remain stable despite cancellations → problem is logistics, not service quality

---

## 📌 Key Takeaways

* Reduce cancellations by improving driver allocation logic
* Improve driver arrival tracking and communication
* Optimize pricing strategy based on vehicle demand
* Focus on operational improvements instead of rating-based changes

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use the date slicer and filters to explore booking behavior
4. Navigate between pages through menu for operational insights

---
