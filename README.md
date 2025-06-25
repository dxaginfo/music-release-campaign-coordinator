# Music Release Campaign Manager

A web application to plan, schedule, and track music release campaigns. Coordinate teams, assets, tasks, and analytics for efficient campaign execution.

## Features
- Campaign planning & calendar
- Task assignment, reminders, notifications
- Asset repository (artwork, audio, press kits)
- Team/user management with roles
- Integrated distribution & marketing tools
- Real-time analytics dashboard

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/dxaginfo/music-release-campaign-coordinator.git
   ```
2. Install dependencies:
   ```
   cd music-release-campaign-coordinator
   npm install
   ```
3. Set up a `.env` file with database and S3 credentials.
4. Initialize the database:
   ```
   npx prisma migrate dev
   ```
5. Start development server:
   ```
   npm run dev
   ```

## Deployment
- Configure environment for AWS/Vercel.
- Set up GitHub Actions for CI/CD.

## Security Notes
- Uses JWT/OAuth2
- Secure HTTPS required

## Architecture
See Google Docs project plan: https://docs.google.com/document/d/1N4WfoWRlf5VcxhcDZT6-fLM4aIx71-vU_3FlcH11R8A/edit

---

## License
MIT
