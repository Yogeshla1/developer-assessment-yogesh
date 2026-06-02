# Developer Assessment - Yogesh Sadanand Lokhande

This repository contains my submissions for the assessment tasks, covering QA manual testing, n8n data pipelines, and system monitoring automation.

## 📂 Included Deliverables
1. **Task 1:** `Task1_QA_Report_Yogesh_Lokhande.pdf` - QA bug table tracking sheet and deep-dive CORS error root-cause analysis.
2. **Task 2:** `Task2_Workflow_Yogesh_Lokhande.json` - High-impact GitHub repository tracking workflow built natively on n8n.
3. **Bonus Task:** `Bonus_UptimeMonitor_Yogesh_Lokhande.json` - Production-ready website health checker and notification trigger.

## ⚙️ Workflow Explanations
* **GitHub Pipeline:** Wakes up every 1 hour, pulls trending assets, filters the top 5 records using a JavaScript array mutation, enriches data with current issue states, and dynamically checks star volume parameters.
* **Uptime Guard:** Continuously monitors targeted app locations every 5 minutes to ensure status returns a successful 200 OK signature, branching cleanly to keep operators safe from live site failures.
