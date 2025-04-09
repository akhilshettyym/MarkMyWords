# 🧵 Threads App (Full Stack)

A full-featured Threads clone built with **Next.js 14**, **TypeScript**, **Tailwind CSS**, **App Router**, **MongoDB**, and **Clerk**. This app replicates the functionality of Meta’s Threads platform — including user authentication, posting, replies, and social interactions — with additional features on the way!

---

## 🚀 Tech Stack

- **Framework:** [Next.js 14](https://nextjs.org/docs) with App Router  
- **Language:** TypeScript  
- **Styling:** Tailwind CSS  
- **Database:** MongoDB with Mongoose ODM  
- **Authentication:** Clerk  
- **Hosting (Coming soon):** Vercel  

---

## 📁 Project Setup

This project was bootstrapped using:

```bash
npx create-next-app@latest
```

### ❌ Why Turbopack is NOT Used
Turbopack is an experimental bundler developed by Vercel (creators of Next.js), written in Rust. It aims to replace Webpack with faster startup and hot reload times. However, it is not yet production-ready, lacks full Webpack config support, and may introduce bugs during development.
- We chose not to use Turbopack because:
- Stability is preferred for full-stack apps
- Custom configuration flexibility is required
- Turbopack is still in its experimental phase

## Why use mongoose
🧩 Why Mongoose?
Mongoose is a powerful ODM library for MongoDB.
✅ Benefits of using Mongoose:

- Schema-based modeling: Define clear data structures for MongoDB collections.
- Validation: Ensure data integrity with built-in validators.
- Middleware support: Add hooks before/after actions like save, remove, etc.
- Query helpers: Simplify database interactions with chaining methods.

Package	Description
@clerk/nextjs	Authentication and user management for Next.js via Clerk
@uploadthing/react	File uploads made simple — frontend integration for UploadThing
mongoose	ODM (Object Data Modeling) library for MongoDB, allows schema definitions, validation, and middleware
svix	Webhook service used for secure, scalable event delivery (e.g., Clerk webhooks)
uploadthing	Backend SDK for handling file uploads and storage with UploadThing

## Packages installed for now
```bash 
npm install @clerk/nextjs @uploadthing/react mongoose svix uploadthing 
```
### what these packages are for :
- @clerk/nextjs	Authentication and user management for Next.js via Clerk

- @uploadthing/react	File uploads made simple — frontend integration for UploadThing

- mongoose	ODM (Object Data Modeling) library for MongoDB, allows schema definitions, validation, and middleware

- svix	Webhook service used for secure, scalable event delivery (e.g., Clerk webhooks)

- uploadthing	Backend SDK for handling file uploads and storage with UploadThing