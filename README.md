# RSSB Indore Attendance

A mobile-first web application built to streamline attendance tracking, statistical analysis, and automated reporting for sewadars in Indore.

**Live App:** https://rssb-indore.github.io

## Key Features
- **Multi-Month Attendance Compilation:** Tracks and consolidates attendance records across multiple months directly from a Google Sheets database.
- **Individual Statistics Engine:** Calculates attendance percentages per member with a customizable threshold slider, day-specific focus filters, and dynamic sorting.
- **One-Tap WhatsApp Sharing:** Formats filtered attendance summaries and copies them directly to the clipboard for quick team updates.
- **Automated Report Exports:** Generates downloadable PDF and Excel reports on demand.
- **Mobile-First Experience:** Supports dark mode, PIN-protected access, and full-screen home screen installation (PWA-style) on Android and iOS.

## Architecture & Tech Stack
- **Backend & Database:** Google Apps Script (`code.gs`) and Google Sheets (kept private to protect attendance records and access controls).
- **Frontend:** Responsive HTML5, CSS3, and vanilla JavaScript.
- **Hosting & Delivery:** Served via a lightweight GitHub Pages wrapper (`index.html`) for a clean URL, custom app icon, and native full-screen mobile viewport.

## Developer
Designed and developed by **[Sameer Paryani](https://github.com/sameerparyani)**.
