# Hi, I'm Rizky 👋

**Business Automation Engineer** at a consulting firm in Indonesia. I turn messy business processes (payroll, compliance, client portals, document workflows) into systems people can rely on.

My day job sits where IT administration meets software engineering: I run and automate a Microsoft 365 tenant serving 50+ client portals, and I build applications for the payroll and compliance work our consultants do every month. I also work as a payroll consultant myself, so I know PPh 21, BPJS and the month-end close from the inside, not just from the spec.

🎓 Informatics Engineering, Universitas Mataram · 📍 Mataram, Lombok (UTC+8) · 🎹 Off the keyboard, I play in a band.

---

## 🚀 Featured projects

### [CoraByte Payroll](https://github.com/mfarizky/CoraByte-Payroll)
A self-contained payroll application for Indonesian payroll consultants, from employee master data to the bank transfer file.

- Server-side calculation engine for **PPh 21 TER** (monthly and daily), the December **Pasal 17** reconciliation, **BPJS** with floors and caps, and THR runs, built as pure functions with a self-test
- **Multi-tenant** by design, with tenant isolation enforced at the repository layer and proven by tests
- One guarded write path: optimistic locking, an enforced Draft → Review → Outputs → Paid flow, immutable paid runs and an audit log
- **Zero npm dependencies**: Node.js standard library only (`node:http`, `node:sqlite`, `node:crypto`, `node:test`)
- Payslip PDFs, remittance summary and a ready-to-upload Bank Mandiri payroll file

`Node.js` `SQLite` `JavaScript` `node:test`

### [M365 Script Automation](https://github.com/mfarizky/M365-SCRIPT-AUTOMATION)
Production scripts from administering a real Microsoft 365 tenant.

- Tenant-wide governance of client portal sites: inventory, guest permission hardening, navigation repair, list schema roll-out
- SharePoint list provisioning and bulk data fixes with backup and rollback
- Storage and audit reporting via SharePoint Search (KQL), Microsoft Graph and Exchange Online
- A scan → compress → track pipeline for large OneDrive files that preserves version history
- Zoho Books API clients, an OCR pipeline for Indonesian deeds of establishment, and Intune remediation
- Certificate-based app-only auth, with every tenant value kept out of the code

`PowerShell 7` `PnP.PowerShell` `Microsoft Graph` `Exchange Online` `Power Fx` `Python`

---

## 🛠️ What I work with

**Microsoft 365 & Power Platform**

![SharePoint](https://img.shields.io/badge/SharePoint-036C70?style=flat-square)
![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat-square)
![Exchange Online](https://img.shields.io/badge/Exchange_Online-0078D4?style=flat-square)
![Intune](https://img.shields.io/badge/Intune-0078D4?style=flat-square)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square)
![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat-square)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square)
![Dataverse](https://img.shields.io/badge/Dataverse-088142?style=flat-square)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logoColor=black)

**Languages & runtimes**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Power Fx](https://img.shields.io/badge/Power_Fx-742774?style=flat-square)

**Integrations & tools**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Zoho Books API](https://img.shields.io/badge/Zoho_Books_API-E42527?style=flat-square)
![REST APIs](https://img.shields.io/badge/REST_APIs-555555?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🌱 Right now

- Building internal business applications for document approval, client monitoring and compliance filing
- Learning to build **LLM-based agents in Python** for real business workflows. A project is on the way.

## 📜 Certifications

- TensorFlow Developer Certificate

## 🗂️ Earlier work

Before automation became my focus, I did data and machine learning projects: [customer segmentation with RFM and K-Means](https://github.com/mfarizky/customer-segmentation-rfm-kmeans), [rice price web scraping](https://github.com/mfarizky/rice-price-webscrapping), [London crime analysis](https://github.com/mfarizky/crime_londonCity) and [ML implementations](https://github.com/mfarizky/ml_implementation).

---

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rmfarizky)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rmfarizky@gmail.com)

Open to conversations about Microsoft 365 automation, Power Platform, and payroll or compliance systems.
