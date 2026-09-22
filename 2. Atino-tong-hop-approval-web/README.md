# Atino Tong Hop Approval Web

[![Node.js](https://img.shields.io/badge/Node.js-22%2B-green.svg)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-19-blue.svg)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC.svg)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-7-646CFF.svg)](https://vitejs.dev/)
[![Turborepo](https://img.shields.io/badge/Monorepo-Turborepo-EF4444.svg)](https://turbo.build/)
[![TanStack Query](https://img.shields.io/badge/State-TanStack%20Query%20v5-FF4154.svg)](https://tanstack.com/query)
[![TanStack Table](https://img.shields.io/badge/Table-TanStack%20Table%20v8-2563EB.svg)](https://tanstack.com/table)

A modern, high-performance financial management and approval dashboard web application built with **React 19**, **TypeScript**, **Tailwind CSS**, and **Vite** within a **Turborepo** monorepo, integrated with **TanStack Query** and **TanStack Table** for real-time ledger reconciliation, multi-tier approvals, cash flow analytics, and granular role-based access control.

---

## Features

- **Multi-tier Approval Workflow & Live Status Tracking**
- **Approval API Testing, Inspection & Payload Preview**
- **General Ledger Accounting & Automated Balance Reconciliation**
- **Cash Outflow Analytics & Category Expense Tracking**
- **Cash Inflow Auditing & Receipt Pipeline Management**
- **Executive KPI Dashboard & Real-time Financial Metrics**
- **Product Performance, Margin Analysis & SKU Profitability**
- **KOC Chat & Team Collaboration Workspace**
- **Granular Role-Based Access Control (RBAC) & Permissions**
- **High-fidelity Excel & Styled PDF Report Exports**

---

## Preview

![Preview 0](Preview_0.png)

![Preview 1](Preview_1.png)

![Preview 2](Preview_2.png)

![Preview 3](Preview_3.png)

![Preview 4](Preview_4.png)

---

## Project Structure

```text
Atino-tong-hop-approval-web/
├── apps/
│   ├── web/                      # Core React 19 web application
│   │   ├── src/
│   │   │   ├── app/              # Root App, routing configuration & layout wrappers
│   │   │   ├── assets/           # Static icons & UI graphics
│   │   │   ├── features/
│   │   │   │   ├── admin/        # Admin management & system configuration
│   │   │   │   ├── approval-api-preview/ # API endpoint testing & payload debugger
│   │   │   │   ├── approval-summary/     # Approval status tracking & filter tables
│   │   │   │   ├── auth/         # Authentication provider & session guards
│   │   │   │   ├── balance-summary/      # Balance position & account reconciliations
│   │   │   │   ├── cashflow/     # Cash outflow, expense logs & category breakdowns
│   │   │   │   ├── cashflow-in/  # Cash inflow, revenue pipelines & receipt audits
│   │   │   │   ├── dashboard/    # Executive KPI metrics, summary charts & widgets
│   │   │   │   ├── koc-chat/     # Internal communication & real-time messaging
│   │   │   │   ├── ledger/       # General ledger records, entries & discrepancies
│   │   │   │   ├── permission-management/ # User roles, permissions & access policies
│   │   │   │   ├── product-dashboard/    # SKU margins, product sales & inventory KPIs
│   │   │   │   └── report/       # Exportable financial statements & audit reports
│   │   │   ├── shared/           # Reusable UI components, hooks & table primitives
│   │   │   ├── index.css         # Global Tailwind CSS styles and theme variables
│   │   │   └── main.tsx          # Frontend entry point
│   │   ├── package.json          # Web app dependencies & Vite build scripts
│   │   └── vite.config.ts        # Vite build & proxy configuration
│   └── mobile/                   # Mobile-optimized client application
├── packages/                     # Shared monorepo packages & common types
├── public/                       # Public static assets & preview images
├── turbo.json                    # Turborepo task pipeline orchestration
└── package.json                  # Root monorepo workspace configuration
```
