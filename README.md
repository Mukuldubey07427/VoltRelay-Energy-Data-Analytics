# ⚡ VoltRelay Energy Data Analytics

A data analytics project for an EV battery swapping network, developed as part of a hackathon challenge.

## 📌 Project Overview

This project analyzes a synthetic EV battery swapping network operating across multiple Indian cities, including Bengaluru, Delhi NCR, Hyderabad, Pune, Mumbai, and Jaipur.

The analysis focuses on network performance, service failures, station-level patterns, battery health, pricing and partner economics, and rider retention.

## 🎯 Business Questions

The analysis investigates:

- Network performance over time
- Completed swaps, revenue, and failure rates
- Queue waits, failed attempts, and abandoned swaps
- Station and geographic performance
- Battery health and supplier patterns
- Pricing and fleet partner economics
- Rider retention and factors associated with repeat usage
- Customer support ticket patterns

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- DuckDB
- Matplotlib
- Google Colab
- Jupyter Notebook

## 📊 Dataset

The project uses eight related datasets:

- `swap_events.csv`
- `station_hourly_status.csv`
- `riders.csv`
- `batteries.csv`
- `support_tickets.csv`
- `stations.csv`
- `city_daily_context.csv`
- `fleet_partners.csv`

The raw dataset files are not included in this repository.

## 🔍 Analysis Performed

### 1. Network Performance
- Monthly swap performance
- Completion and failure rates
- Revenue analysis
- Average queue wait

### 2. Service & Customer Experience
- Failure event breakdown
- Queue abandonment
- Rider cancellations
- Hourly failure patterns
- Station-level service performance

### 3. Station & Geographic Analysis
- City-wise performance
- Station volume
- Failure-rate patterns
- Location type
- Charger generation
- Expansion wave

### 4. Battery Analysis
- State of Health (SOH)
- Battery suppliers
- Pack types
- Retired batteries
- Manufacturing lot patterns

### 5. Pricing & Partner Economics
- Tariff performance
- Average revenue per swap
- Fleet partner vs independent rider patterns

### 6. Rider Retention
- 30-day retention
- Retention by vehicle class
- Comparison of retained vs non-retained riders
- Association with usage and service experience

### 7. Customer Support
- Ticket categories
- Resolution status
- CSAT
- Resolution time

## ⚠️ Data Quality Considerations

The dataset contains several data-quality considerations, including:

- Missing telemetry
- Timestamp inconsistencies
- Test stations
- Offline batches
- Invalid or implausible telemetry values
- Missing CSAT values

These issues are considered during the analysis rather than being silently ignored.

## 📁 Repository Structure

```text
VoltRelay-Energy-Data-Analytics/
│
├── VoltRelay_Energy_FINAL_hackathon.ipynb
└── README.md
