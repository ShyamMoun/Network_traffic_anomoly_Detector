# Network Traffic Anomaly Detector

A beginner-friendly Python project that analyzes **offline sample network traffic** and flags patterns that may be unusual.

## About

This project is for learning the basics of cybersecurity and data analysis. It reads network flow records from a CSV file, checks a few simple traffic measurements, and reports records that cross the selected thresholds.

The first version will use straightforward rules, so it’s easy to understand how each alert is produced. It is a learning tool, not a production security system.

## Planned features

- Load network flow data from a CSV file
- Check traffic measurements such as bytes, packets, and destination port
- Flag records that match simple anomaly rules
- Print a readable summary of the findings
- Include sample data so the project can be tried offline

## Technology

- Python
- CSV files
- Python’s standard library

## Safety

This project analyzes sample data stored in a file. It does not capture live network traffic or monitor other people’s networks. Use only data you are authorized to access.

## Project status

🚧 In progress — the project is being built step by step.
