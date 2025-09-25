# TeacherVault

AI-powered administrative assistant that saves teachers 10-15 hours per week by automating repetitive tasks.

## Quick Start

### Prerequisites
- Node.js (v16+)
- Redis (optional, but recommended)

### Installation

1. Clone the repository

git clone https://github.com/tjohnson012/teachervault.git
cd teachervault

Install dependencies

npm install

Start Redis (optional)

redis-server

Run the application

npm start
Or for development with auto-reload:
npm run dev

Open your browser

http://localhost:3001

Demo
Click the + button in the bottom right to simulate an incoming parent email and watch the system process it in real-time.
Features

Real-time email processing pipeline
Automated attendance updates
Draft response generation
WebSocket live updates
Time tracking & analytics
Life impact metrics

Tech Stack

Backend: Node.js, Express, WebSocket
Frontend: HTML5, CSS3, JavaScript, Chart.js
Database: Redis (for state management)
Architecture: Real-time pipeline processing
