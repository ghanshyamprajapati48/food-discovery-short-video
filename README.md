** Food Discovery App (Short-Video Based) — MERN Project**

A mini project inspired by Instagram Reels / TikTok style short-video experience for food discovery.
Users can explore food through videos, and food partners can upload clips of their dishes.
Built with MERN Stack, Cloud Storage, and secure Auth System.

 **Overview**

This project is a Food Discovery Application that allows restaurants, chefs, and food vendors to upload short food videos, helping users visually explore dishes.
Users can watch, like, and save videos just like Instagram Reels.

This bridges the gap between food delivery apps (Zomato/Swiggy) and visual social platforms (Reels/TikTok).

 **Objectives**

Provide a short-video based food discovery platform

Allow food partners to upload dish videos

Secure login/signup for users and partners

Store video metadata, likes, and user interactions

Use MongoDB for efficient data management

Improve user experience through visual content

 **Project Background**

Short videos dominate modern user engagement

Visual content builds trust more than photos/text

No existing food app focuses on interactive video discovery

Reels/TikTok trends show video content influences user choices

This project introduces a unique fusion of food + reels format

 **Tech Stack**
**Frontend**

React.js

HTML5, CSS3

JavaScript (ES6+)

**Backend**

Node.js

Express.js

Database

MongoDB

Mongoose

**Tools & Services**

VS Code

Postman

JWT (Authentication)

bcrypt.js (Password hashing)

ImageKit (Video storage)

**Modules Developed**
**Authentication Module**

User & Partner login/signup

Password hashing

Secure JWT-based authorization

**Food Partner Module**

Upload short videos

Manage uploaded dishes

**Food Module**

Fetch random food videos

Reels-style feed display

**Likes & Save Module**

Users can like videos

Users can save videos for later

**Storage Module**

Video stored in cloud (Cloudinary/ImageKit)

Metadata stored in MongoDB

**Project Flow (Architecture)**

Upload: Food partner uploads short video

Storage: Video → Cloud | Metadata → MongoDB

Fetch: API returns random videos (/api/food/random)

Display: React shows videos like Instagram Reels

Interaction: Users like/save videos → stored in DB

**Key Learnings**

MERN integration (React ↔ Node ↔ MongoDB)

Designing secure authentication

Cloud storage for large video files

REST API development

Real-world workflows (CRUD, uploads, auth, user interaction)

Implementing dynamic random feed

Managing likes/saves in database

**Outcome / Results**

Built a working mini version of Reels/TikTok focused on food

Seamless video watching experience

Users can like, save, and discover dishes visually

Food partners can promote dishes using video

Scalable concept for future (ordering, ML recommendations, dashboards)

**Future Enhancements**

Online food ordering

Food partner dashboard

Machine Learning recommendation system

Following system (creators)

Comments on videos

👤 **Developed By**

Ghanshyam Prajapati
B.Tech CSE
