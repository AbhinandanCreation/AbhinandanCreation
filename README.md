<div align="center">

<img src="assets/header.svg" alt="Abhinandan Creation" width="100%" />

<img src="assets/typing.svg" alt="Enquiry to Dispatch, 13 in-house web apps, live shop-floor data, built by our MIS team" width="760" />

<p>
  <img src="https://img.shields.io/badge/in--house%20apps-13-0b3a68?style=for-the-badge&labelColor=0a2c52" />
  <img src="https://img.shields.io/badge/platform-Google%20Workspace-34A853?style=for-the-badge&logo=google&logoColor=white&labelColor=0a2c52" />
  <img src="https://img.shields.io/badge/ERP-ERPNext-0089FF?style=for-the-badge&logo=frappe&logoColor=white&labelColor=0a2c52" />
  <!-- LAST_SYNC --><img src="https://img.shields.io/badge/last%20sync-2026--10--26-f5b942?style=for-the-badge&labelColor=0a2c52" /><!-- /LAST_SYNC -->
</p>

</div>

<img src="assets/divider.svg" width="100%" />

## 🏭 About us

<img align="right" src="assets/logo.png" width="220" alt="Abhinandan Creation logo" />

**Abhinandan Creation** is an intimate-wear manufacturer based in Bhiwandi, Maharashtra. We make bras, panties and moulded innerwear for brands. Our MIS team builds the software that runs the business, so that every order, every roll of fabric and every line on the floor can be seen in real time.

- 🧵 **Sampling & costing**: from the first buyer enquiry to the approved sample
- 🏗️ **Production**: daily plans, hourly line output and efficiency
- 🔎 **Quality**: fabric, trims and final AQL inspections, all on the phone
- 👥 **People & process**: HR forms, delegation, checklists and audits

<br clear="right" />

### 🏢 Company at a glance

| | |
|---|---|
| 🏷️ **Company** | Abhinandan Creation |
| 👙 **Industry** | Intimate wear & lingerie manufacturing |
| 🧵 **Products** | Bras, panties, moulded innerwear |
| 🤝 **Business model** | Manufacturing for brands (B2B) |
| 📍 **Location** | Bhiwandi, Maharashtra, India |
| 🌐 **Website** | [abhinandancreation.in](https://abhinandancreation.in) |
| 📧 **Email** | [mis@abhinandancreation.in](mailto:mis@abhinandancreation.in) |
| 💻 **Tech team** | In-house MIS team |

<div align="center">
  <img src="assets/stats.svg" alt="13 web apps, 8+ departments, 6 order stages, 100% built in-house" width="100%" />
</div>

<img src="assets/divider.svg" width="100%" />

## 🔄 One order, start to finish

<div align="center">
  <img src="assets/pipeline.svg" alt="Order flow: Enquiry, Sampling, Planning, Production, Quality, Dispatch" width="100%" />
</div>

## 🗺️ How every system connects

```mermaid
%%{init: {'theme':'base','themeVariables':{'fontFamily':'Segoe UI, Helvetica, Arial','fontSize':'15px','lineColor':'#58a6ff'}}}%%
flowchart TB
    subgraph S1["🧵 Merchandising & Sampling"]
        direction LR
        A["💰 Costing Enquiry<br/>buyer enquiry · PDF"]
        B["🧵 Sample Tracker<br/>Fit → Size Set → PP → GPT"]
        C["✂️ Internal Sample Tracker<br/>sampling room jobs"]
        A ==> B ==> C
    end

    subgraph S2["🔎 Inward Quality"]
        direction LR
        F["🧶 4-Point Fabric<br/>roll scoring"]
        M["🏷️ MQA Trims<br/>10 / 50 / 100%"]
    end

    subgraph S3["🏗️ Production"]
        direction LR
        D["📋 PMS · Master Order Plan<br/>cutting → finishing"]
        P["📈 Production Report<br/>hourly · line-wise"]
        D ==> P
    end

    subgraph S4["✅ Final Quality & Dispatch"]
        direction LR
        Q["✅ AQL Portal<br/>final inspection"]
        X(["🚚 Dispatch"])
        Q ==> X
    end

    subgraph S5["🏠 Platform & People"]
        direction LR
        H["🏠 AC Central Hub<br/>single sign-in · Help Desk"]
        K["🔍 PC Audit Dashboard<br/>checklists · FMS audit"]
        T["🎫 Help Tickets"]
        G["🗂️ Delegation"]
        R["👥 HR Forms"]
    end

    B ==>|order confirmed| D
    F ==>|fabric passed| D
    M ==>|trims passed| D
    P ==>|goods ready| Q
    H -.->|opens| B
    H -.->|opens| D
    K -.->|audits| D
    T -.-> H

    classDef merch fill:#7c3aed,stroke:#c4b5fd,stroke-width:2px,color:#fff
    classDef qc fill:#0891b2,stroke:#67e8f9,stroke-width:2px,color:#fff
    classDef prod fill:#16a34a,stroke:#86efac,stroke-width:2px,color:#fff
    classDef ship fill:#1f6feb,stroke:#93c5fd,stroke-width:2px,color:#fff
    classDef plat fill:#0b3a68,stroke:#f5b942,stroke-width:2px,color:#fff
    class A,B,C merch
    class F,M,Q qc
    class D,P prod
    class X ship
    class H,K,T,G,R plat
    style S1 fill:#f3e8ff,stroke:#7c3aed,stroke-width:2px,color:#0b3a68
    style S2 fill:#e0f7fa,stroke:#0891b2,stroke-width:2px,color:#0b3a68
    style S3 fill:#e8f7ee,stroke:#16a34a,stroke-width:2px,color:#0b3a68
    style S4 fill:#e7f0ff,stroke:#1f6feb,stroke-width:2px,color:#0b3a68
    style S5 fill:#fff7e0,stroke:#f5b942,stroke-width:2px,color:#0b3a68
```

<img src="assets/divider.svg" width="100%" />

## 🧩 Our web apps

> 🔒 All app repositories are **private**. They are listed here to show the scope of our in-house platform.

<table>
<tr>
<td colspan="2" align="center"><h3>🧵 Merchandising & Sampling</h3></td>
</tr>
<tr>
<td width="50%" valign="top">

### 💰 [Costing Enquiry](https://github.com/AbhinandanCreation/costing-enquiry)
Buyer enquiry form: guided flows, Drive-filed attachments, an auto-made **PDF summary** and instant team alerts.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-Drive-34A853?style=flat-square) ![](https://img.shields.io/badge/-PDF-e34f26?style=flat-square)

</td>
<td width="50%" valign="top">

### 🧵 [Sample Tracker](https://github.com/AbhinandanCreation/sample-tracker)
Every sample from Fit/Proto → Size Set → PP → GPT, with a **Plan-vs-Actual engine** and a responsibility matrix.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-Plan%20vs%20Actual-7c3aed?style=flat-square)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### ✂️ [Internal Sample Tracker](https://github.com/AbhinandanCreation/internal-sample-tracker)
Sampling-room jobs: **Raw Material → Cutting → Moulding → Stitching → Handover**, with automatic team load-balancing, linked live to the Sample Tracker.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-Auto%20sync-16a34a?style=flat-square)

