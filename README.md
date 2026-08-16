# 📊 YouTube Social Media Engagement Dashboard

An end-to-end data analytics project that extracts video performance metrics from the YouTube Data API v3 using Python, processes engagement statistics, and presents visual insights in Power BI.

---

## 📸 Dashboard Preview

![Dashboard Screenshot](dashboard_screenshot.png)

---

## 🛠️ Tech Stack & Tools

* **Language:** Python 3.x
* **Libraries:** `google-api-python-client`, `pandas`
* **API:** YouTube Data API v3
* **Visualization:** Power BI (DAX, Custom Visual Formatting)

---

## 🚀 Key Metrics & Features

* **Data Extraction:** Automatically fetches video titles, published timestamps, view counts, likes, and comment counts.
* **DAX Calculations:**
  * **Total Engagement:** `SUM(likes) + SUM(comments)`
  * **Engagement Rate (%):** `DIVIDE([Total Engagement], SUM(views), 0) * 100`
* **Visual Insights:** High-level KPI summary cards, engagement bar charts, and performance breakdown tables.

---

## ⚙️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/social-media-engagement-dashboard.git](https://github.com/YOUR_USERNAME/social-media-engagement-dashboard.git)
   cd social-media-engagement-dashboard
