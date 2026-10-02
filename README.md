# Pro Work AI - Enterprise Workspace Assistant

![Pro Work AI](https://img.shields.io/badge/Status-Live-success) ![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20Tailwind%20%7C%20JS-blue)

**Live Demo:** [View Project on Vercel](https://pro-work-ai-flame.vercel.app/))

## Project Overview
Pro Work AI is a front-end web application designed to act as an intelligent workplace assistant. Built with a classic, enterprise-grade Jira-inspired UI, it consolidates five critical productivity tools into a single, seamless dashboard. This prototype demonstrates how professionals can automate daily administrative tasks using structured AI prompts.

## Core Features
* **Smart Email Generator:** Drafts professional emails based on goal, tone, and assignee/audience.
* **Meeting Notes Extractor:** Converts unstructured meeting transcripts into categorized Jira-style sub-tasks and action items.
* **Sprint Backlog Planner:** Organizes raw to-do lists into a priority-based Kanban board.
* **Confluence Knowledge AI:** Acts as a research assistant to generate executive summaries on technical or business topics.
* **Workspace Service Desk:** An interactive chatbot interface for IT and workspace support.

## UI & UX Highlights
* **Jira-Clone Interface:** Exact Atlassian design system colors, functional sidebars, and system fonts for an authentic enterprise feel.
* **Welcome Burner (Splash Screen):** A dismissible, immersive launch screen that greets the user.
* **Ethical AI Guardrails:** Built-in UI disclaimers permanently visible at the bottom of the workspace, reminding users to verify AI-generated content before execution.

## Technology Stack
* **Frontend UI:** HTML5
* **Styling:** Tailwind CSS (via CDN) tailored with custom Jira hex color codes.
* **Interactivity:** Vanilla JavaScript (ES6) for DOM manipulation, tab switching, and simulating asynchronous API calls.
* **Icons & Avatars:** Font Awesome and UI Avatars API.
* **Deployment:** Vercel

## Prompt Engineering Strategy
While this prototype simulates backend LLM responses to demonstrate UI/UX flow, the underlying logic demonstrates **Structured Prompt Engineering**. It showcases how a production backend (like Google Gemini or OpenAI) would be instructed to respond using System Roles, Task Definitions, and strict Output Formatting constraints (e.g., forcing the AI to output rigid HTML tables instead of conversational fluff).

## How to Run Locally
1. Clone this repository: `git clone https://github.com/karabelokn2-web/pro-work-ai.git`
2. Navigate to the project folder.
3. Open `index.html` in any modern web browser. No build steps or package managers required.

