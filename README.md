💰 AI Finance Platform with Next JS, Supabase, Tailwind, Prisma, Inngest, ArcJet, Shadcn UI

An AI-powered finance dashboard that helps users manage income and expenses effortlessly.
Users can track spending across multiple accounts, visualize data with charts, and even scan receipts using AI to auto-fill expense details.
<img width="1470" alt="Home" src="https://drive.google.com/file/d/13AMdwVSn4w3EJr7hZ8znQYV5xHHRzuTg/view?usp=sharing">
<img width="1470" alt="Dashbord" src="https://drive.google.com/file/d/1QyfoVjQNplCxBye2b0n9OQOwOQqjU7Jl/view?usp=sharing">

⸻

✨ What This App Does
	•	➕ Add income & expenses
	•	🏦 Create multiple accounts and set one as primary
	•	📊 Visualize data using Recharts
	•	🤖 Upload receipt images — AI (Gemini) extracts details automatically
	•	🎯 Track budgets and spending progress

Built to solve a real-world personal finance problem with modern web tech.

⸻

🧠 AI Receipt Feature (Quick Explanation)
	1.	User uploads a receipt image
	2.	Image is processed by Google Gemini AI
	3.	AI detects key details (amount, merchant, etc.)
	4.	Expense form gets auto-filled
	5.	User reviews and saves

Simple, fast, and accurate.

⸻

🛠 Tech Stack
	•	Next.js (App Router)
	•	React
	•	Tailwind CSS + shadcn/ui
	•	Recharts
	•	Prisma + SQL Database
	•	Clerk Authentication
	•	Google Gemini AI

📂 Project Structure (High Level)

actions/        → Server actions (accounts, transactions, budget)
app/            → App Router pages & layouts
components/     → Reusable UI components
lib/            → Prisma, auth checks, utils, integrations
prisma/         → Database schema & migrations
hooks/          → Custom React hooks
emails/         → Email templates


### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```
