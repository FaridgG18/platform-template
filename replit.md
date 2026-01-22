# Angular Web Application

## Overview
This is an Angular 20 web application with SSR (Server-Side Rendering) capabilities. The project was imported from GitHub.

## Project Structure
- `web-app/` - Angular 20 frontend application with SSR
- `backend/` - Hono API backend (Cloudflare Workers - not active in Replit environment)

## Current State
The Angular frontend is running and accessible on port 5000. The backend uses Cloudflare Workers which requires separate deployment.

## Running the Application
The Angular dev server is configured to run via the "Angular Frontend" workflow:
```
cd web-app && npm start
```

## Configuration
- Port: 5000
- Host: 0.0.0.0
- Allowed hosts: `.replit.dev`, `.picard.replit.dev` (for Replit proxy)

## Project Architecture
- Frontend framework: Angular 20
- Styling: SCSS
- SSR: Enabled via @angular/ssr

## Recent Changes
- 2026-01-22: Initial setup for Replit environment
  - Configured Angular dev server for port 5000
  - Added allowedHosts configuration for Replit proxy
  - Disabled Angular CLI analytics
  - Created .gitignore file
