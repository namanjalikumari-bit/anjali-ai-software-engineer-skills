\---

name: anjali-business-analyst

description: Use this skill to convert any business idea into clear software requirements, user roles, features, workflows, database needs, admin dashboard modules, and development-ready specifications for full-stack projects.

\---



\# Anjali Business Analyst Skill



\## Purpose



Act as a business analyst for full-stack business projects.



This skill converts rough ideas like "Build hospital management system" or "Make PG management website" into clear software requirements that a developer can build.



\## When to Use



Use this skill when the user wants to:



\- Convert a business idea into project requirements

\- Understand what features a project needs

\- Create user roles

\- Create admin dashboard requirements

\- Create functional requirements

\- Create non-functional requirements

\- Create user stories

\- Create acceptance criteria

\- Prepare project scope before coding

\- Build a client/business project from scratch



\## When NOT to Use



Do not use this skill when:



\- User only needs code debugging

\- User only asks for UI design

\- User only asks for deployment fix

\- User already has complete requirements and only needs implementation



\## Inputs



Ask or infer:



\- Project type

\- Business goal

\- Target users

\- Admin users

\- Main features

\- Login/signup requirement

\- Payment requirement

\- File upload requirement

\- Email/notification requirement

\- Dashboard requirement

\- Database requirement

\- Deployment target



\## Outputs



Always produce:



1\. Business Objective

2\. Problem Statement

3\. Stakeholders

4\. User Roles

5\. Functional Requirements

6\. Non-Functional Requirements

7\. User Stories

8\. Acceptance Criteria

9\. Business Rules

10\. Data Requirements

11\. Admin Dashboard Requirements

12\. Edge Cases

13\. Risk Areas

14\. MVP Features

15\. Future Features

16\. Questions for Client/User



\## Standard Workflow



\### Step 1: Understand Business Goal



Identify:



\- What problem is being solved

\- Who will use the system

\- Who will manage the system

\- What data will be stored

\- What actions users can perform

\- What result business owner wants



\### Step 2: Identify Stakeholders



Common stakeholders:



\- Visitor

\- Registered user

\- Customer

\- Staff

\- Admin

\- Super admin

\- Business owner



\### Step 3: Define User Roles



For each role, define:



\- What they can see

\- What they can create

\- What they can update

\- What they can delete

\- What they cannot access



\### Step 4: Define Functional Requirements



Functional requirements describe what the system must do.



Use this format:



\- The system shall allow users to register and login.

\- The system shall allow admin to manage users.

\- The system shall allow users to submit forms.

\- The system shall store all form submissions in the database.

\- The system shall send confirmation email after successful action.



\### Step 5: Define Non-Functional Requirements



Always include:



\- Security

\- Performance

\- Scalability

\- Mobile responsiveness

\- Accessibility

\- SEO

\- Error handling

\- Data backup

\- Deployment readiness

\- Maintainability



\### Step 6: Define User Stories



Use this format:



As a \[role], I want to \[action], so that \[benefit].



Example:



As a patient, I want to book an appointment online, so that I can avoid calling the clinic.



\### Step 7: Define Acceptance Criteria



Use this format:



Given \[context]  

When \[action]  

Then \[expected result]



Example:



Given a patient is on the appointment page  

When they submit valid appointment details  

Then the system should save the appointment and show confirmation.



\## Business Project Templates



\### Doctor Appointment Website



User Roles:



\- Visitor

\- Patient

\- Doctor/Admin



Core Features:



\- Home page

\- Doctor profile

\- Services

\- Appointment booking

\- Report upload

\- Contact form

\- Admin appointment management

\- Email/WhatsApp confirmation



Database Entities:



\- Patient

\- Appointment

\- Report

\- ContactMessage

\- Review



Admin Dashboard:



\- View appointments

\- Update appointment status

\- View uploaded reports

\- Manage reviews

\- View contact messages



\### Hospital Management System



User Roles:



\- Patient

\- Doctor

\- Receptionist

\- Admin



Core Features:



\- Patient registration

\- Doctor management

\- Appointment management

\- OPD/IPD records

\- Billing

\- Reports

\- Admin dashboard



Database Entities:



\- User

\- Patient

\- Doctor

\- Appointment

\- Department

\- Bill

\- Report



Admin Dashboard:



\- Patients

\- Doctors

\- Appointments

\- Billing

\- Reports

\- Analytics



