# HR Database Management System

## Overview
A complete SQL Server database solution for Human Resources management, featuring employee records, job history tracking, departmental organization, and location management.

## Database Schema

### Core Tables:
- **EMPLOYEES** - Master employee records with personal and employment details
- **JOBS** - Job positions with salary ranges and titles
- **DEPARTMENTS** - Organizational departments with management hierarchy
- **JOB_HISTORY** - Historical tracking of employee position changes
- **LOCATIONS** - Physical department locations and assignments

## Key Features
- Employee information management (personal details, salary, reporting structure)
- Job position and salary band definitions
- Departmental organization with manager assignments
- Comprehensive job history tracking
- Location-based department mapping
- Referential integrity across all entities

## Table Relationships
- Employees belong to Departments (`DEP_ID` → `DEPT_ID_DEP`)
- Employees have Job positions (`JOB_ID` → `JOB_IDENT`)
- Job History tracks employee career progression
- Departments are associated with Locations

## Installation
1. Execute the schema scripts in SSMS
2. Tables will be automatically dropped and recreated
3. Populate with your organizational data

## Use Cases
- Employee onboarding and offboarding
- Salary administration and position management
- Organizational reporting and analytics
- HR compliance and record keeping

<img width="200" height="200" alt="Upwork" src="https://github.com/user-attachments/assets/b7857693-c7ac-49ba-ab6f-efd1ef767353" />
