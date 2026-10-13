# TaskFlow CRM

Responsive bilingual CRM and task management application built with React, Vite and Tailwind CSS.

## Live Demo

https://taskflow-crm-eosin.vercel.app

## Demo Credentials

```text
Email: demo@taskflow.app
Password: demo123
```

## Overview

TaskFlow CRM is a lightweight client and task management application created as a portfolio project.

The project demonstrates practical React application development including state management, CRUD operations, filtering, search, client management and browser-side data persistence.

## Features

- Demo authentication
- Dashboard with task statistics
- Task creation
- Task editing
- Task deletion
- Client management
- Search
- Filtering by task status
- Filtering by priority
- Responsive desktop and mobile interface
- English / Russian language support
- Local data persistence
- Reusable React components
- Production deployment with Vercel

## Task Management

Each task can contain:

- Title
- Client
- Status
- Priority
- Due date
- Assignee
- Description

Supported task statuses:

```text
Todo
In Progress
Done
```

Supported priorities:

```text
Low
Medium
High
```

## Client Management

Client records can include:

```text
Company
Contact
Email
Status
```

## Data Persistence

Task and client data are stored in browser `localStorage`.

Authentication state is stored in `sessionStorage`.

This is a portfolio/demo implementation and does not use a production backend or production-grade authentication.

## Tech Stack

- React
- Vite
- Tailwind CSS
- JavaScript
- Lucide React
- localStorage
- sessionStorage
- Vercel

## Local Development

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open:

```text
http://localhost:5173
```

## Production Build

Create a production build:

```bash
npm run build
```

The generated production files are placed in:

```text
dist/
```

## Deployment

The project is deployed on Vercel.

Live version:

https://taskflow-crm-eosin.vercel.app

## Source Code

https://github.com/ceoyur/taskflow-crm

## Project Status

Portfolio project.

Possible future improvements:

- Backend API
- Database storage
- Real authentication
- Role-based access control
- User accounts
- Server-side persistence

## Author

Sergey Yurin
