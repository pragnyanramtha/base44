
# MindTrack

## Problem & Impact

| Problem | Impact |
| :--- | :--- |
| **Scattered study materials & no structure** | Students waste 30% of study time just organizing |
| **Constant distractions & lack of focus** | Average attention span is now \< 8 seconds |
| **Studying alone feels isolating** | 67% of students report feeling lonely while studying |

## Our Solution

**MindTrack** is an AI-powered study companion that combines:

  * 🤖 **Personalized AI tutoring** with real-time explanations
  * 📅 **Smart task scheduling** with AI-detected priorities
  * ⏱️ **Gamified focus sessions** with XP rewards & streaks
  * 👥 **Study circles** for collaborative learning

-----

## 2\. Target Audience & Core Features

### 🎯 Target Audience

  * **Primary:** College students (18-25) preparing for competitive exams
  * **Secondary:** High school students, self-learners, working professionals upskilling
  * **Pain Points:** Disorganized workflows, procrastination, lack of accountability

### ⭐ Core Features

| Feature | Description | Benefit |
| :--- | :--- | :--- |
| **AI Tutor (Home)** | Chat with AI, share screen for problem-solving, voice input | Instant explanations, 24/7 availability |
| **Smart Planner (Plan)** | AI-powered task scheduling, knowledge graph mapping | Never miss deadlines, visual learning |
| **Focus Timer (Focus)** | Pomodoro sessions with XP, streaks, ambient music | Build consistency, stay motivated |
| **Wellness Check (Wellness)** | Mental health assessments with AI insights | Prevent burnout, stay balanced |
| **Learning Labs (Labs)** | Resume analyzer, gamified CSS/JS learning (Flexbox Froggy, Grid Garden) | Career prep, interactive skill building |
| **Study Circles (Circle)** | Join topic-based rooms, leaderboards, challenges | Accountability, peer learning |
| **Profile & Progress** | Skill pentagon, weekly charts, achievements | Track growth, celebrate wins |

### 🚀 Most Impressive Features

  * **Screen Sharing + AI Analysis** - Share your screen, AI sees your problem and helps solve it.
  * **AI-Generated Study Roadmaps** - Say "I have an exam in 15 days" and get a day-by-day plan.
  * **Embedded Learning Games** - Flexbox Froggy, CSS Grid Garden, SQL Murder Mystery directly in-app.
  * **Resume ATS Analyzer** - Upload PDF, get AI-scored ATS compatibility with actionable tips.
  * **Binaural/Lofi Study Music** - Built-in focus music player with multiple tracks.

-----

## 3\. Base44 Landing Page

### ✅ Landing Page Checklist

  * ✅ Mobile-optimized responsive design
  * ✅ Clear value proposition in hero section
  * ✅ Problem/Solution section with 3 key pain points
  * ✅ Features grid with 6 core features
  * ✅ Social proof (stats section)
  * ✅ CTA buttons redirect to login/signup
  * ✅ Footer with Privacy Policy, Terms, Feedback links

### Key Copy Elements

  * **Headline:** "Stop Struggling. Start Learning Smarter."
  * **Sub-headline:** "MindTrack combines AI tutoring, smart planning, and gamified focus sessions to help students achieve more in less time."
  * **CTA:** "Get Started Free"

-----

## 4\. Idea Validation

### ✅ Validation Method: Feedback Form

  * **Link:** [https://forms.gle/FQmXF8V8QXTv8FwN9](https://forms.gle/FQmXF8V8QXTv8FwN9)

**Implementation:**

  * Welcome popup for new users prompting feedback
  * Feedback link in Profile page footer
  * Feedback link in Landing page navigation & CTA section
  * "Share Feedback" button on landing page

**Learn More:** [https://github.com/pragnyanramtha/base44](https://github.com/pragnyanramtha/base44)

-----

## 📖 Project Story

### 💡 What Inspired Us

As students ourselves, we experienced the frustration of:

  * Jumping between 10+ apps for studying (timers, planners, notes, music)
  * Feeling lost without a structured study plan
  * Losing motivation when studying alone

We asked: **What if there was ONE app that does it all?**

The pandemic showed us that digital learning is here to stay, but most EdTech focuses on content delivery, not *how* students actually study. MindTrack focuses on the meta-skill of learning itself.

### 🧠 What We Learned

  * **AI + Education is powerful** - LLMs can create personalized roadmaps, explain concepts, and even analyze screenshots.
  * **Gamification works** - XP, streaks, and leaderboards increase engagement by 40%+.
  * **Community matters** - Study circles and accountability partners reduce dropout rates.
  * **Simplicity wins** - Users prefer one integrated app over 10 specialized tools.

### 🔨 How We Built It

```text
┌─────────────────────────────────────────────────────┐
│                   MindTrack Architecture            │
├─────────────────────────────────────────────────────┤
│  Frontend: React + TailwindCSS + Framer Motion      │
│  UI Components: shadcn/ui + Recharts                │
│  Backend: Base44 BaaS (Entities, Auth, Integrations)│
│  AI: Base44 InvokeLLM (GPT-powered)                 │
│  Data: Base44 Entity SDK (Task, FocusSession, etc)  │
└─────────────────────────────────────────────────────┘
```

**Key Technical Decisions:**

  * Used `@tanstack/react-query` for efficient data fetching & caching.
  * Framer Motion for smooth animations.
  * Recharts for interactive data visualization.
  * Embedded iframes for learning games (Flexbox Froggy, etc.).

### ⚡ Challenges We Faced

| Challenge | Solution |
| :--- | :--- |
| **Screen sharing + AI analysis** | Used `navigator.mediaDevices.getDisplayMedia()` → capture frame → upload → send to LLM |
| **Collapsible sidebar with animations** | Built custom animated sidebar component with Framer Motion |
| **Music player with multiple tracks** | Created global audio ref with play/pause/volume controls |
| **Welcome popup timing** | Used `localStorage` to track first-time users |

-----

## 🛠️ Technologies Used

| Category | Technologies |
| :--- | :--- |
| **Frontend Framework** | React 18 |
| **Styling** | Tailwind CSS, shadcn/ui |
| **Animations** | Framer Motion |
| **Charts** | Recharts |
| **Routing** | React Router DOM |
| **State Management** | React Query (`@tanstack/react-query`) |
| **Backend** | Base44 BaaS |
| **AI/LLM** | Base44 InvokeLLM Integration |
| **Authentication** | Base44 Auth |
| **Database** | Base44 Entities |
| **File Storage** | Base44 UploadFile |
| **Icons** | Lucide React |
| **Date Handling** | date-fns |
| **Markdown** | react-markdown |
| **External Games** | Flexbox Froggy, CSS Grid Garden, CSS Diner, CodinGame, etc. |

-----

## 📊 Impact Potential

  * **Productivity:** 2-3x improvement in focused study time.
  * **Retention:** Gamification increases daily active usage by 40%.
  * **Mental Health:** Wellness checks prevent burnout.
  * **Career:** Resume analyzer helps students land jobs.
  * **Community:** Study circles reduce isolation.

> **Built with ❤️ for students everywhere.**
