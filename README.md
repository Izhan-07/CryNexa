# 💰 CryNexa – AI Finance Platform

A **full-stack AI-powered finance platform** built with modern web technologies.  
CryNexa helps you track income & expenses across multiple accounts, gain AI-powered insights, and manage your personal finances with ease.  

---

## 🚀 Features

- **📊 Multi-Account Tracking**  
  Monitor income and expenses across different accounts in one place.  

- **🔐 Authentication & User Onboarding**  
  Secure sign-in and sign-up flows using [Clerk](https://clerk.com).  

- **🤖 AI-Enhanced Finance**  
  Powered by **Gemini AI** for intelligent insights, summaries, and automated financial analysis.  

- **⚡ Background Workflows**  
  Asynchronous job handling with **Inngest** and **ArcJet** for tasks like data fetching, transaction processing, and report generation.  

- **🗄️ Database & ORM**  
  **Supabase** as the backend + authentication, integrated with **Prisma** for seamless database management.  

- **🎨 Modern UI & Styling**  
  Responsive, elegant interface using **Next.js**, **Tailwind CSS**, and **Shadcn UI**.  

- **🌐 Full-Stack Integration**  
  End-to-end setup combining frontend, backend, AI, workflows, and secure authentication.  

---

## 🛠️ Tech Stack

- **Frontend:** Next.js, Tailwind CSS, Shadcn UI  
- **Backend / DB:** Supabase, Prisma  
- **Authentication:** Clerk  
- **AI Integration:** Gemini AI  
- **Background Jobs:** Inngest, ArcJet  
- **Other Tools:** TypeScript, ESLint, Prettier  

---

## 📂 Project Structure

app/ # Next.js App Router (pages, routes, layouts)
components/ # Reusable UI components
prisma/ # Prisma schema & migrations
lib/ # Helper utilities and configs
public/ # Static assets
.env # Environment variables (API keys, DB connection)


---

🧩 Roadmap

 -Add budget planning & forecasting

 -More AI-driven insights & charts

 -Export reports (CSV / PDF)

 -Mobile responsive optimizations

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
