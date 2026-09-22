# 👗 Rantal Clothing House — Rental Analytics Dashboard

An interactive, single-page analytics dashboard for **Rantal Clothing House**, designed to transform clothing rental data and EDA findings into a clean, simple, and visually engaging business dashboard.

The dashboard provides an at-a-glance view of rental performance, revenue, category trends, and key business insights.

---

## 📊 Project Overview

**Rantal Clothing House** is a clothing rental analytics project that uses data analysis and visualization to understand rental patterns and business performance.

The project started with **Exploratory Data Analysis (EDA)** to identify important trends and relationships within the dataset.

The insights from the EDA were then transformed into an **interactive dashboard UI** with filters, KPI cards, and visualizations.

### Dashboard Focus

* Rental performance
* Revenue analysis
* Clothing category performance
* Rental trends over time
* Customer/rental behavior
* Key business insights

---

## ✨ Features

* 🎯 **Single-page dashboard**
* 📌 Interactive KPI cards
* 📊 Rental trend visualization
* 👗 Clothing category analysis
* 💰 Revenue insights
* 🔽 Interactive dropdown filters
* 🔄 Reset filters functionality
* 🖱️ Interactive chart tooltips
* 📈 Dynamic data visualization
* 💡 EDA-based business insights
* 🎨 Minimal and subtle visual design
* 📱 Responsive UI

---

## 🖥️ Dashboard Structure

The dashboard is organized into a simple one-page layout:

```text
┌──────────────────────────────────────────────────────────────┐
│              RANTAL CLOTHING HOUSE                           │
│              Clothing Rental Analytics                       │
├──────────────────────────────────────────────────────────────┤
│ Category ▼ │ Status ▼ │ Customer ▼ │ Time Period ▼ │ Reset  │
├──────────────────────────────────────────────────────────────┤
│  Total       │  Revenue     │ Avg Rental │ Top Category     │
│  Rentals     │              │   Value    │                  │
├──────────────────────────────────────────────────────────────┤
│                         │                                    │
│     Rental Trend        │       Category Performance         │
│                         │                                    │
│     📈 Line Chart       │       📊 Bar Chart                 │
│                         │                                    │
├──────────────────────────────────────────────────────────────┤
│                     Key EDA Insights                         │
│      Insight 1       │       Insight 2       │ Insight 3     │
└──────────────────────────────────────────────────────────────┘
```
Image of the Dashboard=<img width="991" height="568" alt="Capture" src="https://github.com/user-attachments/assets/deb39900-3398-4b1f-892b-19c90b934324" />


---

## 🎨 Design

The UI follows a minimal and modern design philosophy.


### Color Palette

| Purpose          | Color     |
| ---------------- | --------- |
| Background       | `#F7F6F2` |
| Cards            | `#FFFFFF` |
| Primary Text     | `#252525` |
| Secondary Text   | `#777777` |
| Primary Accent   | `#8B7355` |
| Secondary Accent | `#78909C` |
| Borders          | `#E8E5DF` |

The design avoids excessive colors, gradients, and unnecessary visual elements to keep the dashboard clean and business-focused.

---

## 🔽 Interactive Filters

The dashboard includes dropdown filters for exploring the data dynamically.

### Available Filters

* **Category**
* **Rental Status**
* **Customer Type/Segment**
* **Time Period**

Changing a filter dynamically updates the relevant:

* KPI values
* Charts
* Category statistics
* Business insights

A **Reset Filters** option allows users to return to the complete dataset view.

---

## 📈 Visualizations

### Rental Trend

An interactive line/area chart is used to visualize rental activity over time.

Users can switch between metrics such as:

```text
Rentals
Revenue
```

### Category Performance

A horizontal bar chart is used to compare clothing categories based on rental activity.

Hovering over a category provides additional information such as:

* Rental count
* Revenue
* Percentage contribution

---

## 💡 Key Insights

The dashboard converts the findings from the EDA into easily understandable business insights.

Examples include:

* Most rented clothing category
* Highest revenue-generating category
* Peak rental period
* Customer/rental behavior patterns
* Significant rental trends

All insights should be calculated from the underlying dataset rather than manually entered values.

---

## 🛠️ Tech Stack

> Update this section if your implementation uses a different stack.

* **Frontend:** React
* **Styling:** Tailwind CSS
* **Charts:** Recharts
* **Language:** JavaScript / TypeScript
* **Build Tool:** Vite
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```text
rantal-clothing-house/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── Header
│   │   ├── FilterBar
│   │   ├── KPICards
│   │   ├── RentalTrend
│   │   ├── CategoryPerformance
│   │   └── Insights
│   │
│   ├── data/
│   │   └── rentalData
│   │
│   ├── App
│   ├── main
│   └── index.css
│
├── package.json
├── README.md
└── .gitignore
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/rantal-clothing-house.git
```

### 2. Navigate to the project

```bash
cd rantal-clothing-house
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

The application will be available on the local development server shown in your terminal.

---

## 📊 Data & EDA

The dashboard is based on an Exploratory Data Analysis performed on the Rantal Clothing House rental dataset.

The EDA was used to identify:

* Data distribution
* Rental patterns
* Category performance
* Revenue trends
* Customer behavior
* Important relationships between variables
* Potential business insights

The dashboard translates these analytical findings into an interactive visual experience.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze clothing rental data.
2. Identify important rental and revenue patterns.
3. Understand clothing category performance.
4. Create meaningful business KPIs.
5. Present EDA findings through interactive visualizations.
6. Build a simple and intuitive analytics interface.
7. Make data-driven insights easier for business users to understand.

---

## 🔮 Future Improvements

Potential future enhancements include:

* 📅 Advanced date-range filtering
* 📥 Export dashboard data to CSV
* 📄 Generate downloadable reports
* 📊 Additional customer segmentation
* 🔐 User authentication
* ☁️ Cloud database integration
* 📱 Improved mobile optimization
* ⚡ Real-time rental data
* 🤖 AI-powered business insights

---

## 👨‍💻 Author

**Your Name**

If you found this project useful or interesting, feel free to ⭐ the repository.

---

## 📄 License

This project is available for educational and portfolio purposes.
