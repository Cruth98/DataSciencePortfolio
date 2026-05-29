# Data Science & Analytics Engineering Portfolio

Analytics engineer and data scientist with production experience across Microsoft 
Fabric, Python, SQL, Power BI, and applied ML. This portfolio spans data 
infrastructure and platform engineering, AI implementation, machine learning, 
and end-to-end analytics delivery — with an emphasis on solving real operational 
problems at scale.

---

## Featured Projects

### VMI Analytics — Microsoft Fabric Lakehouse Migration
Self-initiated migration of Sazerac's Vendor Managed Inventory analytics 
infrastructure from 90+ fragmented Power Query transformations into a governed 
Medallion Lakehouse — designed, architected, and executed within the first month 
of tenure. Includes live Oracle ERP shortcut views validated at 946K and 2.6M 
rows, a standardized Python ETL pipeline template, shared utility library, full 
ERP data architecture documentation across 13 core objects, and a complete 
reverse-engineering audit of 114 Atlas upload source queries.

- **Tools:** Microsoft Fabric, Python, PySpark, Delta Lake, SQL, Oracle ERP, Informatica MDM
- **Validated by:** Director of Master Data and Performance Reporting
- **Repository:** [View Project](https://github.com/Cruth98/VMI_Analytics_FabricMigration)

---

### VMI Analytics — Microsoft Fabric Data Agent POC
Proof-of-concept deployment of a Microsoft Fabric Data Agent enabling natural 
language querying of Oracle ERP sales order data for VMI analysts and inventory 
planners — no SQL required. Built on governed scut schema shortcut views with 
a custom instruction set, data source descriptions, and an 8-query example 
library covering the most common planning use cases. Includes full technical 
documentation and a plain-English end user guide. Roadmap extends to Teams 
integration, end user adoption measurement, domain expansion across inventory 
and planning data, and eventual multi-domain agent consolidation.

- **Tools:** Microsoft Fabric Data Agent, SQL, Markdown
- **Repository:** [View Project](https://github.com/Cruth98/VMI_Analytics_OrdersDataAgent)

---

### Bellarmine University Basketball Analytics Portal
End-to-end analytics and decision-support platform built for a Division I men's 
basketball program. Integrates four independent data sources via Python ETL 
pipelines, computes custom player metrics including a composite WolfScore, and 
delivers team practice analysis, player-level performance, defensive grading, 
and WARS game segment analysis through a live-deployed Streamlit web application. 
Staff at the University of Kentucky noted it contained capabilities beyond their 
own platform.

- **Tools:** Python, Streamlit, pandas, Plotly, NumPy, GitHub
- **Live Application:** https://bellarmineanalytics.streamlit.app/
- **Repository:** [View Project](https://github.com/Cruth98/BasketballAnalyticsPortal)

---

### NCAA Men's Basketball Defensive Clustering (2024)
Applied unsupervised machine learning analysis clustering all 365 NCAA Division I 
programs by defensive profile — then running a second independent K-Means model 
on roster size and height data to identify peer programs. A dual-cluster 
intersection analysis surfaces programs that are both similar in roster 
composition and execute the most effective defensive profile nationally. 
Multi-source data integration required a custom TeamID mapping layer to normalize 
team names across SportsReference, Synergy, and KenPom.

- **Tools:** Python, pandas, scikit-learn, seaborn, matplotlib
- **Repository:** [View Project](https://github.com/Cruth98/NCAA_MBB_DefensiveClustering2024)

---

### Power BI Semantic Models & Enterprise Reporting
Production-grade Power BI reports built for finance, audit, and operations 
stakeholders in an enterprise restaurant environment. The flagship Unrecorded 
Liability Audit Dashboard is backed by a star schema dimensional model 
(FindingsFact, BaswareFact, StoreListDim, COA) and directly supported 
identification of $2M+ in previously unrecorded liabilities. Also includes 
Fixed Asset & Depreciation Projections and an Outstanding Gift Card Balances 
report with embedded self-service guidance deployed to store-level stakeholders.

- **Tools:** Power BI, DAX, SQL, Dimensional Modeling
- **Repository:** [View Project](https://github.com/Cruth98/PowerBI_Visualizations)

---

### Python Gift Card Audit Workflows
Python-based solutions to three time-sensitive audit requests involving 
multi-GB gift card transaction datasets that exceeded Excel's processing limits. 
Delivered directly to KPMG auditors, Treasury, and the CFO. Includes 
threshold-based population subsampling logic for KPMG audit procedures and 
conditional channel normalization for a Treasury reconciliation request. 
The BHN reconciliation approach was adopted as the standard audit process 
within the accounting department.

- **Tools:** Python, pandas, NumPy, Google Colab
- **Repository:** [View Project](https://github.com/Cruth98/PythonGiftCardAudit)
