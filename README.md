# LinguaStream-AI
AI-powered video translation platform built with Next.js and Node.js using 100% free and open-source models.

LinguaStream AI 🌍🎬

LinguaStream AI is a full-stack AI-powered video translation platform that converts videos from any language into any target language using fully open-source models.

Built with Next.js, Node.js, and local AI models — no paid APIs required.

🚀 Features

🎥 Upload video (MP4, MOV, AVI)

🎙 Extract audio using FFmpeg

🌐 Automatic language detection

📝 Speech-to-text transcription

🔄 Translate transcript to selected language

🔊 Generate AI voice in target language

🎬 Merge translated voice back into video

📄 Generate subtitles (.srt)

⬇ Download translated video

🛠 Tech Stack
Frontend

Next.js (App Router)

TypeScript

TailwindCSS

Backend

Node.js

Next.js API Routes

Multer (file uploads)

FFmpeg

AI Models (100% Free)

Whisper – Speech-to-text

NLLB – Translation

Piper – Text-to-speech

Database

SQLite (MVP)

🏗 Architecture

User Upload
→ Extract Audio (FFmpeg)
→ Transcribe (Whisper)
→ Translate (NLLB)
→ Generate Voice (Piper)
→ Merge Audio + Video
→ Output Download
