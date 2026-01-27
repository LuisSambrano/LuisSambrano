# 📺 M&TVenezuela Core System

> **Role**: System Architect & Lead Developer
> **Status**: 🔒 Private Repository (Client Work)
> **Stack**: React, Supabase, Edge Functions, AI Agents

## The Challenge

M&TVenezuela needed to transition from a static media site to a dynamic, intelligence-driven news portal. The goal was to automate content ingestion, deduplication, and publishing while providing a high-performance, "Netflix-like" user experience for media consumption.

## The Solution

I architected a **"Neural Newsroom"**: a system where AI agents actively monitor, filter, and summarize news before it hits the editorial dashboard.

### Key Architecture Highlights

- **⚡ Supabase Backend**: Utilized Row Level Security (RLS) for multi-role access (Admin, Editor, Journalist).
- **🤖 AI Ingestion Pipeline**:
  - **Deduplication Engine**: Uses vector embeddings to identify and merge similar stories from different sources.
  - **Sentiment Analysis**: Auto-tags articles with sentiment scores to balance the news feed.
- **🎨 Glassmorphism 2.0 UI**: A custom-built design system using Tailwind CSS and Framer Motion, delivering a premium, app-like feel on the web.
- **🛡️ Role-Based Access Control (RBAC)**: Granular permission system ensuring strict editorial workflows.

## Tech Stack

- **Frontend**: React 18, TypeScript, Vite.
- **Styling**: Tailwind CSS, Framer Motion (Spring Physics).
- **Backend**: Supabase (PostgreSQL), Edge Functions (Deno).
- **AI**: OpenAI API (Text Processing), Vector Store (Semantic Search).

---

_This project is a private commercial engagement. Code samples available upon request._
