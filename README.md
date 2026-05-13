# T2R-UI-1

# Time2Result - Elite Sports Timing & Event Management

A modern, high-performance, and responsive front-end user interface designed for **Time To Result Solutions**, an end-to-end race timing and event management company based in Chennai.

## 🚀 Overview

This project provides a complete static front-end architecture for a sports timing platform. It features a sleek, futuristic design utilizing glassmorphism, smooth hover effects, gradient UI elements, and a responsive layout that works perfectly across mobile, tablet, and desktop devices.

## ✨ Key Features

* **Modern UI/UX:** Clean, high-end aesthetics utilizing the `Lexend` font for bold headings and `Inter` for highly readable data and body text.
* **Fully Responsive:** Built with Tailwind CSS, ensuring the layout adapts seamlessly to any screen size.
* **Interactive Leaderboard:** A sophisticated results page (`result.html`) featuring a top-3 podium, tabular data, split times, runner comparison tools, and shareable result modals.
* **Dynamic Event Pages:** Custom landing pages for specific events (e.g., Chennai Marathon, Coastal Tri-Series) indicating live/completed statuses.
* **Smooth Animations:** Scroll-reveal animations using the Intersection Observer API for a polished, professional feel.

## 📁 File Structure

The project consists of the following core HTML pages:

* `index.html` - The main landing page featuring the hero banner, recent events, services overview, and testimonials.
* `about.html` - Company history, vision, and core capabilities.
* `services.html` - Detailed breakdown of all event management and timing services.
* `events.html` - A searchable and filterable directory of upcoming, live, and past events.
* `result.html` - The core timing leaderboard, featuring search, category filters, and detailed individual athlete splits.
* `gallery.html` - A masonry-style photo gallery showcasing event highlights.
* `event-details.html` - A reusable template for standard event information.
* `chennai-marathon.html` - A specific, customized page for the live Chennai City Marathon.
* `coastal-tri-series.html` - A specific, customized page for the completed Coastal Tri-Series event.

## 🛠️ Technology Stack

* **HTML5** - Semantic markup.
* **Tailwind CSS (CDN)** - Utility-first CSS framework for rapid UI development.
* **Vanilla JavaScript** - For scroll animations, tab switching, and modal toggling (No heavy frameworks required).
* **Google Fonts** - `Lexend` (Headings) and `Inter` (Data/Body).
* **Google Material Symbols** - Lightweight, scalable icons used throughout the interface.

## ⚙️ Setup & Installation

Because this project utilizes the Tailwind CSS CDN, there is **no build process or installation required**. 

1. Download or clone the repository to your local machine.
2. Ensure you have an internet connection (required to load Tailwind CSS, Fonts, and Icons).
3. Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Safari, Edge).

## 🎨 Customization

### Brand Colors
The brand colors are configured globally via the Tailwind config script located in the `<head>` of every HTML file. If you need to update the brand colors in the future, locate this block of code:

```javascript
<script id="tailwind-config">
    tailwind.config = {
        theme: {
            extend: {
                "colors": {
                    "brand-teal": "#56BEB4",   /* Primary Teal */
                    "brand-purple": "#5F2D8A", /* Primary Purple */
                    "brand-dark": "#0B1121",   /* Background Dark */
                    // ...other colors
                }
            }
        }
    }
</script>
