# Career Decision Simulator (AI + Market Data)

Production-ready hackathon full-stack platform for immersive, AI-guided career simulation.

## Stack

- Frontend: React + Tailwind CSS + Framer Motion + React Three Fiber + Recharts
- Backend: Node.js + Express
- Database: MongoDB (auto-fallback to in-memory when `MONGODB_URI` is absent)
- AI: OpenAI API (auto-fallback mentor logic when `OPENAI_API_KEY` is absent)

## Quick Start

1. Install dependencies:
   - `npm install`
   - `npm install --prefix backend`
   - `npm install --prefix frontend`
2. Configure environment:
   - Copy `backend/.env.example` to `backend/.env`
   - Copy `frontend/.env.example` to `frontend/.env`
3. Run both apps:
   - `npm run dev`
4. Open:
   - Frontend: `http://localhost:5173`
   - Backend: `http://localhost:4000`

## Core Features Implemented

- Cinematic hero with 3D rotating career globe and interactive career spheres
- Multi-step career input wizard with validation and animated progress
- AI recommendation dashboard with tilt cards, favorites, detail modal
- Career Time Machine with slider, animated forecasting charts, timeline tunnel
- Side-by-side career comparison with radar visualization
- Floating AI mentor chatbot with typing state and quick prompts
- Personality match engine with visual career fit suggestions
- Roadmap generator timeline for selected career
- Future risk meter with safety/evolving/high-risk buckets
- Global market trends charts and analytics
- Testimonials, future scope cards, emotional final CTA
- Dark/light mode, sound toggle, sticky nav, particle background, mouse-follow glow
- Save report API integration, PDF download, and share flow

## API Endpoints

- `GET /api/health`
- `POST /api/profile`
- `POST /api/recommendations`
- `POST /api/salary-prediction`
- `POST /api/automation-risk`
- `POST /api/compare`
- `POST /api/chat`
- `GET /api/roadmap/:careerId`
- `GET /api/careers`
- `GET /api/market-trends`
- `GET /api/risk-buckets`
- `POST /api/reports`
- `GET /api/reports/:id`
