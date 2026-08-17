# FleetTrack V6 — Render Edition

Online fleet tracking system for Render.

Features:
- Multiple trucks
- Multiple driver accounts
- Driver-to-truck assignment
- Admin dashboard
- GPS tracking
- Odometer
- Trip Tickets
- Arrival/departure records
- Geofence workflow
- PostgreSQL
- CSV export
- Browser access from laptop and mobile

## Deploy with Render Blueprint
1. Push this project to GitHub.
2. In Render choose New > Blueprint.
3. Select the repository.
4. Render reads render.yaml and creates the web service and PostgreSQL database.
5. Deploy.

## Manual deployment
Web Service:
- Build Command: npm install
- Start Command: npm start

Environment:
- DATABASE_URL = Render PostgreSQL Internal Database URL

## Production security
The included authentication is a prototype. Before real company use, add password hashing, secure sessions/JWT, role authorization, rate limiting, secure cookies, audit logs, and secure photo storage. Change demo credentials immediately.
