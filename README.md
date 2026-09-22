# Other Private Repo Previews

A curated showcase of architecture, tech stacks, and user interfaces for private production repositories developed by [voanhduy1710](https://github.com/voanhduy1710). Due to NDA and proprietary business logic, this repository provides public documentation, system overviews, and interface previews.

---

## Projects Overview

### [1. QandaStudy Booking Web App](1.%20QandaStudy-booking-webapp)

[![React](https://img.shields.io/badge/React-19-blue.svg)](https://react.dev/)
[![NestJS](https://img.shields.io/badge/NestJS-11-E0234E.svg)](https://nestjs.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.x-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC.svg)](https://tailwindcss.com/)
[![Supabase](https://img.shields.io/badge/Supabase-Postgres-3ECF8E.svg)](https://supabase.com/)

A full-stack, real-time resource and space reservation management web application built for scheduling study spaces, livestream studios, video production, and creative design services.

- **Frontend:** React 19, Vite 8, Tailwind CSS v4, TanStack Query & Table, React Hook Form, Zod.
- **Backend:** NestJS 11, Kysely type-safe SQL query builder, Supabase PostgreSQL, Swagger OpenAPI.
- **Key Features:** Real-time calendar booking, livestream equipment tracking, part-time staff rostering, Slack webhook notifications, and space utilization analytics.

![QandaStudy Booking Preview](1.%20QandaStudy-booking-webapp/Preview_0.png)

*[Explore detailed tech stack & full project preview](1.%20QandaStudy-booking-webapp)*

---

### [2. Atino Tong Hop Approval Web](2.%20Atino-tong-hop-approval-web)

[![React](https://img.shields.io/badge/React-19-blue.svg)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC.svg)](https://tailwindcss.com/)
[![Turborepo](https://img.shields.io/badge/Turborepo-Monorepo-EF4444.svg)](https://turbo.build/)
[![TanStack Query](https://img.shields.io/badge/TanStack%20Query-v5-FF4154.svg)](https://tanstack.com/query)

A high-performance financial operations and approval management dashboard for enterprise retail accounting, cash flow control, and multi-tier approval tracking.

- **Frontend:** React 19, Vite 7, Turborepo monorepo, Tailwind CSS, TanStack Query v5, TanStack Table v8.
- **Architecture:** Monorepo with dedicated `web` and `mobile` workspaces, shared UI packages, and typed API clients.
- **Key Features:** Dynamic approval workflows, real-time general ledger reconciliation, cashflow inflow/outflow auditing, product SKU profitability metrics, and granular RBAC.

![Atino Approval Web Preview](2.%20Atino-tong-hop-approval-web/Preview_0.png)

*[Explore detailed tech stack & full project preview](2.%20Atino-tong-hop-approval-web)*

---

### [3. Atino Approval Webapp FastAPI](3.%20Atino-approval-webapp-FastApi)

[![Python](https://img.shields.io/badge/Python-3.12%2B-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.135-009688.svg)](https://fastapi.tiangolo.com/)
[![Supabase](https://img.shields.io/badge/Supabase-Postgres-3ECF8E.svg)](https://supabase.com/)
[![Google BigQuery](https://img.shields.io/badge/Google%20BigQuery-Cloud-4285F4.svg)](https://cloud.google.com/bigquery)
[![Docker](https://img.shields.io/badge/Docker-Cloud%20Run-2496ED.svg)](https://www.docker.com/)

A high-throughput asynchronous RESTful API and background worker service powering financial data ingestion, ledger validation, and real-time LarkSuite webhook processing. *(Original architecture of the Tong Hop Approval Web platform, originally built with FastAPI before being refactored to TypeScript in Project 2).*

- **Backend:** Python 3.12+, FastAPI, Uvicorn ASGI, Pydantic v2, SlowAPI rate limiter.
- **Data & Infrastructure:** Supabase PostgreSQL, Google Cloud BigQuery, Google Cloud Run auto-scaling.
- **Key Features:** Automated Lark/Feishu approval webhooks, background ETL sync workers, BigQuery analytics sync, JWT security, and ledger reconciliation engine.

![Atino FastAPI Backend Preview](3.%20Atino-approval-webapp-FastApi/Preview_0.png)

*[Explore detailed tech stack & full project preview](3.%20Atino-approval-webapp-FastApi)*

---

### [4. Atino Workspace](4.%20Atino-workspace-duy)

[![Python](https://img.shields.io/badge/Python-3.12%2B-blue.svg)](https://www.python.org/)
[![Dagster](https://img.shields.io/badge/Dagster-Cloud%20ETL-4F46E5.svg)](https://dagster.io/)
[![BigQuery](https://img.shields.io/badge/BigQuery-Data%20Warehouse-4285F4.svg)](https://cloud.google.com/bigquery)
[![Pandas](https://img.shields.io/badge/Data%20Engineering-Pandas%20%2F%20Polars-150458.svg)](https://pandas.pydata.org/)
[![Selenium](https://img.shields.io/badge/Automation-Selenium%20%2B%20Xvfb-43B02A.svg)](https://www.selenium.dev/)

An enterprise-grade data platform and automation engine orchestrating multi-channel retail integrations, financial ledger recomputations, and automated browser scrapers.

- **Stack:** Python 3.12+, Dagster Cloud, Google BigQuery, Supabase PostgreSQL, Pandas, Selenium, Undetected Chromedriver, Xvfb virtual display.
- **Pipelines:** Shopee Open Platform, TikTok Shop API, Nhanh.vn ERP, OneOffice HR/Approvals, LarkSuite Bitable, Sepay bank webhooks.
- **Key Features:** Automated P&L financial statement generation, general ledger backdating, discrepancy auditing, and scheduled headless data extractors.

![Atino Workspace Preview](4.%20Atino-workspace-duy/Preview_0.png)

*[Explore detailed tech stack & full project preview](4.%20Atino-workspace-duy)*

---

## ✆ Contact

- **Work Phone:** +84 978 987 889
- **Email:** voanhduy1710@gmail.com
- **Website:** [voanhduy1710.dev](https://voanhduy1710.dev)
