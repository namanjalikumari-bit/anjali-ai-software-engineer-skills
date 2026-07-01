\---

name: anjali-backend-deployment-manager

description: Deploy production-ready backend applications using Render and Railway with environment variables, MongoDB Atlas, security, health checks, logging, monitoring, and production best practices.

\---



\# Anjali Backend Deployment Manager



\## Purpose



Act as a Senior Backend Deployment Engineer.



Deploy secure, scalable and production-ready backend applications.



Supported Platforms



Primary



\- Render

\- Railway



Future



\- Fly.io

\- AWS

\- DigitalOcean



\---



\# Main Goal



Every backend deployment must be



\- Secure

\- Fast

\- Stable

\- Production Ready

\- Easy to Maintain



\---



\# Claude Decision Rules



If user says



Deploy Backend



↓



Detect Framework



↓



Node



Express



NestJS



Python



↓



Choose Platform



Render



Railway



↓



Prepare Environment



↓



Deploy



↓



Verify



↓



Health Check



\---



\# Platform Selection



\## Render



Use when



\- Node.js

\- Express

\- MERN

\- APIs

\- Business applications



Advantages



Easy



Stable



Free Tier



GitHub Integration



\---



\## Railway



Use when



\- Full Stack APIs

\- PostgreSQL

\- Internal dashboards

\- Fast deployment



\---



\# Deployment Workflow



Project



↓



Build Backend



↓



Verify Environment Variables



↓



Connect Database



↓



Configure CORS



↓



Deploy



↓



Verify Logs



↓



Health Check



↓



Production Testing



\---



\# Build Rules



Always verify



package.json



start script



build script



dependencies



Node version



PORT



\---



\# Environment Variables



Never hardcode secrets.



Always verify



PORT



MONGO\_URI



JWT\_SECRET



CLIENT\_URL



EMAIL\_USER



EMAIL\_PASS



RAZORPAY\_KEY



CLOUDINARY



API Keys



\---



\# MongoDB Connection



Always verify



Database User



Network Access



Connection String



Indexes



Collections



Health



Connection Status



\---



\# CORS Rules



Always configure



Allowed Origin



Frontend URL



Credentials



Methods



Headers



Never allow unrestricted CORS in production.



\---



\# API Rules



Verify



Authentication



Protected Routes



Validation



Error Handling



Rate Limiting



Response Format



Logging



\---



\# Performance Rules



Always optimize



Database Queries



Indexes



Pagination



Compression



Caching



Minimal Response Payload



Background Jobs



\---



\# Health Check Rules



Always verify



Server Running



Database Connected



API Reachable



Authentication Working



Uploads Working



Payments Working



Email Working



Memory Usage



CPU Usage



\---



\# Logging Rules



Always check



Build Logs



Runtime Logs



Deployment Logs



API Errors



Unhandled Exceptions



Database Errors



\---



\# Security Rules



Always verify



JWT Secret



Environment Variables



Password Hashing



Protected Admin Routes



Input Validation



Helmet



Rate Limiting



CORS



No Secrets in GitHub



\---



\# Production Rules



Before deployment



Verify



Build Success



Environment Variables



Database Connected



Frontend URL



Health Endpoint



README Updated



\---



\# Common Deployment Errors



Check



Server Crash



Missing PORT



MongoDB Connection Failed



JWT Missing



CORS Error



API Timeout



Build Failed



Environment Variable Missing



404



500



\---



\# Backend Testing



Test



GET APIs



POST APIs



PUT APIs



DELETE APIs



Authentication



Authorization



Admin Routes



Uploads



Payments



Email



Database Writes



\---



\# Health Endpoint



Always recommend



GET



/health



Return



{

&#x20; "status":"ok"

}



\---



\# Final Deployment Checklist



Backend Build



Environment Variables



Database



CORS



Authentication



Admin Routes



Health Check



Logs



Performance



Security



README



\---



\# Claude Automatic Verification



Before saying



Deployment Successful



Always verify



Backend Live



Health Endpoint



Database Connected



No Runtime Errors



No Build Errors



API Working



Authentication Working



Frontend Connected



\---



\# Final Output



Always provide



Platform Used



Environment Variables



Deployment Steps



Health Check URL



Testing Checklist



Troubleshooting Tips



Production Checklist



\---



\# Related Skills



\- anjali-full-stack-developer

\- anjali-system-architect

\- anjali-database-manager

\- anjali-github-manager

\- anjali-frontend-deployment-manager

\- anjali-build-to-deploy-workflow

