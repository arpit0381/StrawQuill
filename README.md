# StrawQuill ✨

A modern, collaborative real-time document editor built with Next.js, Lexical, and Liveblocks.

## 🎯 Overview

StrawQuill is a live collaborative documents platform that enables multiple users to edit documents simultaneously in real-time. Powered by advanced text editing capabilities and seamless synchronization, it provides a smooth, responsive writing experience similar to Google Docs or Notion.

**Live Demo:** [straw-quill.vercel.app](https://straw-quill.vercel.app)

## ✨ Features

- **Real-time Collaboration** - Multiple users can edit the same document simultaneously with live updates
- **Rich Text Editing** - Powered by Lexical, a powerful JavaScript text editor framework
- **Modern UI** - Built with React and Radix UI components for a polished user experience
- **User Authentication** - Secure authentication with Clerk
- **Responsive Design** - Tailwind CSS for beautiful, mobile-friendly layouts
- **Error Tracking** - Sentry integration for production monitoring

## 🚀 Tech Stack

### Frontend
- **Next.js 14** - React framework for production
- **TypeScript** - Type-safe development (76.3% of codebase)
- **Lexical** - Powerful text editor library
- **React 18** - UI library
- **Tailwind CSS** - Utility-first CSS framework

### Real-time & Collaboration
- **Liveblocks** - Real-time collaboration infrastructure
  - `@liveblocks/client` - Client library
  - `@liveblocks/react` - React hooks and components
  - `@liveblocks/react-lexical` - Lexical integration
  - `@liveblocks/react-ui` - Pre-built UI components

### UI Components
- **Radix UI** - Unstyled, accessible component library
- **Lucide React** - Beautiful icon library

### Authentication & Security
- **Clerk** - Modern authentication and user management
- **Sentry** - Error tracking and monitoring

### Styling
- **CSS** (22.1% of codebase)
- **TailwindCSS Animate** - Animation utilities

### Development Tools
- ESLint - Code linting
- PostCSS - CSS preprocessing

## 📋 Prerequisites

- Node.js 18+ 
- npm or yarn

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/arpit0381/StrawQuill.git
cd StrawQuill
