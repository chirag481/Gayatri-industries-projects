# Gayatri Industries — Cabin Order Management System

A multi-step web application built with **HTML, CSS, JavaScript**, and **Google Apps Script** to digitize and streamline the cabin order intake process for a porta cabin manufacturing business. The app replaces manual, paper-based order forms with a guided 9-step interface covering client details, fabrication specs, carpentry, electrical, paint, washroom, furniture, and accessories — complete with smart defaults, conditional sections, and quantity tracking.

On submission, order data is automatically written to a structured **Google Sheets** database, uploaded drawing files are saved to organized **Google Drive** folders, and a professionally formatted **order PDF** (via jsPDF) is generated and downloaded instantly. A built-in **Machine Operator workflow** lets staff flag orders for production with a single checkbox — automatically compiling all jobs ticked on the same day into one clean, bilingual (English + Gujarati) production PDF, saved directly to Drive for the shop floor.

**Key features:** multi-step form with jump navigation, auto-filled "Basic" configuration defaults, dynamic quantity fields, multi-file drawing uploads with individual Drive links, real-time Google Sheets sync, automated datewise PDF generation with Arial/Gujarati typography, and a fully serverless architecture powered entirely by Google Apps Script.

**Tech stack:** HTML5, CSS3, Vanilla JavaScript, jsPDF, Google Apps Script, Google Sheets API, Google Drive API.


## Purchase Rate Tracker

A browser-based purchase rate intelligence tool that ingests raw purchase register data and 
automatically flags price anomalies, compares vendor rates, and generates audit-ready PDF reports 
— no backend, no installation, runs entirely client-side.

**Key Features**
- Automated rate-spike/drop detection with configurable alert thresholds (previously no such check existed)
- Vendor comparison engine — identifies lowest-rate vendor per item across purchase history
- Interactive dashboards: monthly purchase trends, top 10 items/vendors by spend, spike distribution
- One-click PDF exports: date-wise, item-wise, and vendor-wise reports (with tables, headers, formatting)
- Client-side Excel ingestion with column auto-mapping, filtering, search, and pagination

**Tech Stack**
Vanilla JavaScript, HTML5/CSS3, SheetJS (XLSX parsing), Chart.js (data viz), jsPDF + AutoTable (report generation)

**Impact**
- Processes 5,000+ purchase records across 100+ vendors per run
- Flagged ₹15,000–20,000 in rate overpayments across 10-12 vendors via automated alerts
- Replaced a manual, ad-hoc rate-checking process with zero prior anomaly detection
