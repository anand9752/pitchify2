# Pitchify - Virtual Pitch Platform 🚀  


## Table of Contents  

- 🤖 [Introduction](#introduction)  
- ⚙️ [Tech Stack](#tech-stack)  
- 🔋 [Features](#features)  
- 🤸 [Quick Start](#quick-start)  
- 🕸️ [Snippets](#snippets)  
- 🔗 [Assets](#assets)  
- 🚀 [More](#more)  
- 🚨 [Tutorial](#tutorial)  

---

## 🤖 Introduction  

A **Next.js 15** platform where entrepreneurs can submit their startup ideas for virtual pitch competitions, browse other pitches, and gain exposure through a clean, minimalistic design for a smooth user experience.  

If you're getting started and need assistance or face any bugs, join our active [Discord community](https://discord.com) with over **34k+ members**. It's a place where people help each other out.  

---

## ⚙️ Tech Stack  

- **React 19**  
- **Next.js 15**  
- **Sanity**  
- **TailwindCSS**  
- **ShadCN**  
- **TypeScript**  

---

## 🔋 Features  

- 👉 **Live Content API**: Displays the latest startup ideas dynamically on the homepage using Sanity's Content API.  
- 👉 **GitHub Authentication**: Allows users to log in easily using their GitHub account.  
- 👉 **Pitch Submission**: Users can submit startup ideas, including title, description, category, and multimedia links (image or video).  
- 👉 **View Pitches**: Browse through submitted ideas with filtering options by category.  
- 👉 **Pitch Details Page**: Click on any pitch to view its details, with multimedia and description displayed.  
- 👉 **Profile Page**: Users can view the list of pitches they've submitted.  
- 👉 **Editor Picks**: Admins can highlight top startup ideas using the "Editor Picks" feature managed via Sanity Studio.  
- 👉 **Views Counter**: Tracks the number of views for each pitch instead of an upvote system.  
- 👉 **Search**: Search functionality to load and view pitches efficiently.  
- 👉 **Minimalistic Design**: Fresh and simple UI with only the essential pages for ease of use and a clean aesthetic.  

...and many more, including the latest **React 19**, **Next.js 15**, and **Sanity** features alongside code architecture and reusability.  

---

## 🤸 Quick Start  

### Prerequisites  

Make sure you have the following installed on your machine:  
- [Git](https://git-scm.com)  
- [Node.js](https://nodejs.org)  
- [npm](https://www.npmjs.com) (Node Package Manager)  

### Cloning the Repository  

Clone the repository and navigate into the project directory:  

```bash
git clone https://github.com/JavaScript-Mastery-Pro/pitchify.git  
cd pitchify  
```
### Installation  

Install the project dependencies using npm:  

```bash
npm install  
```

### Set Up Environment Variables  

Create a new file named `.env.local` in the root of your project and add the following content:  

```env
NEXT_PUBLIC_SANITY_PROJECT_ID=  
NEXT_PUBLIC_SANITY_DATASET=  
NEXT_PUBLIC_SANITY_API_VERSION='vX'  
SANITY_TOKEN=  
AUTH_SECRET=  
AUTH_GITHUB_ID=  
AUTH_GITHUB_SECRET=  
```

Replace the placeholder values with your actual Sanity credentials. You can obtain these credentials by signing up and creating a new project on the [Sanity website](https://www.sanity.io).  

---

### Running the Project  

Start the development server:  

```bash
npm run dev  
```