</td>
</tr>

<tr>
<td colspan="2" align="center"><h3>🏗️ Production</h3></td>
</tr>
<tr>
<td width="50%" valign="top">

### 📋 [PMS: Shop-Floor Entry](https://github.com/AbhinandanCreation/pms-shop-floor)
Department-wise daily entry on the phone that drives the **Master Order Plan** from cutting to dispatch.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-ERPNext-0089FF?style=flat-square)

</td>
<td width="50%" valign="top">

### 📈 [AC Production Report](https://github.com/AbhinandanCreation/production-report)
Hourly, line-wise output and **efficiency against an SMV-based plan**, with style and supervisor dashboards.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-PIN%20sign--in-ea580c?style=flat-square)

</td>
</tr>

<tr>
<td colspan="2" align="center"><h3>🔎 Quality</h3></td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧶 [4-Point Fabric Inspection](https://github.com/AbhinandanCreation/fabric-4-point-inspection)
Roll-wise fabric scoring with automatic **pass / fail** and photo reports saved to Drive.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-Drive-34A853?style=flat-square)

</td>
<td width="50%" valign="top">

### 🏷️ [MQA: Trims & Accessories](https://github.com/AbhinandanCreation/mqa-trims-accessories)
Staged **10% → 50% → 100%** audits of incoming trims, synced every hour with ERPNext.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-ERPNext%20API-0089FF?style=flat-square)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### ✅ [AQL Quality Portal](https://github.com/AbhinandanCreation/aql-quality-portal)
AQL final inspections on the phone, with dashboards by checker and by style.

![](https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square) ![](https://img.shields.io/badge/-Mobile%20first-0891b2?style=flat-square)

</td>
</tr>

<tr>
<td colspan="2" align="center"><h3>👥 Operations, People & Platform</h3></td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏠 [AC Central Hub](https://github.com/AbhinandanCreation/ac-central-hub)
One portal for every app, sheet and dashboard, with **role-based access** and a built-in Help Desk.

</td>
<td width="50%" valign="top">

### 🔍 [Checklist Dashboards](https://github.com/AbhinandanCreation/checklist-dashboards)
PC Audit Dashboard: on-time performance for checklists and FMS, people scorecards and follow-up tickets.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗂️ [Delegation System](https://github.com/AbhinandanCreation/delegation-system)
Assign, revise and follow up on tasks, with weekly scores and daily email reminders.

</td>
<td width="50%" valign="top">

### 👥 [HR Forms](https://github.com/AbhinandanCreation/hr-forms)
Grievance, Referral and Reimbursement forms with signatures, print copies and dashboards.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🎫 [Help Ticket Sheet](https://github.com/AbhinandanCreation/help-ticket-sheet)
Automation that keeps the shared Help Tickets register tidy: solved tickets move out, reopened tickets move back.

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" />

## 🛠️ Built with

<div align="center">

<img src="https://skillicons.dev/icons?i=gcp,js,html,css,nodejs,git,github,vscode&perline=8" alt="Tech icons" />

<br/><br/>

![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![ERPNext](https://img.shields.io/badge/ERPNext-0089FF?style=for-the-badge&logo=frappe&logoColor=white)
![clasp](https://img.shields.io/badge/clasp-CLI-555555?style=for-the-badge)

</div>

## ✨ Why we build our own

| | |
|---|---|
| 📊 **One source of truth** | Every app writes to the Google Sheets the team already knows |
| 📱 **Mobile-first** | Supervisors and checkers enter data from the floor on their phones |
| ⏱️ **Plan vs Actual everywhere** | Frozen plan dates, real timestamps, on-time rates |
| 🔐 **Secure by default** | Company Google sign-in, role-based access, no secrets in code |
| ⚡ **Fast to change** | Built in-house, so changes go live in hours, not weeks |

<div align="center">

## 📬 Get in touch

<a href="https://abhinandancreation.in"><img src="https://img.shields.io/badge/Website-abhinandancreation.in-1f6feb?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
<a href="mailto:mis@abhinandancreation.in"><img src="https://img.shields.io/badge/Email-mis%40abhinandancreation.in-0b3a68?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<img src="assets/footer.svg" alt="Crafted with care by the MIS team" width="100%" />

</div>
