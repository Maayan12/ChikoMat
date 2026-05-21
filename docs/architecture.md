# Chikomat Architecture

## Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- Mobile-first responsive UI

### Backend
- Spring Boot
- Java
- REST API
- PostgreSQL

### Database
- PostgreSQL

### Initial Entities

#### Plot
- id
- name
- targetCubicMeters
- active
- createdAt
- updatedAt

#### User
- id
- name
- active
- createdAt
- updatedAt

#### IrrigationSession
- id
- plotId
- userId
- status
- startTime
- endTime
- startMeterReading
- finalMeterReading
- targetCubicMeters
- actualCubicMeters
- averageFlowRate
- notes

#### MeterReading
- id
- irrigationSessionId
- readingValue
- readingTime
- readingType
