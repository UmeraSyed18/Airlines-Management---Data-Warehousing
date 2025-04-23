Airlines Management - Data Warehouse Project

This project explores the complexities of airline operations using data warehousing techniques, with a focus on managing booking systems, flights, services, and passenger trends. 
The core objective is to provide analytical insights that help understand airline business operations and passenger behavior.

The Airlines Management project models various aspects of the airline industry including:
- Passenger profiles
- Booking and flight data
- Pricing and cabin classes
- Services and aircraft details

The data warehouse was designed using a Star Schema to support efficient querying and reporting.

The central Fact Table records flight and booking-related metrics, while multiple Dimension Tables store detailed data on:
- Passengers
- Flights
- Aircraft
- Services
- Pricing
- Cabin Class

This structure enables fast, flexible queries for business intelligence.

Data Generation

- Synthetic data was generated for all entities.
- Each dataset was exported to `.csv` format for compatibility.
- The datasets were imported into SQL Server Management Studio (SSMS) for processing.
