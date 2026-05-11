# 🌟 Kindness Engine

A sophisticated, professional compliment generator designed to brighten someone's day through intentional, high-quality praise. Built with a focus on modern UI/UX principles and micro-interactions.

## ✨ Features

- **Categorized Compliments**: Filter by vibe, including **Professional**, **Wholesome**, and **Funny**.
- **Smart Generation**: An intelligent randomization logic that prevents showing the same compliment twice in a row.
- **Micro-Interactions**: Smooth `fadeInBlur` animations and success-state pops for a premium app-like feel.
- **Output Suite**: 
    - **One-Click Copy**: Integrated clipboard support with visual feedback (Toast notifications).
    - **Native Sharing**: Utilizes the Web Share API to share compliments via the device's native sharing menu.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop using Tailwind CSS.

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Utility-first framework)
- **Typography**: 
    - *Outfit*: For bold, high-character headings.
    - *Inter*: For highly readable, professional body text.
- **Icons**: [Lucide Icons](https://lucide.dev/) (SVG format)
- **Scripting**: Vanilla JavaScript (ES6+)

## 🚀 Quick Start

1. Clone the repository or download the `index.html` file.
2. Open `index.html` in any modern web browser.
3. No build step or installation required—all dependencies are served via CDN.

## 📂 Project Structure

```text
index.html
├── Internal CSS (Tailwind + Custom Animations)
├── Main UI (Header, Category Filter, Display Card, Action Suite)
└── Script Logic (Compliment Data, State Management, Clipboard/Share APIs)