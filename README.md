# Industrial MES Dashboard Demo

Demo project showcasing an industrial MES-style dashboard focused on production digitalization:
- Production orders overview
- Events & alarms logging
- SQL Server persistence (scripts included)
- Filtering/search and CSV export

## Why this project
In many industrial environments, production visibility depends on fragmented tools.  
This demo illustrates how to build a lightweight digitalization layer connecting shopfloor operations and IT systems.

## Tech stack
- C# / .NET (WinForms or WPF)
- SQL Server (schema + stored procedures)
- Python (optional) for data generation / analysis

## Features (MVP)
- Production orders list (status, timestamps, basic KPIs)
- Events/alarms log
- Filters and quick search
- Export to CSV
- SQL scripts to create database objects

## Repository structure
- `src/`  Application source code
- `sql/`  SQL Server scripts (tables, indexes, procedures)
- `data/` Sample/demo data (no real company data)
- `docs/` Screenshots and diagrams

## How to run (planned)
1. Create the database using scripts in `sql/`
2. Configure the connection string in the application settings
3. Run the application

## Roadmap
- PLC/Signal simulator
- Basic dashboard charts (OEE-style indicators)
- Role-based access (optional)

## Contact
LinkedIn: https://www.linkedin.com/in/ricardojl
