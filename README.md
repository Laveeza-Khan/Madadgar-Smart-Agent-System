# (Madadgar) — Smart Autonomous Agent Ecosystem

 (Madadgar) is an AI-powered, autonomous multi-agent orchestration platform built for the AI Seekho Hackathon 2026. The platform is designed to streamline on-demand home services in Pakistan by solving localization, discovery, and reliability issues using advanced agentic workflows.

## 🚀 Live Demo & Repository
- **Live Web App Link:** [https://vitejsvite2mun9pdu-3jo1--5173--4c73681d.local-credentialless.webcontainer.io/]Running on StackBlitz Local Development. Please inspect the source code files and view the Demo Video for full application functionality.
- **GitHub Repository:** https://github.com/Laveeza-Khan/Madadgar-Smart-Agent-System

## 🌌 Core Core Architecture & Agentic Workflow
The system completely replaces traditional static APIs with a dynamic backend driven by 7 autonomous specialized micro-agents:

1. **Intent Parser Agent:** Evaluates multilingual user inputs (English, Urdu script, and Roman Urdu), auto-correcting typos and extracting service requests.
2. **Discovery Match Agent:** Scans, filters, and locates nearby validated service providers based on geolocation metrics.
3. **Algorithmic Ranking Agent:** Scores and pairs providers dynamically using an intense 8-factor weighted matrix (evaluating distance, response time, rating recency, baseline cost, historical completion rate, cancellation history, slot gaps, and loyalty retention).
4. **Dynamic Pricing Agent:** Adapts invoicing structures instantly using dynamic multipliers based on urgency and distance surcharges.
5. **Conflict Booking Agent:** Monitors schedule blocks to systematically eliminate double-bookings.
6. **Notification Gateway Agent:** Drives automated multi-channel client and provider communications.
7. **Automated Follow-up Agent:** Executes post-service loops, tracking ratings, customer satisfaction metrics, and loyalty accrual.

## 🛡️ Self-Healing & Failure Recovery
Engineered for real-world scenarios, the platform has robust self-healing mechanisms:
- **Provider Cancellation:** If a provider cancels a booking, the system autonomously triggers the *Discovery Match* and *Ranking* agents to re-assign the best matching provider instantly without crashing the user session.
- **Trace Logs:** All underlying agent decision chains, communication states, and confidence metrics are exposed to the user via a live **Antigravity Agent Trace Log** interface.

## 🛠️ Tech Stack
- **Frontend Framework:** React.js (Tailwind CSS for responsive layout)
- **NLP Interface:** Multilingual Roman Urdu Smart Simulator
- **State Tracking:** Live Autonomous Telemetry Logs
- **Development Tool:** Antigravity Platform (Vibe Coding)

## 👥 Team Members
- **Laveeza Khan** (Team Lead)
- **Mahnoor Urooj**
