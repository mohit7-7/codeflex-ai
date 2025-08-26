💪 AI Fitness Assistant 🤖

A modern AI-powered fitness platform that creates personalized workouts, diet plans, and provides an interactive voice assistant experience. Built with cutting-edge tech like Next.js, Tailwind, Gemini AI, and Convex, this app delivers fitness guidance in real time.

🚀 Key Highlights

⚡ Next.js + React + Tailwind + Shadcn UI → Modern, fast, and responsive frontend

🎙 Voice AI Assistant (Vapi) → Talk to your fitness coach in real time

🧠 Gemini AI Integration → AI-generated fitness & nutrition plans

🏋 Custom Workout Programs → Tailored routines based on your fitness level & goals

🥗 Smart Diet Recommendations → Personalized meal plans with allergy & preference support

🔐 Authentication with Clerk → Secure login via Google, GitHub, or email/password

💾 Convex Database → Real-time program storage & retrieval

🎬 On-Demand Program Creation → AI instantly generates your new plan

🎭 Full-stack Next.js (Server + Client components)

✨ Features

AI Chat & Voice Assistant – Have natural conversations about your fitness journey

Workout Customization – Exercises tailored to strength, injuries, and progress

Meal Planning – Balanced nutrition suggestions adapted to your lifestyle

User Profiles – Manage multiple fitness programs, track only the latest active one

Cross-Platform UI – Beautiful, responsive design optimized for all devices

⚙️ Setup

Create a .env.local file in the root folder with the following variables:

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

🛠 Getting Started

Clone the repo

git clone <your-repo-url>
cd <repo-folder>


Install dependencies

npm install


Set up environment variables (see above)

Run development server

npm run dev


Open your app → http://localhost:3000

🚀 Deployment

Deploy seamlessly with Vercel:

npm run build
npm start


Or simply connect the repo to Vercel Dashboard for automatic deployments.

🧩 Tech Stack

Next.js → Frontend & API routes

React + Tailwind + Shadcn UI → Clean, modern UI

Clerk → User authentication & management

Vapi → AI-powered voice interactions

Convex → Real-time database

Gemini AI → Personalized fitness + nutrition generation

📚 Resources

Next.js Docs

Clerk Docs

Vapi Docs

Convex Docs

Gemini AI Docs

🔥 Built with passion for fitness and tech!
