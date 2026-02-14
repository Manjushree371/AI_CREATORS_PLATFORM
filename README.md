# Full Stack AI Content Platform with Next JS, Tailwind, React Quill, ImageKit, Shadcn UI 

🤖 AI Creators Platform

A full-stack, AI-powered content creation and social platform that enables creators to generate, edit, publish, analyze, and grow content using AI — all within a modern, scalable web application.


---

✨ Features

📝 AI-Powered Content Creation Flow

End-to-end content creation pipeline combining:

AI-generated content

Manual rich text editor


Edit AI output to:

Enhance

Expand

Simplify


Full creative control over final published content



---

🖋️ Rich Text Editor

Powerful manual editor for fine-grained content control

Supports headings, lists, formatting, embeds, and links

Seamless transition between AI-generated and manual content



---

🖼️ Advanced Image Handling

Add featured images to posts

Embed images anywhere within content

Image transformation features powered by ImageKrate:

Background removal

Drop shadow

Smart cropping

Aspect ratio adjustment

Text overlay

Image optimization




---

👤 User Profiles & Creator Identity

Username-based identity system

Public creator profiles

View posts, followers, and engagement metrics

Simple setup to start posting instantly



---

📰 Dynamic Content Feed

For You feed with personalized recommendations

Trending feed highlighting popular content

Creator discovery and user suggestions



---

🤝 Social Engagement

Follow / unfollow creators

Like posts

Comment and interact with content

Build a connected creator community



---

📊 Creator Analytics Dashboard

Real-time analytics including:

Live views

Likes and comments

Recent activity

Follower count


Daily growth charts and performance tracking



---

👥 Follower & Network Management

Manage followers and following lists

Track creator network growth

Easy navigation across connections



---

⚙️ Full Content Management System (CMS)

Create, edit, publish, and delete posts

Draft and scheduled content support

Analytics-driven content decisions



---

🎨 Fully Responsive Modern UI

Built using Next.js

Styled with Chat GQI

Mobile-first and fully responsive design

Optimized for performance and accessibility



---

🚀 Scalable Full-Stack Architecture

Modular backend architecture

Secure authentication and APIs

Designed for future expansion:

Monetization

Creator subscriptions

AI insights

Content recommendations

🛠️ Tech Stack

Frontend

Next.js – App Router, Server Actions

React

Tailwind CSS

Shadcn UI / Chat GQI

Responsive, mobile-first design


Backend

Next.js API routes

Server Actions for mutations

REST-style endpoints


Database & Auth

Supabase

Authentication

PostgreSQL database

Row Level Security (RLS)



Storage

Supabase Storage Buckets

Image uploads and retrieval


AI & Media

OpenAI API (content generation)

ImageKrate (image transformations)


Analytics

Custom analytics logic

Real-time engagement tracking


Tooling

TypeScript

ESLint

Prettier



---

⚙️ Setup & Installation

1️⃣ Clone the Repository

git clone https://github.com/your-username/ai-creators-platform.git
cd ai-creators-platform


---

2️⃣ Install Dependencies

npm install


---

3️⃣ Create Environment Variables

Create a .env.local file in the root directory:

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

OPENAI_API_KEY=your_openai_api_key

IMAGEKRATE_API_KEY=your_imagekrate_api_key


---

4️⃣ Setup Supabase

1. Create a project in Supabase


2. Enable Authentication (Email / OAuth)


3. Create database tables:

users

posts

comments

likes

followers

analytics



4. Enable Row Level Security (RLS)


5. Create a storage bucket for images




---

5️⃣ Run the Development Server

npm run dev

App will be available at:

http://localhost:3000


---

6️⃣ Build for Production

npm run build
npm start


---

📦 Scripts

npm run dev     # Start development server
npm run build   # Build for production
npm run start   # Start production server
npm run lint    # Lint codebase


---

🔮 Future Enhancements

AI content insights

Creator monetization

Subscriptions

Advanced recommendations

Media uploads (video/audio)



### Make sure to create a `.env` file with following variables -

```
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

CLERK_JWT_ISSUER_DOMAIN=

# Imagekit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=
IMAGEKIT_PRIVATE_KEY=

# Unsplash
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

#Gemini
GEMINI_API_KEY=
```
