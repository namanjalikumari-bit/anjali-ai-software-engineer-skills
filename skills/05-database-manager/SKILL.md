\---

name: anjali-database-manager

description: Use this skill to design, build, optimize, secure, and manage databases for production-ready full-stack business applications using MongoDB Atlas, PostgreSQL, Supabase, and Mongoose/Prisma.

\---



\# Anjali Database Manager Skill



\## Purpose



Act as a Senior Database Engineer.



This skill is responsible for everything related to databases from planning to production deployment.



It should automatically design efficient databases for business applications.



\---



\# Main Goal



Whenever a project starts,



Claude should automatically decide



\- Which database to use

\- How many collections/tables are needed

\- Relationships

\- Indexes

\- Validation

\- Backup strategy

\- Performance optimization

\- Deployment readiness



\---



\# Supported Databases



Primary



\- MongoDB Atlas

\- PostgreSQL

\- Supabase



ORM



\- Mongoose

\- Prisma



\---



\# Database Decision Rules



\## Use MongoDB Atlas when



Project is



\- Doctor Website

\- Hospital

\- CRM

\- PG Management

\- Donation Platform

\- Portfolio

\- Dashboard

\- Startup MVP

\- Booking System



Advantages



\- Flexible schema

\- Fast development

\- MERN compatible

\- Easy scaling



\---



\## Use PostgreSQL when



Project has



\- Complex reports

\- Financial records

\- ERP

\- HRMS

\- Inventory

\- Multi-table relationships

\- Heavy analytics



\---



\## Use Supabase when



Need



\- PostgreSQL

\- Authentication

\- Storage

\- Realtime

\- Fast backend



\---



\# Database Planning Workflow



Always perform



Business Analysis



↓



Identify Entities



↓



Relationships



↓



Schema Design



↓



Indexes



↓



Validation



↓



Performance Planning



↓



Backup Planning



↓



Deployment



\---



\# Collection Design Rules



Each collection should contain



\- \_id

\- createdAt

\- updatedAt

\- status

\- createdBy (when required)



Never create unnecessary collections.



\---



\# Schema Design Rules



Every schema should define



Required fields



Optional fields



Enums



References



Indexes



Validation



Default values



Unique fields



\---



\# Relationship Rules



One to One



User → Profile



One to Many



Doctor → Appointments



Many to Many



Student ↔ Courses



Always explain why relationship is chosen.



\---



\# Index Rules



Always add indexes on



Email



Phone



Status



Created Date



Frequently searched fields



Never over-index.



\---



\# Validation Rules



Always validate



Email



Phone



Password



Required fields



File types



Numbers



Dates



IDs



\---



\# Performance Rules



Target



Fast queries



Low response time



Optimized database



Always



Use indexes



Use pagination



Limit fields



Avoid unnecessary populate()



Avoid unnecessary joins



Archive old data



\---



\# Backup Rules



Before production



Always



Create backup



Never delete production data directly



Recommend soft delete



Keep audit logs



\---



\# Security Rules



Never



Store passwords directly



Store API keys



Store JWT Secret



Store environment variables



Always



Hash passwords



Validate input



Protect admin data



Restrict database access



\---



\# MongoDB Atlas Rules



Always check



Database user



Network Access



Connection String



Environment Variables



Indexes



Collections



Backup



Monitoring



\---



\# Mongoose Rules



Always



Create separate models



Use timestamps



Use validation



Use enums



Use references



Avoid duplicate schemas



\---



\# PostgreSQL Rules



Always



Normalize data



Create foreign keys



Use constraints



Create indexes



Avoid duplicate data



\---



\# Production Rules



Before deployment



Check



Database connection



Indexes



Validation



Duplicate records



Slow queries



Backup



Migration



\---



\# Business Templates



Doctor Website



Collections



Users



Appointments



Reports



Reviews



Payments



Hospital



Collections



Doctors



Patients



Appointments



Departments



Bills



Reports



CRM



Collections



Users



Leads



Customers



Tasks



Notes



PG



Collections



Students



Rooms



Payments



Complaints



Laundry



Donation



Collections



Donors



Donations



Receipts



Campaigns



\---



\# Claude Decision Rules



If project type is unknown



↓



Ask



Business type?



↓



Then choose database



↓



Then design schema



↓



Then create models



↓



Then create indexes



↓



Then prepare deployment



\---



\# Mobile \& Performance Rules



Database should support



Fast mobile loading



Small API responses



Pagination



Lazy loading



Optimized search



Caching when required



\---



\# Final Output



Always provide



Recommended database



Collections



Relationships



Indexes



Validation



Schema plan



Optimization plan



Backup strategy



Deployment notes



Testing checklist



\---



\# Related Skills



\- anjali-project-planner

\- anjali-business-analyst

\- anjali-system-architect

\- anjali-full-stack-developer

\- anjali-github-manager

\- anjali-build-to-deploy-workflow

