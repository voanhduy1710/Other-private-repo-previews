# Atino Workspace

[![Python](https://img.shields.io/badge/Python-3.12%2B-blue.svg)](https://www.python.org/)
[![Dagster](https://img.shields.io/badge/Orchestration-Dagster%20Cloud-4F46E5.svg)](https://dagster.io/)
[![Google BigQuery](https://img.shields.io/badge/Data%20Warehouse-BigQuery-4285F4.svg)](https://cloud.google.com/bigquery)
[![Supabase](https://img.shields.io/badge/Database-Supabase%20Postgres-3ECF8E.svg)](https://supabase.com/)
[![Pandas](https://img.shields.io/badge/Data%20Engineering-Pandas%20%2F%20Polars-150458.svg)](https://pandas.pydata.org/)
[![Selenium](https://img.shields.io/badge/Automation-Selenium%20%2F%20Webcrawling-43B02A.svg)](https://www.selenium.dev/)
[![Docker](https://img.shields.io/badge/Container-Docker%20%2B%20Xvfb-2496ED.svg)](https://www.docker.com/)

An enterprise data platform and automation workspace built in **Python**, utilizing **Dagster** for workflow orchestration, **Google Cloud BigQuery** for analytical data warehousing, and **Supabase PostgreSQL** for operational data stores, integrating multi-channel e-commerce APIs, financial ledger backdating, and automated headless web scraping.

---

## Features

- **Dagster Orchestrated Data Pipelines & Cloud Schedules**
- **Multi-Platform E-commerce ETL (Shopee, TikTok Shop, Nhanh.vn)**
- **Automated Financial P&L & Balance Sheet Computations**
- **General Ledger Backdating & Discrepancy Reconciliation**
- **LarkSuite / Feishu Approval Automation & Bitable Sync**
- **OneOffice ERP Approval & Attendance Integrations**
- **Google Sheets Automated Two-way Synchronization**
- **Headless Browser Scraping via Selenium & Undetected Chromedriver**
- **Banking & Payment Webhook Ingestion (Sepay)**
- **Dockerized Runtime with Virtual Framebuffer (Xvfb) for Browser Automation**

---

## Preview

![Preview 0](Preview_0.png)

---

## Project Structure

```text
Atino-workspace-duy/
├── backdating_codes/             # Historical financial ledger backdating & recomputation
├── bigquery_sql/                 # Production SQL models & BigQuery data pipelines
├── dagster_etl/                  # Dagster asset definitions, jobs & cloud schedules
├── functions/                    # Core business logic, Supabase loaders & helper routines
├── google_sheets/                # Google Sheets API synchronization & formatting scripts
├── larksuite/                    # Lark / Feishu Open API integrations & approval exports
├── mapping/                      # Chart of accounts, category & store mapping dictionaries
├── nhanh_v3/                     # Nhanh.vn retail ERP API sync (orders, customers, stock)
├── one_office/                   # OneOffice HRM/ERP approval & timekeeping extractors
├── P_and_L/                      # Profit and Loss reporting engines & aggregation rules
├── sepay/                        # Real-time bank transaction webhook handlers
├── shopee/                       # Shopee Open Platform orders & financial data sync
├── tiktok/                       # TikTok Shop seller API pipelines & payout reconciliations
├── webcrawling/                  # Selenium, Apify & stealth scraping modules
├── Dockerfile                    # Container definition with Xvfb headless display
└── requirements.txt              # Data platform dependencies
```
