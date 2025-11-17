# 🎾 Sakka Tennis Coach - Professional Website

A modern, professional website for Sakka, a tennis coach based in Montreal, QC. This site showcases coaching services, experience, achievements, and testimonials.

## 📋 Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running Locally](#running-locally)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

## ✨ Features

- **Hero Section** - Eye-catching introduction with call-to-action
- **Services** - Detailed coaching offerings (private lessons, group sessions, competitive development)
- **About Me** - Coach profile with certifications and experience
- **Achievements** - Showcase of accomplishments and success stories
- **Testimonials** - Client reviews and feedback
- **Contact Section** - Coaching philosophy and engagement
- **Responsive Design** - Optimized for mobile, tablet, and desktop
- **Modern UI** - Built with React 19 and Tailwind CSS 4

## 📦 Prerequisites

Before you begin, ensure you have the following installed on your system:

### Windows Users:
1. **Git for Windows** - Download from https://git-scm.com/download/win
2. **Node.js (LTS)** - Download from https://nodejs.org/
   - This includes npm (Node Package Manager)

### macOS Users:
```bash
# Install using Homebrew
brew install git node
```

### Linux Users:
```bash
# Ubuntu/Debian
sudo apt-get install git nodejs npm

# Fedora
sudo dnf install git nodejs npm
```

**Verify Installation:**
```bash
git --version
node --version
npm --version
```

## 🚀 Installation

### Option 1: Clone from GitHub (Recommended)

1. **Open Command Prompt / Terminal** in your desired directory

2. **Clone the repository:**
```bash
git clone https://github.com/sakkovic/tennis_website.git
cd tennis_website
```

3. **Extract the ZIP file:**
   - Right-click on `tennis_website.zip`
   - Select "Extract All..." (Windows) or use `unzip tennis_website.zip` (Mac/Linux)
   - Choose the current directory

4. **Install dependencies:**
```bash
npm install
```

### Option 2: Download ZIP Directly

1. Go to https://github.com/sakkovic/tennis_website
2. Click the green **"Code"** button
3. Select **"Download ZIP"**
4. Extract the ZIP file to your desired location
5. Open Command Prompt/Terminal in the extracted folder
6. Run `npm install`

## 🏃 Running Locally

### Start the Development Server

```bash
npm run dev
```

The server will start and display output similar to:
```
➜  Local:   http://localhost:5173/
➜  Network: http://192.168.x.x:5173/
```

### Access the Website

Open your web browser and navigate to:
```
http://localhost:5173
```

The website will automatically reload when you make changes to the code.

### Stop the Server

Press `Ctrl+C` (or `Cmd+C` on Mac) in the terminal to stop the development server.

## 📁 Project Structure

```
tennis_website/
├── client/
│   ├── public/              # Static assets (images, icons, etc.)
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   │   ├── Hero.tsx
│   │   │   ├── Services.tsx
│   │   │   ├── About.tsx
│   │   │   ├── Portfolio.tsx
│   │   │   ├── Testimonials.tsx
│   │   │   ├── Contact.tsx
│   │   │   ├── Navigation.tsx
│   │   │   └── Footer.tsx
│   │   ├── pages/           # Page components
│   │   │   ├── Home.tsx
│   │   │   └── NotFound.tsx
│   │   ├── App.tsx          # Main app component
│   │   ├── main.tsx         # React entry point
│   │   ├── index.css        # Global styles
│   │   └── const.ts         # Application constants
│   ├── index.html           # HTML template
│   └── package.json         # Dependencies
├── todo.md                  # Project tasks and features
└── README.md               # This file
```

## 🛠️ Technologies Used

- **React 19** - UI library
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS 4** - Utility-first CSS framework
- **Vite** - Fast build tool and dev server
- **Wouter** - Lightweight routing library
- **shadcn/ui** - High-quality UI components
- **Lucide React** - Icon library

## ✏️ Customizing the Website

### Edit Content

All content is located in the `client/src/components/` directory:

1. **Hero Section** - Edit `client/src/components/Hero.tsx`
2. **Services** - Edit `client/src/components/Services.tsx`
3. **About** - Edit `client/src/components/About.tsx`
4. **Achievements** - Edit `client/src/components/Portfolio.tsx`
5. **Testimonials** - Edit `client/src/components/Testimonials.tsx`
6. **Contact** - Edit `client/src/components/Contact.tsx`
7. **Footer** - Edit `client/src/components/Footer.tsx`

### Update Logo and Branding

Edit `client/src/const.ts` to change:
- `APP_LOGO` - Website logo
- `APP_TITLE` - Website title

### Modify Styles

Global styles are in `client/src/index.css`. Tailwind CSS classes are used throughout the components.

## 🔧 Common Commands

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Check for TypeScript errors
npm run type-check
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Mobile** - 320px and up
- **Tablet** - 768px and up
- **Desktop** - 1024px and up

## 🌐 Deployment

To deploy this website online:

1. Build the production version:
```bash
npm run build
```

2. The `dist/` folder contains the production-ready files
3. Upload to your hosting provider (Vercel, Netlify, GitHub Pages, etc.)

## 📞 Contact

**Coach Sakka**
- **Location:** Montreal, QC, Canada
- **Phone:** +1 (514) 812-0621
- **Email:** anis.federe@gmail.com
- **Languages:** Arabic, English, French

## 📄 License

This project is private and belongs to Sakka Tennis Coach.

## 🤝 Support

For issues or questions about the website, please contact the coach directly.

---

**Last Updated:** November 17, 2025

