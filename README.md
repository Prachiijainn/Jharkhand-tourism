Jharkhand Travel Website

A modern, AI-powered travel platform designed to help people explore the beauty of Jharkhand, India. The website brings together interactive maps, intelligent trip planning, and a smart chatbot to make traveling easier, personalized, and more engaging.

 What is this project about?

This project is a digital tourism platform for Jharkhand that combines:

Interactive destination guides – Explore attractions, culture, and hidden gems.

AI-powered travel assistant – Ask questions, get instant answers, and personalized suggestions.

📋 Trip planner – Build itineraries based on your preferences.

🎨 Modern UI/UX – Clean, responsive, and mobile-friendly design.

🌟 Beautiful visuals – Use of animations and imagery to bring Jharkhand’s charm to life.

In short: It’s a smart tourism website that helps locals and tourists discover Jharkhand like never before.

🛠️ Tech Stack

This website is built using modern web technologies:

Framework: Next.js 14

Frontend: React, Tailwind CSS, Radix UI

AI Integration: Vercel AI SDK + Groq API

Icons: Lucide React

Fonts: Inter & JetBrains Mono

🚀 How to Run the Project

Install dependencies

npm install


Set up your Groq API key

Create a .env.local file in the project root.

Add your key like this:

GROQ_API_KEY=your_groq_api_key_here


Get a free key from Groq Console
.

Start the development server

npm run dev


Open the website at http://localhost:3000
.

💬 Chatbot Setup

The chatbot won’t work without a valid Groq API key.

If you see "Groq API key not configured", check your .env.local file and restart the server.

📂 Project Structure
├── app/                 # Next.js app directory
│   ├── api/             # API routes
│   ├── destinations/    # Destination pages
│   └── ...
├── components/          # UI & reusable components
├── lib/                 # Utility functions
└── public/              # Static assets (images, icons, etc.)
