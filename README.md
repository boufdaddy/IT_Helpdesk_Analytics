# IT Help Desk Performance Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Interactive-yellow) ![Status](https://img.shields.io/badge/Status-In%20Progress-blue)

## 📌 Project Overview
This Power BI dashboard analyzes IT Help Desk performance, delivering real-time insights into ticket resolution, service efficiency, and customer satisfaction. Built to empower IT support teams with data-driven decisions, it transforms raw ticketing data into actionable metrics and trends.

## 🎯 Objectives
- Monitor and optimize IT service desk performance.
- Track key metrics: resolution time, ticket volume, and customer satisfaction.
- Identify common IT issues and trends to enhance user experience.
- Enable proactive decision-making with dynamic analytics.

## 📂 Data Sources
- **Ticketing System Data**: Synthetic CSV generated for this project (simulating ticket ID, status, timestamps).
- **Employee Satisfaction Surveys**: Simulated feedback scores (CSAT).
- **System Logs**: Placeholder for downtime records (not fully implemented).

## 📊 Key Metrics & Features
### KPIs Tracked
- ✅ **Total Tickets Created vs. Resolved**: Daily, weekly, monthly trends.
- ✅ **Average Resolution Time**: By category (e.g., hardware, software) and severity.
- ✅ **First Contact Resolution Rate**: Measures support team efficiency.
- ✅ **Most Common IT Issues**: Hardware, software, network, security breakdowns.
- ✅ **High-Priority Incidents & SLA Compliance**: Tracks urgent tickets.
- ✅ **Customer Satisfaction Score (CSAT)**: Aggregated from surveys.

### Power BI Features
- ✔ **Interactive Filters**: Date range, issue category, priority.
- ✔ **DAX Measures**: Time intelligence, running totals, escalations.
- ✔ **Conditional Formatting**: Highlights overdue tickets and SLA breaches.
- ✔ **Drill-through Analysis**: Deep dive into unresolved issues.
- ✔ **Automated Refresh**: Via Power BI Service.

## 🏗️ Project Steps
1. **Data Creation**
   - Generated synthetic IT help desk data using Python (`pandas`, `faker`) to simulate a realistic ticketing system.
   - Created ~100 tickets for March 29-30, 2025, with fields like `TicketID`, `CreatedDate`, `ResolvedDate`, `Category`, `Severity`, `Status`, `FirstContactResolved`, `CSAT`, and `ShotsTaken`.
   - Script randomized timestamps, categories (Hardware, Software, etc.), and resolution status (80% resolved, 20% open), saved as `IT_HelpDesk_Data.csv`.
   - See `generate_helpdesk_data.py` in the repository for details.

2. **Data Preparation**
   - Cleaned and transformed data with Power Query (e.g., converted dates, calculated resolution time).
   - Built a single-table model for simplicity.
   - Created calculated columns and DAX measures for KPIs.

3. **Dashboard Development**
   - Designed a multi-page Power BI report with slicers and filters.
   - Applied color-coded visuals for quick insights.

4. **Optimization & Publishing**
   - Optimized DAX for performance.
   - Published to Power BI Service with scheduled refresh.

## 🚀 How to Use
1. Download `IT_HelpDesk_Data.csv` from the repository or connect to your own ticketing system.
2. Open the `.pbix` file in Power BI Desktop.
3. Explore filters, drill-throughs, and KPIs interactively.

## 📸 Screenshots
*(Screenshots to be added post-development)*  
- Overview Page: KPIs and trends.  
- Ticket Details: Drill-through analysis.

## 🔗 Links
- **GitHub Repository**: [github.com/yourusername/it-helpdesk-analytics](#) *(Update with your link)*  
- **Live Demo**: [Power BI Service Link](#) *(Add after publishing)*

## 📢 Future Enhancements
- Integrate Power Automate for automated SLA breach alerts.
- Add AI/ML for predictive issue detection.
- Optimize for mobile viewing.

## 🤝 Connect with Me
- 📧 **Email**: tobechukwuokoro6@gmail.com  
- 💼 **LinkedIn**: [linkedin.com/in/yourprofile](#)  
- 📝 **Portfolio**: [yourportfolio.com](#)  

---

*Built by Tobechukwu Charles Okoro to showcase BI skills for IT optimization.*
