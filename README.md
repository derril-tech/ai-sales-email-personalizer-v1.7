# AI Sales Email Personalizer

> **Transform your sales outreach with AI-powered email personalization**

A production-ready, full-stack application that leverages CrewAI agents to generate highly personalized B2B sales emails. Built with Next.js 15, FastAPI, Supabase, and OpenAI.

**🌐 Live Application:** [https://sales-email-personalizer-api.vercel.app/](https://sales-email-personalizer-api.vercel.app/)

---

## 🎯 Overview

The AI Sales Email Personalizer is an intelligent email generation platform that uses a multi-agent AI system to:

1. **Research prospects** using Apollo and HubSpot integrations
2. **Personalize emails** based on lead context and pain points
3. **Quality assurance** to ensure emails meet professional standards
4. **Export and refine** with OpenAI chat integration

### Key Features

- 🤖 **Multi-Agent AI System** - Prospector, Personalizer, and QA agents work together
- 📧 **Email Generation** - Generate personalized sales emails in seconds
- 💬 **AI Chat Integration** - Refine emails with OpenAI-powered chat
- 📚 **Template Library** - Save and reuse email templates
- 📊 **Multi-Project Support** - Organize emails by project/client
- 📈 **Real-Time Updates** - Server-Sent Events for live job status
- 🎨 **Modern UI/UX** - Beautiful, responsive design with light/dark themes
- 💾 **Data Persistence** - Supabase PostgreSQL for reliable data storage
- ⚡ **Real-Time Stats** - Live dashboard showing Supabase connection status

---

## 🏗️ Architecture

### Tech Stack

**Frontend:**
- Next.js 15 (React 19, App Router)
- TypeScript
- Tailwind CSS + shadcn/ui
- Server-Sent Events (SSE) for real-time updates

**Backend:**
- FastAPI (Python 3.11+)
- CrewAI for multi-agent orchestration
- OpenAI API (gpt-4.1-mini) for chat and refinement
- Pydantic for data validation

**Database & Cache:**
- Supabase (PostgreSQL) for data persistence
- Upstash Redis for job queues and rate limiting

**External Integrations:**
- Apollo API for lead enrichment
- HubSpot API for CRM data
- OpenAI API for chat and email refinement

---

## 🎨 Features

### 1. Multi-Agent Email Generation

Three specialized AI agents work together:

- **Prospector Agent** - Researches leads using Apollo/HubSpot
- **Personalizer Agent** - Crafts personalized email content
- **QA Agent** - Ensures quality, compliance, and clarity

### 2. AI Chat Integration

Refine generated emails with OpenAI-powered chat:

- Ask for tone adjustments ("Make it more casual")
- Request modifications ("Add urgency")
- Get writing advice ("What makes a good subject line?")

### 3. Template Library

Save and reuse email templates:

- Save generated emails as templates
- Load templates to pre-fill forms
- Organize templates by project

### 4. Multi-Project Support

Organize your work by project:

- Create multiple projects
- Switch between projects
- Isolated data per project

### 5. Real-Time Updates

Server-Sent Events (SSE) for live updates:

- Real-time job status
- Instant message notifications
- No polling overhead

### 6. Modern UI/UX

Beautiful, responsive design:

- Light/dark theme support
- Mobile-optimized interface
- Smooth animations and micro-interactions
- Accessible components

### 7. Data Dashboard

Live Supabase statistics:

- Connection status
- Message count
- Template count
- Project count
- Last message timestamp

---




---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## 🙏 Acknowledgments

- [CrewAI](https://github.com/joaomdmoura/crewAI) - Multi-agent framework
- [Next.js](https://nextjs.org/) - React framework
- [FastAPI](https://fastapi.tiangolo.com/) - Python web framework
- [Supabase](https://supabase.com/) - Backend as a service
- [shadcn/ui](https://ui.shadcn.com/) - UI component library
- [OpenAI](https://openai.com/) - AI models and API


---

## 🗺️ Roadmap


### Completed Features ✅

- ✅ Copy to Clipboard with Toast Notification
- ✅ Email Export (HTML/Plain Text)
- ✅ Theme Persistence
- ✅ Smooth Animations & Micro-interactions
- ✅ Real-Time Updates with SSE
- ✅ OpenAI Chat Integration
- ✅ Email Templates Library
- ✅ Multi-Project Support
- ✅ Supabase Data Dashboard

### Upcoming Features 🚀

- 🔜 Advanced analytics and reporting
- 🔜 Email scheduling
- 🔜 A/B testing for email variations
- 🔜 Integration with more CRM platforms

---

**Built with ❤️ by Derril Filemon**
