# Chikomat MVP Specification

## Goal
Build a mobile-first irrigation management system for managing olive grove watering sessions.

## Users
- Field user: starts and manages irrigation sessions
- Admin: manages plots, users, settings, and history

## MVP Scope

### 1. Plot Management
Admin can:
- Create plot
- Edit plot name
- Set target cubic meters per irrigation
- Activate / deactivate plot

Field user can:
- View active plots
- Select plot for irrigation

### 2. User Management
- Add family members / operators
- Select current user on first visit
- Store selected user locally in browser

### 3. Irrigation Session
Field user can:
- Select plot
- Enter opening meter reading
- Enter second reading
- See calculated flow rate
- See estimated finish time
- Add intermediate readings
- Close session with final meter reading

### 4. History
Admin can view:
- Date
- Plot
- User
- Start/end readings
- Total cubic meters
- Flow rate
- Status
- Notes

### 5. Basic Weather
- Show current weather
- Show 5-day forecast
- Future: rainfall-based recommendation

## Out of Scope for MVP
- Push notifications
- Full offline sync
- AI recommendations
- Advanced permissions
- Payment/subscription
- Native mobile app
- Machine learning anomaly detection