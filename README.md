# 📊 Customer Feedback Analysis System
### BPO Operations Dashboard — Final Year Project

> A web-based dashboard that aggregates customer feedback across Voice, Chat, and Email channels, tracks satisfaction across the customer lifecycle, and auto-generates actionable insights to help BPO managers improve service quality and reduce complaint resolution time.

---

## 🔗 Live Demo

👉 **[View Live Project](https://asmithanandu.github.io/customer-feedback-dashboard/)**
> *(Replace the link above with your actual deployed URL)*

---

## 📌 Project Overview

This project was developed as part of my B.Tech final year to demonstrate practical understanding of **customer lifecycle management**, **complaint handling workflows**, and **satisfaction metrics** in a BPO/KPO environment.

The system simulates a real-world customer support operations dashboard used by Team Leaders and Quality Analysts to monitor agent performance, identify service gaps, and take corrective actions.

---

## 🎯 Key Features

| Feature | Description |
|---|---|
| 📈 CSAT Trend Chart | Tracks Customer Satisfaction Score month-over-month against target |
| 🍩 Feedback Categories | Breaks down feedback by Billing, Tech Support, Delivery, Returns, Other |
| 📞 Channel Analysis | Compares complaint volume across Voice, Chat, and Email |
| ⏱️ Resolution Time | Pie chart showing SLA adherence — % resolved within 1hr, 4hr, 24hr |
| 🔄 Customer Lifecycle | 6-stage lifecycle tracker (Onboarding → Loyalty) with satisfaction % per stage |
| 🗂️ Complaints Log | Live ticket table with status tags (Open / Pending / Resolved) and CSAT ratings |
| 💡 Actionable Insights | Auto-generated Good / Warning / Critical insights with recommendations |
| 🔽 Filters | Filter dashboard by month and support channel |

---

## 📸 Dashboard Preview

```
┌─────────────────────────────────────────────────────────┐
│  📊 Customer Feedback Analysis System   ● BPO Dashboard  │
├─────────────────────────────────────────────────────────┤
│  CSAT: 82%  │  Feedback: 1,248  │  FCR: 74%  │  AHT: 4.2m │
├──────────────────────┬──────────────────────────────────┤
│  Satisfaction Trend  │     Feedback by Category         │
│  [Line Chart]        │     [Doughnut Chart]             │
├──────────────────────┼──────────────────────────────────┤
│  Channel Volume      │     Resolution Time              │
│  [Stacked Bar]       │     [Pie Chart]                  │
├─────────────────────────────────────────────────────────┤
│  Customer Lifecycle: Onboarding→Purchase→Support→...    │
├─────────────────────────────────────────────────────────┤
│  Complaints Log Table + Actionable Insights             │
└─────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Structure and layout |
| **CSS3** | Responsive styling, card components, color-coded insights |
| **Vanilla JavaScript** | DOM manipulation, chart logic, filter interactivity |
| **Chart.js 4.4.1** | Line, Doughnut, Bar, and Pie charts |
| **Tabler Icons** | UI icon library |

> 🔒 Zero dependencies to install. Single file. Runs in any browser.

---

## 📂 Project Structure

```
customer-feedback-dashboard/
│
├── index.html        ← Entire project (HTML + CSS + JS in one file)
└── README.md         ← Project documentation
```

---

## 🚀 How to Run Locally

```bash
# Option 1 — Just open in browser
Double-click index.html

# Option 2 — Using VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click index.html → Open with Live Server

# Option 3 — Using Python
python -m http.server 8000
# Then open http://localhost:8000
```

---

## 📊 Metrics Tracked

- **CSAT** — Customer Satisfaction Score (%)
- **FCR** — First Call Resolution Rate (%)
- **AHT** — Average Handle Time (minutes)
- **SLA Adherence** — % of complaints resolved within defined time windows
- **Open Complaint Count** — Real-time ticket backlog indicator

---

## 🔄 Customer Lifecycle Stages

```
Onboarding (88%) → Purchase (83%) → Support (71%) → Complaint (54%) → Retention (79%) → Loyalty (91%)
```

Each stage is clickable and shows improvement tips — helping agents and managers understand where customers drop in satisfaction.

---

## 💡 Sample Actionable Insights Generated

- ✅ **CSAT improved 11 points in 6 months** — Training and script adherence are working
- ⚠️ **Support stage satisfaction lowest at 54%** — Empathy training needed
- 🔴 **10% of complaints exceed 24-hour resolution** — SLA alerts required at 4-hour mark
- ✅ **Chat has highest first-contact resolution (81%)** — Route simpler queries to chat
- ⚠️ **Billing is top complaint category (28%)** — Automate discrepancy detection

---

## 🎓 Learning Outcomes

Through this project, I developed practical understanding of:

- Customer lifecycle management in BPO/KPO operations
- KPI tracking — CSAT, FCR, AHT, SLA adherence
- Complaint handling workflows and escalation logic
- Voice, Chat, and Email channel performance comparison
- Data-driven decision making for service quality improvement
- Frontend development — responsive UI, interactive charts, filters

---

## 👩‍💻 Author

**Asmitha Nandu Indrapally**
B.Tech Graduate — Malla Reddy Engineering College, Hyderabad
CGPA: 8.7 | Batch of 2026

📧 asmithaindrapally@gmail.com
📞 8639009322

---

## 📄 License

This project is open for academic and portfolio review purposes.
