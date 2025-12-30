# Thai Working Days Calculator 📅

A web-based tool to calculate Thai working days, accounting for weekends and national holidays with this link https://armzone01.github.io/thai_working_days/

## Features

- **Two calculation modes:**
  - Calculate end date from a starting date and number of working days
  - Count working days within a date range

- **Automatic holiday detection** with fallback options
- **Detailed breakdown** showing each day's status
- **Thai language interface** with proper formatting and day names
- **Real-time holiday data** from Nager.Date API

## How to Use

1. **Select calculation mode:**
   - 🔢 Working days mode: Enter start date and number of days
   - 📅 Date range mode: Enter start and end dates

2. **Fill in dates** using the date pickers

3. **Click "คำนวณวันทำการ"** (Calculate) to see results

4. **View detailed breakdown** of each day with status (working day, weekend, or holiday)

## Data Sources

- **Primary:** Nager.Date API for official Thai public holidays
- **Fallback:** Built-in holiday data for 2025-2026 if API unavailable

## What Counts as Working Day?

Working days = Monday-Friday that are NOT national holidays

## Notes

- Data covers January 1, 2025 - December 31, 2026
- Includes compensatory holidays and special closures
- Last updated: November 1, 2025

## Technical Stack

- HTML
- Tailwind CSS for styling

The HTML and this readme.md files were 100% developed by Claude AI.
