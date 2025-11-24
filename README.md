# MindWhisper

MindWhisper is an AI-powered mental wellness platform built with React, TypeScript, Tailwind CSS, and Lovable Cloud (Supabase) that helps people track their mental health, build positive habits, set wellness goals, and receive personalized AI coaching.

## Core Features

### AI Wellness Coach & Chat System
- Intelligent conversational AI powered by Lovable AI (Google Gemini models)
- Persistent chat history with session management
- Proactive wellness check-ins that flag at-risk users based on stress patterns
- Personalized recommendations using Retrieval-Augmented Generation (RAG)
- Automated weekly wellness summaries delivered every Monday
- Message feedback (thumbs up/down) to personalize future recommendations
- Privacy-first design that only analyzes wellness scores, never conversation content

### Daily Check-ins
- Wellness tracking for stress, happiness, and energy levels (1-10 scale)
- Journaling with daily summaries, key moments, and bright spots
- Photo attachments for visual journaling
- Voice recording for audio journaling
- AI-generated gratitude prompts for reflection
- Streak tracking with milestone rewards for consecutive days

### Gamification & Achievements
- XP system:
  - Complete check-in: 10 XP
  - Create goal: 5 XP
  - Complete goal: 25 XP
  - Create habit: 5 XP
  - Complete habit: 3 XP
- Level progression with exponential XP requirements
- Badge system with 11 default badges (First Steps, Week Warrior, Unstoppable, etc.)
- Milestone rewards covering 3-day to 365-day streaks
- Automatic award system via `check-achievements` edge function
- Achievements page with earned and locked badge tabs

### Smart Habit Tracker
- Habit creation with 10 customizable icons (🎯 💪 📚 🧘 🏃 💧 🥗 😴 🎨 🧠)
- Target days per week settings (1-7 days)
- Streak calculation for consecutive completions
- Weekly progress bars showing completions versus targets
- AI-powered insights linking habits and wellness scores
- Challenge integration for habit-based challenges

### Goals & Progress Tracking
- Goal creation with customizable descriptions
- Progress tracking with visual progress bars
- Goal completion rewards XP
- AI goal suggestions based on wellness patterns
- Incremental goal updates to track progress

### Wellness Challenges
- Community challenges with group participation
- Individual challenges for personal targets
- Challenge progress tracking
- Integration with habits for habit-based challenge tracking

### Sleep Tracking
- Sleep logs capturing duration and quality ratings
- AI-generated sleep insights and observations
- Notes for additional context
- Trend visualizations to analyze patterns

### Wellness Library
- Seventy curated articles across seven categories:
  - Stress (10)
  - Anxiety (10)
  - Sleep (10)
  - Depression (10)
  - Mindfulness (10)
  - Self-Care (10)
  - Relationship (10)
- User interactions: like, save/bookmark, and social sharing (Messenger, WhatsApp, Twitter, Facebook, LinkedIn)
- Publication controls for admins to publish or unpublish articles
- Article view tracking and engagement analytics
- Rich text editor for admin article creation

### Trends & Analytics
- Mood calendar for daily mood visualization
- AI-generated wellness insights
- Pattern analysis to detect stress trends
- Data visualization with charts and graphs

### Export & Sharing
- PDF report generation for printable wellness summaries
- CSV data export for check-ins, goals, and insights
- Date range selection for custom exports
- Social sharing for achievements with privacy protections
- Foundation for professional B2B reports

### Wellness Tools
- Guided breathing exercises
- Grounding exercises for mindfulness
- Meditation timer with customizable sessions

### Safety Features
- Crisis resources with emergency mental health contacts
- Personalized safety plans
- Quick access to safety plans during emergencies
