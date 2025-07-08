# Sahayak – AI Assistant for Multi-Grade Classrooms 🧠📚

Sahayak is an AI-powered classroom assistant designed for multi-grade, low-resource schools. It leverages Google’s Gemini, Vertex AI, and Firebase to help teachers generate content, answer student questions, and plan weekly lessons — all in local languages and formats.

## 🔥 Key Features
- 📖 Generate hyperlocal stories & learning content
- 🧮 Multilevel worksheet creator from textbook images
- 🎤 Speech Q&A: vernacular voice input → simple answer output
- 📊 Visual aid generator (charts, drawings)
- 🗓️ AI-powered weekly lesson planner

## ⚙️ Tech Stack
- **Frontend**: React.js + Firebase Hosting + Auth
- **Backend**: Node.js (or Python) + Firebase Functions
- **AI Services**: Vertex AI Agent Builder, Gemini Pro, Vision OCR, Speech-to-Text, Text-to-Speech
- **Storage**: Firebase Firestore + Firebase Storage

## 👥 Team Roles
| Member | Role | Responsibilities |
|--------|------|------------------|
| 👨‍🎨 Frontend Lead | UI + Integration | Build React UI, integrate APIs, upload/display content |
| 🤖 Backend Agent | Gemini + Functions | Prompt engineering, Vertex API calls, logic flows |
| 📸 Vision/Speech | Multimodal Lead | OCR pipeline, voice Q&A, TTS responses |
| 🗄️ DevOps & Firebase | Infra & Analytics | Auth, Firestore setup, Hosting, usage tracking |

## 🚀 Getting Started

```bash
git clone https://github.com/YOUR-USERNAME/sahayak-ai-agent.git
cd sahayak-ai-agent
npm install    # or yarn install
npm start      # if using CRA or Next.js dev mode
```

## 🔐 Private Access Notes
This is a private hackathon repository. If you're on the team, make sure you've accepted your GitHub invite.

## 📁 Folder Structure
```
/frontend         # React app
/functions        # Firebase Cloud Functions
/agent            # Vertex AI + Gemini logic
/docs             # PPT, architecture, planning
```
