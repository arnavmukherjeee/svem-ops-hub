# SVEM Command Center

A ServiceNow scoped application for manufacturing operations management. Built on the **Svem Command** app scope (`x_1964226_svem_com`).

## Overview

SVEM Command Center provides real-time visibility into manufacturing jobs, staff assignments, and machine status through two interfaces:

- **Manager Dashboard** — KPI overview, job management, staff assignment, machine status updates, and work review
- **Employee Portal** — Role-based view for shop floor workers to see their assigned jobs, update progress, and view machine/team status

## Tables

| Table | Description |
|-------|-------------|
| **Jobs** (`x_1964226_svem_com_jobs`) | Manufacturing jobs with status tracking, priority, customer info, and staff/machine assignment |
| **Staff** (`x_1964226_svem_com_staff`) | Shop floor employees with role, shift, status, and current job/machine tracking |
| **Machines** (`x_1964226_svem_com_machines`) | Equipment with status (running/idle/maintenance), current job, and uptime tracking |

## Dashboards

| Page | URL |
|------|-----|
| Manager Dashboard | `/x_1964226_svem_com_dashboard.do` |
| Employee Portal | `/x_1964226_svem_com_employee_portal.do` |

## Features

- Job assignment and reassignment (staff to jobs)
- Machine status management with modal updates
- Work review workflow (approve/reject pending jobs)
- Priority-based job tracking (critical/high/medium/low)
- Ship status tracking (not shipped/OSP/partial/shipped)
- Spanish language support via field label translations
- Role-based access (manager vs employee views)

## Instance

- **Instance**: dev367527.service-now.com
- **App Scope**: x_1964226_svem_com
- **App ID**: 83b23c9493500310414ef2375d03d6d7

## Setup

1. Connect this repo to your ServiceNow instance via Source Control
2. Pull to sync all application files
3. Navigate to the dashboard or employee portal URLs above
