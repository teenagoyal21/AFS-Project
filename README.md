<div align="center">

  <h1>🔗 Zoom Clone</h1>
  <p>A full-stack Zoom-like video conferencing platform built using modern technologies like Next.js, TypeScript, Clerk, getstream, and Tailwind CSS.</p>
  
  <p>Build this project step-by-step by following the <a href="https://youtu.be/R8CIO1DZ2b8" target="_blank"><b>JavaScript Mastery YouTube Tutorial</b></a>.</p>

</div>

---

## 📚 Table of Contents

1. [📌 Introduction](#introduction)
2. [🧰 Tech Stack](#tech-stack)
3. [🚀 Features](#features)
4. [⚡ Quick Start](#quick-start)
5. [📁 Folder Structure](#folder-structure)
6. [🛠️ Snippets](#snippets)
7. [🧠 More](#more)

---

## 🤖 Introduction

This Zoom Clone replicates the core functionalities of Zoom including user authentication, secure video meetings, meeting scheduling, and media controls like screen sharing and recording.

The project is a great learning experience for building real-time video applications with modern web tools.

---

## ⚙️ Tech Stack

- **Next.js 14** – React framework with app router
- **TypeScript** – For type safety and maintainability
- **Tailwind CSS** – Utility-first CSS for fast UI development
- **Clerk** – Authentication and user management
- **getstream** – Real-time video and audio functionality
- **Shadcn UI** – Reusable UI components
- **Vercel** – Hosting (optional)

---

## 🔋 Features

✅ **Authentication with Clerk**  
✅ **Create/Join Meetings via Link**  
✅ **Schedule Future Meetings**  
✅ **Upcoming & Past Meeting History**  
✅ **Join Personal Room**  
✅ **Real-Time Video/Audio Calls**  
✅ **Screen Sharing & Emoji Reactions**  
✅ **Meeting Controls: Mute/Unmute, End Call, Pin, Block Users**  
✅ **Responsive UI for All Devices**  
✅ **View Meeting Recordings**

---

## 🤸 Quick Start

### 🔧 Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- [npm](https://www.npmjs.com/)

### 🚀 Installation

```bash
git clone https://github.com/your-username/zoom-clone.git
cd zoom-clone
npm install


🔐 Environment Variables
Create a .env file in the root and add the following:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key


🧪 Run the Development Server
npm run dev
Visit http://localhost:3000 in your browser.
