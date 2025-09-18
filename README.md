# 30-days-learning-path-on-ai-automation
30-Day Daily Learning Path
🔹 Week 1: n8n Foundations

Goal: Be comfortable building workflows with triggers, API calls, and logic.

Day 1:

Install n8n locally with Docker.

Explore UI: nodes, credentials, workflows.

Build a simple workflow: Cron → HTTP request → write to a file.

Day 2:

Learn built-in nodes (Webhook, HTTP Request, Set, Function).

Create workflow: Webhook → transform JSON → respond with custom output.

Day 3:

Add conditional logic (IF, Switch).

Build: Incoming webhook → filter data → send Slack/Discord notification.

Day 4:

Use email nodes (Gmail/SMTP).

Build: Cron → fetch API → send formatted email report.

Day 5:

Explore credentials management (API keys, OAuth).

Build: GitHub trigger → send commit summary to Slack.

Day 6:

Explore error handling & retry strategies in workflows.

Build: API request → retry on failure → log result.

Day 7 (Review Project):

Mini-project: “Automated Daily Weather Reporter”

Cron → Weather API → format → send email/Discord message.

🔹 Week 2: Supabase Basics

Goal: Use Supabase for auth, CRUD, storage, and realtime.

Day 8:

Create a Supabase project.

Explore dashboard, DB tables, SQL editor.

Create users table with fields: id, name, email.

Day 9:

Set up Supabase auth (email/password).

Connect with Nuxt app (basic signup/login).

Day 10:

CRUD with Supabase client in Nuxt: add, fetch, update, delete users.

Day 11:

Supabase storage: upload images, serve via public URLs.

Build: Profile with avatar upload.

Day 12:

Supabase realtime: subscribe to changes in a table.

Build: Simple chat (messages appear instantly without refresh).

Day 13:

Create DB triggers & functions.

Example: New row in orders → set default status = "pending".

Day 14 (Review Project):

Mini-project: “Realtime Notes App”

Users auth → add/edit notes → realtime sync → file attachments.

🔹 Week 3: n8n + AI Automation

Goal: Automate AI tasks with n8n + Supabase integration.

Day 15:

Explore OpenAI node in n8n.

Build: Workflow → input text → AI summary → output.

Day 16:

Combine OpenAI with Supabase.

Workflow: New row in Supabase → send to GPT → store AI response back.

Day 17:

File automation: Upload file to Supabase → n8n retrieves → AI summarizes → store summary.

Day 18:

Build auto-reply bot: Incoming email → AI generates response → send reply.

Day 19:

Explore LangChain basics (chaining prompts, embeddings).

Connect LangChain with n8n using custom HTTP nodes.

Day 20:

Experiment with pgvector in Supabase.

Store embeddings → query them with AI.

Day 21 (Review Project):

Mini-project: “AI-Powered Support Inbox”

User sends message (Supabase) → n8n → GPT summarizes → store in DB + send email.

🔹 Week 4: Advanced Projects & Deployment

Goal: Production-ready AI automations with Supabase + n8n.

Day 22:

Deploy Supabase project to cloud.

Deploy n8n (self-hosted or n8n cloud).

Day 23:

Secure workflows: API keys, auth, rate limits.

Add logging & error handling in n8n.

Day 24:

Build: Automated onboarding flow.

User signs up (Supabase) → n8n sends welcome email → creates default records.

Day 25:

Build: AI-powered document pipeline.

Upload PDF → chunk text → embeddings → store in Supabase → retrieval with GPT.

Day 26:

Build: AI content generator.

Input topic in Supabase → n8n → AI → generate blog outline → save result.

Day 27:

Build: AI chatbot with Nuxt frontend.

Query Supabase embeddings → retrieve + AI answer → display in UI.

Day 28:

Connect Stripe (or fake payments).

Automate subscription logic with n8n + Supabase (new customer → workflow).

Day 29:

Optimize & refactor:

Environment variables.

Modular workflows in n8n.

Secure AI keys.

Day 30 (Final Project):

Capstone: “AI Knowledge Base SaaS”

Users sign up in Nuxt (Supabase auth).

Upload documents (Supabase storage).

n8n extracts → AI embeddings in pgvector → searchable Q&A chatbot.
