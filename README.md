# Asif Sulaiman

**Full-stack engineer** - I build production software end to end, from
PostgreSQL schema design to the React interface people use every day.

## Flagship: Raas Tracker

A chemical inventory, production and sales ERP, live in production.

[Repository](https://github.com/asif-sulaiman/Raas-Tracker) ·
[Live app](https://chemcalc-omega.vercel.app)

- **Sales pipeline:** PI -> LC -> shipment -> payment, with LC payment terms,
  per-invoice maturity, overdue reminders and a sheet-like commercial report.
- **Operations:** recipe-based production runs, stock reconciliation and
  approval workflows.
- **Backend:** Flask 3, psycopg3, PostgreSQL (Supabase) - transactional writes,
  parameterized SQL, audited mutations, 1,300+ tests.
- **Frontend:** React 19, Vite, Tailwind 4 - 350+ tests, accessible dialogs,
  exact integer-cent money math.
- **Delivery:** CI on every PR (backend + frontend), deployed on Vercel with a
  daily reminder cron.

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

## How I work

- **Tests first.** A change is finished when the suite, linters and the
  production build are green.
- **Exact by default.** Money in integer cents, quantities in SQL `numeric` -
  no float drift.
- **Secure by default.** Parameterized SQL, server-side validation, role-gated
  routes and an audit trail on every mutation.
- **Small, atomic commits.** Each one tells you why, not just what.
