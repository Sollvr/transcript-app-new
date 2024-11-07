# Video Transcription & Clip Creation Platform

A modern, subscription-based web application that enables users to upload videos, generate accurate transcriptions, create clips with subtitles, and translate content. The platform emphasizes speed, user experience, and professional-grade output.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
- [Subscription Plans](#subscription-plans)
- [Development Roadmap](#development-roadmap)
- [Security](#security)
- [Future Plans](#future-plans)

## 🎯 Overview

### Target Audience
- Content Creators
- Educators
- Digital Marketers
- Professional Video Editors
- Podcast Producers

## ✨ Features

### Video Management
- Upload support for MP4 and MOV files (up to 5 hours)
- YouTube video import with copyright verification
- Video processing status tracking
- 5-day storage limit for all processed content

### Transcription & Translation
- Fast transcription using Groq Whisper API
- Multi-language translation support via OpenAI API
- Editable transcripts with automatic timestamp adjustment
- Export options for SRT/VTT formats

### Clip Creation & Export
- Intuitive clip selection interface with waveform visualization
- Subtitle embedding options
- Preview mode for clips with subtitles
- Multiple clips per video supported

### Search & Navigation
- Keyword-based search in transcripts
- Advanced filtering by timestamp ranges
- Speaker diarization support
- Multiple occurrence highlighting
- Direct video navigation from search results

## 🛠 Tech Stack

### Frontend
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- ShadcN UI
- React Query
- Zustand

### Backend
- Next.js API Routes
- Supabase
  - Auth
  - PostgreSQL Database
  - Storage
  - Edge Functions

### External Services
- Groq Whisper API
- OpenAI API
- Stripe & PayPal
- Resend.com
- Vercel Services

## 🏗 Architecture

### Database Schema