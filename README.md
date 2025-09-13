# Hotel Booking Data Analysis

This project analyzes hotel booking data to uncover trends related to booking times, hotel types, and cancellation rates. The primary dataset is `hotel_booking.csv`, and the analysis was originally performed using pivot tables in Microsoft Excel.

## 📂 Files in this Repository

* **`hotel_booking.csv`**: The raw dataset containing all booking information. Each row represents a single hotel booking.
* **`Hotel Booking.xlsx`**: The original Microsoft Excel workbook. This file contains the raw data sheet and the pivot tables used for the analysis. Open this file to interact with the analysis directly.
* **`README.md`**: This explanatory file.

## 📈 Analysis Summary

The analysis in the `Hotel Booking.xlsx` file focuses on summarizing key metrics. The main pivot table answers the following questions:

* **Question 1:** Which hotel type (`Resort Hotel` vs. `City Hotel`) has a higher cancellation rate?
* **Question 2:** What is the average number of bookings per month?
* **Question 3:** [Add another question your pivot table answers]

**Pivot Table Structure:**
* **Rows:** `hotel`, `arrival_date_month`
* **Columns:** `is_canceled`
* **Values:** Count of bookings
