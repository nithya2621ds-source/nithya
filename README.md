# LaborShield — Labor Law Compliance Tracker

A high-density MVP for tracking labor law compliance requirements.

## Quick Start

```bash
npm install
npm run dev
```

Then open http://localhost:5173

## Build for Production

```bash
npm run build
npm run preview
```

## Features

- **Dashboard** — Compliance score ring, pending actions, upcoming deadlines
- **Compliance Table** — Sortable list with status badges and category icons
- **Filters** — By status (Compliant / Warning / Overdue) and category (Wages / Safety / Tax)
- **Search** — Live text search across regulation names
- **Expandable Rows** — Click any row to view description and assignee
- **Role-based login** — Admin and Employee workflows with session persistence
- **Dashboard** — Total compliances, pending, completed, overdue, and upcoming charts
- **Compliance management** — Add/Edit/Delete, assign users, upload proof documents, and add categories
- **Alerts** — Auto reminders and simulated email notifications before due dates
- **Add Requirement** — Modal form to create new compliance tasks
- **Mark Done** — One-click to mark any item as compliant
- **Delete** — Remove regulations from the tracker

## Demo users
- Admin: `admin@laborshield.com` / `admin123`
- User: `employee@laborshield.com` / `employee123`

## Sample Data Includes

1. Minimum Wage Compliance Review (Wages)
2. Provident Fund (PF) Monthly Filing (Tax)
3. ESI Contribution Filing (Tax)
4. OSHA Safety Audit (Safety)
5. Overtime Pay Audit (Wages)

## Tech Stack

- React 18 + Vite
- Tailwind CSS v3
- Lucide React icons
