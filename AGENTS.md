## Project Summary
HNA — HireNextAI is an AI-powered mock interview and learning platform designed to run 100% offline. It features a cinematic logo intro, a NeetCode-style learning roadmap, and a full mock interview pipeline (Aptitude, Technical, Coding, Project Discussion, HR) using local AI (Ollama) and computer vision (OpenCV).

## Tech Stack
- **Frontend**: Next.js (React), Tailwind CSS, Framer Motion, Monaco Editor
- **Backend**: Node.js (Next.js API Routes)
- **Database**: MongoDB (Local)
- **Local AI**: Ollama (Llama3/Mistral), Vosk (STT), OpenCV (Facial Expression Analysis)

## Architecture
- `src/components/intro`: Cinematic logo intro and scroll tracking.
- `src/components/interview`: Interview pipeline components.
- `src/app/api/ai`: Proxy routes for Ollama integration.
- `assets/`: Local storage for videos, materials, and company logos.

## User Preferences
- **Theme**: Dark theme (#111111 background) with blue/purple gradient highlights.
- **Privacy**: 100% offline, no external APIs or CDNs.
- **Typography**: Large bold typography, modern SaaS layout.

## Project Guidelines
- Use Framer Motion for all animations.
- Ensure all assets are loaded locally from the `public/assets` directory.
- Avoid using `localhost` in client-side API calls; use relative URLs.
- Maintain a glassy, light grey card aesthetic (non-transparent).

## Common Patterns
- Scroll-linked animations for logo transitions.
- Local LLM interaction via API proxy.
- Step-based interview flow management.