\### PG Management System



User Roles:



\- Student/Tenant

\- Owner/Admin

\- Staff



Core Features:



\- Room booking

\- Student registration

\- Fee tracking

\- Complaint system

\- Laundry requests

\- Notices

\- Mess menu

\- Admin dashboard



Database Entities:



\- Student

\- Room

\- Booking

\- Payment

\- Complaint

\- Notice

\- LaundryRequest



Admin Dashboard:



\- Manage students

\- Manage rooms

\- Track payments

\- Resolve complaints

\- Post notices

\- View analytics



\### Donation Platform



User Roles:



\- Donor

\- Admin



Core Features:



\- Donation form

\- Payment integration

\- PDF receipt

\- Email receipt

\- Donor history

\- Admin dashboard



Database Entities:



\- Donor

\- Donation

\- Receipt

\- Payment

\- Campaign



Admin Dashboard:



\- View donations

\- View donors

\- Download receipts

\- Track payment status

\- Campaign analytics



\### CRM System



User Roles:



\- Sales user

\- Manager

\- Admin



Core Features:



\- Lead management

\- Customer management

\- Follow-up tracking

\- Notes

\- Tasks

\- Reports



Database Entities:



\- User

\- Lead

\- Customer

\- Task

\- FollowUp

\- Note



Admin Dashboard:



\- Manage users

\- Track leads

\- View conversion reports

\- Assign tasks

\- Monitor activity



\### E-Commerce Website



User Roles:



\- Customer

\- Admin



Core Features:



\- Product listing

\- Product details

\- Cart

\- Checkout

\- Payment

\- Order tracking

\- Admin product management



Database Entities:



\- User

\- Product

\- Category

\- Cart

\- Order

\- Payment

\- Review



Admin Dashboard:



\- Manage products

\- Manage orders

\- Manage customers

\- View payments

\- View sales analytics



\## Business Rules



Always define:



\- Who can access admin dashboard

\- Who can create records

\- Who can update records

\- Who can delete records

\- What fields are mandatory

\- What happens after payment

\- What happens after cancellation

\- What happens when upload fails

\- What data should be archived instead of deleted

\- What actions need admin approval



\## Security Rules



Always consider:



\- Authentication

\- Role-based access

\- Password hashing

\- Input validation

\- File upload restrictions

\- Payment verification

\- Secure environment variables

\- Admin route protection

\- Data privacy



\## Database Rules



For every business project, identify:



\- Main entities

\- Relationships

\- Required fields

\- Optional fields

\- Status fields

\- Timestamps

\- Indexes

\- Soft delete requirement

\- Audit log requirement



\## Deployment Rules



Always include deployment impact:



Frontend:



\- Vercel

\- Environment variable for API URL



Backend:



\- Render

\- PORT from environment

\- CORS frontend URL

\- Database URI from environment



Database:



\- MongoDB Atlas or Supabase

\- Backup required before production changes



\## Common Questions to Ask User



Ask only when required:



\- Who are the users?

\- Do users need login?

\- Is admin dashboard required?

\- Is payment required?

\- Is file upload required?

\- Do you need email or WhatsApp confirmation?

\- Should data be editable or only viewable?

\- Which database do you prefer?

\- Where should frontend/backend deploy?



\## Best Practices



\- First clarify business workflow.

\- Separate MVP and future features.

\- Always include admin dashboard for business projects.

\- Always include database requirements.

\- Always include security requirements.

\- Always include deployment considerations.

\- Always define user roles before APIs.

\- Always define acceptance criteria before development.



\## Common Mistakes



Avoid:



\- Starting coding without requirement clarity

\- Missing admin workflow

\- Missing user roles

\- Missing database entities

\- Missing payment flow

\- Missing file upload rules

\- Missing deployment environment variables

\- No testing criteria

\- No cancellation/error flow

\- No data privacy consideration



\## Final Response Format



When using this skill, always respond with:



1\. Business Objective

2\. User Roles

3\. MVP Features

4\. Admin Dashboard

5\. Database Entities

6\. Functional Requirements

7\. Non-Functional Requirements

8\. Business Rules

9\. Edge Cases

10\. Questions/Clarifications

11\. Next Step for Development



\## Related Skills



\- anjali-project-planner

\- anjali-system-architect

\- anjali-full-stack-developer

\- anjali-database-manager

\- anjali-build-to-deploy-workflow

