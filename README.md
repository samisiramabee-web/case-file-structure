# Law Firm Case File Structure App

A static web app that helps law firms create a case file folder structure from a matter intake form.

## Project Overview

This app provides a simple interface for entering case details and generating a folder list for legal matter organization. It is designed as a lightweight prototype for planning case file structure and does not include backend storage.

## Project Files

- `index.html` – Main application markup with form fields and result display.
- `styles.css` – Styling for layout, form controls, and folder list presentation.
- `script.js` – Logic to generate folder templates, append custom folders, and render the summary.

## How to Use

1. Open `law-firm-case-file-structure-app/index.html` in your browser.
2. Enter the case name and client name.
3. Select a matter type.
4. Optionally add a start date.
5. Optionally type comma-separated custom folder names.
6. Click **Generate Structure**.

## Features

- Generates a default folder structure based on matter type:
  - Litigation
  - Real Estate
  - Corporate
  - Family Law
  - Other
- Supports custom folder names.
- Displays a case summary and generated folder list.

## Example Use Case

A paralegal or attorney can use this app to sketch a new matter’s file structure before creating actual folders in the firm’s file system.

## Notes

- This project is static and runs entirely in the browser.
- No server or database is required.
- The folder structure is generated visually and not created on disk.
