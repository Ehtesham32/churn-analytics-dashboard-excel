# Churn Analytics Dashboard - Excel

Interactive Excel dashboard for tracking and analyzing customer churn metrics across branches and time periods with dynamic year-wise filtering.

## 📊 Dashboard Preview
![Churn Dashboard](dashboard.png)

## 🎯 Key Features
- **Dynamic Year Selection**: Dashboard title and all KPIs auto-update based on Year slicer. Supports 2025 and 2026 data
- **KPI Cards**: Total Disconnections, Reconnections, Net Churn with monthly averages for selected year
- **Trend Analysis**: Monthly Net Churn trend with Disconnection vs Recon+TOO breakdown
- **IVD Bucket-wise View**: Churn trends segmented by MT, FT3, FT2, FT1 buckets
- **Root Cause Analysis**: Top 5 reasons for Voluntary Disconnection - Permanent Disconnection, Service Churn, Shifting, etc
- **Reconnection Insights**: Category-wise trend for Pull, Push, and Direct Activations
- **Dynamic Filters**: Year and Branch slicers for drilled-down analysis
- **Data Table**: Month-wise view of Disconnection, IVD, VD, Reconnection, TOO, Net Churn

## 🛠️ Tech Stack
- **Tool**: Microsoft Excel
- **Techniques**: Pivot Tables, Slicers, Dynamic Charts, Conditional Formatting, Data Modeling, Named Ranges
- **Key Formula**: Dynamic titles using `="Churn Dashboard for the year " & SelectedYear`

## 📈 Data Coverage
- **Period**: Jan 2025 to May 2026 | 17 months of data
- **Sample Metrics for 2025**: 22,763 Disconnections, 4,360 Reconnections, 18,403 Net Churn
- **Last Refreshed**: 31-May-2026

## 💡 Business Impact
Enables Retention and CCnR teams to:
1. Monitor churn health with 6 core KPIs that update per selected year
2. Identify high-churn IVD buckets and peak months for targeted campaigns
3. Prioritize retention efforts based on top VD reasons
4. Track reconnection effectiveness across Pull/Push channels
5. Compare YoY performance using multi-year data

## 📁 Repository Structure
