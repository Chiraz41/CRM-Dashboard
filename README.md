# Simple CRM Dashboard

A modern and responsive Customer Relationship Management (CRM) dashboard developed to simplify lead and contact management, organize customer information, and improve business workflow efficiency.

## Overview

Simple CRM Dashboard is a web application developed during an internship at **VISIOAD**, Sousse, Tunisia, from July to August 2025.

The application provides a centralized interface for managing leads and contacts, tracking customer-related activities, and organizing reminders and calendar events. It aims to improve the efficiency of customer relationship management through an intuitive user interface and a structured data management system.

## Features

### Lead Management
- Organize and manage sales leads.
- Access and update lead information.
- Centralize prospect data for easier follow-up.

### Contact Management
- Manage customer and contact information.
- Access contact details from a centralized dashboard.
- Keep customer records organized.

### Authentication
- Secure user authentication.
- Session management using NextAuth.js.
- Access to protected application features.

### Reminders and Calendar
- Organize reminders for customer follow-ups.
- Manage scheduled activities.
- Integrate calendar functionality to improve task organization.

### Dashboard Interface
- Responsive and intuitive user interface.
- Structured navigation and reusable components.
- Clear presentation of customer-related information.

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | React framework for application development |
| React | Component-based user interface |
| TypeScript | Static typing and maintainable code |
| Prisma ORM | Database access and data modeling |
| PostgreSQL | Relational database |
| NextAuth.js | Authentication and session management |
| Tailwind CSS | Utility-first styling |
| ShadCN UI | Reusable and accessible UI components |
| Zod | Schema validation and data validation |

## Architecture

The application follows a modern web architecture in which the frontend communicates with application logic and database access layers.

```text
User
  |
  v
Next.js Application
  |
  +----------------------+
  |                      |
  v                      v
React Components     NextAuth.js
  |                  Authentication
  |
  v
Application Logic
  |
  v
Prisma ORM
  |
  v
PostgreSQL Database
```

## Getting Started

### Prerequisites

- Node.js
- npm
- PostgreSQL
- Git

Open the local address displayed in the terminal, typically:

http://localhost:3000

## Project Structure

An indicative structure for a Next.js application:

```text
simple-crm-dashboard/
├── prisma/
│   └── schema.prisma
├── public/
├── src/
│   ├── app/
│   ├── components/
│   ├── lib/
│   └── ...
├── .env
├── package.json
├── tsconfig.json
└── README.md
```

The actual structure may vary depending on the Next.js routing system and the organization of the project.

## Skills and Concepts

This project involved working with:

- Full-stack web application development.
- TypeScript and reusable React components.
- Relational database design with PostgreSQL.
- Database operations using Prisma ORM.
- Authentication and session management.
- Form and data validation using Zod.
- Responsive interface development with Tailwind CSS and ShadCN UI.
- Customer and lead management workflows.

## Project Information

**Project:** Simple CRM Dashboard  
**Company:** VISIOAD  
**Location:** Sousse, Tunisia  
**Period:** July 2025 – August 2025  
**Domain:** Full-Stack Web Development

---

This project demonstrates the development of a modern CRM application combining a responsive user interface, structured database management, authentication, and customer follow-up features.
