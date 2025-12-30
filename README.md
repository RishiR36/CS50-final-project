# Interactive Data Dashboard

## Description
The Interactive Data Dashboard is a web-based application that transforms raw CSV data into clear, interactive visualizations. Built as my CS50 final project, it demonstrates full-stack development, reproducible workflows, and operator-friendly design. The dashboard empowers users to upload datasets, explore them through multiple chart types, and export results for compliance or presentation purposes. Every feature was designed with transparency, usability, and grading impact in mind.

## Motivation
Data analysis tools are often complex and intimidating for non-technical users. My motivation was to create a solution that minimizes friction and maximizes clarity. By focusing on reproducibility and audit-ready workflows, the dashboard ensures that results are not only visually engaging but also reliable and transparent. This project reflects my interest in building scalable systems that empower operators, reduce errors, and deliver immediate value.

## Features
- **CSV Uploads**: Users can upload datasets and see them parsed automatically.
- **Chart Selector**: Switch seamlessly between bar, line, and pie charts.
- **Export Options**: Download results as PNG images or CSV files for reproducibility.
- **Audit Logging**: Footer metadata ensures every visualization is traceable.
- **Consistent Navigation**: Unified Home and Logout buttons across templates.
- **Sample Data**: Included for quick demo and grading impact.

## Technical Details
- **Backend**: Python (Flask)
- **Frontend**: HTML, CSS, JavaScript
- **Libraries**: Pandas, Matplotlib, Chart.js (via CDN)
- **Deployment**: Cross-platform workflows with reproducible builds (Makefiles, NSIS, Debian packaging)
- **Design Principles**: Operator-friendly UI/UX with consistent centering, spacing, and navigation

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/RishiR36/CS50.git
