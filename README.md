# booking-platform

A booking and client management MVP for small appointment-based businesses (barbers, clinics, tutuors). Built as a learning project in my early career stages to explore backend design, relational data modeling, and scheduling logic.

> status: MVP, in active development

## What it does

- Create and view appointments for a business
- Look up client records and their booking history
- Prevent overlapping bookings for the same provider

## Design goals:

- **No double booking:** enforced at the database level, not just in app code
- **less manual fetching:** one view of today's and upcoming appointments
- **Simple for non-technical users:** minimal UI, few clocks to book

## Tech stack

| Layer    | Choice                | Why                                              |
|----------|-----------------------|--------------------------------------------------|
| Language | TypeScript            | Type safety across the API and data layer        |
| Runtime  | Node.js               | Lightweight runtime with unified TypeScript tooling                                    |
| Server   | Express               | Minimal, explicit routing                        |
| Database | PostgreSQL            | Relational data, constraints, transactions       |
| Frontend | HTML / CSS            | Kept simple on purpose; the focus is the backend |

## Roadmap

- [x] **Stage 1:** Repository setup and initial documentation
- [ ] **Stage 2:** Project tooling (TypeScript, linting) and PostgreSQL database schema
- [ ] **Stage 3:** Core REST API endpoints for providers, clients, and appointments
- [ ] **Stage 4:** Minimal frontend dashboard for viewing and creating bookings