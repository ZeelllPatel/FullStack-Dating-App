## FullStack Dating App

##  Introduction

In this in-depth tutorial you'll build a production-ready **FullStack Dating Website** using **Next.js**, **Supabase** (Postgres + Realtime), and **Stream** for chat & video. We cover everything from authentication and DB schema to matching logic, realtime chat, and one-to-one video calls — a complete, intermediate → advanced project.

---

## Tech Stack

* **Next.js (App Router)** – Server & client components for fast SSR/SSG
* **Supabase** – Postgres database, auth, RLS, storage & realtime
* [**Stream** – Real-time chat & video/call SDK](https://getstream.io/chat/sdk/react/?utm_source=youtube&utm_medium=referral&utm_content=&utm_campaign=pedro2025)
* **TailwindCSS** – Utility-first styling & responsive layouts
* **TypeScript** – Type-safe codebase
* **Vercel** – Recommended hosting & serverless deployment

---

## Features

*  **Auth** — Secure sign-up, sign-in, and session handling
*  **Postgres Schema** — Profiles, matches, messages, calls (RLS-ready)
*  **Profile Page** — View & edit user profile with photos & bio
*  **Fake Profiles Seeder** — Seed the database for local testing
*  **Matching System** — Discover, like & match users
*  **Realtime Chat** — One-to-one messaging via Stream
*  **Live Video Calls** — WebRTC-backed calls using Stream SDK
*  **Responsive UI** — Mobile-first design with Tailwind
*  **Production-ready** — Env config, deployment guide, and seeding scripts

---


### Database Setup (Supabase)

1. Create a new Supabase project and Postgres database.
2. Run the provided SQL (schema) file or use the SQL editor to create tables (users, profiles, matches, messages, calls).
3. Enable Realtime or replication features if you plan to use Supabase realtime.
4. Optionally run the seeder script to create fake profiles for testing:

```

### Run Dev Server

```bash
npm run dev
# opens at http://localhost:3000
```

---

## 🖼️ Screenshots
<img width="998" height="850" alt="Screenshot 2025-08-18 at 4 52 24 PM" src="https://github.com/user-attachments/assets/a9a05363-26b6-4b66-9de8-b476ed0d39a1" />
<img width="958" height="840" alt="Screenshot 2025-08-18 at 4 56 45 PM" src="https://github.com/user-attachments/assets/36e4b4f8-deb5-46db-952d-ecf59b172647" />
<img width="1811" height="924" alt="Screenshot 2025-08-14 at 7 20 03 PM" src="https://github.com/user-attachments/assets/490ec5c9-7553-4d89-ab39-9b6a892d77de" />

---

### Deploy on Vercel

1. Push your completed code to GitHub.
2. Go to [Vercel](https://vercel.com/).
3. Import your repository.
4. Add Environment Variables in Vercel (same as `.env.local`).
5. Set up any server-side secrets (Stream secret, Supabase service key).
6. Click **Deploy**.

Your live app will be hosted on a Vercel subdomain (e.g. `https://your-dating-app.vercel.app`).

---

Enjoy your Dating!!!😁💕
