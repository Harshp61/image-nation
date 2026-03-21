<div align="center">

# 🖼️ Image Nation

### *Create Without Limits.*

[![Next.js](https://img.shields.io/badge/Next.js-16.1.6-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Convex](https://img.shields.io/badge/Database-Convex-EE4B2B?style=for-the-badge)](https://convex.dev/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)](https://clerk.com/)
[![ImageKit](https://img.shields.io/badge/Media-ImageKit-FF5A5F?style=for-the-badge)](https://imagekit.io/)
[![Vercel](https://img.shields.io/badge/Deployed-Vercel-000?style=for-the-badge&logo=vercel)](https://image-nation-ten.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

> A professional-grade, AI-powered image editor built for the web.
> Crop, resize, adjust colors, remove backgrounds, extend canvases, and upscale — all in the browser.

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-image--nation--ten.vercel.app-blue?style=for-the-badge)](https://image-nation-ten.vercel.app)

---

</div>

## 🌟 About

**Image Nation** is a full-stack web application that brings desktop-quality image editing to the browser. It combines a **Fabric.js** canvas editor with **ImageKit's AI transformation API** to give users powerful tools — from basic adjustments to advanced AI features like background removal, generative fill, and 4× upscaling — all without installing any software.

Projects are saved in real-time via **Convex**, and the whole experience is secured with **Clerk** authentication.

<br/>

## ✨ Features

| | Tool | What it does |
|--|------|-------------|
| ✂️ | **Smart Crop & Resize** | Interactive cropping with aspect ratio locks and quality-preserving resizing at any dimension |
| 🎨 | **Color & Light Adjustment** | Brightness, contrast, and saturation controls with real-time preview and one-click auto-enhance |
| 🤖 | **AI Background Removal** | Instantly remove or replace backgrounds — AI handles complex edges, hair, and fine details |
| 🔧 | **AI Content Editor** | Edit images using natural language — remove objects, swap elements, or add new content via generative AI |
| 📏 | **Image Extender** | Expand your canvas in any direction; AI fills the new space so it blends seamlessly with the original |
| ⬆️ | **AI Upscaler** | Enhance resolution up to 4× — detail-preserving AI upscaling with reduced noise and artifacts |
| 🖌️ | **Canvas Editor** | Fabric.js-powered interactive canvas with layers, drawing tools, text, and real-time editing |
| 🎨 | **Color Picker** | Precise color selection using `react-colorful` for fills, text, and overlays |
| 💾 | **Project Management** | Save, organize, and revisit projects at any time — stored in a real-time Convex database |
| 🌙 | **Dark Mode** | Full light/dark theme support across the entire app |

<br/>

## 🛠️ Tech Stack

### 🎨 Frontend
**Next.js 16** (App Router) · **React 19** · **TailwindCSS v4** · **shadcn/ui** · **Radix UI** · **Lucide React**

**Fabric.js 7** powers the interactive canvas engine — handling object manipulation, layers, drawing, and rendering directly in the browser.

**react-colorful** for color picking · **react-dropzone** for drag-and-drop uploads · **next-themes** for dark mode · **sonner** for toasts · **date-fns** for date formatting.

### 🗄️ Backend & Storage
**Convex** provides a real-time serverless database with reactive queries — project changes sync instantly without manual refreshes.

**ImageKit** handles image storage, CDN delivery, and all AI-powered transformations (background removal, generative fill, upscaling, content editing).

### 🔐 Auth & Security
**Clerk** manages authentication and user sessions, with a **Next.js middleware** layer protecting all private routes.

<br/>

## 📁 Project Structure

```
image-nation/
├── 📂 app/           # Next.js App Router — pages, layouts, API routes
├── 📂 components/    # UI components — canvas toolbar, panels, editor controls
├── 📂 context/       # React context — global editor state & theme
├── 📂 convex/        # Convex schema, queries, mutations & server functions
├── 📂 hooks/         # Custom React hooks
├── 📂 lib/           # Utilities & ImageKit client config
├── 📂 public/        # Static assets
└── 📄 middleware.js  # Clerk auth middleware for route protection
```

<br/>

## 🚀 Getting Started

### Prerequisites
- **Node.js** `v18+`
- Free accounts on [Clerk](https://clerk.com), [Convex](https://convex.dev), and [ImageKit](https://imagekit.io)

### Installation

```bash
# Clone & install
git clone https://github.com/Harshp61/image-nation.git
cd image-nation
npm install

# Start the dev server
npm run dev
# → Open http://localhost:3000
```

> 💡 Run `npx convex dev` in a separate terminal to start the Convex backend locally.

<br/>

## 💰 Pricing

| Feature | 🆓 Free | ⭐ Pro ($5/mo) |
|---------|:-------:|:-------------:|
| Projects | 3 max | ♾️ Unlimited |
| Exports / month | 20 | ♾️ Unlimited |
| Crop, Resize & Color Tools | ✅ | ✅ |
| Text Tool | ✅ | ✅ |
| AI Background Remover | ❌ | ✅ |
| AI Image Extender | ❌ | ✅ |
| AI Retouch & Upscaler | ❌ | ✅ |

<br/>

## 🌐 Deployment

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Harshp61/image-nation)

1. Import the repo on [Vercel](https://vercel.com/new)
2. Add your environment variables in the Vercel dashboard
3. Deploy your Convex backend: `npx convex deploy`
4. Hit **Deploy** 🚀

<br/>

## 🤝 Contributing

1. 🍴 Fork the repo
2. 🌿 Create a branch: `git checkout -b feature/YourFeature`
3. 💾 Commit: `git commit -m "✨ Add: YourFeature"`
4. 📤 Push & open a Pull Request

Found a bug or have an idea? [Open an issue →](https://github.com/Harshp61/image-nation/issues)

<br/>

## 📄 License

Licensed under the [MIT License](LICENSE).

<br/>

<div align="center">

Made with ❤️ by **[Harsh](https://github.com/Harshp61)**

⭐ **If you like this project, give it a star!** ⭐

[![GitHub stars](https://img.shields.io/github/stars/Harshp61/image-nation?style=social)](https://github.com/Harshp61/image-nation/stargazers)

</div>
