# Sarabloh Community Operations

Integrated operations management platform for community safety organizations.

## Overview
Comprehensive system for incident management, evidence logging, team communications, and operational coordination. Designed for organizations prioritizing community safety and operational transparency.

## Features
- Incident tracking and reporting
- Evidence management and chain-of-custody logging
- Real-time team communications
- Operational dashboards and analytics
- Role-based access control
- Data audit trails

## Tech Stack
**Frontend:** React, TypeScript, Tailwind CSS
**Backend:** Node.js, Express, PostgreSQL with Drizzle ORM
**Infrastructure:** Docker containerization, Canadian cloud hosting
**Data Sovereignty:** OCAP® principles compliant, on-premise deployment option available

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL 14+

### Installation
```bash
git clone https://github.com/Sarabloh/sarabloh-community-operations.git
cd sarabloh-community-operations
npm install
cd backend && npm install && cd ../frontend && npm install
cp .env.example .env
```

### Running Locally
```bash
# Terminal 1: Backend
cd backend && npm run dev

# Terminal 2: Frontend
cd frontend && npm run dev
```

## Database
```bash
npm run migrate
npm run seed
```

## Documentation
- [API Reference](./docs/API.md)
- [Deployment Guide](./docs/DEPLOYMENT.md)
- [Architecture](./docs/ARCHITECTURE.md)
- [Security & Privacy](./docs/SECURITY.md)

## License
MIT - See [LICENSE](./LICENSE)

---

**Sarabloh Technologies Ltd.**  
Canada
