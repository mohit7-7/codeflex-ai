💪 AI Fitness Assistant 🤖
Your AI-powered personal trainer & nutritionist

An intelligent fitness platform that creates personalized workouts, tailored diet plans, and real-time interactive coaching. Built with Next.js, TailwindCSS, Gemini AI, Convex, and Vapi Voice Assistant, this app delivers fitness guidance anytime, anywhere. 🚀

✨ Features
✅ AI Fitness Coach – Chat or talk with your fitness trainer in real-time
✅ Custom Workouts – Programs tailored to your goals, fitness level, and injuries
✅ Personalized Diet Plans – Smart meal suggestions with allergy & preference support 🥗
✅ Voice Assistant (Vapi) – Talk naturally, get instant advice 🎙
✅ Progress Tracking – Save & update routines in real-time with Convex DB
✅ On-Demand Program Creation – New workouts & diet plans instantly with Gemini AI
✅ Secure Authentication – Login via Google, GitHub, or Email (Clerk Auth) 🔐
✅ Responsive Design – Clean, modern UI powered by Tailwind + Shadcn UI

🖥 Tech Stack
Layer	Tech Used
Frontend	Next.js, React, TailwindCSS, Shadcn UI
AI	Gemini AI (fitness & nutrition intelligence), Vapi (voice AI)
Backend	Next.js Server Components, Convex DB
Auth	Clerk (Google, GitHub, Email/Password)
Hosting	Vercel (optimized deployment)
🚀 Getting Started
1️⃣ Clone the repository
bash
git clone <your-repo-url>
cd <repo-folder>
2️⃣ Install dependencies
bash
npm install
3️⃣ Configure environment variables
Create a .env.local file in the root folder and add the following:

bash
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
4️⃣ Start the development server
bash
npm run dev
👉 Open http://localhost:3000

🌍 Deployment
Easily deploy with Vercel:

bash
npm run build
npm start
Or connect your repo to Vercel Dashboard for automatic deployments 🚀

📸 Screenshots (Optional)
Add some cool screenshots or demo GIFs here to showcase the UI/UX.
Example:

📚 Documentation & Resources
Next.js Docs

Clerk Docs

Vapi AI Docs

Convex Docs

Gemini AI Docs

❤️ Built for Fitness & Tech Enthusiasts
This project is a blend of technology + fitness passion.
Stay consistent, stay healthy, and let AI guide your journey 💪👟
