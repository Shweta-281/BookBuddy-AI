## 📚 BookBuddy AI
BookBuddy AI is a voice-first AI book companion platform that allows users to interact with books through natural voice conversations.
It combines modern web technologies and AI voice services to provide an interactive learning and reading experience.

Users can explore book summaries, ask questions, and receive explanations through real-time AI voice conversations.

## 🚀 Features

### 📄 PDF Upload & Intelligent Ingestion

Seamlessly upload PDF books with automated text extraction, intelligent chunking, and high-dimensional embeddings to enable accurate semantic search and context-aware AI responses.

### 🎙 Voice-First Conversations

Interact with your books through natural, real-time voice conversations. Ask questions, explore ideas, or discuss concepts verbally using AI-powered voice interactions via Vapi.

### 🎭 AI Voice Personas

Choose from multiple AI voice personalities and preview them instantly. High-fidelity voice synthesis powered by ElevenLabs creates a personalized and immersive reading companion.

### 🧠 Smart Summaries & Insights

Generate concise chapter summaries or request deeper explanations of complex topics, helping transform long-form content into digestible insights.

### 📝 Session Transcripts

Every voice interaction is automatically converted into text transcripts, allowing users to review conversations, capture insights, and revisit important discussions.

### 📚 Library Management

Organize and search through your uploaded books or explore a shared global collection with a fast and intuitive search interface.

### 3 🔐 Authentication & Subscriptions

Secure user authentication with email and social login, combined with a flexible subscription system to manage premium features and platform access.

## 🛠 Tech Stack
### Frontend
- Next.js 16
- Tailwind CSS
- shadcn/ui
### AI & Voice
- Vapi – Real-time voice interaction
- ElevenLabs – AI voice synthesis
### Authentication
- Clerk

## ⚙️ Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Shweta-281/bookbuddy-ai.git
```
### 2️⃣ Navigate to Project
```bash
cd bookbuddy-ai
```
### 3️⃣ Install Dependencies
```bash
npm install
```
### 4️⃣ Setup Environment Variables

Create a ```.env``` file.
```
NODE_ENV='development'
NEXT_PUBLIC_BASE_URL=

# CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# VERCEL BLOB
BLOB_READ_WRITE_TOKEN=

# MONGODB
MONGODB_URI=

# VAPI
NEXT_PUBLIC_VAPI_API_KEY=
VAPI_SERVER_SECRET=

# Google Gemini API for embeddings
GOOGLE_GEMINI_API_KEY=

# ELEVENLABS
ELEVENLABS_API_KEY=
```

### ▶️ Run the Project
```bash
npm run dev
```
Open in browser:
```
http://localhost:3000
```

### 🧠 How It Works

1. User logs in using Clerk authentication.

2. User starts a voice conversation.

3. Voice input is processed through Vapi.

4. AI generates responses.

5. ElevenLabs converts responses into natural speech.

## 🌟 Future Improvements

- 📖 PDF book upload

- 🧠 RAG-based book understanding

- 📊 Reading analytics

- 💬 Conversation memory

- 📚 Personalized book recommendations


## 👨‍💻 Author
Developed by Shweta 
