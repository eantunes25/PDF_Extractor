# 🧾 PDF Error Extractor 

## Overview

This project automates the detection of known error messages in PDF reports that summarize daily backend transactions. These reports—often lengthy and densely formatted—require manual inspection to identify processing issues like failed records, payment errors, or rejected entries.

This Python program eliminates the need for repetitive manual review by automatically scanning PDFs for predefined error keywords and extracting relevant policy-level details. It consolidates findings into a clean Excel file for quick triage.

---

## What It Does

- Scans all PDF files in a specified folder  
- Searches for predefined error phrases using regex  
- Extracts relevant policy numbers (formatted like `ABC2500123`)  
- Records the page number and matching keywords  
- Outputs results into a structured Excel file

---

## Why This Matters

As someone responsible for reviewing daily reports, I built this tool to reduce manual work while improving error detection reliability. It’s a practical example of how lightweight automation with Python can produce immediate operational value.

---

## Folder Structure

