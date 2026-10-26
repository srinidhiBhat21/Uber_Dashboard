# Uber Ride Booking Dataset 📁

## Dataset Overview

The dataset used in this project contains Uber ride-booking records for 2025. It is stored in the Excel file `uber.xlsx`.

- Total records: 150,000
- Total columns: 19
- Date coverage: January–December 2025
- Main data sheet: `Sheet1`

## Column Description

| Column Name | Description |
|---|---|
| `Date` | Date of the booking |
| `Time` | Time associated with the booking |
| `Booking ID` | Identifier assigned to a booking |
| `Booking Status` | Outcome of the booking |
| `Customer ID` | Identifier assigned to a customer |
| `Vehicle Type` | Category of vehicle |
| `Pickup Location` | Starting location of the ride |
| `Drop Location` | Destination of the ride |
| `Cancelled Rides by Customer` | Customer cancellation indicator or count |
| `Reason for cancelling by Customer` | Reason recorded for customer cancellation |
| `Cancelled Rides by Driver` | Driver cancellation indicator or count |
| `Driver Cancellation Reason` | Reason recorded for driver cancellation |
| `Incomplete Rides` | Incomplete ride indicator or count |
| `Incomplete Rides Reason` | Reason recorded for an incomplete ride |
| `Booking Value` | Recorded value of the booking |
| `Ride Distance` | Distance associated with the ride |
| `Driver Ratings` | Rating given to the driver |
| `Customer Rating` | Rating associated with the customer |
| `Payment Method` | Method used for payment |

## Booking Status Categories

The dataset includes the following booking statuses:

- Completed
- Cancelled by Driver
- Cancelled by Customer
- No Driver Found
- Incomplete

## Potential Analysis Questions

- What percentage of bookings are completed?
- What are the most common cancellation reasons?
- How does booking value vary by vehicle type?
- How do booking trends change over time?
- Which pickup and drop locations appear most frequently?
- How do customer and driver ratings compare?
- How do booking outcomes vary by vehicle type?

## Data Quality Considerations

- Some fields contain missing values because they may not apply to every booking.
- Cancellation reasons should be analyzed in the context of the booking status.
- Check for duplicate booking IDs before assuming every row represents a unique booking.
- Confirm the currency and distance units before interpreting or presenting these measures.
- Verify whether cancellation and incomplete-ride columns are flags or counts before aggregating them.

## Purpose

This dataset supports exploratory analysis and dashboard development to understand ride-booking patterns and operational performance.

