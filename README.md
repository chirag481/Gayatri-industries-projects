# Gayatri Industries — Cabin Order Processing System

## Description
A multi-step web application (HTML/CSS/JS + Google Apps Script) that digitizes cabin order intake for a porta cabin manufacturing business — replacing fully manual, paper-based order forms with a guided 9-step digital workflow covering fabrication, carpentry, electrical, paint, washroom, furniture, and accessories.

## Key Features
- 9-step guided form with jump navigation, smart "Basic" configuration defaults, and conditional sections
- Multi-file drawing uploads, auto-organized into Google Drive with individual shareable links
- One-click, auto-formatted order PDF generation (jsPDF) on submission
- Real-time sync to a 72-column Google Sheets database — zero manual data entry
- Machine Operator workflow: single checkbox auto-compiles all same-day orders into one bilingual (English + Gujarati) production PDF for the shop floor
- Fully serverless — built entirely on Google Apps Script, Sheets, and Drive APIs

## Tech Stack
HTML5, CSS3, Vanilla JavaScript, jsPDF, Google Apps Script, Google Sheets API, Google Drive API

## Impact
- Reduced order processing time from **~15 minutes to ~5 minutes per order** (~65% faster)
- Digitized **25+ cabin orders/month**, eliminating fully manual paper-based intake
- Adopted across **3 departments** — Sales, Production, and Machine Operators — as a shared source of truth
- Tracks **72 structured data fields** per order, up from an untracked, error-prone paper process
