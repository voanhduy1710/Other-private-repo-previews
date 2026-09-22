# QandaStudy Booking Web App

[![React](https://img.shields.io/badge/React-19-blue.svg)](https://react.dev/)
[![NestJS](https://img.shields.io/badge/Backend-NestJS%2011-E0234E.svg)](https://nestjs.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.x-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC.svg)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF.svg)](https://vitejs.dev/)
[![Kysely](https://img.shields.io/badge/SQL%20Builder-Kysely-00C4CC.svg)](https://kysely.dev/)
[![Supabase](https://img.shields.io/badge/Database-Supabase%20Postgres-3ECF8E.svg)](https://supabase.com/)
[![Swagger](https://img.shields.io/badge/API%20Docs-Swagger%20OpenAPI-85EA2D.svg)](https://swagger.io/)

A full-stack, real-time resource and space reservation management web application built with **React 19**, **Vite 8**, **Tailwind CSS v4**, and **NestJS 11**, powered by **Kysely** and **Supabase PostgreSQL** for scheduling study spaces, livestream rooms, studio facilities, and creative design services.

---

## Features

- **Interactive Studio & Room Booking Calendar**
- **Livestream Schedule & Equipment Management**
- **Design & Video Production Request Workflows**
- **Real-time Availability & Conflict Detection**
- **Automated Date Blocking & Holiday Management**
- **Part-time Staff Scheduling & Shift Rostering**
- **Role-Based Access Control (Admin, Staff, Student)**
- **Slack & Push Notification Event Triggers**
- **Comprehensive Space Utilization Reports & Statistics**
- **Mobile-Responsive UI with Dark & Light Theme Support**

---

## Preview

![Preview 0](Preview_0.png)

![Preview 1](Preview_1.png)

![Preview 2](Preview_2.png)

![Preview 3](Preview_3.png)

![Preview 4](Preview_4.png)

![Preview 5](Preview_5.png)

![Preview 6](Preview_6.png)

---

## Project Structure

```text
QandaStudy-booking-webapp/
├── frontend/                     # React 19 Client Application
│   ├── src/
│   │   ├── app/                  # Application layout, root shell & router config
│   │   ├── features/
│   │   │   ├── admin/            # Admin controls, system configurations & auditing
│   │   │   ├── auth/             # Login, authentication guards & profile sessions
│   │   │   ├── block-dates/      # Facility closure dates & holiday scheduling
│   │   │   ├── design-booking/   # Graphic design service requests & approvals
│   │   │   ├── edit-requests/    # Booking modification & cancellation workflows
│   │   │   ├── livestream/       # Livestream room allocation & equipment presets
│   │   │   ├── notifications/    # In-app alerts, activity log & push messaging
│   │   │   ├── parttime/         # Staff shift assignments & attendance tracking
│   │   │   ├── personnel/        # Team member directory & role assignments
│   │   │   ├── reports/          # Space utilization analytics & booking statistics
│   │   │   ├── studio-booking/   # Audio/video studio reservations & time slots
│   │   │   └── video-booking/    # Video shooting & editing schedule requests
│   │   ├── shared/               # Shared components, date pickers, modals & UI hooks
│   │   ├── index.css             # Tailwind CSS v4 design tokens & base rules
│   │   └── main.tsx              # Frontend bootstrap entry point
│   ├── package.json              # Frontend dependencies & scripts
│   └── vite.config.ts            # Vite 8 configuration
├── backend/                      # NestJS 11 Microservice Backend
│   ├── src/
│   │   ├── core/                 # Database connection, interceptors & auth guards
│   │   ├── features/
│   │   │   ├── accounts/         # User accounts & credentials service
│   │   │   ├── auth/             # JWT auth strategy & authentication modules
│   │   │   ├── blocked-dates/    # Blackout dates CRUD & validation logic
│   │   │   ├── design-booking/   # Design reservation domain logic & endpoints
│   │   │   ├── livestream/       # Livestream scheduling & conflict checks
│   │   │   ├── notifications/    # Notification dispatcher & email alerts
│   │   │   ├── parttime/         # Staff scheduling & roster management
│   │   │   ├── slack-notification/# Slack webhook integrations & event triggers
│   │   │   ├── studio-booking/   # Studio room calendar engine
│   │   │   └── video-booking/    # Video facility booking controllers & services
│   │   ├── integrations/         # Supabase & third-party API clients
│   │   └── main.ts               # NestJS bootstrap & Swagger OpenAPI setup
│   ├── package.json              # Backend dependencies & NestJS CLI scripts
│   └── tsconfig.json             # TypeScript compiler configuration
└── package.json                  # Root npm workspace configuration
```
