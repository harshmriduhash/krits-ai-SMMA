<img src="https://github.com/user-attachments/assets/a1d7ced5-e6fc-41fd-9256-9d73a5f33597" alt="Krits Logo" width="50" height="50">

## 🌟 Introduction
Krits is an innovative social media marketing platform designed to help you streamline your social media management effortlessly. Built with Next.js, Tailwind CSS, Shadcn UI, Magic UI, Aceternity UI, Prisma, MongoDB, Clerk, React Hook Form, and TypeScript, Krits provides powerful analytics and user-friendly features to enhance your social media marketing experience.

## 🚀 Features

- Real-time performance tracking across platforms
- Engagement rate calculations and trends
- Audience growth and demographic insights
- Custom report generation
- ROI tracking and analysis

## 🔗 Live Preview

Check out the live demo of Krits here: [Live Preview](http://Krits-Ai.vercel.app) 

## 💻 Tech Stack

* Next.js
* Tailwind CSS
* Shadcn UI
* Magic UI
* Aceternity UI
* Prisma
* MongoDB
* Clerk
* Recharts
* Framer Motion

## 🛠️ Installation
To run Krits locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone 
    ```
2. Install dependencies:
    ```bash
    pnpm install
    ```
3. Set up environment variables in a `.env` file:
    ```
    # app
    NEXT_PUBLIC_APP_NAME=
    NEXT_PUBLIC_APP_DOMAIN=

    # database
    DATABASE_URL=

    # auth
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=
    NEXT_PUBLIC_CLERK_SIGN_IN_URL="/signin"
    NEXT_PUBLIC_CLERK_SIGN_UP_URL="/signup"
    NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_URL="/"
    NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_URL="/"
    ```

4. Run the development server:
    ```bash
    pnpm run dev
    ```