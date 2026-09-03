# OLA Data Analyst Project

## Project Overview

This project is an end-to-end data analytics case study based on ride-booking
data from OLA. The objective of the project is to analyze booking behaviour,
ride cancellations, revenue, vehicle performance, and customer and driver
ratings using SQL and Power BI.

The project demonstrates how structured data analysis and interactive
visualization can be used to extract meaningful business insights from
large-scale ride-booking data.

---

## Business Problem

The objective of this project is to analyze OLA ride-booking data and answer
important business questions related to:

- Booking performance
- Successful and cancelled rides
- Customer and driver cancellations
- Revenue generation
- Vehicle type performance
- Ride distance
- Payment methods
- Customer and driver ratings

The analysis helps identify important patterns and trends that can support
data-driven business decisions.

---

## Dataset Information

The dataset contains approximately:

- 103,000 ride-booking records
- 19 columns

### Key Features

The dataset includes information related to:

#### Trip Details

- Date
- Time
- Booking ID
- Pickup Location
- Drop Location
- Vehicle Type

#### Booking Status

- Successful Rides
- Cancelled by Customer
- Cancelled by Driver
- Incomplete Rides
- Incomplete Ride Reasons

#### Performance

- Vehicle Turnaround Time
- Customer Turnaround Time
- Ride Distance

#### Financial Information

- Booking Value
- Payment Method

#### Ratings

- Driver Ratings
- Customer Ratings

---

## Technologies Used

- SQL
- MySQL / PostgreSQL
- Power BI
- DAX
- Microsoft Excel

---

# Project Workflow

## 1. Data Preparation

The ride-booking dataset was prepared for analysis by:

- Reviewing the dataset structure and available columns
- Understanding booking status and ride-related attributes
- Organizing the data for SQL analysis
- Preparing relevant fields for Power BI visualization

---

## 2. SQL Data Analysis

SQL was used to answer business-focused questions related to booking
performance and customer behaviour.

The analysis included:

- Retrieving successful bookings
- Calculating average ride distance by vehicle type
- Counting rides cancelled by customers
- Identifying top customers based on number of bookings
- Analyzing driver cancellations
- Finding maximum and minimum driver ratings
- Analyzing UPI payment bookings
- Calculating average customer ratings by vehicle type
- Calculating total booking value of successful rides
- Identifying incomplete rides and their reasons

Reusable SQL queries and views were created to organize important business
analysis results.

---

## 3. Power BI Dashboard

An interactive Power BI dashboard was created to visualize important
ride-booking insights.

The dashboard includes analysis of:

### Overall Performance

- Ride volume over time
- Booking status distribution

### Vehicle Performance

- Top vehicle types based on ride distance

### Revenue Analysis

- Revenue by payment method
- Top customers based on booking value
- Ride distance distribution

### Cancellation Analysis

- Customer cancellation reasons
- Driver cancellation reasons

### Ratings Analysis

- Driver rating distribution
- Customer rating analysis
- Customer and driver rating correlation

---

## Key Business Insights

The project helps analyze:

- Ride booking trends
- Successful versus cancelled bookings
- Revenue generated from successful rides
- Vehicle type performance
- Customer booking behaviour
- Cancellation patterns
- Payment preferences
- Customer and driver satisfaction

---

## Project Structure

```text
OLA-Data-Analyst-Project/
│
├── data/
│   └── Bookings.csv
│
├── sql/
│   └── ola_business_analysis.sql
│
├── powerbi/
│   └── Ola_DA_Project.pbix
│
├── presentation/
│   └── Ola_Project_Presentation.pptx
│
├── images/
│   └── dashboard.png
│
└── README.md
