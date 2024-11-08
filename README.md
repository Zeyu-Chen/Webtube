# YouTube Clone

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)

A responsive YouTube clone built with React, TypeScript, and Tailwind CSS that replicates core YouTube UI features.

## Features

- 🎥 Video Grid Layout - Responsive grid of video thumbnails
- 📱 Mobile Responsive - Adapts seamlessly across devices
- 🎨 Custom UI Components - Pixel-perfect recreation of YouTube's UI
- 🎬 Video Preview - Hover preview functionality
- 📋 Category Navigation - Horizontal scrollable category pills
- 🔍 Search Integration - Fully functional search bar
- ⚡ Performance Optimized - Efficient rendering and animations

## Tech Stack

- **Framework:** React 18
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Icons:** Lucide React
- **Utilities:**
  - class-variance-authority
  - tailwind-merge
  - Vite

## Getting Started

### Prerequisites

- Node.js 16+
- npm/yarn

### Installation

1. Clone the repository

```bash
git clone git@github.com:Zeyu-Chen/Webtube.git
cd Webtube
```

2. Install dependencies

```bash
npm install
```

3. Start the development server

```bash
npm run dev
```

## Project Structure

```text
src/
├── assets/     # Static assets
├── components/ # Reusable UI components
├── contexts/   # React context providers
├── data/       # Mock data
├── layouts/    # Layout components
├── utils/      # Utility functions
```

## Key Components

### Video Grid

- Responsive grid layout
- Hover preview functionality
- View count formatting
- Time ago formatting

### Sidebar

- Collapsible navigation
- Responsive design
- Category organization

### Category Pills

- Horizontal scrolling
- Active state management
- Smooth animations
