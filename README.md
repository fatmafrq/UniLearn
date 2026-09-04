# UniLearn — AI-Based Smart Learning System for Inclusive Education

🔗 **Live Demo:** https://unilearn-six.vercel.app/

UniLearn is an inclusive learning platform built for **Build.it.ON Hackathon**, addressing the problem statement on AI-driven accessible education for students with visual, hearing, speech, or learning disabilities. Out of 50 teams, we placed in the **Top 11**.

## Problem Statement

Students with disabilities often struggle with standard education platforms that don't adapt to their pace, needs, or the specific way they learn — while creating accessible content in multiple formats remains time-consuming for educators.

## What We Built

UniLearn adapts the entire learning experience based on the student's accessibility needs, with dedicated workspaces for:

- **Blind Mode** – cursor-aware text-to-speech, audio-first navigation, large focus outlines
- **Dyslexia Mode** – adjusted typography and spacing, simplified written explanations
- **Hearing Disability Mode** – persistent captions, visual alerts, text-based tutoring
- **Speech Disability Mode** – text and voice-input based communication support

### Key Features

- **Uni — Voice Assistant**: Responds to student queries using speech recognition and speech synthesis, adapting its tone and explanation style based on the active accessibility mode.
- **Interactive Quizzes**: Subject-wise quizzes with instant scoring, pass/fail feedback, and explanations for each answer.
- **Progress Dashboard**: Tracks study hours, quiz scores, streaks, badges, and subject-wise performance trends over time.
- **Daily Challenges**: Bite-sized daily questions to keep students engaged and reward consistency.
- **Learner Insights**: Highlights strongest subjects, focus areas, and personalized recommendations based on activity.
- **Accessibility Controls**: High-contrast mode, adjustable font scale, and large-text support built into every workspace.
- **Voice Assistant Backend (Experimental)**: A Python + FastAPI module integrating OpenAI's chat, speech-to-text, and text-to-speech APIs for a more advanced conversational tutoring experience, with an offline fallback mode.

## Tech Stack

- **Frontend**: React, TypeScript, Vite
- **Speech**: Web Speech API (recognition + synthesis)
- **Experimental Backend**: Python, FastAPI, OpenAI API

## Team

Built for Build.it.ON Hackathon — placed in the **Top 11 out of 50 teams**.

---

*UniLearn — making learning adapt to the student, not the other way around.*
