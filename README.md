# hr-hiring-download-automation

# HR Operations
# HRSC Document Download Automation

## Overview

Python + Selenium automation to download and organize hiring documents from an internal recruitment portal.

Built to eliminate manual work involved in collecting candidate onboarding documents.

---

## What it does

* Reads hiring data from Excel
* Searches candidates by Job Opening
* Downloads:

  * Resume (external hires)
  * Offer Letter
  * Offer Acceptance
  * CTC breakup (INR cases)
* Renames files using standard naming format
* Converts HTML acceptance to PDF
* Merges final signed offer package
* Moves files to shared folders

---

## Tech Stack

Python, Selenium, pandas, xlwings, PyPDF2, pdfkit

---

## How to run

1. Update file paths and ChromeDriver location in the script
2. Install dependencies
3. Run:

```bash
python script.py
```

---

## Notes

* Designed for internal enterprise HR system
* Requires portal access and shared drive permissions
* Element selectors may need updates if UI changes

---

**Year:** ~2018–2020
Reference project showcasing real-world business process automation.
